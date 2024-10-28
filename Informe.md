# Informe sobre tipos de ataque, metodologías de pentesting y herramientas
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
| Metodología                               | Enfoque Principal                             | Aplicable a Ingeniería Social | Aplicable a Malware | Aplicable a Redes y Sistemas |
|-------------------------------------------|-----------------------------------------------|-------------------------------|---------------------|-------------------------------|
| OWASP Testing Guide                       | Aplicaciones web                              | Parcialmente                  | Sí                  | Sí                            |
| OSSTMM                                    | Sistemas y redes                             | Sí                            | Sí                  | Sí                            |
| ISSAF                                     | Riesgos en sistemas y redes                  | Sí                            | Sí                  | Sí                            |
| NIST Cybersecurity Framework              | Identificación y mitigación de riesgos       | Sí                            | Sí                  | Sí                            |
| OSINT                                     | Información pública                           | Sí                            | Parcialmente        | Parcialmente                  |
| Ethical Hacking                           | Simulación de ataques                         | Sí                            | Sí                  | Sí                            |
| VAPT                                      | Evaluación de vulnerabilidades y pruebas de penetración | Parcialmente          | Sí                  | Sí                            |
| PTES                                      | Planificación y ejecución de pruebas         | Sí                            | Sí                  | Sí                            |
| STIG                                      | Mejora de la seguridad en sistemas           | No                            | Sí                  | Sí                            |
| TIC                                       | Recopilación de información técnica          | Parcialmente                  | Sí                  | Sí                            |

### Selección de Metodologías

Considerando los servicios específicos mencionados (ingeniería social, malware, y ataques a redes y sistemas), las metodologías más adecuadas son:

- #### OSSTMM (Open Source Security Testing Methodology Manual):
    El OSSTMM es una metodología integral que abarca todos los aspectos de la seguridad de sistemas y redes. Su enfoque holístico permite evaluar tanto la seguridad técnica como la humana, lo que la hace ideal para abordar ataques de ingeniería social, malware y vulnerabilidades en redes y sistemas.

- #### ISSAF (Information Systems Security Assessment Framework):
    El ISSAF proporciona un marco detallado para la evaluación de riesgos en sistemas de información. Su estructura en fases (planificación, evaluación, tratamiento, acreditación y mantenimiento) permite una evaluación completa de la seguridad, cubriendo desde la ingeniería social hasta las vulnerabilidades técnicas.

- #### Ethical Hacking:
    Esta metodología se centra en simular ataques reales, lo que la hace particularmente efectiva para identificar vulnerabilidades en todos los niveles. Su enfoque práctico permite descubrir fallos de seguridad que podrían pasar desapercibidos con métodos más teóricos, siendo especialmente útil para evaluar la resistencia a ataques de ingeniería social y malware.

- #### PTES (Penetration Testing Execution Standard):
    El PTES ofrece un enfoque estandarizado para las pruebas de penetración, cubriendo todas las fases desde la recopilación de información hasta la post-explotación. Su estructura detallada permite una evaluación exhaustiva de la seguridad, siendo particularmente útil para auditar redes y sistemas, así como para evaluar la efectividad de las defensas contra malware.

### Fases Clave de un Ataque y Relación con Tipos de Auditorías

Las fases clave de un ciberataque típico son:

- #### Reconocimiento

    - **Descripción**: En esta fase, el atacante recopila información sobre el objetivo. Esto puede incluir búsquedas en internet, ingeniería social, y escaneo de redes.

    - **Relación con auditorías**: Crucial para la auditoría de ingeniería social y la evaluación de la exposición de información pública.

- #### Weaponización y entrega

    - **Descripción**: El atacante prepara las herramientas para el ataque (como malware) y las entrega al objetivo, a menudo a través de phishing o explotando vulnerabilidades conocidas.

    - **Relación con auditorías**: Fundamental para las auditorías de malware y la evaluación de la resistencia a ataques de ingeniería social.

- #### Explotación

    - **Descripción**: En esta fase, el atacante aprovecha las vulnerabilidades identificadas para ganar acceso inicial al sistema objetivo.

    - **Relación con auditorías**: Crítica para las auditorías de redes y sistemas, especialmente en la evaluación de vulnerabilidades y pruebas de penetración.

- #### Instalación

    - **Descripción**: El atacante instala herramientas adicionales o malware para mantener el acceso y facilitar futuras actividades maliciosas.

    - **Relación con auditorías**: Esencial para las auditorías de malware y la evaluación de la seguridad de los sistemas.

- #### Comando y control

    - **Descripción**: Se establece una comunicación bidireccional entre el sistema comprometido y la infraestructura del atacante.

    - **Relación con auditorías**: Importante para las auditorías de redes, especialmente en la detección de tráfico anómalo y conexiones no autorizadas.

- #### Acciones sobre los objetivos

    - **Descripción**: El atacante realiza las acciones finales para lograr sus objetivos, como exfiltración de datos, destrucción de sistemas, o extorsión.

    - **Relación con auditorías**: Relevante para todas las auditorías, ya que representa el impacto final de un ataque exitoso.

### Auditoría de Ingeniería Social

- **Fases relacionadas**: Reconocimiento, Weaponización y entrega
- **Servicios**: Evaluación de vulnerabilidades a phishing, spear phishing y whaling
- **Metodologías aplicables**: OSSTMM, ISSAF, Ethical Hacking

### Auditoría de Malware

- **Fases relacionadas**: Weaponización y entrega, Explotación, Instalación
- **Servicios**: Análisis de virus, gusanos, troyanos, ransomware, spyware y adware
- **Metodologías aplicables**: OSSTMM, ISSAF, Ethical Hacking, PTES

### Auditoría de Redes y Sistemas

- **Fases relacionadas**: Reconocimiento, Explotación, Instalación, Comando y control, Acciones sobre los objetivos
- **Servicios**:
  - Evaluación de vulnerabilidades a ataques DDoS
  - Pruebas de penetración para detectar vulnerabilidades a ataques Man-in-the-Middle
  - Auditoría de seguridad en aplicaciones web para prevenir inyecciones SQL y Cross-Site Scripting
  - Evaluación de la robustez de contraseñas y políticas de acceso para prevenir ataques de fuerza bruta
- **Metodologías aplicables**: OSSTMM, ISSAF, Ethical Hacking, PTES

## Evaluación de herramientas de monitorización


## Fuentes
[Ciberseguridad: Tipos de ataque y en qué consisten](https://www.iebschool.com/blog/ciberseguridad-ataques-tecnologia/)

[Ataques informáticos: Causas y 15 Tipos de Ciberataques](https://winempresas.pe/blog/ataques-informaticos-causas-y-12-tipos-de-ciberataques)