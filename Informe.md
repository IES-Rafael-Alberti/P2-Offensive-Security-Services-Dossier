# Informe sobre tipos de ataque, metodologías de pentesting y herramientas
![Portada](portada.png)

**Participantes:** *Grupo 3*
- Jesús Cordero
- Álvaro González
- Alejandro Seoane
- Israel Valderrama

## Índice
- [Introducción](#introducción)
- [Clasificación de tipos de ataque](#clasificación-de-tipos-de-ataque)
    - [Ataques de ingeniería social](#ataques-de-ingeniería-social)
    - [Ataques de malware](#ataques-de-malware)
    - [Ataques a redes y sistemas](#ataques-a-redes-y-sistemas)
- [Metodologías de pentesting](#metodologías-de-pentesting)
- [Evaluación de herramientas de monitorización](#evaluación-de-herramientas-de-monitorización)
    - [Herramientas ataques de ingeniería social](#herramientas-ataques-de-ingeniería-social)
    - [Herramientas ataques de malware](#herramientas-ataques-de-malware)
    - [Herramientas ataques a sistemas y redes](#ataques-a-redes-y-sistemas)
- [Conclusiones](#conclusiones)
- [Fuentes](#fuentes)


## Introducción


## Clasificación de tipos de ataque
Esta parte del informe se centrará en la investigación y clasificación de los ataques cibernéticos más comunes teniendo en cuenta los métodos, características y objetivos de cada uno.

### Ataques de ingeniería social
Este tipo de ataques consiste en manipular psicológicamente a las víctimas para obtener información del usuario o acceso a sus dispositivos. Existen tres tipos:

+ **Phishing:** Se usa principalmente para robar datos del usuario como números de tarjetas de crédito o contraseñas. Los ciberdelincuentes se suelen hacer pasar por personas o entidades de confianza (servicio de correos, bancos...) y engañan a la víctima con un mensaje normalmente alarmante para que pinchen en el enlace malicioso proporcionado. 

    Se le llama smishing en caso de realizarse por SMS o vishing si se realiza a través de una llamada.

+ **Spear Phishing:** Son ataques de phishing dirigidos a una persona o empleado concreto de una compañía específica con el fin de obtener información o acceso a dicha compañía. Para ganarse su confianza los ciberdelincuentes investigan meticulosamente a la víctima recopilando toda la información posible antes de comenzar.
+ **Whaling:** Estos ataques, también conocidos como "cazas de ballenas", son similares a los ataques de spear phishing. La principal diferencia es que van dirigidos a altos cargos de las empresas, como CEOs y CFOs ya que estos suelen tener acceso completo a la empresa y a su información confidencial.

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

+ **Denegación de servicio distribuido (DDoS):** Consiste en realizar peticiones constantes a un servidor hasta lograr que colapse y deje de funcionar provocando así la parada del servicio suministrado por el servidor. Para estos ataques se suelen usar botnets formadas por equipos infectados por gusanos.

+ **Man-in-the-Middle (MitM):** Es un tipo de ataque en el que el ciberdelincuente intercepta la comunicación de dos dispositivos pudiendo leerla o modificarla. Tienen como fin el robo de datos o la manipulación de los mismos.
+ **Inyección SQL:** Consiste en infiltrar código en un campo de entrada de una aplicación web aprovechándose de vulnerabilidades en ella. De esta manera los ciberdelincuentes pueden obtener acceso a la base de datos de la aplicación web y obtener información sensible, modificarla u obtener control de la aplicación web.
+ **Cross-Site Scripting (XSS):** Es un tipo de inyección en la que el atacante envía secuencias de comandos maliciosos al contenido de páginas web para desacreditarla. Cuando una víctima accede a la aplicación web, el navegador de la víctima ve el código malicioso del ciberdelincuente como parte del sitio web y lo ejecuta.
+ **Ataques de fuerza bruta:** Consiste en intentar obtener acceso a un dispositivo de una red o a información protegida por una contraseña a base de intentar descifrar dichas contraseñas probando múltiples combinaciones hasta encontrar una. Se puede realizar probando todas las combinaciones posibles, con el uso de un diccionario de contraseñas o con una combinación de ambas.

## Metodologías de pentesting


## Evaluación de herramientas de monitorización
Bueno una vez analizada las metodologías que podemos encontrar en el campo del pentesting y haber elegido la nuestra propia basandonos en ellas continuaremos con las herramientas que utilizaremos. 

En este apartado, evaluaremos y seleccionaremos herramientas de auditoría, las cuales nos ayudarán a ejecutar nuestras pruebas de pentesting en los sistemas, bases de datos, aplicaciones webs..., de las empresas que contacten con nosotros.

Dentro de las diferentes herramientas que nos brinda el mercado podemos ver herramientas más enfocadas al ataque (las cuales simulan ataques cibernéticos para identificar vulnerabilidades en un sistemas) y de monitoreo (las cuales supervisan el comportamiento de la red o el sistema en busca de actividad sospechosa durante o ya después de un ataque). 

Ahora pasamos a definir las herramientas más adecuadas para los tipos de ataques de los que se encarga nuestra empresa. 

### Herramientas ataques de ingeniería social

#### Gophish
Esta aplicación es de código abierto y esta enfocada para ayudar a los profesionales de ciberseguridad y a las organizaciones a ejecutar campañas de pruebas de *pishing*.   
Esto nos permite evaluar la concienzación que tienen los empleados de una empresa sobre este tipo de ataques.   
Como punto a favor podemos ver que es multi-plataforma (Windows, Linux, macOS), gratuita, panel de control y métricas.

#### Cofense PhishMe
Es una plataforma comercial que está enfocada en la prevención y detección de atauqes de pishing mediante la capacitación de los empleados.
Lo bueno que tiene esta herramienta es que puedes efectuar simulaciones de pishing a la empresa, estos ataques podrán ser monitoreados en tiempo real con métricas.   
Si uno de los empleados cae en uno de los ataques se ofrecen módulos de capacitación para enseñar a estos a reconocer futuros ataques. Como único inconveniente es que la licencia es de pago. 

#### SET (Social-Engineer Toolkit)
Es una herramienta de código abierto muy utilizada en el ámbito de la ciberseguridad para las simulaciones de ingeniería social y evaluaciones de seguridad.   
Lo que diferencia esta aplicación son las herramientas que nos proponen. A parte de las simulaciones de pishing por correos electrónicos, también nos da la opción de crear sitios webs falsos donde con los que se podría probar a los empleados con el robo de sus credenciales.   
Como único inconveniente es que requiere de conocimientos previos debido a que su configuración es por consola de comandos. 
<br>
<br>
<br>
Una vez recabado información sobre estas aplicaciones vamos a compararlas siguiendo los siguientes parámetros. 

| Nombre         | Gophish    | Cofense | SET     |
|------------|------------------|-----------|--------|
| Precio | Gratuito (código abierto) | Pago (subscripción anual) | Gratuito (código abierto) |
| Plataforma | Windows, Linux, macOS | Basado en nube o local (Windows y Linux) | Linux (preferiblemente en Kali Linux) |
| Funcionalidad | Simulación phishing (email) | Simulación pishing (email) + concienciación | Simulación de pishing (email) + webs falsas (robo de credenciales) |
| Complejidad | Media (requiere un poco de conocimiento). Interfaz gráfica | Baja (intuitiva). Interfaz gráfica | Alta (requiere de bastantes conocimientos previos). Consola de comandos |
| Escalabilidad | Alta. Ideal para empresas de cualquier tamaño. | Muy alta, ideal para grandes organizaciones | Alta.  Adaptable pero enfocada en pruebas de penetración específicas |


### Herramientas ataques de malware

#### ClamAV
Esta es un antivirus de código abierto diseñado para detectar malware y otras amenazas. Se suele utilizar principalmente en servidores o sistemas Linux (aunque es multiplataforma) para analizar archivos en busca de gusanos, troyanos, virus y otros tipos de malware.   
Esta desarollado por Cisco y se ejecuta a través de la terminal. 

#### Cuckoo Sandbox
Es una herramienta de código abierto para el análisis dinámico de malware en entornos controlados. Su objetivo es ejecutar archivos en entornos seguros (una máquina virtual), para poder observar el comportamiento en tiempo real y generando un detallado análisis de cualquier posible actividad maliciosa.
Muy utilizado en ciberseguirdad para identificar y estudiar amenazas como pueden ser ransomware, troyanos y exploits. 
Para su instalación hay que tener cocnocimientos previos debido a que es un poco compleja. 

#### Volatility 
Es una herrmaienta avanzada de análisis de memoria forense de código abierto que se utiliza en ciberseguirdad para la investigación de incidentes y amenazas. 
Esta herramienta permite examinar el contenido de la RAM (la memoria volátil de un sistema), lo cuál es muy importante para el análisis forense y la detección de actividades maliciosas como podrían ser rootkits, spyware u otros malware residentes en memoria. 
También hace falta conocimentos previos para sacarle todo su potencial y es debido a que si ejecución es a través de terminal. 

#### Sysmon
Es una herramienta de monitoreo de eventos del sistemas desarrollada por Microsoft. Está ayuda a los equipos de seguridad a monitorear y registrar la actividad detallada de procesos, redes, archivos y cambios en el sistema a tiempo real.  
Se utiliza principalemtne para la detección y análisis de amenazas, proporcionando información valiosa sobre actividades de malware y comportamientos sospechosos. 

| Nombre     | ClamAV    | Cuckoo Sandbox | Volatility | Sysmon |
|------------|-----------|----------------|------------|--------|
| Precio     | Gratuito  | Gratuito       | Gratuito   |Gratuito|
| Plataforma | Multiplataforma (Windows, Linux, macOS)| Multiplataforma (principalmente Linux) | Multiplataforma (Windows, Linux, macOS) | Windows |
| Funcionalidad | Escaneo antivirus y antimalware | Análisis dinámico de malware en máquina virtual | Análisis de memoria forense | Monitoreo y resgitro de eventos |
| Complejidad | Media (Interfaz de consola, requiere configuración para entornos empresariales) | Alta (Requiere configuración técnica)| Alta (Requiere algo de experiencia en forense digital) | Media (necesita algunos conociemintos de logs)
| Escalabilidad | Escalable, pero depende del rendimiento del sistema y la red | Escalables dependiendo de los recursos del hardware y vistualización | Muy escalable, adecuado para incidencias de cualquier escala | Muy escalable, ideal para entornos empresariales |

Como podemos observar destaca que todas son gratuitas, algunas requieren de conocimientes para su instalación o uso (debido a que son en consola algunas). También su escalabilidad dependen algunas de la potencia de los medios tanto hardware como de red. 

## Evaluación de herramientas de monitorización
Bueno una vez analizada las metodologías que podemos encontrar en el campo del pentesting y haber elegido la nuestra propia basándonos en ellas continuaremos con las herramientas que utilizaremos. 

En este apartado, evaluaremos y seleccionaremos herramientas de auditoría, las cuales nos ayudarán a ejecutar nuestras pruebas de pentesting en los sistemas, bases de datos, aplicaciones webs..., de las empresas que contacten con nosotros.

Dentro de las diferentes herramientas que nos brinda el mercado podemos ver herramientas más enfocadas al ataque (las cuales simulan ataques cibernéticos para identificar vulnerabilidades en un sistemas) y de monitoreo (las cuales supervisan el comportamiento de la red o el sistema en busca de actividad sospechosa durante o ya después de un ataque). 

Ahora pasamos a definir las herramientas más adecuadas para los tipos de ataques de los que se encarga nuestra empresa. 

### Herramientas ataques de ingeniería social

#### Gophish
Esta aplicación es de código abierto y está enfocada para ayudar a los profesionales de ciberseguridad y a las organizaciones a ejecutar campañas de pruebas de *phishing*.   
Esto nos permite evaluar la concienciación que tienen los empleados de una empresa sobre este tipo de ataques.   
Como punto a favor podemos ver que es multiplataforma (Windows, Linux, macOS), gratuita, panel de control y métricas.

#### Cofense PhishMe
Es una plataforma comercial que está enfocada en la prevención y detección de ataques de phishing mediante la capacitación de los empleados.
Lo bueno que tiene esta herramienta es que puedes efectuar simulaciones de phishing a la empresa, estos ataques podrán ser monitoreados en tiempo real con métricas.   
Si uno de los empleados cae en uno de los ataques se ofrecen módulos de capacitación para enseñar a estos a reconocer futuros ataques. Como único inconveniente es que la licencia es de pago. 

#### SET (Social-Engineer Toolkit)
Es una herramienta de código abierto muy utilizada en el ámbito de la ciberseguridad para las simulaciones de ingeniería social y evaluaciones de seguridad.   
Lo que diferencia esta aplicación son las herramientas que nos proponen. A parte de las simulaciones de pishing por correos electrónicos, también nos da la opción de crear sitios webs falsos donde con los que se podría probar a los empleados con el robo de sus credenciales.   
Como único inconveniente es que requiere de conocimientos previos debido a que su configuración es por consola de comandos. 
<br>
<br>
<br>
Una vez recabada la información sobre estas aplicaciones vamos a compararlas siguiendo los siguientes parámetros. 

| Nombre         | Gophish    | Cofense | SET     |
|------------|------------------|-----------|--------|
| Precio | Gratuito (código abierto) | Pago (subscripción anual) | Gratuito (código abierto) |
| Plataforma | Windows, Linux, macOS | Basado en nube o local (Windows y Linux) | Linux (preferiblemente en Kali Linux) |
| Funcionalidad | Simulación phishing (email) | Simulación phishing (email) + concienciación | Simulación de phishing (email) + webs falsas (robo de credenciales) |
| Complejidad | Media (requiere un poco de conocimiento). Interfaz gráfica | Baja (intuitiva). Interfaz gráfica | Alta (requiere de bastantes conocimientos previos). Consola de comandos |
| Escalabilidad | Alta. Ideal para empresas de cualquier tamaño. | Muy alta, ideal para grandes organizaciones | Alta.  Adaptable pero enfocada en pruebas de penetración específicas |


### Herramientas ataques de malware

#### ClamAV
Está es un antivirus de código abierto diseñado para detectar malware y otras amenazas. Se suele utilizar principalmente en servidores o sistemas Linux (aunque es multiplataforma) para analizar archivos en busca de gusanos, troyanos, virus y otros tipos de malware.   
Está desarrollado por Cisco y se ejecuta a través de la terminal. 

#### Cuckoo Sandbox
Es una herramienta de código abierto para el análisis dinámico de malware en entornos controlados. Su objetivo es ejecutar archivos en entornos seguros (una máquina virtual), para poder observar el comportamiento en tiempo real y generando un detallado análisis de cualquier posible actividad maliciosa.
Muy utilizado en ciberseguridad para identificar y estudiar amenazas como pueden ser ransomware, troyanos y exploits. 
Para su instalación hay que tener conocimientos previos debido a que es un poco compleja. 

#### Volatility 
Es una herramienta avanzada de análisis de memoria forense de código abierto que se utiliza en ciberseguridad para la investigación de incidentes y amenazas. 
Esta herramienta permite examinar el contenido de la RAM (la memoria volátil de un sistema), lo cuál es muy importante para el análisis forense y la detección de actividades maliciosas como podrían ser rootkits, spyware u otros malware residentes en memoria. 
También hace falta conocimientos previos para sacarle todo su potencial y es debido a que si ejecución es a través de terminal. 

#### Sysmon
Es una herramienta de monitoreo de eventos del sistemas desarrollada por Microsoft. Esto ayuda a los equipos de seguridad a monitorear y registrar la actividad detallada de procesos, redes, archivos y cambios en el sistema a tiempo real.  
Se utiliza principalmente para la detección y análisis de amenazas, proporcionando información valiosa sobre actividades de malware y comportamientos sospechosos. 

| Nombre     | ClamAV    | Cuckoo Sandbox | Volatility | Sysmon |
|------------|-----------|----------------|------------|--------|
| Precio     | Gratuito  | Gratuito       | Gratuito   |Gratuito|
| Plataforma | Multiplataforma (Windows, Linux, macOS)| Multiplataforma (principalmente Linux) | Multiplataforma (Windows, Linux, macOS) | Windows |
| Funcionalidad | Escaneo antivirus y antimalware | Análisis dinámico de malware en máquina virtual | Análisis de memoria forense | Monitoreo y registro de eventos |
| Complejidad | Media (Interfaz de consola, requiere configuración para entornos empresariales) | Alta (Requiere configuración técnica)| Alta (Requiere algo de experiencia en forense digital) | Media (necesita algunos conocimientos de logs)
| Escalabilidad | Escalable, pero depende del rendimiento del sistema y la red | Escalables dependiendo de los recursos del hardware y virtualización | Muy escalable, adecuado para incidencias de cualquier escala | Muy escalable, ideal para entornos empresariales |

Como podemos observar destaca que todas son gratuitas, algunas requieren de conocimientos para su instalación o uso (debido a que son en consola algunas). También su escalabilidad dependen algunas de la potencia de los medios tanto hardware como de red. 

### Herramientas ataques a sistemas y redes

#### Wireshark
Es una herramienta de análisis de protocolos de red de código abierto. Está se utiliza frecuentemente en redes y ciberseguridad para capturar y analizar el tráfico en una red en tiempo real.  
Wireshark nos permite analizar todos los paquetes que circulan en una red para identificar vulnerabilidades, problemas de rendimiento y actividades sospechosas.  
Para utilizarla hay que tener conocimientos de redes para poder interpretar la información. 

#### Nmap
Es una herramienta de código abierto para el escaneo y mapeo de redes, ampliamente utilizada en ciberseguridad para identificar servicios, puertos abiertos y dispositivos de una red.   
Es de las herramientas para auditoría más utilizadas debio a su flexibilidad, potencia y eficiencia. También hay que tener algún que otro tipo de conocimiento.

#### Wanguard
Es una solución avanzada de mitigación y monitoreo de ataques DDoS y tráfico no deseado. Esta aplicación está diseñada para proteger las redes empresariales y las infraestructuras de centros de datos contra amenazas basadas en el tráfico y ataques de denegación de servicio. 
Wanguard destaca por su capacidad para identificar y detener el tráfico malicioso, preservando así la seguridad y estabilidad de la red.   
Es una herramienta de pago y que requiere de conocimientos previos sobre redes. 

#### Metasploit
Es una plataforma de código abierto la cual se diseñó para facilitar pruebas de penetración y explotación de vulnerabilidades en las redes, servicios y aplicaciones de un sistema.     
Esta permite simular ataques reales para poder identificar y solucionar debilidades en la seguridad de un sistema antes de que puedan ser explotados por los atacantes.  
Esta aplicación es altamente utilizada en ciberseguridad debido a su amplia biblioteca de exploits, su personalización y que es multiplataforma. Pero como inconveniente es que se utiliza a través de la línea de comandos y la personalización de los ataques se crean en scripts. 

#### SQLMap
Es una herramienta de código abierto que permite detectar y explotar vulnerabilidades de inyección SQL en aplicaciones web. Podremos automatizar procesos de prueba para identificar si una base de datos de datos puede tener vulnerabilidades contra este tipo de ataques de inyección SQL.   
Es muy utilizada para realizar pruebas de penetración en bases de datos y detectar posibles vulnerabilidades contra estos ataques que son de los más comunes y dañinos. 

#### BruteX
Es una herramienta automatizada de fuerza bruta. Está diseñada para realizar múltiples ataques a servicios comúnmente usados como pueden ser SSH, servicios web, FTP... Automatiza procesos de búsqueda y prueba de credenciales en redes.   
Es utilizada en el ámbito de la ciberseguridad para realizar ataques de prueba de manera eficiente y rápida. 

****

Esta tabla resume los conocimientos técnicos y la interfaz de cada herramienta para su uso en pruebas de seguridad en diferentes niveles de complejidad.

| Herramienta  | Costo | Plataforma  | Funcionalidad | Complejidad | Escalabilidad|
|----------|-------|---------|--------|-------|---|
| Wireshark | Gratuita | Windows, Linux, macOS | Análisis de tráfico de red en tiempo real, captura y filtrado de paquetes | Media (Interfaz gráfica intuitiva). Requiere conocimientos en redes para un buen análisis | Alta. Permite analizar grandes redes, aunque depende de los recursos locales|
|Nmap| Gratuita | Windows, Linux, macOS | Escaneo y mapeo de redes, y detección de puertos o servicios abiertos | Media (Interfaz de consola). Necesita el uso de scripts para configuración y personalización | Alta. Adaptable para pequeñas o grandes redes|
| Wanguard | Pago | Linux | Detección y mitigación de ataques DDoS | Alta (Interfaz de consola). Configuraciones avanzadas | Muy alta. Ideal para grandes centros de datos con gran volumen de tráfico|
| Metasploit | Gratuita y versión de pago | Windows, Linux, macOS| Pruebas de penetración y explotación de vulnerabilidades| Alta (Interfaz gráfica en versión de pago). Requiere conocimientos en ciberseguridad| Alta. Ampliamente escalable en grandes redes | 
| SQLMap | Gratuita | Windows, Linux, macOS | Escaneo y explotación de inyecciones SQL| Media (Interfaz de consola). Conocimientos básicos en base de datos | Media. Excelente para sitios individuales, y posibilidad de escalabilidad reducida para sistemas con mas de una base de datos| 
|BruteX| Gratuita| Linux | Ataques de fuerza bruta a servicios de red | Media (Interfaz de consola). Fácil de usar pero con previos conocimientos en redes| Media. Adecuada para redes pequeñas, con limitaciones para redes muy grandes|

## Conclusiones
En este informe hemos visto una visión general de los ciberataques, detallando las técnicas y herramientas utilizadas en las auditorías de seguridad. Nos hemos enfocado en analizar los ataques de ingeniería social, malware y redes y sistemas. Destacamos la importancia de comprender cada tipo de amenaza posible para fortalecer una gran seguridad.   
Hemos analizado diversas metodologías y seleccionado herramientas específicas para cada tipo de auditoría. 

Es importante una parte de la inversión de una empresa en la ciberseguridad, tanto en la capacitación del personal de la propia empresa, el uso de tecnologías de última generación o la contratación de auditores de pentesting los cuales se encargarán de buscar las posibles vulnerabilidades que haya en una empresa.

## Fuentes
[Ciberseguridad: Tipos de ataque y en qué consisten](https://www.iebschool.com/blog/ciberseguridad-ataques-tecnologia/)

[Ataques informáticos: Causas y 15 Tipos de Ciberataques](https://winempresas.pe/blog/ataques-informaticos-causas-y-12-tipos-de-ciberataques)

[Top mejores aplicaciones para pruebas de pishing](https://geekflare.com/es/phishing-simulation-software/)

[10 herramientas de hacking ético](https://www.tokioschool.com/noticias/herramientas-hacking-etico/)

[Ordenadores para la inversión](https://www.pccomponentes.com/hp-victus-15-fa0059ns-intel-core-i5-12450h-16gb-512gb-ssd-rtx-3050-156)

[Dossier del grupo 3](Dossier_Auditorias_Ofensivas.md)