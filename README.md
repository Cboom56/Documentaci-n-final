# Documentaci-n-final
Proyecto académico de la asignatura Programación Web
Requisitos del Proyecto
Para la correcta ejecución del proyecto CineRent se requieren los siguientes elementos:

- Sistema Operativo: Windows, Linux o macOS.
- Java Development Kit (JDK) versión 21.
- Apache NetBeans 18 o superior.
- PostgreSQL versión 13 o superior.
- pgAdmin 4 para la administración de la base de datos.
- Base de datos Pagila correctamente importada.
- Conexión a internet (solo para descarga de dependencias Maven).

Tecnologías utilizadas:
- Spring Boot (arquitectura MVC).
- Thymeleaf (motor de plantillas).
- JDBC Template (acceso a datos).
- Maven (gestión de dependencias).
- PostgreSQL (base de datos relacional).
   Pasos de Instalación
1. Instalar el JDK 21 y configurar la variable de entorno JAVA_HOME.
2. Instalar Apache NetBeans 18.
3. Instalar PostgreSQL y pgAdmin 4.
4. Crear una base de datos llamada 'pagila'.
5. Importar los archivos pagila-schema.sql y pagila-data.sql desde pgAdmin.
6. Abrir NetBeans y seleccionar 'Open Project'.
7. Cargar el proyecto CineRent.
8. Verificar el archivo application.properties y configurar usuario, contraseña y puerto de PostgreSQL.
9. Permitir que Maven descargue automáticamente las dependencias.
3. Ejecución del Proyecto
Para ejecutar el proyecto se deben seguir los siguientes pasos:

1. Abrir el proyecto CineRent en NetBeans.
2. Ejecutar la opción 'Clean and Build'.
3. Ejecutar el proyecto con 'Run Project'.
4. Acceder desde el navegador web a:
   - http://localhost:8090/ (Inicio)
   - http://localhost:8090/dashboard (Dashboard)
   - http://localhost:8090/films (Catálogo de películas)
   - http://localhost:8090/customers (Clientes)
   - http://localhost:8090/reports (Reportes)

El servidor embebido Tomcat se inicia automáticamente.
Conclusión
El proyecto CineRent constituye una aplicación web robusta desarrollada bajo una arquitectura MVC, orientada al análisis y consulta de información real proveniente de la base de datos Pagila. A través de módulos como el catálogo de películas, gestión de clientes, dashboard y reportes analíticos, el sistema permite explorar datos transaccionales y financieros de forma estructurada y eficiente.

La utilización de JDBC Template garantiza un control preciso sobre las consultas SQL, permitiendo optimizar el rendimiento y adaptarse a variaciones reales del esquema de datos. Asimismo, la separación por capas mejora la mantenibilidad, escalabilidad y claridad del proyecto.

En conclusión, CineRent demuestra la correcta integración de tecnologías backend, bases de datos relacionales y presentación web, cumpliendo con los objetivos académicos y sentando bases sólidas para futuras mejoras como autenticación, gráficos interactivos y despliegue en producción.
