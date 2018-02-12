Listener 

Este proyecto consiste en la implementación de un listener. El listener o herramienta de escucha activa consiste en la extracción de información de una red social, en este caso twitter, mediante unas keywords impuestas por el usuario y en tiempo real.

El lenguaje de programación empleado para la extracción de la información es python.
A continuación, se plantea la arquitectura a alto nivel del almacenamiento de la información obtenida por la herramienta de escucha activa. 

![](https://github.com/franrs6/Ilunion/blob/master/Modelo_Entidad_Relaci%C3%B3n.PNG)

Las herramientas necesarias y el papel que van tomar en este proyecto se describe a continuación:

  * El lenguaje de programación que se usa es python, por lo que la versión usada es 3.6.3
  
  * La información será almacenada en una base de datos de google cloud, con el sistema que se ha especificado en la imagen anterior.
  
  * La versión de la api de twitter "tweetpy" es la 3.5.
  
  * El listener correrá en el cmd del sistema, preferiblemente en una máquina virtual para evitar que se pare el sistema de ejecución.
  
  Una vez definido los elementos necesarios para comenzar a utilizar el listener, el modo de actuación a grandes rasgos será tener la base de datos en una máquina virtual junto al listener ejecutado en CMD. El proceso de extracción de datos no se parará y obtendrá tweet todo el tiempo.
  
