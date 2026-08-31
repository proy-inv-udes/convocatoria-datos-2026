# Cómo entregar los productos de un proyecto aprobado

1. Cree una rama o directamente una carpeta nueva en la raíz: `PROYECTO_<nombre-corto>`.
2. Copie todo el contenido de `plantilla-proyecto/` dentro de esa carpeta.
3. Diligencie el `README.md` de la carpeta del proyecto con la ficha resumen.
4. Cargue cada entregable en la subcarpeta correspondiente, respetando los formatos aceptados (ver tabla en el README raíz).
5. En `04-dataset-publicado/`, complete únicamente `ENLACE_DATASET.md` con el enlace, DOI y licencia — **nunca suba el dataset en sí**.
6. Diligencie el checklist de `05-cumplimiento-fair/`.
7. Abra un Pull Request para revisión antes de fusionar a la rama principal (opcional, según flujo de trabajo del grupo).

## Buenas prácticas
- No suba archivos de datos crudos, ni siquiera de muestra, a ninguna carpeta.
- Use nombres de archivo con la convención `<CODIGO-PROYECTO>_<tipo-documento>_v<AAAAMMDD>.<ext>`.
- Mantenga las carpetas vacías con un archivo `README.md` mínimo si aún no hay entregable, para conservar la estructura.
