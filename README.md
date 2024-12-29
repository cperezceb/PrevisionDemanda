# Previsión de la Demanda
Este estudio presenta un modelo para predecir la demanda de productos en una empresa de distribución del sector de la automoción. Se aplican técnicas avanzadas de ciencia de datos para obtener previsiones de demanda más precisas y, por ende, mejorar la gestión de stock.

La metodología de este estudio incluye la recolección y limpieza de datos, identificar patrones y tendencias, seleccionar las características relevantes y evaluar diferentes modelos. 
Se elegirá el modelo que mejor se ajusta a nuestros datos para ofrecer predicciones de la demanda futura.

En la carpeta de Preparación se encuentra un fichero desarrollado en R donde se trabaja para obtener un conjunto de datos de calidad con el que entrenar a los distintos modelos. Incluye analisis descriptivo, valores nulos, inexistentes, transformaciones, varios conjuntos de datos, outliers, estudio de la serie temporal, clustering...

En la carpeta de Modelos se encuentran por separado los distintos modelos evaluados, al inicio se pone una breve explicación de las características y todos parten del mismo conjunto de datos. Por cuestiones de rendimiento están configurados para que tomen los datos de 10 artículos. Son evaluados con las métricas RMSE, MSE, MAE, R2. 

También se proporciona la generación en formato HTML.
