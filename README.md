# 🌳 Inventario Forestal Nacional

Sistema interactivo de registro forestal desarrollado en Python utilizando `ipywidgets` en Google Colab.

El programa permite registrar especies forestales como pájaros y flores organizadas por brigadas y lotes de muestreo, además de generar archivos CSV descargables automáticamente.

---

## ✨ Características

- Registro de especies forestales
- Interfaz visual interactiva
- Generación automática de IDs únicos
- Control de especies repetidas
- Registro por:
  - Brigada
  - Departamento
  - Municipio
  - Lote de muestreo
- Registro de cantidad de individuos
- Exportación de datos en CSV
- Descarga:
  - Por lotes
  - Por especies
  - Inventario completo

---

## 🖥️ Interfaz del sistema

El proyecto utiliza `ipywidgets` para crear una interfaz visual similar a un formulario profesional de inventario forestal.

### Secciones principales

- Información de brigada
- Lote de muestreo
- Registro forestal
- Gestión de archivos CSV

---

## 🌿 Especies soportadas

### 🐦 Pájaros
- Migratoria
- Residente
- Invasora

### 🌸 Flores
- Silvestre
- Medicinal
- Ornamental

---

## 🆔 Sistema de IDs inteligentes

Cada especie recibe un ID único generado automáticamente.

### Ejemplos

```plaintext
PAJ-0001
PAJ-0002
FLO-0001
FLO-0002
```

### Características

- No se repiten IDs
- Los IDs aumentan automáticamente
- Si una especie ya existe:
  - conserva el mismo ID
  - aunque cambie el municipio o el lote

---

## 📦 Datos registrados

Cada registro almacena:

| Campo | Descripción |
|---|---|
| ID | Identificador automático |
| Especie | Pájaro o Flor |
| Nombre común | Nombre registrado |
| Tipo | Clasificación de la especie |
| Cantidad | Número de individuos |
| Departamento | Departamento del registro |
| Municipio | Municipio del registro |
| Brigada | Brigada responsable |
| Lote | Lote de muestreo |

---

## 📁 Exportación CSV

El sistema permite descargar los registros automáticamente en formato `.csv`.

### Opciones disponibles

- Descargar por lotes
- Descargar por especies
- Descargar inventario completo

---

## 🛠️ Tecnologías utilizadas

- Python
- Google Colab
- ipywidgets
- csv

---

## ▶️ Ejecución

El proyecto fue diseñado para ejecutarse en Google Colab.

### Librerías utilizadas

```python
import csv
from google.colab import files
import ipywidgets as widgets
from IPython.display import display, clear_output
```

---

## 📌 Funcionalidades principales

### Agregar registros
Permite registrar nuevas especies dentro del inventario.

### Eliminar registros
Elimina registros mediante índice.

### Imprimir registros
Muestra todos los datos almacenados.

### Descargar información
Genera archivos CSV automáticamente.

---

## 📷 Diseño de interfaz

El sistema utiliza:
- Contenedores visuales
- Distribución por columnas
- Botones interactivos
- Formularios organizados

Inspirado en interfaces modernas de sistemas de monitoreo ambiental.

---

## 👩‍💻 Autor

**Valery Montes**  
01240372023
