# Actividad ETL

Este proyecto realiza una serie de transformaciones y análisis en un conjunto de datos extraído de una base de datos SQL Server. Utilizando Python y bibliotecas como `pandas` y `SQLAlchemy`, el proyecto tiene como objetivo limpiar y preparar los datos para su posterior análisis y carga en una base de datos.

## Descripción del Proyecto

El proceso ETL (Extract, Transform, Load) consiste en extraer datos de una base de datos SQL Server, realizar diversas transformaciones y análisis, y finalmente cargar los datos transformados en una nueva tabla de la misma base de datos.

El flujo de trabajo incluye las siguientes fases:
1. **Extracción**: Conexión a la base de datos SQL Server y extracción de datos usando una consulta SQL.
2. **Transformación**: Limpieza de datos, renombrado de columnas, conversión de tipos de datos, manejo de valores nulos y transformación de valores categóricos.
3. **Carga**: Los datos transformados se cargan de nuevo en la base de datos bajo una nueva tabla.

## Requisitos

- Python 3.x
- pandas
- SQLAlchemy
- pymssql (para conectar con SQL Server)

### Instalar las dependencias

```bash
pip install pandas sqlalchemy pymssql
