# PurificadoraDeAgua
Proyecto Purificadora de agua por los alumnos del 5B

PROYECTO PURIFICADORA DE AGUA

Crear e implementar un proyecto basado en una purificadora de agua para el hogar brindando una solución de una problemática en la actualidad como lo es la ingesta del agua contaminada. Estos datos se registrarán a una base de datos de página web y uso de un servidor para almacenar los datos relevantes.

Propósito: Se hace con el fin de llevar agua de la mejor calidad a los lugares fuera del alcance de este servicio. implementando el IoT a nuestro purificador de agua para que sea más optimo y mejores a uno convencional.

Proceso: Con base a la problemática planteada se pretende la creación de un sistema de purificación automatizado de tal manera que sea capaz de iniciar el proceso por sí mismo partiendo desde un recipiente que tendrá el agua potable, pasado por una manguera que tendrá insertado un filtro y dentro  del compartimiento principal donde se obtendrá el agua para la purificación tendrá el carbón activo el cual tiene las propiedades de atrapar impurezas en el agua como solventes, pesticidas, residuos industriales y otros productos químicos y dado que también remueve los contaminantes que generan olores, logra que el agua potable sea más sabrosa, esto con la ayuda de una mini bomba de agua que hará que el líquido se vaya  almacenando en un compartimento en el cual podamos dispensar agua limpia para la ingesta. Y usando un sensor ultrasónico donde medirá el llenado del agua.

Resultado: Teniendo como resultado la purificación de agua, conforme al proceso aplicado, esto mandando la información si se llegara a vaciar el contenedor en forma de porcentaje, también cuantos recipientes cuantos ya lleno. Y de tal manera ofreciendo el agua más económica con los mejores estándares. También se considera que esto puede servir para ofrecerles a los micro empresarios para automaticen su servicio.

Diagrama de datos*****

Flujo de información que se guarda en la base de datos.


Envió de datos mediante el sensor de distancia, el sensor manda cuantos objetos ha detectado y a qué hora, este nos sirve para saber 
la cantidad de las botellas y así tú mismo hacer tus cuentas y saber cuánta ganancia se obtuvo al día a la semana o al mes debido a que 
se puede filtrar que los registros no sean actualizados cada día si no cada semana o cada mes. 

Envió de datos mediante el sensor de agua, este envía datos de cuantos litros hay cada minuto a la base de datos y así saber con cuánta agua
potable contamos para su purificación, los datos enviados son litros de agua y la fecha y hora.

Envió de datos mediante el sensor ultrasónico, estos datos envían la cantidad de agua que se encuentra llenándose en el recipiente, este nos sirve 
para detectar que cuando ya esté lleno la mini bomba deje de hacer su llenado y nos marque que el agua ya se encuentra lleno, el envió es la cantidad
de litros llenados y la fecha y hora.


LAS 5´V DEL BIG DATA EN NUESTRO PROYECTO

En nuestro proyecto está presente el Volumen ya que se almacenará una gran cantidad de datos en nuestra base de datos, por ejemplo, los datos de los sensores que se van enviando a la página web.
 
velocidad: en nuestro proyecto esta dimensión se encuentra presente ya que los sensores al enviar los datos a la página web necesitan de una tener minada velocidad, todo dependiendo de la calidad de los sensores y del servicio de internet.

Valor: En nuestro proyecto esta dimensión está presente ya que los datos que se envían a nuestra base de datos son muy importante y útiles para cualquier usuario o cliente que adquiera el servicio.

Veracidad: En nuestro proyecto consideramos que no cumple con esta dimensión ya que por el momento no es capaz de eliminar los datos tomados de manera incorrecta y detectar patrones reales, pero es algo que debemos mejorar ya que es un reto para el Big Data.

Variedad: En este caso consideramos que nuestro proyecto no cumple con esta dimensión ya que no tiene distintas tipologías formatos y estructuras de los datos procediendo de fuentes muy diversas, pero es algo que debemos mejorar.


