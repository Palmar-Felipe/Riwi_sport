# Riwi Sport — Análisis de ventas

Este repositorio contiene un notebook de análisis (`analisis_RIWI_Sport_felipe_palmar.ipynb`) que se conecta a una base de datos PostgreSQL y realiza análisis de ventas (KPIs, visualizaciones y RFM básico). A continuación se describen pasos para restaurar la base de datos local, configurar variables de entorno y ejecutar el notebook.

## Requisitos mínimos
- Python 3.10+ (recomendado 3.11/3.12)
- PostgreSQL 12+
- Dependencias Python (ver `requirements.txt`)

## Dependencias sugeridas
Las dependencias mínimas recomendadas están en `requirements.txt` e incluyen:
- pandas
- numpy
- sqlalchemy
- psycopg2-binary
- matplotlib
- seaborn
- python-dotenv


## Instalar dependencias Python
Se recomienda crear un entorno virtual y luego instalar las dependencias:

```bash
python -m venv nombre_del_entorno
source nombre_del_entorno/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Ejecutar el notebook
1. Activar el entorno virtual (si no está ya activo):

```bash
source nombre_del_entorno/bin/activate
```

2. Iniciar Jupyter Notebook o Jupyter Lab:

```bash
jupyter notebook

jupyter lab
```

3. Abrir `analisis_RIWI_Sport_felipe_palmar.ipynb` y ejecutar las celdas en orden. Asegúrate de haber configurado `.env` con la conexión correcta.

# Estructura recomendada de carpetas

```
riwi_sport/
├── README.md
├── requirements.txt
├── analisis_RIWI_Sport_felipe_palmar.ipynb  # Notebook principal
├── RiwiSport.sql       # Dump SQL para restaurar la base de datos
```

coder:  Felipe miguel palmar ramirez 
cc: 111392593
correo: pipepalmar@hotmail.com

