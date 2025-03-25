# DataWrangling
Se llevará el proceso de datos completo para un analista: estudiar tus datos, limpiarlos cuidadosamente y ocuparte de los valores ausentes y duplicados, responder preguntas analíticas y visualizar los hallazgos.


# Descripción del proyecto
Para este proyecto, trabajarás con datos de Instacart.

Instacart es una plataforma de entregas de comestibles donde la clientela puede registrar un pedido y hacer que se lo entreguen, similar a Uber Eats y Door Dash. Este conjunto de datos particular fue lanzado públicamente (materiales en inglés) por Instacart en 2017 para una competición Kaggle (materiales en inglés). Los datos reales pueden descargarse directamente de la página de la competición Kaggle.

El conjunto de datos que te hemos proporcionado tiene modificaciones del original. Redujimos el tamaño del conjunto para que tus cálculos se hicieran más rápido e introdujimos valores ausentes y duplicados. Tuvimos cuidado de conservar las distribuciones de los datos originales cuando hicimos los cambios.

Tu misión es limpiar los datos y preparar un informe que brinde información sobre los hábitos de compra de los clientes de Instacart. Después de responder a cada pregunta, escribe una breve explicación de tus resultados en una celda markdown de tu Jupyter notebook.

Este proyecto requerirá que hagas gráficos que comuniquen tus resultados. Asegúrate de que cualquier gráfico que vayas a crear tenga un título, ejes etiquetados y una leyenda si es necesario; e incluye plt.show() al final de cada celda con un gráfico.

# Paso 2: Preprocesa los datos de la siguiente manera:

Verifica y corrige los tipos de datos (por ejemplo, asegúrate de que las columnas de ID sean números enteros).
Identifica y completa los valores ausentes.
Identifica y elimina los valores duplicados.
Asegúrate de explicar qué tipos de valores ausentes y duplicados encontraste, cómo los completaste o eliminaste y por qué usaste esos métodos. ¿Por qué crees que estos valores ausentes y duplicados pueden haber estado presentes en el conjunto de datos?

# Paso 3: Una vez que los datos estén procesados y listos, haz el siguiente análisis:


Verifica que los valores en las columnas 'order_hour_of_day' y 'order_dow' de la tabla orders sean razonables (o sea, 'order_hour_of_day' va de 0 a 23 y 'order_dow' va de 0 a 6).
Crea un gráfico que muestre el número de personas que hacen pedidos dependiendo de la hora del día.
Crea un gráfico que muestre qué día de la semana la gente hace sus compras.
Crea un gráfico que muestre el tiempo que la gente espera hasta hacer su próximo pedido, y comenta los valores mínimos y máximos.

¿Hay alguna diferencia en las distribuciones de 'order_hour_of_day' en miércoles y sábados? Traza los histogramas de ambos días en el mismo gráfico y describe las diferencias que observes.
Traza la distribución del número de pedidos que hacen los clientes y las clientas (por ejemplo, cuántos clientes hicieron un solo pedido, cuántos hicieron solo dos, cuántos solo tres, etc.)
¿Cuáles son los 20 principales productos que se piden con más frecuencia (muestra su identificación y nombre)?

¿Cuántos artículos compra la gente por lo general en un pedido? ¿Cómo es la distribución?
¿Cuáles son los 20 principales artículos que se vuelven a pedir con más frecuencia (muestra sus nombres e identificaciones de producto)?
Para cada producto, ¿qué proporción de sus pedidos se vuelven a pedir (crea una tabla con columnas para el ID del producto, el nombre del producto y la proporción en que se ha vuelto a comprar)?
¿Cuál es la proporción de productos pedidos que se vuelven a pedir para cada cliente?
¿Cuáles son los 20 principales artículos que la gente pone en sus carritos primero (muestra las identificaciones de los productos, los nombres de los productos y el número de veces que fueron el primer artículo añadido al carrito)?