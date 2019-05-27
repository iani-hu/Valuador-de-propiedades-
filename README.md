# Real Estate predictor


Desafio 2 Curso de Data Science. Digital House

Autores:

Faro, Gonzalo

Cabrol, Angelica

Vinyolas, Mariana

Hutler, Ianina


Objetivos:

● Estimar un modelo de regresión lineal que realice predicciones para el precio por metro cuadrado. 
Deberá prestar cierta atención a la estructura espacial de los precios.

● Aplicar regularización a modelos lineales (pueden hacerlo para obtener un puntaje adicional). 
La idea es la siguiente: estimar una regresión Ridge y una LASSO sobre el dataset. 
Para ello, deberán usar cross-validation para tunear el parámetro de regularización que maximiza R2 en tu test set. 
¿Cómo son las performances entre los modelos regularizados y no regularizado? ¿Cuál funciona mejor? ¿Qué hace una regresión Ridge? 
¿Y una LASSO?¿Qué diferencias hay con la regresión lineal sin regularizar?

● Seleccionar mediante muestreo aleatorio simple una submuestra de 100 propiedades. Este será su portafolio de departamentos. 
En base al mejor modelo que haya encontrado determine cuáles de los departamentos, tanto en su portafolio como fuera de él, se encuentran
sobrevaluados o subvaluados y en qué magnitud.

● Teniendo en cuenta que podría comprar y vender propiedades al precio de mercado, omitamos costos de transacción, con un capital inicial
igual al valor de mercado de las propiedades en su portafolio. ¿Cuál es el mejor portafolio de propiedades que podría comprar?
