# Predicción de Ventas en Retail Online

Este proyecto tiene como objetivo desarrollar un modelo predictivo para estimar la cantidad de ventas futuras en un negocio de retail online. Con esta información, la empresa puede anticipar la demanda y mejorar la gestión del inventario, optimizando así las estrategias comerciales y la planificación de stock.

Para lograrlo, se realizó un exhaustivo procesamiento de los datos, incluyendo la limpieza, transformación y generación de variables temporales clave. Se eliminaron valores atípicos y se aplicaron técnicas de normalización para mejorar la calidad del dataset. Posteriormente, se implementó un modelo de `XGBoost` con optimización de hiperparámetros para predecir las ventas futuras basándose en patrones históricos.

Los resultados obtenidos muestran que el modelo tiene una precisión adecuada, con un coeficiente de determinación (`R²`) de **0.75**, lo que indica que captura el 75% de la variabilidad en los datos. Esto permite a la empresa tomar decisiones informadas sobre estrategias de venta, descuentos y abastecimiento, reduciendo riesgos y maximizando oportunidades de negocio.

## 📌 Librerías Usadas

### Procesamiento de Datos
- `pandas`
- `numpy`
- `sklearn.preprocessing.StandardScaler`
- `sklearn.preprocessing.LabelEncoder`

### Modelado Predictivo
- `xgboost.XGBRegressor`
- `sklearn.model_selection.RandomizedSearchCV`
- `sklearn.model_selection.train_test_split`
- `sklearn.metrics.mean_absolute_error`
- `sklearn.metrics.mean_squared_error`
- `sklearn.metrics.r2_score`

### Visualización
- `matplotlib.pyplot`
- `seaborn`

## 📥 Cómo Ejecutar el Proyecto

Clona el repositorio:
```bash
git clone https://github.com/usuario/proyecto-retail-ventas-futuras.git
cd proyecto-retail-ventas-futuras
```

