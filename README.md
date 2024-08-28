# Análisis de Acceso a Internet en Argentina

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento del acceso a internet en Argentina, a través de un análisis exploratorio de datos (EDA) y un proceso de extracción, transformación y carga (ETL). El proyecto se centra en la identificación de tendencias en el acceso a internet por diferentes tecnologías y regiones, permitiendo a una empresa de telecomunicaciones identificar oportunidades de crecimiento y mejorar la calidad de sus servicios.

## Contexto

Las telecomunicaciones juegan un papel crucial en nuestra sociedad, permitiendo la comunicación y transferencia de datos a nivel global. En Argentina, la industria está en constante evolución, y para el año 2020, el país contaba con más de 62 millones de conexiones. Este proyecto analiza estos datos, centrándose en el acceso a internet, pero también considerando otros servicios de comunicación.

## Rol Desarrollador

En este contexto, se me encargó realizar un análisis completo del sector de telecomunicaciones en Argentina, con un enfoque particular en el acceso a internet. El objetivo es identificar oportunidades de mejora y crecimiento para la empresa, proporcionando un análisis detallado de los datos y un tablero interactivo para visualizar los resultados.

## Estructura del Proyecto

- **EDA/EDA_DA.ipynb**: Contiene el análisis exploratorio de los datos. Aquí se documentan todos los pasos realizados, incluyendo la identificación de valores faltantes, outliers, y duplicados, así como la generación de visualizaciones clave.
- **ETL/ETL_DA.ipynb**: Contiene el proceso de ETL, donde se realiza la limpieza y transformación de los datos para su posterior análisis.
- **ETL/csv_normalizado**: Carpeta que almacena los archivos CSV normalizados y preparados durante el proceso ETL.
- **PowerBI/Conectividad-Internet[1].pbix: Contiene el tablero de Power BI utilizado para visualizar los resultados del análisis.
- **requirements.txt**: Archivo que lista todas las dependencias necesarias para ejecutar el proyecto.
- **README.md**: Este archivo, que proporciona una visión general del proyecto, la estructura del repositorio, y las instrucciones para su uso.

## Instalación y Configuración

Clona el repositorio en tu máquina local:

```bash
git clone https://github.com/tuusuario/henry_pi2_data_analytics.git

Navega al directorio del proyecto:

bash
Copiar código
cd henry_pi2_data_analytics
Crea y activa un entorno virtual:

bash
Copiar código
python -m venv venv
source venv/bin/activate # En Windows: venv\Scripts\activate
Instala las dependencias:

bash
Copiar código
pip install -r requirements.txt
## Uso
Ejecuta el notebook de ETL para procesar los datos y generar los archivos normalizados.
Ejecuta el notebook de EDA para analizar los datos y generar visualizaciones.
Los resultados del análisis pueden ser utilizados para construir un dashboard en Power BI u otra herramienta de visualización.

## Visualizaciones

Top 10 Localidades con Mayor Acceso a Internet: Identifica las ciudades con mayor penetración de internet.

Distribución por Tecnologías de Acceso: Muestra cómo se distribuyen los accesos a internet entre diferentes tecnologías.

Detalles del Tablero de Power BI
El tablero de Power BI proporciona una visualización interactiva de la conectividad a Internet en Argentina, centrándose en las siguientes áreas clave:

Top 10 Localidades con Mayor Acceso a Internet: Identifica las ciudades con mayor penetración de internet.

Distribución por Tecnologías de Acceso: Muestra cómo se distribuyen los accesos a internet entre diferentes tecnologías.

Análisis por Localidades:

Distribución del Acceso por Velocidad: Muestra la cantidad de accesos a Internet en diferentes provincias, destacando que la Ciudad Autónoma de Buenos Aires tiene el mayor número de accesos, mientras que Catamarca registra el menor número.

Comparativo de Accesos: Permite comparar la cantidad de accesos entre diferentes localidades y tipos de tecnología (Fibra Óptica, ADSL, Modem, etc.).

Top 5 Localidades: Presenta las cinco localidades con mayor cantidad de accesos, proporcionando un enfoque en las áreas con más desarrollo de infraestructura de Internet.

Análisis por Tecnología:

Comparación de Tecnologías: Se realiza un análisis de las tecnologías de acceso predominantes, como Banda Ancha Fija y Dial-Up, mostrando su evolución en distintas provincias.

KPI de Aumento de Acceso: Mide el crecimiento en la cantidad de accesos en función de las nuevas tecnologías implementadas, destacando el avance de la fibra óptica en comparación con otras tecnologías.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas colaborar, por favor abre un issue o envía un pull request.