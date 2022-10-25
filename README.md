# service-configuration
Configuración de los microservicios atravez de un proyecto en spring de nombre "config server" jalando las configuraciones aca realizadas, pero este 
jalado de informacion se realiza en vivo, para que los proyectos que dependan de esta "configuracion" no se paren por alguna modificacion de sus properties, 
esto se realizo gracias a las dependencias [Spring Boot Actuator OPS, Config Server SPRING CLOUD CONFIG] y modificando el file properties con spring.cloud
como lo veras en la siguiente imagen
