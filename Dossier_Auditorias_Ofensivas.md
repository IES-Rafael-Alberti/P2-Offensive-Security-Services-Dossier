# Dossier de auditorías ofensivas

**Participantes:** *Grupo 3*
- Álvaro González
- Alejandro Seoane
- Israel Valderrama

## Índice
+ [Introducción](#introducción)
+ [Propuesta de auditorías ofensivas](#propuesta-de-auditorías-ofensivas)
    + [Auditoria de seguridad de aplicaciones](#auditoria-de-seguridad-de-aplicaciones)
    + [Auditoria de seguridad de redes](#auditoria-de-seguridad-de-redes)
    + [Auditoria de gestión de incidentes](#auditoria-de-gestión-de-incidentes)
    + [Auditoria de políticas y procedimientos](#auditoria-de-políticas-y-procedimientos)
+ [Propuesta de metodología de auditoría](#propuesta-de-metodología-de-auditoría)
    + [Auditoría de ingeniería social](#auditoría-de-ingeniería-social)
    + [Auditoría de malware](#auditoría-de-malware)
    + [Auditoría de seguridad de redes y sistemas](#auditoría-de-seguridad-de-redes-y-sistemas)
    + [Auditoría integral de ciberseguridad](#auditoría-integral-de-ciberseguridad)
+ [Propuesta de herramientas de monitorización](#propuesta-de-herramientas-de-monitorización)
    + [Herramientas de ingeniería inversa](#herramientas-de-ingeniería-inversa)
    + [Herramientas de malware](#herramientas-de-malware)
    + [Herramientas para redes y sistemas](#herramientas-para-redes-y-sistemas)
+ [Inversión inicial](#inversión-inicial)

## Introducción
En este dossier incluiremos descripciones detalladsa de los servicios que ofrecemos, la metodología seleccionada y las herramientas necesarias para realizar cada auditoría.

Por último, proporcionaremos una estimación de los costos asociados a la implementación de las herramientas. 

## Propuesta de auditorías ofensivas
A continuación introduciremos los distintos tipos de auditoría que ofrecemos, indicando los servicios de cada una, su alcance y los resultados que el cliente puede esperar.

### Auditoria de seguridad de aplicaciones
Esta auditoría tiene como objetivo evaluar la seguridad de los sistemas y aplicaciones usados o desarrollados, identificando vulnerabilidades que un atacante pueda localizar y explotar.

**Servicios ofrecidos**
+ Pruebas de inyección SQL, cross-site scripting (XSS)...
+ Análisis del código fuente para detectar fugas de datos.
+ Revisión de políticas de autenticación y autorización.
+ Validación de protocolos de seguridad y cifrado.

**Alcance**

Se analizarán únicamente las aplicaciones que el cliente tenga desplegadas, ya sean internas o externas, priorizando las que manejen datos sensibles.

**Resultados esperados**
+ Informe detallado de las vulnerabilidades encontradas y categorizadas por su gravedad.
+ Recomendaciones para mitigar las vulnerabilidades encontradas.
+ Mejora en la seguridad de las aplicaciones tras implementar las contramedidas sugeridas.

### Auditoria de seguridad de redes
La auditoría de seguridad de red se centra en evaluar la seguridad de la infraestructura de red de la organización. Para ello se identifican vulnerabilidades en servidores, routers, switches, ordenadores personales, firewalls y otros dispositivos de la red de la empresa.

**Servicios ofrecidos**
+ Pruebas de penetración para identificar puntos débiles de la red.
+ Revisión de la configuración y la seguridad de dispositivos internos como firewalls, switches y routers.
+ Revisión de la gestión de parches y actualizaciones.

**Alcance**
Se realizará sobre todos los activos conectados a la red interna de la empresa (Servidores, switches, portátiles...).

**Resultados esperados**
+ Un informe detallado con los hallazgos y recomendaciones para mejorar la seguridad de la red.
+ Un plan de acción para la mitigación de las vulnerabilidades identificadas.
+ Reducción del impacto provocado por ataques de fuerza bruta, DDoS o MitM.

### Auditoria de gestión de incidentes
Este tipo de auditoría evalúa los procedimientos y la capacidad de respuesta de la organización ante diversos incidentes de seguridad.

**Servicios ofrecidos**
+ Evaluación del sistema actual de gestión de incidentes.
+ Análisis del proceso completo, desde que se detecta el incidente hasta su resolución.
+ Implementación o mejora del sistema de gestión basado en mejores prácticas.

**Alcance**
Todos los procesos internos relacionados con la gestión y respuesta a incidentes.

**Resultados esperados**
+ Mejora en la capacidad de respuesta a incidentes, ya sean provocados por ataques de malware, ataques a la red u otras causas.
+ Reducción del impacto negativo de los incidentes.
+ Prevención efectiva contra futuros incidentes.

### Auditoria de políticas y procedimientos
La auditoría de políticas y procedimientos se centra en la revisión y evaluación de las políticas, normas y procedimientos de seguridad establecidos en la empresa. 

**Servicios ofrecidos**
+ Revisión de las políticas actuales.
+ Evaluación del cumplimiento de las normativas legales.
+ Desarrollo o actualización de políticas siguiendo estándares internacionales.

**Alcance**
Todas las políticas internas relacionadas con la ciberseguridad.

**Resultados esperados**
+ Aumento de la concienciación sobre la ciberseguridad por parte de los empleados reduciendo así posibles ataques de ingeniería social, de fuerza bruta o de malware que dependa de la acción de la víctima.
+ Mejora en la efectividad de las políticas internas.

[Auditoría de seguridad informática: qué es, ventajas, tipos y fases](https://blog.hubspot.es/website/auditoria-de-seguridad
)

## Propuesta de metodología de auditoría
A continuación introduciremos los distintos tipos de auditoría que ofrecemos, indicando los servicios de cada una, su alcance y los resultados que el cliente puede esperar.

### Auditoría de ingeniería social
Esta auditoría tiene como objetivo evaluar la resistencia de la organización frente a ataques de ingeniería social, identificando vulnerabilidades en el factor humano que podrían ser explotadas por atacantes.

**Servicios ofrecidos**
+ Simulaciones de phishing, spear phishing y whaling
+ Pruebas de pretexting y baiting
+ Evaluación de la concienciación de seguridad de los empleados
+ Análisis de la exposición de información sensible en redes sociales y fuentes públicas

**Alcance**
Se realizará sobre una muestra representativa de empleados de todos los niveles de la organización, con énfasis en aquellos con acceso a información crítica o sistemas sensibles.

**Resultados esperados**
+ Informe detallado de las vulnerabilidades encontradas en las prácticas de los empleados
+ Estadísticas de efectividad de los ataques simulados
+ Recomendaciones para mejorar la resistencia a ataques de ingeniería social
+ Plan de formación y concienciación personalizado basado en los hallazgos

### Auditoría de malware
La auditoría de malware se centra en evaluar la capacidad de la organización para prevenir, detectar y responder a diferentes tipos de software malicioso.

**Servicios ofrecidos**
+ Pruebas de penetración con malware simulado (virus, gusanos, troyanos)
+ Evaluación de la efectividad de las soluciones antimalware existentes
+ Análisis de la resistencia frente a ransomware, spyware y adware
+ Revisión de políticas y procedimientos de prevención y respuesta a malware

**Alcance**
Se realizará sobre los sistemas críticos de la organización, incluyendo servidores, estaciones de trabajo y dispositivos móviles corporativos.

**Resultados esperados**
+ Informe detallado de las vulnerabilidades encontradas frente a diferentes tipos de malware
+ Evaluación de la efectividad de las defensas actuales contra malware
+ Recomendaciones para mejorar la detección y prevención de malware
+ Plan de acción para fortalecer la resistencia de la organización contra ataques de malware

### Auditoría de seguridad de redes y sistemas
Esta auditoría se enfoca en evaluar la seguridad de la infraestructura de red y sistemas de la organización, identificando vulnerabilidades que podrían ser explotadas por atacantes.

**Servicios ofrecidos**
+ Pruebas de penetración en redes internas y externas
+ Evaluación de vulnerabilidades a ataques DDoS
+ Pruebas de Man-in-the-Middle (MitM)
+ Análisis de seguridad en aplicaciones web (incluyendo inyecciones SQL y Cross-Site Scripting)
+ Evaluación de la robustez de contraseñas y políticas de acceso

**Alcance**
Se realizará sobre toda la infraestructura de red de la organización, incluyendo servidores, firewalls, routers, switches, y aplicaciones web críticas.

**Resultados esperados**
+ Informe detallado de las vulnerabilidades encontradas en redes y sistemas
+ Mapa de la red con puntos críticos identificados
+ Recomendaciones para mitigar las vulnerabilidades descubiertas
+ Plan de acción priorizado para mejorar la seguridad de la infraestructura

### Auditoría integral de ciberseguridad
Esta auditoría combina elementos de las auditorías anteriores para proporcionar una evaluación completa de la postura de seguridad de la organización.

**Servicios ofrecidos**
+ Todos los servicios mencionados en las auditorías anteriores
+ Evaluación holística de la seguridad, abarcando factores técnicos y humanos
+ Análisis de la madurez en ciberseguridad de la organización
+ Simulación de escenarios de ataque complejos que combinan múltiples vectores

**Alcance**
Abarca todos los aspectos de la seguridad de la organización, incluyendo personal, procesos y tecnología.

**Resultados esperados**
+ Informe exhaustivo del estado de seguridad de la organización
+ Identificación de vulnerabilidades críticas en todos los niveles
+ Plan estratégico de mejora de la seguridad a corto, medio y largo plazo
+ Recomendaciones para establecer un programa de seguridad continuo y efectivo


## Propuesta de herramientas de monitorización
En este apartado recabaremos las herramientas que hemos seleccionado para nuestro catálogo de auditorías de pentesting. Las hemos dividido las herramientas por auditoría

### Herramientas de ingeniería inversa
Hemos seleccionado: 

+ Cofense PhisMe  
    - Justificación: Es una plataforma ideal para realizar campañas de phishing y concienciar a los empleados sobre este tipo de ataques
    - Coste: 500 € anuales
    - Ventajas: monitoreo en tiempo real, módulos de capacitación para los empleados e informes detallados sobre las campañas. 

+ SET (Social-Engineer Toolkit)
    - Justificación: ideal para simulaciones de ingeniería social como pueden ser campañas de phishing o clonaciones de sitios webs para la captura de credenciales.
    - Coste: gratuito (código abierto)
    - Ventajas: gratis, gran variedad de ataques y porta avanzadas herramientas para hacer las pruebas.

### Herramientas de malware
Para este apartado hemos seleccionado: 

+ Cuckoo Sandbox
    - Justificación: podemos hacer análisis dinámicos de malware en entornos seguros sin peligro alguno de infección.
    - Coste: gratuito (código abierto)
    - Ventajas: gratis, personalizable, perfecto para análisis profundos de malware

### Herramientas para redes y sistemas

+ Wireshark
    - Justificación: esta herramienta es esencial para el análisis del tráfico de red y detección de vulnerabilidades
    - Coste: gratuito (código abierto)
    - Ventajas: gratis, interfaz intuitiva y muy utilizado en la industria de ciberseguridad (mucha documentación)

+ Nmap
    - Justificación: casi obligatoria para el escaneo y mapeo de redes.
    - Coste: gratuito (código abierto)
    - Ventajas: gratis, muy versátil y personalizable, y bastante potente

+ Metasploit
    - Justificación: plataforma con gran variedad de pruebas de penetración a sistemas
    - Coste: 
        - Versión Community: Gratis
        - Versión Pro: 4000 € anuales (depende del tamaño de la empresa)
    - Ventajas: tiene una amplia biblioteca de exploits, con actualizaciones regulares y posibilidad de opción gratuita

## Inversión inicial
Ahora crearemos una tabla donde recogeremos la inversión inicial que tendremos que tener para iniciar. En el recuento contaremos los sueldos, herramientas, portátiles y otros posibles gastos. 
Las herramientas en su mayoría son de código abierto por lo que no tendremos que pagar nada, aunque algunas tienen suscripciones.  

| Recurso / herramienta | Precio/mes |
|------|-----|
| Sueldos de los 3 integrantes | 1400 € x 3 = 4200 € |
| Metasploit | Rango entre 250-330 mensuales según la empresa| 
| Cofense | 10 € mensuales | 
| Portátiles HP Victus 15-fa0059ns (3 integrantes) | 700€ x 3 = 2100€|
| Otros posibles gastos | 1000 €
| Total | 7.640 € |

Contamos con que esto sería gasto mensual y los ordenadores solo entrarían dentro de los gastos del primer mes.
