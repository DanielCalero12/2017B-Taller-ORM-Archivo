# 2017B-Taller-ORM-Archivo

1)Se descarga Postman https://www.getpostman.com/downloads/ de este enlace y se ejecuta

![alt text](https://github.com/DanielCalero12/2017B-Taller-ORM-Archivo/blob/master/images/Captura.PNG)

2)Para verificar las tablas ingresadas en la base de datos, se hace a travez de request Get 

![alt text](https://github.com/DanielCalero12/2017B-Taller-ORM-Archivo/blob/master/images/Captura2.PNG)

3)Se agregar la url http://node21.codenvy.io:37830/contacts en enter request url

![alt text](https://github.com/DanielCalero12/2017B-Taller-ORM-Archivo/blob/master/images/CapturaGet.PNG)

4)Para verificar el request post en el "body" se cambia a la opcion "x-www-form-urlencoded" 
se llenan los valores "clave" con "id","first Name", "last Name", "EmailAddres"
y por ultimo la opcion send para insertar un campo

![alt text](https://github.com/DanielCalero12/2017B-Taller-ORM-Archivo/blob/master/images/Captura3.PNG)

5)para verificar el request put se hacen los pasos del "body" del paso 4  se llena la 
url http://node21.codenvy.io:37830/contacts/4  y al final se le agrega "/id" en este caso es 3
y por ultimo la opcion send para buscar los valores de la tabla con ese id

![alt text](https://github.com/DanielCalero12/2017B-Taller-ORM-Archivo/blob/master/images/Captura4.PNG)

6)para eliminar el request delete se llena la url url http://node21.codenvy.io:37830/contacts/4 
a lo ultimo al igual que en el request put se adiciona el "/id" del cual se quiere eliminar 
y por ultimo la opcion send para eliminar un campo

![alt text](https://github.com/DanielCalero12/2017B-Taller-ORM-Archivo/blob/master/images/Captura5.PNG)









