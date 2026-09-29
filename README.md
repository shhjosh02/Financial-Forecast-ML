# Financial-Forecast-ML

Sistema Híbrido de Alertas Tempranas para la Predicción de Tendencias Financieras mediante Análisis de Sentimiento y Machine Learning Multimodal.

## Objetivo

Construir un pipeline predictivo que clasifique si una noticia financiera provocará un movimiento al alza (Label=1) o a la baja/neutro (Label=0) en el precio de cierre de una acción, combinando NLP con indicadores cuantitativos de mercado.

## ¿Por qué es útil?

Permite anticiparse al mercado emitiendo alertas tempranas antes de que el mercado absorba por completo los impactos informativos.

## ¿Cómo funciona?

1. **Fase 1 (Notebook 01):** Carga, limpia y explora los datos.
2. **Fase 2 (Notebook 02):** Entrena modelos clásicos (Regresión Logística, Random Forest) y una red MLP en PyTorch.
3. **Fase 3 (Notebook 03):** Entrena una red LSTM híbrida (texto + números) en TensorFlow/Keras.

## Estructura del proyecto
A continuación se muestra la organización de carpetas y archivos del proyecto:
<img width="1672" height="941" alt="Estructura del financial forecast" src="https://github.com/user-attachments/assets/6d795969-aa53-4836-8131-325ef2642176" />

## Tecnologías usadas

| Herramienta | Para qué |
|-------------|----------|
| Pandas / NumPy | Carga y limpieza |
| Matplotlib / Seaborn | Gráficos |
| NLTK | NLP |
| Scikit-learn | ML clásico |
| PyTorch | MLP |
| TensorFlow / Keras | LSTM |

## Capturas

### Fase 1: Análisis Exploratorio

<img width="2327" height="1997" alt="eda_matriz_correlacion" src="https://github.com/user-attachments/assets/b643c510-a74e-40ca-a97b-adc3e78e0a73" />
<img width="2105" height="1227" alt="eda_histograma_kde" src="https://github.com/user-attachments/assets/27fa11a5-7e6c-4f1b-ba45-b8e8b12bab8d" />


### Fase 2: Modelos ML


<img width="2236" height="1242" alt="ml_feature_importance" src="https://github.com/user-attachments/assets/bc56ec65-3b6f-428f-a03a-18af69fe8578" />
<img width="2442" height="1243" alt="ml_comparativa_modelos" src="https://github.com/user-attachments/assets/1be3eb2a-072d-4db2-9769-2d11dc9e419f" />


### Fase 3: LSTM

<img width="3019" height="1217" alt="lstm_curvas_aprendizaje" src="https://github.com/user-attachments/assets/4ec19a36-299e-4c26-a710-1af25cb6f134" />
<img width="1943" height="1312" alt="lstm_curva_roc" src="https://github.com/user-attachments/assets/2cfd5cde-c7de-4dec-920a-0f9c4e13b4c8" />


## Cómo ejecutar

1. Clona el repo.
2. Instala las dependencias: `pip install -r requirements.txt`
3. Abre los notebooks en orden (01 → 02 → 03).

## Resultados

| Modelo | Accuracy |
|--------|----------|
| Regresión Logística | (pendiente) |
| Random Forest | (pendiente) |
| PyTorch MLP | (pendiente) |
| LSTM Híbrido | (pendiente) |

## Estado del proyecto

🚧 En desarrollo — Fase 1 y 2 completadas, Fase 3 en progreso.

## Autor

Joshua Calle Salazar — [LinkedIn](https://linkedin.com/in/joshua-calle-salazar-396932415)


