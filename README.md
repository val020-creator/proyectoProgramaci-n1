# Inventario Forestal Nacional
Sistema básico de registro para especies forestales desarrollado en Python utilizando `ipywidgets` en Google Colab.
El programa permite registrar información de especies como pájaros y flores organizadas por brigadas y lotes de trabajo, además de generar archivos CSV descargables.

---

## Características
- Registro de especies forestales
- Generación automática de ID
- Registro por:
  - Municipio
  - Brigada
  - Lote
- Clasificación por especies
- Descarga de archivos CSV:
  - Por lotes
  - Por especies
- Interfaz interactiva con `ipywidgets`

---

## Tecnologías utilizadas
- Python
- Google Colab
- ipywidgets
- csv

---

## Estructura de los registros
Cada registro almacena:
| Campo | Descripción |
|---|---|
| ID | Identificador generado automáticamente |
| Especie | Tipo de especie registrada |
| Nombre común | Nombre de la especie |
| Tipo | Clasificación de la especie |
| Municipio | Municipio del registro |
| Brigada | Brigada responsable |
| Lote | Lote asignado |

---

## Especies soportadas
### Pájaros
- Ave pequeña
- Ave mediana
- Ave grande

### Flores
- Silvestre
- Medicinal
- Ornamental

---

## Opciones del sistema
El programa cuenta con cuatro opciones principales:
1. Agregar registros
2. Eliminar registros
3. Imprimir registros
4. Descargar archivos CSV

## Descarga de archivos
Los registros pueden descargarse:
- Por lotes
- Por especies
Los archivos se generan automáticamente en formato `.csv`.

---

## Ejecución
El proyecto fue diseñado para ejecutarse en Google Colab.
### Librerías necesarias
```python
import csv
import random
from google.colab import files
import ipywidgets as widgets
from IPython.display import display, clear_output
