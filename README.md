# 20191.DL Fundamentos de Deep Learning
### 2019 - Semestre I - Pregrado Ingeniería de Sistemas Universidad de Antioquia


## Programa (antiguo, sólo por referencia)

```
                   TUE                                THU
   week# starts    CLASSROOM 20-238                   CLASSROOM 20-234         
----------------------------------------------------------------------------------------------
    W01 05/jun     Intro.ML1                          Intro.ML2
    W02 10/jun     U1.Intro.NN                        Lab 1.1
    W03 17/jun     U2.NN.Archs.TrainAlgs.Reg          Lab 2.1         23/jul DLC1
-------------------- VACACIONES --------------------------------
    W04 08/jul     U2.NN.Initz.Batch.Relu.Vanish      Lab 2.2
    W05 15/jul     Labs                               Parcial         21/jul Deadline Lab1 Lab2
    W06 22/jul     U3.CNN.ConvOp.Archs                Lab 3.1
    W07 29/jul     U3.CNN.Classf.Detectn.Segmtn       Lab 3.2         04/ago Deadline U3.05-3.11
    W08 05/ago     U3.CNN.Transfer Learning           Lab 3.3         11/ago Deadline U3.15-3.17
    W09 19/ago     U3.Proyecto                        U3.Proyecto
    W10 26/ago     U3.Proyecto                        U3.Proyecto     01/sep Deadline U3.Proyecto
    W11 02/sep     U4.RNN.SeqModels.BProp in Time     Lab 4.1         05/sep presentación proyectos seleccionados
    W12 09/sep     U4.RNN.LSTM.Archs.Seq2Seq          Lab 4.2
    W13 16/sep     U4.RNN.CNN-LSTM                    Lab 4.3         21/sep Deadline Lab4
    W14 23/sep     U4.Proyecto                        U4.Proyecto
    W15 30/sep     U4.Proyecto                        U4.Proyecto
    W16 07/oct                                                        10/oct Deadline U4.Proyecto
```
**calendario**

       5 jun           inicio clases
      12 ago           40% evaluación (recomendado)
      12 oct           finalización de las clases
      14 oct           fecha límite cierre notas finales
      14-19 oct        habilitaciones
      21-16 oct        validación y reporte de notas
      28 oct           cierre oficial semestre
    
 ## Evaluación
 
     10% Parcial
     10% Lab1 + Lab 2
     15% Lab 3
     15% Lab 4
     25% U3.Proyecto
     25% U4.Proyecto
     
## Proyectos

Para el proyecto U3 (redes convolucionales) y U4 (redes recurrentes) tendrás que:

- escoger un dataset, de un tema de tu interés, de tu investigación, etc.
- plantear una tarea de aprendizaje junto con una métrica de evaluación (p.ej. clasificación, detección, etc.)
- plantear una estrategia de resolución (preprocesado, arquitectura de red, trasnfer learning, data augmentation, feature learning, etc.)
- implementar el flujo de trabajo experimental

### Entrega

Tu entrega habrá de ser **un repositorio github** con uno o varios notebooks donde proveas evidencia del trabajo realizado, incluyendo experimentos pruebas, etc.

**Para realizar tu entrega**, crea un documento llamado `U3.Proyecto` o `U4.Proyecto` en el Google drive compartido, que contenga el enlace a tu repositorio github. Si llamas distinto a este documento **no será tenido en cuenta**.

### Criterios de evaluación

- **25% Reproducibilidad**: Tus notebooks han de ser 100% ejecutables sin errores, desde la descarga de datos hasta la obtención de tus resultados. Si lo consideras necesario crea un fichero descargable con tus datos y publícalo en algún lado como están en los notebooks del curso. **No incluyas los datos en el repositorio**.
- **25% Claridad**: Explica bien tu tarea (en los mismos notebooks), la métrica de evaluación que ests usando y el ciclo experimental que hiciste (probé tales arquitecturas de red, el modelo final tiene tal arquitectura porque las anteriores sufrían de overfitting, etc.) 
- **25% Repositorio**: Tu repositorio ha de estar ordenado, con una estructura clara y con un README.md que indique qué notebooks ejecutar con tu resultado final, qué notebooks contienen los experimentos previos que hiciste, etc.
- **25% Compleción**: Tu tarea ha de utilizar las técnicas vistas en clase y ha de demostrar un flujo experimental (prueba de varias arquitecturas, preprocesados, etc.). Igualmente has de incluir una **interpretación de tus resultados**.

### Presentación

Si se te requiere tendrás que realizar una **breve presentación** de tu proyecto, teniendo en cuenta que:

