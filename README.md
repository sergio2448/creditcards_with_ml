# Detección de fraude con tarjetas de crédito mediante Machine Learning en Python

## Dataset

El conjunto de datos contiene transacciones realizadas con tarjetas de crédito en septiembre de 2013 por titulares de tarjetas europeos.
El conjunto de datos presenta transacciones que ocurrieron en dos días, donde tenemos 492 fraudes de 284,807 transacciones. El conjunto de datos está desbalanceado, la clase positiva (fraudes) representa el 0,172 % de todas las transacciones.

Contiene solo variables de entrada numéricas que son el resultado de una transformación PCA. Las características V1, V2, … V28 son los principales componentes obtenidos con PCA, las únicas características que no han sido transformadas con PCA son 'Time' y 'Amount'. La característica 'Time' contiene los segundos transcurridos entre cada transacción y la primera transacción en el conjunto de datos. La característica 'Amount' es la cantidad de la transacción. 'Class' es la variable de respuesta y toma valor 1 en caso de fraude y 0 en caso contrario.

El dataset es tomado de kaggle <a href='https://www.kaggle.com/mlg-ulb/creditcardfraud' target='_blank'>aquí</a>.

## Desarrollo

Se toman diferentes medidas de performance aplicando los algorítmos KNeighborsClassifier, LogisticRegression y DecisionTreeClassifier variando los métodos de balanceo: con el conjunto desbalanceado, balanceando con Oversampling (SMOTE, ADASYN) y balanceando con Undersampling (EditedNearestNeighbours,
RandomUnderSampler).
                                  

