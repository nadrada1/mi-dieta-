# Mi Dieta V5.6.1 Beta — Cocinero IA

Fecha: 3 octubre 2026

## Cambios de esta build
- Cocinero IA pasa a tener acceso propio en `Más > Cocinero IA`.
- Se mantiene también el acceso desde `Más > En casa`.
- Ambos accesos comparten las mismas propuestas: entrar o cambiar de pantalla NO genera una nueva llamada a OpenAI.
- OpenAI solo se consulta al pulsar `Dame ideas para cocinar`, `Dame otras ideas` o `Reintentar`.
- `No me apetece` ya NO genera automáticamente otra llamada: registra el rechazo y descarta visualmente esa propuesta.
- Nutrición: solo se muestran kcal/proteína de Mi Dieta cuando reconoce el 100% de los ingredientes. Si faltan ingredientes, muestra `Nutrición pendiente` en vez de una cifra parcial engañosa.
- Se mantiene la integración autenticada con `cocinero-ai` mediante la sesión Supabase del usuario.
- No se modifica ni elimina el almacenamiento local existente.
- No sustituye V5.5.6: esta beta se publica como `v56.html` para probar en paralelo.

## Pruebas técnicas realizadas antes de empaquetar
- JavaScript: `node --check` correcto.
- IDs HTML duplicados: 0.
- `localStorage.clear`: 0.
- `localStorage.removeItem`: 0.
- Verificado acceso `data-go="aiCook"` y sección `id="aiCook"`.

## Despliegue
Subir `v56.html` a la raíz del repositorio `mi-dieta-`, reemplazando únicamente la beta anterior `v56.html`.
No tocar `index.html` ni `v55.html`.

URL de prueba:
https://nadrada1.github.io/mi-dieta-/v56.html
