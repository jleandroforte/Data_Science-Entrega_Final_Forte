# Data_Science-Entrega_Final_Forte
Mediante este trabajo utilizaremos datos del website de una farmacia online a lo largo de 90 días de observaciones para predecir el revenue, o ingreso por ventas, utilizando fundamentalmente distintos modelos de regresión.

Tenemos información sobre varias características de los productos, sus precios, los precios de la competencia, y también sobre el comportamiento de los clientes, a saber, si hacen click en un producto, si los colocan en una canasta de productos y finalmente si compran un producto. Nótese que no todas las líneas del dataset representan ventas.

Finalmente, una vez que se produce una venta, tenemos un ingreso monetario, "revenue", que constituirá nuestra variable objetivo a lo largo de la mayor parte del trabajo, con excepciòn del apéndice final, en el cual vamos a explorar también la posibilidad de predecir ventas, lo cual requeriría la aplicación de modelos de clasificación.

Una clave del dataset es que la farmacia sigue una política de 'pricing dinámico' donde los precios de cada producto son ajustados diariamente, dentro de ciertas bandas. Es decir, los productos no tienen un precio constante a lo largo de los 90 días de observaciones, sino que presentan pequeñas variaciones diarias.

Veremos que modelos de regresión de ensamble y_o boosting se adaptan bien a nuesttra estructura de datos, logrando obtener predicciones adecuadas de revenue. 
