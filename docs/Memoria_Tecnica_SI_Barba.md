

**Marco Legal y Estructura del “Relato”**  
---

María Dolores Barba López  
Desarrollo de Aplicaciones Multiplataforma  
15/5/26

**Índice**

1. Análisis de Necesidades	

2. Estimación de Costes de Infraestructura	

3. Estrategia de espliegue y comunicación

4. Justificación Científica

Bibliografía	

 ## 1. Análisis de Necesidades {#análisis-de-necesidades}

     
2. **¿Qué problema de la empresa resolvemos con Guacamole y Docker? (*Pista: centralización, ahorro de recursos, seguridad…*).**  
   En primer lugar, con guacamole se les permite a los usuarios poder manejar y vigilar las máquinas virtuales a través del mismo navegador web y dictar a los administradores para que se puedan conectar a través de un sistema extensible de autenticación, asegurando la seguridad de las MV bajo vigilancia.   
   En el docker, se permite a los usuarios construir, distribuir y ejecutar las aplicaciones que tengan los usuarios desde cualquier lugar. Con docker se puede aislar las aplicaciones dentro de los contenedores, su punto fuerte, quienes tendrán librerías y dependencias, esto provoca un ahorro de recurso que evita la ralentización  
3. **¿Por qué elegimos esta solución y no conectar directamente por RDP a cada máquina?**  
   Porqué con estas dos herramientas se permite hacer un uso excelente de las funciones al máximo sin tener que estar dependiendo de varias aplicaciones a la vez, permite que se pueda trabajar de manera simultánea desde un mismo punto lo que se rige como una de las mejores opciones que puede haber dentro de la distribución. 

## 2. Estimación de Costes de Infraestructura
<img width="788" height="191" alt="image" src="https://github.com/user-attachments/assets/7d4ed8fe-9d30-438e-9614-b149db8ba973" />

## 3. Estrategia de espliegue y comunicación
Se va a usar las integraciones de Cloud nativas pero combinandolas con SFTP. Estas integraciones trabajan de manera segura con HTTPS garantizando así el tránsito de las claves gestionadas. Además, para la autentificación de los roles, se elimina la necesidad de exponer las credenciales estáticas. Como va a ser una transferencia directa a los servidores, SFTP es la mejor opción frente a la otra ya que solo usa un único puerto protegido por SSH, asegurando una comunicación exitosa. 

Para que el equipo esté totalmente comunicado cuando pase algo o se tenga que hacer una reunión, la mejor manera es por Microsoft Teams. Es un app preparada para gestionar de manera eficiente la comunicación con los equipos, apoyo en los proyectos y aviso de cualquier incidencia. Es por escelencia la que usan la mayo0ría de las empresas. 

## 4. Justificación Científica
La tesis recoge lo consciente que es el problema de la nube para la búsqueda y la selección de los servicios web. Es por ello que indaga el como nuevas tecnologías pueden hacer frente a este problema y mejorar una calidad con respecto a este problema. El sistema es concebido desde una arquitectura por componentes que brinda la seguridad y a la adaptación de nuevos criterios. 

## Bibliografía 

| \[1\] | “Introducción a Docker ¡Evita problemas de compatibilidad\!”, .*Ed.team*. \[En línea\]. Disponible en: https://ed.team/blog/introduccion-a-docker-evita-problemas-de-compatibilidad. \[Consultado: 15-may-2026\]. |
| :---- | :---- |

| \[2\] | “Busqueda y selección de servicios web con restricciones QoS en ambientes cloud computing\!”, .*A. Jaimes y M. Antonio*. \[En línea\] Universidad del Norte, 2021. Disponible en: https://manglar.uninorte.edu.co/handle/10584/10092 . \[Consultado: 22-may-2026\]. |
| :---- | :---- |




