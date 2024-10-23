# Informe sobre tipos de ataque, metodologías de pentesting y herramientas
## Introducción


## Clasificación de tipos de ataque
Esta parte del informe se centrará en la investigación y clasificación de los ataques cibernéticos más comunes teniendo en cuenta los métidos, características y objetivos de cada uno.

### Ataques de ingeniería social
Este tipo de ataques consiste en manipular psicológicamente a las víctimas para obtener información del usuario o acceso a sus dispositivos. Existen tres tipos:

+ **Phishing:** Se usa principalmente para robar datos del usuario como números de tarjetas de credito o contraseñas. Los ciberdelincuentes se suelen hacer pasar por personas o entidades de confianza (servicio de correos, bancos...) y enganñan a la víctima con un mensaje normalmente alarmante para que pinchen en el enlace malicioso proporcionado. 

    Se le llama smishing en caso de realizarse por SMS o vishing si se realiza a través de una llamada.

+ **Spear Phishing:** Son ataques de phishing dirigidos a una persona o empleado concreto de una compañía específica con el fin de obtener información o acceso a dicha compañía. Para ganarse su confianza los ciberdelincuentes investigan meticulosamente a la víctima recopilando toda la información posible antes de comenzar.
+ **Whaling:** Estos ataques, tambien conocidos como "cazas de ballenas", son similares a los ataques de spear phishing.La principal diferencia es que van dirigidos a altos cargos de las empresas, como CEOs y CFOs ya que estos suelen tener acceso completo a la empresa y a su información confidencial.

### Ataques de malware
Estos ataques utilizan software malicioso para infiltrarse, dañar o deshabilitar los sistemas de una red. Veremos seis tipos:

+ **Virus:** Es un código malicioso que infecta los archivos del sistema y que debe de ser ejecutado por un usuario. Una vez dentro se propaga a todo lo que tenga acceso.
+ **Gusanos:** Es un programa que, al igual que los virus, una vez infectado el dispositivo empieza a propagarse, en este caso a otros dispositivos a través de la red. Las principales diferencias con los virus son que en el caso de los gusanos no necesita que un usuario lo ejecute y que como su principal objetivos es la propagación a otros equipos no afecta al funcionamiento normal del sistema. 

    Principalmente se usan para crear botnets para luego realizar acciones de forma remota.
+ **Troyanos:** Suelen estar integrados en archivos ejecutables aparentemente inofensivos. Una vez ejecutado este archivo ejecutable, el troyano crea una puerta trasera para facilitar la entrada del ciberdelincuente u otros malwares al dispositivo.
+ **Ransomware:** Se suele propagar como los troyanos, integrado en un archivo ejecutable pero, a diferencia de los troyanos, los ransomware secuestran a los datos encriptándolos y pidiendo un rescate (normalmente en criptomonedas) a cambio de la clave para desencriptar los datos. Pagar el rescate no asegura que los ciberdelincuentes nos vayan a suministrar la clave.

    Este tipo de ataque puede provocar el paro total de las actividades de una empresa hasta que se solucione.
+ **Spyware:** Son programas espía cuyo principal objetivo es la obtención de información intentando dejar el menor rastro posible para no ser detectado.
+ **Adware:** Su principal función es mostrar publicidad de forma invasiva y, aunque su objetivo no es dañar a los sistemas, puede ser considerado un spyware ya que es posible que recopile y transmita información del usuario para mostrar publicidad más personalizada al usuario.

### Ataques a redes y sistemas
Son ataques que aprovechan vulnerabilidades en la infraestructura de redes y sistemas informáticos con el objetivo de comprometer la seguridad, interrumpir operaciones u obtener acceso a datos e información sensible. Hablaremos de cuatro tipos

+ **Denegación de servicio distribuido (DDoS):** Consiste en realizar peticiones constantes a un servidor hasta lograr que colapse y deje de funcionar probocando así la parada del servicio suministrado por el servidor. Para estos ataques se suelen usar botnets formadas por equipos infectados por gusanos.

+ **Man-in-the-Middle (MitM):** Es un tipo de ataque en el que el ciberdelincuente intercepta la comunicación de dos dispositivos pudiendo leerla o modificarla. Tienen como fin el robo de datos o la manipulación de los mismos.
+ **Inyección SQL:** Consiste en inflitrar código en un campo de entrada de una aplicación web aprovechandose de vulnerabilidades en ella. De esta manera los ciberdelincuentes pueden obtener acceso a la base de datos de la aplicación web y obtener información sensible, modificarla u obtener control de la aplicación web.
+ **Ataques de fuerza bruta:** Consiste en intentar obtener acceso a un dispositivo de una red o a información protegida por una contraseña a base de intentar descifrar dichas contraseñas probando múltiples combinaciones hasta encontrar una. Se puede realizar probando todas las combinaciones posibles, con el uso de un diccionario de contraseñas o con una combinación de ambas.


## Metodologías de pentesting


## Evaluación de herramientas de monitorización


## Fuentes