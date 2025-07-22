# Análisis de Evasión de Clientes Telecom X

📌 Descripción
Telecom X es una empresa de telecomunicaciones que está enfrentando un alto índice de evasión de clientes (churn). Aún no se han identificado las causas principales detrás de esta evasión, por lo que este proyecto busca analizar los datos disponibles y brindar información clave para ayudar a resolver este problema.

🧠 Objetivos
Realizar un análisis exploratorio de los datos.
Identificar variables clave relacionadas con la evasión de clientes.
Visualizar tendencias y segmentos de mayor riesgo.
Proponer recomendaciones prácticas para mitigar el churn.
📁 Estructura del Repositorio
⚠️ Nota: La estructura actual del repositorio aún está en desarrollo. Pueden agregarse nuevos archivos y carpetas conforme avance el análisis.

🛠️ Herramientas Utilizadas
Python: Pandas, Matplotlib, Seaborn
Google Colaboratory

💡 Principales hallazgos

Tipo de Contrato
El tipo de contrato es el principal predictor de evasión. Los clientes con contratos mensuales (mes a mes) presentan tasas de cancelación significativamente más altas en comparación con aquellos con contratos anuales o bianuales.

Servicio de Internet
Los usuarios de fibra óptica muestran una mayor propensión a cancelar el servicio. Esto sugiere posibles problemas relacionados con la calidad, el precio o el desajuste entre expectativas y experiencia.

Método de Pago
El uso de cheque electrónico se asocia fuertemente con la evasión, lo que podría estar vinculado a la experiencia de pago o al perfil sociodemográfico de quienes utilizan este método.

Falta de Servicios Complementarios
Clientes que no contratan servicios de soporte técnico, seguridad online o respaldo en la nube presentan mayores tasas de cancelación, especialmente si cuentan con servicio de internet.

Cargos Mensuales Elevados
Se observa una concentración de cancelaciones en clientes con cargos mensuales cercanos a los $100, lo cual indica sensibilidad al precio o percepción de bajo valor recibido.

Perfil Demográfico
Los adultos mayores, así como los clientes solteros o sin dependientes, muestran una mayor probabilidad de abandonar el servicio.

🚀 Cómo ejecutar el código
Clona este repositorio.

Asegúrate de tener instaladas las bibliotecas mencionadas.

Ejecuta las celdas secuencialmente para replicar el análisis.

📂 Dataset
El dataset utilizado para este análisis se carga directamente desde una URL de GitHub en formato JSON. Contiene información sobre clientes de Telecom X, incluyendo datos demográficos, servicios contratados, información de cuenta y si el cliente ha abandonado el servicio (Churn).

✉️ Autora
Verónica González Ross
