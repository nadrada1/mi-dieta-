# Mi Dieta v2 — Nacho & Lucía

Aplicación estática para registrar cada día lo comido y ver al instante las calorías consumidas y restantes.

## Incluye
- Perfiles independientes: Nacho (1.100 kcal) y Lucía (1.300 kcal).
- Registro por fecha y por comida.
- kcal consumidas/restantes y proteína.
- Historial de los últimos 7 días.
- Peso y cintura opcionales.
- Alimentos precargados + alimentos personalizados.
- Exportar/importar copia de seguridad.
- Funciona sin servidor: los datos quedan en `localStorage`.

## Publicar gratis en GitHub Pages
1. Crea un repositorio, por ejemplo `mi-dieta`.
2. Sube `index.html` y `manifest.json` a la raíz.
3. En GitHub: Settings → Pages.
4. Source: Deploy from a branch.
5. Selecciona `main` y `/root`.
6. Guarda. GitHub mostrará la dirección pública.

## Importante
Las kcal son aproximadas. En productos envasados conviene crear el alimento con los datos de su etiqueta.
Al estar alojada como web estática, cada navegador conserva sus propios datos. Usa Exportar/Importar para moverlos entre dispositivos.
