# Examen-Parte-B-3-Evaluacion

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

## Apartado 2
# Proyecto Tomcat

Primero insertamos tomcat en docker


Ahora instalamos unos parámetros básicos


Activamos las app de manager, host manager y docs


Copiamos tomcat-users.xml en el contenedor


Modificamos las apps por defecto


Y compiamos la app

