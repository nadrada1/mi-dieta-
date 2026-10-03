# Mi Dieta · V5.6.2 Beta

## Cambios
- Cocinero IA pasa a una experiencia principal con petición libre: "¿Qué te apetece?".
- Accesos rápidos: Rápido, Ligero, Proteína, Pescado, Pasta, En casa y Sorpréndeme.
- La petición escrita o elegida se incorpora al contexto que recibe el Cocinero.
- Se mantiene el contexto automático: perfil, momento del día, kcal/proteína restantes, despensa, lo comido hoy y comidas recientes.
- Plan se simplifica: queda centrado en crear un menú del día sin duplicar las sugerencias del Cocinero IA.
- Limpieza de textos explicativos en Más, Alimentos, En casa, Recetas y otras pantallas.
- Cocinero IA sube de posición visual y reduce el espacio vacío en escritorio y móvil.
- Se mantiene la validación nutricional con la biblioteca interna: no se muestran kcal/proteína parciales como si fueran totales.
- Entrar en Cocinero IA, escribir o pulsar un acceso rápido NO llama a OpenAI. La llamada solo ocurre al pulsar "Dame ideas" / "Dame otras ideas".

## Seguridad y datos
- No se modifica ni borra el almacenamiento histórico.
- Sin `localStorage.clear()` ni `removeItem()`.
- V5.5.6 (`index.html`) y `v55.html` no deben sustituirse durante la beta.
- `cocinero-ai` continúa requiriendo sesión autenticada de Supabase.

## Despliegue beta
Subir `v56.html` al raíz del repositorio y probar en `/mi-dieta-/v56.html`.
