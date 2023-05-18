# Birthdays Flask
Ésta práctica consiste en crear una página web en con flask para registrar y mostrar los cumpleaños de una base de datos

## app.py
En app.py debemos codificar que hacen nuestros métodos post y get.
### Get
En get debemos mandarle a nuestra página web index.html los valores de nuestra base de datos para que en el html, mediante un for muestre los datos de nuestra base de datos en una tabla.
### Post
En post, recogemos los datos que nos manda el html según el form, y hacemos el insert en nuestra base de datos.

## index.html
Esta es nuestra página web, aquí mostramos las fechas de cumpleaños en una tabla cuyos valores nos mandan desde app.py y también podemos insertar nuevos cumpleaños en nuestra base de datos.

Finalmente, si ejecutamos nuestro programa con flask run, podremos ver el resultado de nuestra web.