# AGENTS – LUNA

## Descripcion breve
LUNA es una aplicacion de organizacion personal que centraliza tareas, recordatorios, eventos y pendientes en un solo espacio. Su objetivo es ayudar a los usuarios a administrar mejor sus actividades cotidianas mediante una experiencia simple y accesible.

---

## Archivos de especificaciones
Los siguientes archivos se encuentran en la carpeta `docs/` y deben ser respetados por la IA:

- **IDENTIDAD-MARCA.md** → Define nombre, logo, paleta de colores, tipografias y tono de comunicacion.
- **01-CONTEXTO.md** → Explica el problema, objetivo, publico y alcance inicial.
- **02-REQUERIMIENTOS.md** → Lista de requerimientos funcionales y no funcionales.
- **03-TECNOLOGIAS.md** → Stack tecnologico elegido y justificacion.
- **04-ARQUITECTURA.md** → Organizacion del codigo y estructura de carpetas.
- **05-DATOS.md** → Entidades, tablas y ejemplos de datos.
- **06-DISENO-UI.md** → Pantallas principales y aplicacion de la identidad visual.
- **07-CONVENCIONES.md** → Normas de estilo de codigo, idioma y commits.
- **08-TAREAS.md** → Etapas de trabajo con casillas de verificacion.
- **09-SEO.md** → Estrategia de posicionamiento en buscadores.
- **10-SEGURIDAD.md** → Manejo de datos sensibles y validaciones.
- **MEMORY.md** → Reglas de almacenamiento, persistencia y olvido de datos.

---

## Reglas generales para la IA
1. **No inventar precios ni datos de marcas reales.**  
2. **Respetar la identidad visual:** colores, tipografias y logo definidos en `IDENTIDAD-MARCA.md`.   
3. **Usar sintaxis Markdown real:** titulos, listas, tablas, bloques de codigo y casillas de tareas.  
4. **Mantener coherencia:** lo definido en identidad debe reflejarse en diseño y demas archivos.  
5. **No alterar el tono de comunicacion:** debe ser cercano, claro y motivador.  
6. **No ejecutar codigo:** sin revision humana previa.  
7. **Cada commit:** debe corresponder a una tarea pequeña y comprensible.

## Comandos disponibles
- `/spec`: Solicitar o mostrar especificaciones detalladas de una funcionalidad o modulo.
- `/clarificar`: Pedir aclaraciones o detalles adicionales cuando algo no esta claro.
- `/verificar`: Validar que ciertos criterios o condiciones se cumplan.

## Skills del agente
- `verificar-criterios`: Revisa si una tarea o funcionalidad cumple con los criterios establecidos en la constitucion y especificaciones.
- `gestionar-memoria`: Maneja el almacenamiento y recuperacion de datos persistentes segun las reglas definidas en memory.md.

## Interaccion con la memoria
- La IA debe respetar las reglas de almacenamiento, persistencia y olvido definidas en `memory.md`.
- Mantener contexto relevante para asegurar coherencia en la interaccion.

## Validacion y verificacion
- Antes de finalizar cualquier tarea, usar `/verificar` para asegurar que cumple con los principios y criterios definidos.
- Reportar cualquier inconsistencia o duda usando `/clarificar` para solicitar mas informacion o ajustes.
