# TelecomX
Proyecto Telecom X: Análisis de Evasión de Clientes (Churn)
📌 Descripción del proyecto
Este proyecto realiza un análisis exploratorio de datos para la empresa Telecom X, con el objetivo de comprender los factores que influyen en la evasión de clientes (churn). A partir de un conjunto de datos proporcionado, se realizó una limpieza, transformación, análisis visual y exploración de correlaciones para generar insights valiosos.

🎯 Objetivos
Analizar el comportamiento de clientes que abandonan el servicio.

Identificar variables relacionadas con el churn.

Generar visualizaciones para comunicar patrones.

Producir un dataset limpio listo para modelos predictivos.

🧰 Tecnologías utilizadas
Python

Pandas

NumPy

Seaborn

Matplotlib

Jupyter Notebook

Telecom-X-Churn-Analysis/
│
├── TelecomX_Data.json        # Archivo de datos original en formato JSON
├── notebook_analisis.ipynb   # Notebook con análisis completo
├── README.md                 # Este archivo
└── /imagenes                 # Carpeta opcional con visualizaciones exportadas

🔎 Etapas del análisis
1. Importación y transformación de datos
Lectura de archivo .json con estructura anidada.

Aplanamiento del dataset y estandarización de nombres.

2. Limpieza de datos
Conversión de texto a binario (sí/no → 1/0).

Conversión de columnas numéricas mal tipadas.

Creación de nuevas variables (cuentas_diarias, servicios_totales).

3. Análisis exploratorio
Visualización de tasas de abandono por género, tipo de contrato, forma de pago.

Análisis de distribución de cargos y tiempo de contrato.

Correlación entre variables y abandono.

4. Insights
Los clientes con contratos mensuales y menor tiempo contratado tienen mayor tasa de evasión.

Las formas de pago electrónicas presentan más abandono.

Hay relación entre menor cantidad de servicios y mayor churn.

🧠 Recomendaciones
Fidelizar a clientes nuevos durante los primeros meses.

Ofrecer incentivos para cambiar a contratos anuales.

Identificar y segmentar clientes en riesgo para ofrecer soporte o promociones.

👨‍💻 Autor
Enrique A Hernández
Analista de datos
