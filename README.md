# Proyecto Integración Continua - Laboratorio Dental

## Objetivo del Proyecto
Este repositorio contiene el proyecto de una aplicación móvil desarrollada en **Ionic y Angular**. El objetivo es implementar y demostrar prácticas de Integración Continua (CI) a lo largo del semestre, evidenciando un desarrollo iterativo e incremental.

## Estado del Proyecto (Evolución)

### Fase 1 (Entrega 1): Configuración Base e Infraestructura Docker
En esta primera etapa, se ha establecido la base del proyecto. Se subieron los archivos de configuración de dependencias (como 'package.json' y 'angular.json') para inicializar el entorno de desarrollo.

Adicionalmente, se implementó la infraestructura base de contenedores:
*   **Red Docker:** Se configuró una red interna llamada 'red-integracion'.
*   **Contenedores:** Se crearon dos contenedores ('contenedor-cliente' y 'contenedor-servidor') para validar la comunicación y resolución de nombres (DNS interno de Docker).

#### Evidencia de Ejecución (Docker)
A continuación, se adjunta la evidencia del ping exitoso entre los contenedores, comprobando la correcta comunicación:

![Evidencia Ping](evidencia-ping.png)
