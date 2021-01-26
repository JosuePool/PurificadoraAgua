# PurificadoraDeAgua
Proyecto Purificadora de agua por los alumnos del 5B

PROYECTO PURIFICADORA DE AGUA

Crear e implementar un proyecto basado en una purificadora de agua para el hogar brindando una solución de una problemática en la actualidad como lo es la ingesta del agua contaminada. Estos datos se registrarán a una base de datos de página web y uso de un servidor para almacenar los datos relevantes.

Proposito: Se hace con el fin de llevar agua de la mejor calidad a  los lugares fuera del alcanze de este servicio. implementando el IoT a nuestro purificador de agua para que sea mas optimo y mejores a uno convencional.

Proceso: Con base a la problemática planteada se pretende la creación de un sistema de purificación automatizado de tal manera que sea capaz de iniciar el proceso por sí mismo partiendo desde un recipiente que tendrá el agua potable, pasado por una manguera que tendrá insertado un filtro y dentro  del compartimiento principal donde se obtendrá el agua para la purificación tendrá el carbón activo el cual tiene las propiedades de atrapar impurezas en el agua como solventes, pesticidas, residuos industriales y otros productos químicos y dado que también remueve los contaminantes que generan olores, logra que el agua potable sea más sabrosa, esto con la ayuda de una mini bomba de agua que hará que el líquido se vaya  almacenando en un compartimento en el cual podamos dispensar agua limpia para la ingesta. Y usando un sensor ultrasónico donde medirá el llenado del agua.

Resultado: Teniendo como resultado la purificacion de agua, conforme al proceso aplicado, esto mandando la informacion si se llegara a vaciar el contenedor en forma de porcentjae, tambien cuantos recipientes cuantos ya lleno. Y de tal manera ofrecindo el agua mas economico con los mejores estandare. Tambien se considera que esto puede servir para ofrecerles a los micro empresarios para automatizen su servicio.

Diagrama de datos*****

Flujo de informacion que se guarda en la base de datos.


Envio de datos mediante el sensor de distancia, el sensor manda cuantos objetos ah detectado y a que hora, este nos sirve para saber 
la cantidad de las botellas y asi tu mismo hacer tus cuentas y saber cuanta ganancia se obtuvo al dia a la semana o al mes debido a que 
se puede filtrar que los registros no sean actualizados cada dia si no cada semana o cada mes. 

Envio de datos mediante el sensor de agua, este envia datos de cuantos litros hay cada minuto a la base de datos y asi saber con cuanta agua
potable comtamos para su purificacion, los datos enviados son litros de agua y la fecha y hora.

Envio de datos mediante el sensor ultrasonico, estos datos envian la cantidad de agua que se encuentra llenandose en el recipiente, este nos sirve 
para detectar que cuando ya este lleno la mini bomba deje de hacer su llenado y nos marque que el agua ya se encuentra lleno, el envio es la cantidad
de litros llenados y la fecha y hora.


# Las 5´v del Big Data en nuestro proyecto.

En nuestro proyecto esta presente el Volumen ya que se almacenara una gran cantidad de datos en nuestra base de datos, por ejemplo los datos de los sensores que se van enviando a la pagina web.
 
velocidad: en nuestro proyecto este dimencion se encuentra presente ya que los sensores al enviar los datos a la pagina web necesitan de una tenerminada velocidad, todo dependiendo de la calidad de los sensores y del servicio de internet.

Valor: En nuestro proyecto esta dimensión esta presente ya que los datos que se envían a nuestra base de datos son muy importante y útiles para cualquier usuario o cliente que adquiera el servicio.

Veracidad: En nuestro proyecto consideramos que no cumple con esta dimencion ya que por el momento no es capaz de eliminar los datos tomados de manera incorrecta y detectar patrones reales pero es algo que debemos mejorar ya que es un reto para el big data.

Varieadad: En este caso consideramos que nuestro proyecto no cumple con esta dimencion ya que no tiene distintas tipologías formatos y estructuras de los datos procediendo de fuentes muy diversas, pero es algo que debemos mejorar.

