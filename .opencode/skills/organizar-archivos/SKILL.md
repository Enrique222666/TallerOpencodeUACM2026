---
name: OrganizadorSkill
description: Organiza archivos .py, .c y .jar del directorio actual en carpetas dedicadas (python/, c_code/, java/), manejando conflictos de nombres de forma segura.
slash: true
metadata:
  opencode/autoinvoke: false
---

# Objetivo

Tu tarea es organizar los archivos del directorio de trabajo actual, moviendo las extensiones `.py`, `.c` y `.jar` a sus carpetas correspondientes: `python/`, `c_code/` y `java/`.

# Instrucciones de Ejecución

NO intentes mover los archivos manualmente con comandos `mv` o `find` complejos. En su lugar, utiliza el script auxiliar proporcionado en este skill, que ya maneja la creación de carpetas y los conflictos de nombres de forma segura.

### Paso 1: Ejecutar el Script de Organización

Ejecuta el siguiente comando en la terminal:

```bash
bash .opencode/skills/organizar-archivos/scripts/organize.sh
```
