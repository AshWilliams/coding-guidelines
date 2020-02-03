
# Nombre o titulo del proyecto

## 1. Resumen o Descripci�n
Proyecto de administraci�n de notas de estudiantes de ...


## 2. Prerequisitos
Debe tener instaladas en su m?quina las siguientes herramientas: 

- Java JDK 1.8 
- Maven: https://maven.apache.org/download.cgi
- Eclipse: http://download.jboss.org/jbosstools/updates/m2e-extensions/m2e-apt


## 3. Instalaci?n

Desde el directorio /lib ejecutar el siguiente comando 
```
	mvn install:install-file -Dfile=ojdbc7.jar -DgroupId=com.oracle -DartifactId=ojdbc7 -Dversion=12.1.0.2.0 -Dpackaging=jar
```

## 4. Como utilizar

Utilizando Eclipse ...
```
    maven > Update project
```
	
Para compilar el proyecto utilizar el siguiente comando maven:
```
    mvn clean install -DskipTests
```
## 5. Wiki

Puedes encontrar mucho m�s de c�mo utilizar este proyecto en nuestra Link a la wiki

## 6. Contribuyentes

Andres Perez (usuario GitHub)

## 7. Versi�n

1.0.1.2 LTS

## 8. Autores
 
Cristian Camacho (usuario GitHub)
Andres Perez (usuario GitHub)

## 9. Soporte

Este software esta soportado por el equipo de ... Si tienes alg�n inconveniente con el software puedes reportarlo en ....

## 10. Licencia
Este proyecto est� bajo la Licencia GPL, BSD, Software Propietario

## 11. Estado del proyecto

Este proyecto a�n est� en fase de desarrollo, actualmente se est� trabajando en los m�dulos...

Este proyecto se encuentra en fase de soporte, actualmente no se est�n trabajando nuevos desarrollos sobre el mismo.

**Nota: Este proyecto cumple con el estandar definido para la gesti�n de versionamiento del c�digo definido por la DSIT. El cual se encuentra publicado en...**