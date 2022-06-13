# Examen-Parte-B-3-Evaluacion
***
## Apartado 1

# Ejemplo 1:
Al crear el contenedor se nos da un acceso a un shell del mismo. Es importante destacar que estamos accediendo como root que tiene unas implicaciones de seguridad que trataremos en el módulo 8 de este mismo curso. Al salir del terminal el contenedor se para.

![imagen](https://user-images.githubusercontent.com/91874740/173307859-4987ee54-e11c-4122-839e-a3de9ffc9c50.png)

# Ejemplo 2:
Al crear el contenedor se ejecuta la orden ls / y posteriormente el contenedor pasa a estar parado. Y ya no podremos acceder a él. 

![imagen](https://user-images.githubusercontent.com/91874740/173308082-49f28d50-cb0a-426a-a687-50c385f74667.png) 

# Ejemplo 3:
Al ejecutar esa orden se crea un servidor Web Apache 2.4 en la ip mostrada y se nos muestra por pantalla el log de dicho servicio.

![imagen](https://user-images.githubusercontent.com/91874740/173302365-fce9b001-537c-4441-a20e-03dfbffc216e.png)

# Ejemplo 4:
Al crear el contenedor se ejecuta la orden ls desde el directorio /etc, posteriormente el contenedor pasa a estar parado. Y ya no podremos acceder a él. 

![imagen](https://user-images.githubusercontent.com/91874740/173302885-e34bb09a-7e67-4ce6-b3b9-3d921d933a6c.png)

Estos son dos comandos con los cuales podemos hacer un seguimiento de nuestro sistema.
La diferencia es que el que no lleva -a solo muestra los contenedores que estan en ejecución, en cambio el otro muestra los que estan en ejecución o los que estan parados.

![imagen](https://user-images.githubusercontent.com/91874740/173302932-a18a4894-a72f-408d-b460-4815295bce0e.png)

***

## Apartado 2
# Proyecto Tomcat

Primero insertamos tomcat en docker

![imagen](https://user-images.githubusercontent.com/91874740/173312593-3f1f862f-aeee-446b-8333-bd9d30731cd7.png)

Comprobamos si esta insertada

![imagen](https://user-images.githubusercontent.com/91874740/173312719-932267f0-4358-4be2-abe3-0927b8c75e8a.png)

Ahora le cambiamos el nombre para que sea mas fácil de reconocer para nosotros

![imagen](https://user-images.githubusercontent.com/91874740/173312839-a5a6fcf7-d800-4c08-8d43-05d68fd64165.png)

Comprobamos si se ha cambiado el nombre correctamente

![imagen](https://user-images.githubusercontent.com/91874740/173312932-c7ddcfa8-d252-42c3-a516-c9e77c40575c.png)


Y por ultimo hacemos un push para que se suba a nuestro dockerhub

![imagen](https://user-images.githubusercontent.com/91874740/173313076-f9cb117b-527f-4110-8090-4662fbd0368e.png)
