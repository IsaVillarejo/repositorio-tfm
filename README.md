# repositorio-tfm
Este repositorio contiene el código empleado para el procesamiento de los datos e implementación de modelos para la detección de fraude sobre el conjunto IEEE-CIS Fraud Detection de Kaggle. Se incluyen dos notebooks correspondientes a las dos perspectivas empleadas para el balanceo de datos

 - TFM_CLASSWEIGHT: preprocesamiento de datos e implementación de modelos usando técnica de ponderación de clases para abordar el problema de desbalanceo.
 - TFM_SMOTE: preprocesamiento de datos e implementación de modelos usando SMOTE para balancear las clases.

Descripción del dataset:
Se trata de un conjunto de datos real proporcionado por la competición IEEE-CIS Fraud Detection organizada en la plataforma Kaggle. El dataset está compuesto por un conjunto destinado al entrenamiento de los modelos y por otro de test destinado a evaluar los mismos. A su vez, cada uno de estos conjuntos consta de dos archivos principales: train_transaction.csv y train_identity.csv para el entrenamiento, y test_transaction.csv y test_identity.csv para el test. En cada caso, los datos sobre transacciones e identidad se integran mediante la variable clave TransactionID. 
El conjunto de entrenamiento consta de 590.540 instancias y 433características mas la avriable objetivo (isFraud), de 
las cuales 31 son categóricas y el resto numéricas.

Uso:
Cada notebook debe ejecutarse de forma independiente
