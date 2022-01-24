# practica-consultas-mongodb

El formato es: "consulta a realizar" - Número de documentos que satisfacen dicha consulta

Acordaos que podeis obtener el número de documentos de una consulta con db.restaurants.find().count()

ENCONTRAR - base de datos **sample_restaurants**, en la coleccion de **restaurant**

- Encuentra todos los restaurantes cuyo tipo de cocina sea "American" - 6183
- Encuentra todos los restaurantes que estan ubicados en el barrio (borough) the 'Queens' - 5656
- Encuentra si existe un restaurante cuyo nombre sea "Cafe Espanol" - 2
- Encuentra todos los restaurantes que, en su nombre (name), contengan la palabra 'Cafe'. Debes

usar una expresion regular - 1650

- Encuentra todos los restaurantes que esten en el edificio '41' - 34
- Encuentra todos los restaurantes que esten en el edificio '41' o en el edificio '66' - 62

ENCONTRAR - base de datos sample_mflix, en la coleccion de 'movies'

- Todas las peliculas entre filmadas antes del 1917 (columna 'year') - 24
- Crea una proyeccion, de manera que el comando find tan solo muestre el 'title' de la pelicula
- Crea una proyeccion, de manera que el comando find tan solo muestre el 'title' de todas las películas

filmadas antes del 1912.

- Muestra todas las peliculas cuyo género (genres) sea 'Short' Y ADEMáS 'Romance' Y TAMBIÉN 'Animation' . Mirar

el operador logico $all

- Encuentra todas las películas que tienen la propiedad 'rated' con algún valor. Mirar el operador $exists
- Encuentra todas las películas que tienen la propiedad 'rated' con el valor 'G'. Mirar el operador $exists y $and.

BORRAR - base de datos sample_mflix, en la coleccion de 'movies'

Antes de borrar, comprueba tu consula con un find

- Borra todas las películas cuyo campo 'rating' en la propiedad 'imdb' sea menor de 5. - 1288

Una vez acabada la tarea podeis practicar un poco más con las planteadas en [](https://www.w3resource.com/mongodb-exercises/mongodb-exercise-2.php)[esta página](https://www.w3resource.com/mongodb-exercises/)
