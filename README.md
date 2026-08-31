# Repositorio de Entregables — Convocatoria Interna para el Diseño y Publicación de Conjunto de Datos con Potencial de
Explotación en Inteligencia Artificial 2025- 2026. Ejecución 2026

Este repositorio centraliza los productos de los proyectos aprobados en la convocatoria de curaduría/publicación de datasets, conforme a los Anexos 1 a 4 de los términos de referencia.

## Cómo usar este repositorio

1. Cada proyecto aprobado tiene **su propia carpeta en la raíz**, nombrada así:

   ```
   PROYECTO_<nombre-corto-del-proyecto>
   ```

   Ejemplo: `PROYECTO_PredAgro`, `PROYECTO_MedPredict`.

2. Copie el contenido completo de `plantilla-proyecto/` dentro de la nueva carpeta del proyecto y reemplace los archivos `README.md` de ejemplo por los entregables reales.

3. **El dataset NUNCA se sube a este repositorio.** Debe publicarse por el investigador en un repositorio público reconocido (institucional, Zenodo, Figshare, Dataverse, Kaggle, RE3data, etc.) y en la carpeta `04-dataset-publicado/` solo se deja un archivo `ENLACE_DATASET.md` con el enlace, DOI y licencia (ver plantilla).

## Estructura de cada proyecto

```
PROYECTO_<nombre>/
├── README.md                      → resumen ejecutivo y ficha del proyecto (Anexo 4)
├── 01-propuesta/                  → propuesta completa presentada a la convocatoria
├── 02-documento-tecnico/          → Documento Técnico del Conjunto de Datos (Anexo 1)
├── 03-diccionario-datos/          → diccionario de variables del dataset
├── 04-dataset-publicado/          → SOLO el enlace al dataset público (no el dataset)
├── 05-cumplimiento-fair/          → checklist FAIR diligenciado (Anexo 2)
├── 06-consideraciones-eticas/     → soportes éticos/legales (consentimientos, autorizaciones)
└── 07-productos-adicionales/      → informes técnicos, artículos, presentaciones derivadas
```

## Formatos aceptados por carpeta

| Carpeta | Formatos aceptados | Notas |
|---|---|---|
| `01-propuesta/` | `.pdf`, `.docx` | Documento de propuesta tal como fue aprobado |
| `02-documento-tecnico/` | `.pdf`, `.docx`, `.md` | Debe cubrir las 10 secciones del Anexo 1 |
| `03-diccionario-datos/` | `.csv`, `.xlsx` | Obligatorio como anexo aparte si el dataset supera 20 variables |
| `04-dataset-publicado/` | `.md` únicamente | Solo el archivo `ENLACE_DATASET.md`; nunca datos crudos |
| `05-cumplimiento-fair/` | `.md`, `.pdf`, `.docx` | Checklist de las 4 dimensiones FAIR (Anexo 2) |
| `06-consideraciones-eticas/` | `.pdf` | Consentimientos, autorizaciones de terceros, actas de comité de ética si aplica |
| `07-productos-adicionales/` | `.pdf`, `.docx`, `.pptx` | Informes técnicos, artículos, ponencias asociadas |

## Convenciones de nombres de archivo

`<CODIGO-PROYECTO>_<tipo-documento>_<vAAAAMMDD>.<ext>`

Ejemplo: `PredAgro_documento-tecnico_v20260805.docx`

## Áreas de conocimiento OCDE de referencia

Al clasificar el dataset en el Documento Técnico (Anexo 1, sección 2 "Ámbito Temático"), use una de las cinco áreas Frascati/OCDE (ver Anexo 3): Ciencias Naturales, Ingeniería y Tecnología, Ciencias Médicas y de la Salud, Ciencias Agrícolas, Ciencias Sociales y Humanidades.
