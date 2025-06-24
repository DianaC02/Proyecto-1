APRENDIZAJE SUPERVISADO
Beta Bank – Predicción de abandono de clientes
Propósito: Predecir clientes con riesgo de abandono para reducir la pérdida mensual de usuarios.
Contribución clave:
•	Entrené y optimicé modelos predictivos (árboles, random forest, regresión logística) para detectar churn.
•	Apliqué técnicas de balanceo de clases (undersampling y ponderación) para mejorar precisión y recall.
•	Alcancé F1 > 0.59 y analicé desempeño con AUC-ROC.
Habilidades aplicadas: Python, scikit-learn, pandas, visualización de métricas, ajuste de hiperparámetros

APRENDIZAJE AUTOMÁTICO EN NEGOCIOS 
OilyGiant – Selección óptima de pozos petroleros
Propósito: Identificar la región más rentable para abrir 200 nuevos pozos, minimizando riesgo y maximizando beneficio.
Contribución clave:
•	Entrené un modelo de regresión lineal para predecir reservas en nuevos pozos usando datos geológicos.
•	Seleccioné los 200 pozos con mayor volumen estimado en cada región y evalué rentabilidad.
•	Apliqué bootstrapping para estimar beneficios y riesgos; elegí la región con mayor retorno y riesgo < 2.5%.
Habilidades aplicadas: Python, regresión lineal, análisis de riesgo, NumPy, pandas, visualización de resultados, evaluación económica

SERIES TEMPORALES
Sweet Lift Taxi – Predicción de pedidos por hora
Propósito: Predecir la cantidad de pedidos de taxis para la próxima hora en aeropuertos y ayudar a atraer más conductores durante las horas pico.
Contribución clave:
Descargué y remuestreé el archivo /datasets/taxi.csv, agregando los datos en intervalos de una hora.
Realicé análisis exploratorio (timelines, autocorrelación, estacionalidad diaria/semanal).
Implementé make_features() con variables temporales robustas:
Transformaciones cíclicas para hora del día (seno/coseno).
Indicadores de fin de semana y madrugada.
Lags de pedidos y medias móviles.
División: 90 % entrenamiento, 10 % prueba.
Entrené varios modelos (Random Forest, XGBoost, LightGBM) ajustando hiperparámetros con validación cruzada por tiempo.
Evité duplicación de código estructurando el pipeline (scikit-learn Pipeline, funciones reutilizables).
Habilidades aplicadas: Python, pandas, scikit‑learn, XGBoost, análisis temporal, ingeniería de variables, visualización (Matplotlib/Seaborn), evaluación de modelos (RECM).

