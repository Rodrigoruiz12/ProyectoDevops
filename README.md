# Laboratorio DevOps

Este proyecto implementa una infraestructura de red segura en AWS utilizando una arquitectura de tres capas en la nube (Web, App y Datos) y automatización mediante GitHub Actions.

## Estructura del Proyecto
- **Frontend**: Archivo `index.html` básico con un servidor Nginx.
- **Contenerización**: Uso de `Dockerfile` basado en `nginx:alpine`.
- **CI/CD**: Automatización con GitHub Actions para subir la imagen a Docker Hub.

## Metodología de Trabajo
Se utiliza **GitFlow** para el manejo de ramas:
- `main`: Rama de producción.
- `feature/*`: Ramas de desarrollo para nuevas funcionalidades.

## Infraestructura (Fase III y IV)
- **VPC**: Red virtual privada con soporte DNS.
- **Subredes**: 1 Pública y 2 Privadas.
- **Seguridad**: Grupos de seguridad aislados por capas.