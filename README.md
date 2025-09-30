# RNAs-online: Redes Neuronales Artificiales

**Descripción del curso:**

Este curso avanzado proporciona una exploración exhaustiva de técnicas de aprendizaje automático avanzadas, centrándose en redes neuronales artificiales y técnicas de aprendizaje profundo como LSTM, CNN, GAN y transformers. Los estudiantes aprenderán a diseñar, entrenar y aplicar modelos de redes neuronales avanzados para una variedad de aplicaciones prácticas.

El curso está orientado al uso de **Python** con **TensorFlow/Keras** y **PyTorch**, los frameworks más utilizados en la industria y la academia para aprendizaje profundo. Se recomienda trabajar en **Google Colab**, complementado con asistentes de IA como **Gemini**, que facilitan la escritura y depuración de código.

Adicionalmente, se incluyen **ejercicios introductorios en KNIME**, con el fin de ofrecer una perspectiva visual y de flujo de trabajo que ayude a comprender de manera intuitiva las etapas de análisis de datos y modelado.

### Docente

[Mario González](https://sitios.udla.edu.ec/direccion-investigacion-vinculacion/grupos-de-investigacion/si2lab/)

- [Perfil Google scholar](https://scholar.google.co.uk/citations?user=cmuZCwsAAAAJ&hl=en)

### Contenido

| Semana | Notebook                          | Temas| 
| :---:  | :---------------------------------------------   | :---------------------------------------------   |
| 1      | [Introducción a las redes neuronales](https://marsgr6.github.io/presentations/rnas_html/S1/S1_intro_ann.html) | Introducción a las redes neuronales: desde la neurona de McCulloch-Pitts hasta el perceptrón multicapa, explorando los fundamentos del procesamiento neuronal artificial. |
|       | [Entrenando una red simple](https://marsgr6.github.io/presentations/rnas_html/S1/S1_intro_ann.html#rlsnn) | Estudio de la minimización del error en redes neuronales: desde la **función de pérdida (error)** hasta los algoritmos de optimización como descenso del gradiente. |
|       | [Perceptrón Multicapa (MLP)](https://marsgr6.github.io/presentations/rnas_html/S1/S1_intro_ann.html#mlp) | Introducción al Perceptrón Multicapa (MLP): estructura de capas ocultas, aprendizaje de funciones no lineales y entrenamiento mediante el algoritmo de retropropagación del error. |
| 2      | [Optimización de hiperparámetros y evaluación de un MLP](https://marsgr6.github.io/presentations/rnas_html/S2/S2.2_mlp_hyperparameter_optimization.html) | Optimización de hiperparámetros de un MLP. Cross-validation, y grid search. | 
|        | [Redes neuronales para problemas de clasificación y regresión](https://marsgr6.github.io/presentations/rnas_html/S2/S2.1_ann_dnn.html) | Redes neuronales artificiales, redes feedforward, retro propagación, deep neural networks. Aplicación a clasificación y regresión. | 
| 3      | [Modelado de datos temporales y espaciales](https://marsgr6.github.io/presentations/rnas_html/S3/S3_cnn_yolo.html) | LSTM para series temporales, CNN para detección de objetos. |
| 4      | [SAITS y transformers para series temporales](https://marsgr6.github.io/presentations/rnas_html/S4/S4.1_saits_transformers_ts.html) | Aplicación de Transformers al modelado de series temporales: una aproximación moderna para capturar dependencias a largo plazo y patrones secuenciales complejos. SAITS para imputación de valores faltantes en series temporales.|
|        | [LSTM, transformers, GAN](https://marsgr6.github.io/presentations/rnas_html/S4/S4.2_lstm_transformers_gan.html) | LSTM y transformers para análisis de texto, GAN para aumentación de datos, transfer learning. |

### Ejercicios Colab+Gemini

- [**Tutorial de Colab**](https://marsgr6.github.io/presentations/rnas_html/colab_ai_tutorial.html)

Se propone que, en cada ejercicio a continuación, el estudiante realice de manera autónoma un **Análisis Exploratorio de Datos (EDA)**, a fin de complementar el material proporcionado y fortalecer la comprensión del proceso de modelado.

### 🔹 EDA en Clasificación

* Verificar **equilibrio de clases** (conteo de instancias por categoría).
* **Distribuciones por clase** usando histogramas o **KDE plots**.
* **Boxplots agrupados por el target** para comparar la variación de atributos entre clases.
* Análisis de **correlación entre variables** y su relación con la clase.
* Identificación de **outliers** o valores atípicos dentro de cada clase.
* **Matrices de confusión preliminares** con modelos simples para explorar separabilidad.

### 🔹 EDA en Regresión

* Revisar la **distribución del target** (histograma, KDE, boxplot).
* Análisis de **correlación (correlation matrix)** entre las variables predictoras y el target.
* Uso de **pairplots** para explorar relaciones bivariadas.
* Detección de **outliers** en la variable objetivo y en los predictores.
* Comprobación de **tendencias o patrones temporales**, en caso de series de tiempo.
* Verificación de **linealidad** o necesidad de transformaciones (log, sqrt, etc.).

| Semana | Notebook | Temas |
|--------|----------|-------|
| 1 | [Semana 1 – Clasificación y Regresión (Colab).html](https://marsgr6.github.io/presentations/rnas_html/S1/S1_RNAs_colab.html) | **Clasificación:** dataset Breast Cancer. **Regresión:** dataset Diabetes. Introducción a redes neuronales, función de pérdida y entrenamiento de perceptrones multicapa. |
| 2 | [Semana 2 – Optimización de Hiperparámetros (Colab).html](https://marsgr6.github.io/presentations/rnas_html/S2/S2_RNAs_colab.html) | Optimización de hiperparámetros en MLP con **cross-validation** y **grid search**, usando los mismos datasets (breast cancer y diabetes). |
| 3 | [Semana 3 – Series Temporales LSTM (Colab).html](https://marsgr6.github.io/presentations/rnas_html/S3/S3_RNAs_LSTM_colab.html) | Modelado de series temporales con **LSTM** (usuarios/visitas web). |
|   | [Semana 3 – CNN Fashion-MNIST (Colab).html](https://marsgr6.github.io/presentations/rnas_html/S3/S3_RNAs_CNN_colab.html) | **CNN** aplicadas a la clasificación de imágenes con **Fashion-MNIST**. |
| 4 | [Semana 4 – Transformers y Autoencoder (Colab).html](https://marsgr6.github.io/presentations/rnas_html/S4/S4.1_saits_transformers_ts.html) | **SAITS y Transformers** para series temporales: imputación de valores faltantes y modelado de dependencias complejas. |

Ejercicios prácticos en **KNIME (PDF)**. Se sugiere que el estudiante realice de manera autónoma un **Análisis Exploratorio de Datos (EDA)** en cada caso, como parte fundamental del flujo de trabajo en ciencia de datos.  

| Semana | Notebook | Temas |
|--------|----------|-------|
| 1 | [Clasificación y Regresión (KNIME).pdf](https://marsgr6.github.io/presentations/rnas_html/S1/S1_KNIME.pdf) | **Clasificación:** dataset Breast Cancer. **Regresión:** dataset Diabetes. Introducción a redes neuronales, función de pérdida y entrenamiento de perceptrones multicapa. |
| 2 | [Optimización de Hiperparámetros (KNIME).pdf](https://marsgr6.github.io/presentations/rnas_html/S2/S2_KNIME.pdf) | Optimización de hiperparámetros en MLP con **cross-validation** y **grid search**, usando los mismos datasets (breast cancer y diabetes). |
| 3 | [Series Temporales LSTM (Bike Sharing, KNIME).pdf](https://marsgr6.github.io/presentations/rnas_html/S3/S3_KNIME.pdf) | **Series temporales:** predicción de usuarios en el dataset *Bike Sharing* con **LSTM**. |
|   | [CNN Fashion-MNIST (KNIME).pdf](https://marsgr6.github.io/presentations/rnas_html/S3/S3_KNIME.pdf) | **CNN** aplicadas a clasificación de imágenes con **Fashion-MNIST**. |
| 4 | [Autoencoder (KNIME).pdf](https://marsgr6.github.io/presentations/rnas_html/S4/S4_KNIME.pdf) | **Autoencoder** para detección de fraude. |


