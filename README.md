# Taller de productividad basada en tecnologicas
Software de gestion adiministrativa para la Guarderia Mi escuelita 


# Descripción
El desarrollo de un sistema de gestión de documentos para la Guardería Mi Escuelita busca optimizar procesos administrativos y asegurar el cumplimiento de estándares de calidad, especialmente los establecidos por el IMSS. Surge de un análisis de las dificultades en la gestión de archivos relacionados con la afiliación al IMSS y otros aspectos administrativos. Los beneficios incluyen mayor eficiencia operativa, cumplimiento normativo, seguridad de la información y facilitación de la toma de decisiones. Los objetivos específicos son mejorar la gestión de documentos, agilizar el acceso y almacenamiento de los mismos, garantizar el cumplimiento normativo, incrementar la eficiencia operativa, mejorar la seguridad de la información, facilitar la toma de decisiones y mejorar la experiencia del usuario.

# Problema identificado
La Guardería Mi Escuelita, ubicada en Toluca, Estado de México, enfrenta 
desafíos significativos en la gestión de archivos relacionados con la 
afiliación al Instituto Mexicano del Seguro Social (IMSS) y los estándares 
de calidad requeridos por dicha institución. A pesar de los esfuerzos 
manuales por parte del personal administrativo, la gestión de documentos 
se ha vuelto compleja y poco eficiente, lo que impacta negativamente en la 
operatividad y el cumplimiento normativo de la guardería.

# Aviso sobre el desarrollo del proyecto
Este proyecto ha sido desarrollado principalmente en HTML y JavaScript, aunque su implementación final se realizará en Java. Nos gustaría proporcionar una explicación sobre esta elección.

Debido a un acuerdo de confidencialidad con nuestro cliente, no podemos divulgar detalles específicos sobre la tecnología utilizada ni compartir el código fuente completo del proyecto en este momento. Sin embargo, podemos asegurarles que el proyecto está en proceso y que estamos trabajando diligentemente en su desarrollo.

Dado este contexto, hemos decidido presentar una versión simplificada del proyecto en HTML y JavaScript en este repositorio público de GitHub. Esto nos permite compartir una representación visual del proyecto y demostrar algunos de los conceptos clave sin comprometer la confidencialidad de la implementación final en Java.

# Requisitos solicitados

Se requiere un diseño intuitivo, simple y fácil de usar.
Es necesario poder visualizar la información de manera clara.
Debe haber una opción para agregar nueva información directamente desde el software.
Se debe permitir guardar nueva información, como detalles de empleados, planos y estándares de calidad actualizados.

# Requerimentos de la aplicación
Servidores:
  
  -Aplicación web: Apache Tomcat 9.0
  
  -Base de datos: MySQL Server 8.0
  
  -Servidor de aplicaciones: WildFly 20.0

Paquetes adicionales:

  -Framework de desarrollo web: Spring Boot 2.5.0
  
  -Manejador de dependencias: Maven 3.8.1
  
  -Biblioteca de pruebas: JUnit 5.7.2
  
  -Herramienta de integración continua: Drone 1.0

# Requisitos de Java
JDK 11 (OpenJDK 11.0.12)

# Instalación

Ambiente de desarrollo:

-Descarga e instala JDK 11 desde el sitio web oficial de OpenJDK.

-Instala Apache Maven 3.8.1 siguiendo las instrucciones de instalación en el sitio web de Maven.

-Configura las variables de entorno JAVA_HOME y MAVEN_HOME según corresponda.

-Clona el repositorio del proyecto desde GitHub.

-Abre el proyecto en tu IDE preferido.

Ejecución de pruebas manualmente:

-Abre una terminal y navega hasta el directorio raíz del proyecto.
Ejecuta el comando mvn test para ejecutar todas las pruebas del proyecto.
Observa los resultados de las pruebas en la consola y en los informes generados.

Implementación en producción en un ambiente local:

-Configura un servidor Apache Tomcat 9.0 en tu máquina local.

-Crea una base de datos MySQL Server 8.0 y configura las credenciales de acceso.

-Construye el proyecto utilizando Maven con el comando mvn clean install.

-Despliega el archivo WAR generado en el servidor Tomcat.

-Configura el archivo de propiedades de la aplicación para apuntar a la base de datos MySQL local.

-Inicia el servidor Tomcat y accede a la aplicación desde tu navegador web.

# Modificación del Código
Para realizar cambios en el código, se debe instalar y configurar un entorno de desarrollo integrado (IDE) preferido.
Luego, se debe abrir la carpeta del proyecto dentro del IDE.

# Uso
Este software está destinado para uso interno dentro del departamento correspondiente de la empresa.
Los permisos de acceso variarán según las responsabilidades individuales de cada usuario.

# Drone para Pruebas
Cada vez que realizamos una modificación en el repositorio de GitHub, Drone automáticamente ejecuta una serie de pruebas para verificar la integridad y el rendimiento del código. Estas pruebas incluyen la compilación del proyecto, la ejecución de pruebas unitarias y cualquier otra validación necesaria para asegurar que el código cumple con nuestros estándares de calidad.

Al utilizar Drone, hemos podido automatizar gran parte del proceso de desarrollo, lo que nos permite detectar y solucionar problemas de manera más rápida y eficiente. Además, al integrar Drone con nuestras herramientas de control de versiones y despliegue, hemos logrado un flujo de trabajo más fluido y coherente en todo el ciclo de vida del desarrollo de nuestro proyecto.


# Diagrama de arquitectura del sistema 
[DIagrama de Arquitectura.pdf](https://github.com/ALEXRR02/MiEscuelita/files/15156467/DIagrama.de.Arquitectura.pdf)
