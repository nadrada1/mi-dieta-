# Mi Dieta V5.0.1

Corrección crítica de V5.0.

La V5.0 tenía una colisión JavaScript entre la colección de recetas existente
y una nueva función de recetas familiares. Eso detenía la inicialización de la app.

V5.0.1:
- corrige la colisión;
- supera `node --check` sin errores de sintaxis;
- conserva las mismas claves de datos de V4.x;
- no contiene ninguna rutina para borrar localStorage;
- mantiene perfiles, fecha, diario, biblioteca y datos históricos existentes;
- añade despensa y recetas V5 en claves nuevas separadas.