- la presentacin ha de durar **10 minutos**. Esto es un límite **estricto**. Al cabo de ese tiempo se cortará la presentación esté en el punto que esté.
- Tendrás que presentar **tres aspectos**: 1) qué tarea se resolvió, 2) qué experimentos se hicieron, 3) tus conclusiones e interpretación de los resultados.
- La calificación será **un factor entre 0.5 y 1.5**, que se multiplicará con la calificación obtenida a la entrega para obtener la calificación final.

 ## Registro y materiales
 
 - [Listado de estudiantes](https://docs.google.com/spreadsheets/d/1jbCc0ZHC5qFMhwMEpoCgSFzHwP6lx_V77E4Blh6Tk38/edit#gid=2001230691)
 - [Máquina virtual del curso](https://drive.google.com/file/d/1VI5oU_gQQ0LO_Eoiq8N66j1zgi8-vC6j/view?usp=sharing)
 

## Lecturas recomendadas

- Hastie, Tibshirani, Friedman, **The Elements of Statistical Learning**, Springer-Verlag [website](https://web.stanford.edu/~hastie/ElemStatLearn/) [pdf](https://web.stanford.edu/~hastie/ElemStatLearn/printings/ESLII_print12.pdf)
- Goodfellow, Bengio, Courville, **Deep Learning**, MIT Press [website](https://www.deeplearningbook.org/) [pdf](https://github.com/janishar/mit-deep-learning-book-pdf)
- Bengio, **Learning Deep Architectures for AI**, Foundations and Trends in
Machine Learning, Vol. 2, No. 1 (2009) 1–127, [pdf](http://www.iro.umontreal.ca/~bengioy/papers/ftml_book.pdf)


## Laboratorios (_Programming Assignments_) de deeplearning.ai
[C1. Neural Networks and Deep Learning](https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning)
- Lab1 Logistic Regression with a Neural Network mindset
- Lab2 Planar data classification with a hidden layer
- Lab3 Building your Deep Neural Network - Step by Step

[C2. Improving Deep Neural Networks](https://www.coursera.org/learn/deep-neural-network?specialization=deep-learning)
- Lab1 Initialization
- Lab2 Regularization
- Lab3 Gradient checking
- Lab4 Optimization
- Lab5 Tensorflow

[C3 Structuring Machine Learning Projects](https://www.coursera.org/learn/machine-learning-projects)
No programming asignments, only quizes

[C4. Convolutional Neural Networks](https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning)
- Lab1 Convolutional model: step by step
- Lab2 Convolutional model application
- Lab3 Residual Networks
- Lab4 Car Detection with YOLOv2
- Lab5 Art generation
- Lab6 Face recognition

[C5 Sequence models](https://www.coursera.org/learn/nlp-sequence-models)
- Lab1 Building a RNN step by step
- Lab2 Character level language modeling
- Lab3 Jazz improvisation with LSTM
- Lab4 Operations on word vectors
- Lab5 Emojify
- Lab6 Neural machine translation
- Lab7 Trigger word detection|



## Programa basado en talleres de DeepLearning AI

```
                   TUE                                THU
   week# starts    CLASSROOM 20-238                   CLASSROOM 20-234         
----------------------------------------------------------------------------------------------
    W01 05/jun     Intro.ML1                          Intro.ML2
    W02 10/jun     U1.Intro.NN                        Lab 1.1
    W03 17/jun     U2.NN.Archs.TrainAlgs.Reg          Lab 2.1         23/jun C1 
-------------------- VACACIONES --------------------------------
    W04 08/jul     U2.NN.Initz.Batch.Relu.Vanish      Lab 2.2
    W05 15/jul     Labs                               Parcial         21/jul C2 
    W06 22/jul     U3.CNN.ConvOp.Archs                Lab 3.1
    W07 29/jul     U3.CNN.Classf.Detectn.Segmtn       Lab 3.2         
    W08 05/ago     U3.CNN.Transfer Learning           Lab 3.3         04/ago C4 Lab1,2,3
    W09 19/ago     U3.Proyecto                        U3.Proyecto
    W10 26/ago     U3.Proyecto                        U3.Proyecto     04/ago C4 Lab4,5,6
    W11 02/sep     U4.RNN.SeqModels.BProp in Time     Lab 4.1         
    W12 09/sep     U4.RNN.LSTM.Archs.Seq2Seq          Lab 4.2
    W13 16/sep     U4.RNN.CNN-LSTM                    Lab 4.3         21/sep C5 Lab1,2,3
    W14 23/sep     U4.Proyecto                        U4.Proyecto
    W15 30/sep     U4.Proyecto                        U4.Proyecto     07/Oct C5 Lab4,5,6
    W16 07/oct                                                        
```
