# Archivos de Configuración para Microservicios

Esta carpeta contiene los archivos de configuración para los microservicios del proyecto. Cada archivo YAML corresponde a un microservicio específico y contiene su configuración.

## Estructura de Archivos

- `gateway.yml`: Configuración del Gateway Service
- `dashboard.yml`: Configuración del Dashboard Service
- `mc1.yml`: Configuración del Microservicio 1
- `mc2.yml`: Configuración del Microservicio 2

## Uso

Estos archivos son utilizados por el Config Server para proporcionar configuración centralizada a los microservicios. Cada microservicio se conecta al Config Server y obtiene su configuración correspondiente.

## Formato

Los archivos están en formato YAML y contienen la configuración específica para cada microservicio, incluyendo:
- Configuración de la base de datos
- Configuración del servidor
- Configuración de Eureka
- Configuración de seguridad
- Otras configuraciones específicas del servicio 