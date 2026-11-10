# Proyecto Integración Continua - Entrega 1

## Objetivo
Implementar dos contenedores Docker comunicados entre sí para la primera entrega del proyecto.

## Arquitectura
Se utiliza Docker Compose para crear dos contenedores basados en Alpine Linux:
1. **contenedor-cliente**: Inicia la comunicación.
2. **contenedor-servidor**: Recibe la comunicación.

Ambos están conectados a la red `red-integracion`, lo que permite que se resuelvan por nombre (DNS interno de Docker).

## Demostración
*(Las capturas de pantalla de la ejecución se adjuntan a continuación)*
