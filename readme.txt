pasos 
*******************
explorar datos
pre procesarlos para que el modelo de ml los tome regresion logistica binaria
escalado en las columnas numericas: lat, lon, fechas,numero de baños
variables dummies con tipo de propiedad, tipo de moneda 
------->archivo Exploring-the-data_test
------->Exploring-the-data_train
********************
realizar prediccion con diferentes metodos de preprocesamiento:  StandardScaler,MinMaxScaler,MaxAbsScaler,RobustScaler  
----->carpeta jupyter nt
********************
guardalos en un archivo csv de una sola columna con la prediccion realizada 0,1(barato o caro)

Type of Scaling	Test_Accuracy

StandardScaler	70.96306367550419
MinMaxScaler	70.55286304074673
MaxAbsScaler	70.912127093018
RobustScaler	70.4969652717565
