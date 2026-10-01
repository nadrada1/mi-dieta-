# Mi Dieta V5.2.1 — corrección funcional

Correcciones sobre V5.2:
- Corregido el cruce entre los nombres de ingredientes del motor y los nombres reales de la biblioteca.
- Añadidos alias robustos (espacios, barras, acentos y variantes de producto).
- Añadidos noodles de arroz a la biblioteca base.
- El menú inteligente ahora también aparece claramente dentro de “Menú diario”, con botones separados para comida y cena.
- Si no puede formar un plato solo con lo que hay en casa, muestra platos razonables y qué ingrediente falta en vez de quedarse sin respuesta.
- Mantiene las porciones familiares Nacho/Lucía/Javi y la penalización de repeticiones.
- No modifica ni borra las claves existentes de datos.

Auditoría:
- JavaScript `node --check`: OK.
- Sin borrado de localStorage.
- IDs y referencias estáticas revisados.
