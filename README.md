# sprint7-final-project
TripleTen - Sprint 7 
## Proyecto 6 - Análisis de una empresa de telecomunicaciones 

# Objetivos del proyecto
- Entender cómo los clientes usan los servicios móviles (llamadas y mensajes)
- Identificar patros de uso en las categorías de clientes
- Detectar comportamientos atipicos.
- Comprender las necesidades de cada segmento de clientes.
- Responder las preguntas de negocio.

# Datasets utilizados 
Se trabaja con tres fuentes de datos:
- plan.csv : Contiene los planes actuales (precio, minutos incluidos, GB incluidos, costo extra)
- users_latam.csv : Información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv : Contiene el detalle de uso real: llamadas (duración) y mensajes (longitud).

# Etapas de analisis realizadas 

1. Cargar y explorar los datasets. Encontrar la primera idea acerca de cual es el comportamiento de los datos, cuantas filas y columnas contienen.
2. Identificar problemas de calidad: Identificación de valores nulos, inválidos y sentinels. Así como identificar las acciones que se van a tener en cuenta con cada uno de los valores encontrados.
3. Limpieza del dataset: Realizar procesos como estandarización de fechas, corregir sentinels y fechas imposibles.
4. Resumen estadistico: Revisar las medidas claves en variables categoricas y numericas.
5. Visualización: Identificar la distribución y outliers.
6. Segmentación de clientes por uso y edad.
7. Insight ejecutivo: redactar conclusiones, responder a las preguntas de negocio y proponer acciones concretas

# Guía de reproducción
- Requisitos: Python, librerias como: pandas, numpy, seaborn, matplotlib.
- Cargar los archivos CSV usando pd.read_csv()
/datasets/plans.csv
/datasets/users_latam.csv
/datasets/usage.csv
- Abre jupyter notebook y ejecuta el archivo 'S7 Version-Estudiante-Project-ConnectaTel'
