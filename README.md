# PruebaPhyton
prueba para analisis de codico con Snyk

## Aplicación Python intencionalmente vulnerable
Este repositorio contiene una aplicación web Python deliberadamente vulnerable, diseñada para realizar pruebas. La aplicación presenta varias vulnerabilidades de seguridad que pueden detectarse mediante herramientas de seguridad como el Análisis de Composición de Software (SCA), las Pruebas de Seguridad de Aplicaciones Estáticas (SAST) y las Pruebas de Seguridad de Aplicaciones Dinámicas (DAST).

### Vulnerabilidades Clave: 
### Inyección de Comandos: 
La entrada del usuario se pasa directamente a un comando del sistema sin validación.  
### Credenciales codificadas: 
Almacenamiento inseguro de credenciales dentro del código fuente. 
### Deserialización insegura: 
Uso del módulo pickle de Python, que puede provocar la ejecución de código arbitrario. 
### Bibliotecas Obsoletas: 
La aplicación utiliza una versión obsoleta de la biblioteca de solicitudes, que puede presentar vulnerabilidades conocidas. 
### Inyección SQL: 
La entrada del usuario se utiliza para crear consultas SQL sin una limpieza adecuada. 
### Propósito: 
Este repositorio está diseñado para su uso en capacitación en seguridad, análisis de vulnerabilidades y herramientas de prueba como DefectDojo. Proporciona un entorno seguro para comprender cómo se pueden identificar y explotar diferentes vulnerabilidades de seguridad.
