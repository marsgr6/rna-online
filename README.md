# RNAs-online: Redes Neuronales Artificiales

**Descripción del curso:**

Este curso introductorio proporciona una exploración exhaustiva de técnicas de aprendizaje automático, centrándose en redes neuronales artificiales y técnicas de aprendizaje profundo como LSTM, CNN, GAN y transformers. Los estudiantes aprenderán a diseñar, entrenar y aplicar modelos de redes neuronales avanzados para una variedad de aplicaciones prácticas.

El curso está orientado al uso de **Python** con **TensorFlow/Keras** y **PyTorch**, los frameworks más utilizados en la industria y la academia para aprendizaje profundo. Se recomienda trabajar en **Google Colab**, complementado con asistentes de IA como **Gemini**, que facilitan la escritura y depuración de código.

Adicionalmente, se incluyen **ejercicios introductorios en KNIME**, con el fin de ofrecer una perspectiva visual y de flujo de trabajo que ayude a comprender de manera intuitiva las etapas de modelado.

### Docente

[Mario González](https://sitios.udla.edu.ec/direccion-investigacion-vinculacion/grupos-de-investigacion/si2lab/)

- [Perfil Google scholar](https://scholar.google.co.uk/citations?user=cmuZCwsAAAAJ&hl=en)

## Contenido

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

- Resumen ([mapas conceptuales](https://github.com/marsgr6/rna-online/tree/main/misc/mapas)) de los modelos más comunes de redes neuronales.
  
- Repositorio [GitHub](https://github.com/marsgr6/rna-online) del contenido ([descargar](https://github.com/marsgr6/rna-online/archive/refs/heads/main.zip))

- [Tinker With a Neural Network Right in Your Browser](https://playground.tensorflow.org/)

- [NN-SVG](https://alexlenail.me/NN-SVG/)

- [Netron](https://netron.app/)

## Ejercicios Colab+Gemini

- [Tutorial de Colab](https://marsgr6.github.io/presentations/rnas_html/colab_ai_tutorial.html)

| Semana | Notebook | Temas |
|--------|----------|-------|
| 1 | [Clasificación y Regresión (Colab)](https://marsgr6.github.io/presentations/rnas_html/S1/S1_RNAs_colab.html) | **Clasificación:** dataset Wine. **Regresión:** dataset Diabetes. Introducción a redes neuronales, función de pérdida y entrenamiento de perceptrones multicapa. |
| 2 | [Optimización de Hiperparámetros (Colab)](https://marsgr6.github.io/presentations/rnas_html/S2/S2_RNAs_colab.html) | Optimización de hiperparámetros en MLP con **cross-validation** y **grid search**, usando los mismos datasets (breast cancer y diabetes). |
| 3 | [Series Temporales LSTM (Colab)](https://marsgr6.github.io/presentations/rnas_html/S3/S3_RNAs_LSTM_colab.html) | Modelado de series temporales con **LSTM** (usuarios/visitas web). |
|  | [CNN Fashion-MNIST (Colab)](https://marsgr6.github.io/presentations/rnas_html/S3/S3_RNAs_CNN_colab.html) | **CNN** aplicadas a la clasificación de imágenes con **Fashion-MNIST**. |
| 4 | [Transformers y Autoencoder (Colab)](https://marsgr6.github.io/presentations/rnas_html/S4/S4.1_saits_transformers_ts.html) | **SAITS y Transformers** para series temporales: imputación de valores faltantes y modelado de dependencias complejas. |

- [Descargar notebooks colab](https://github.com/marsgr6/rna-online/raw/refs/heads/main/misc/colab_ipynb.zip)

## Ejercicios KNIME

- [Instalación de KNIME](https://marsgr6.github.io/presentations/rnas_html/KNIME_Installation.pdf)

Ejercicios prácticos en **KNIME (PDF)**.  

| Semana | Notebook | Temas |
|--------|----------|-------|
| 1 | [Clasificación y Regresión (KNIME)](https://marsgr6.github.io/presentations/rnas_html/S1/S1_KNIME.pdf) | **Clasificación:** dataset Breast Cancer. **Regresión:** dataset Diabetes. Introducción a redes neuronales, función de pérdida y entrenamiento de perceptrones multicapa. |
| 2 | [Optimización de Hiperparámetros (KNIME)](https://marsgr6.github.io/presentations/rnas_html/S2/S2_KNIME.pdf) | Optimización de hiperparámetros en MLP con **cross-validation** y **grid search**, usando los mismos datasets (breast cancer y diabetes). |
| 3 | [Series Temporales LSTM (Bike Sharing, KNIME)](https://marsgr6.github.io/presentations/rnas_html/S3/S3_KNIME.pdf) | **Series temporales:** predicción de usuarios en el dataset *Bike Sharing* con **LSTM**. |
| 4 | [CNN Fashion-MNIST (KNIME)](https://marsgr6.github.io/presentations/rnas_html/S3/S3_KNIME.pdf) | **CNN** aplicadas a clasificación de imágenes con **Fashion-MNIST**. |
|   | [Autoencoder (KNIME)](https://marsgr6.github.io/presentations/rnas_html/S4/S4_KNIME.pdf) | **Autoencoder** para detección de fraude. |

- [Descargar datos y workflows KNIME](https://udlaec-my.sharepoint.com/:f:/g/personal/mario_gonzalez_rodriguez_udla_edu_ec/EvtXdO57yQ5JnuayR5xJTk0BsZXPg1ZA22iYY2wkGgIT5A?e=8I8cFT)

### Fuentes y Recursos (KNIME)

### Artículos Científicos
- Villarroel Ordenes, F., & Silipo, R. (2021). Machine learning for marketing on the KNIME Hub: The development of a live repository for marketing applications. *Journal of Business Research*, 137(1), 393-410. DOI: [10.1016/j.jbusres.2021.08.036](https://doi.org/10.1016/j.jbusres.2021.08.036), [KNIME Hub Space](https://hub.knime.com/knime/spaces/Machine%20Learning%20and%20Marketing/~JyadcetnSt5U1vcw/)

- KNIME Hub – Example Workflows Repository. Disponible en: [https://hub.knime.com/knime/spaces/Examples/~h7x1z5Px5dNWE24v/](https://hub.knime.com/knime/spaces/Examples/~h7x1z5Px5dNWE24v/)

### Libros
- Melcher, K., & Silipo, R. (2021). *Codeless Deep Learning with KNIME*. Packt Publishing. [KNIME Hub Space](https://hub.knime.com/kathrin/spaces/Codeless%20Deep%20Learning%20with%20KNIME/~yMp8GBkT0Xwzx5X2/)

## 📘 Ejercicios Prácticos Autónomos (Tareas)

| Semana | Enunciado                                                                                  | Temas                                                                                                                                                                                                                               |
| ------ | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1      | [Clasificación y/o Regresión.](https://marsgr6.github.io/presentations/rnas_html/S1/Tarea_semana_1.html) | Clasificación con dataset **Breast Cancer**. Introducción a redes neuronales, función de pérdida y entrenamiento de perceptrones multicapa. |
| 2      | [Optimización de Hiperparámetros](https://marsgr6.github.io/presentations/rnas_html/S2/Tarea_semana_2.html) | Uso de **cross-validation** y **grid search** en MLP. Aplicación al datasets **Breast Cancer** |
| 3      | [CNN on MNIST digits y/o Series Temporales con LSTM](https://marsgr6.github.io/presentations/rnas_html/S3/Tarea_semana_3.html) | **CNN para clasificar imágenes**: MNIST digits dataset. **Series Temporales con LSTM:** Construcción de un modelo LSTM y análisis de resultados.                                                                       |
| 4      | [SAITS, Transformers y Sentiment Analysis](https://marsgr6.github.io/presentations/rnas_html/S4/Tarea_semana_4.html) | **SAITS y Transformers** para series temporales. Implementación de un **clasificador de sentimientos** en KNIME.                                                                                                                  |

**Ejemplos**

* [Descargar datasets y workflows](https://udlaec-my.sharepoint.com/:f:/g/personal/mario_gonzalez_rodriguez_udla_edu_ec/EvtXdO57yQ5JnuayR5xJTk0BsZXPg1ZA22iYY2wkGgIT5A?e=8I8cFT)
* [Descargar notebooks colab](https://github.com/marsgr6/rna-online/raw/refs/heads/main/misc/colab_ipynb.zip)

## 📂 Recursos adicionales

- [Modern Computer Vision with PyTorch](https://github.com/PacktPublishing/Modern-Computer-Vision-with-PyTorch-2E)
- Pyrcz, M.J., 2024, Applied Machine Learning in Python: A Hands-on Guide with Code. Zenodo. doi:10.5281/zenodo.15169138, [e-book](https://geostatsguy.github.io/MachineLearningDemos_Book/MachineLearning_ANN.html)
- [Neural networks from scratch - Animations](https://nnfs.io/neural_network_animations)
- [Data Science Interactive with Python](https://github.com/GeostatsGuy/DataScienceInteractivePython/tree/main)

