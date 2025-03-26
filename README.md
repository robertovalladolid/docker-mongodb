# MongoDB Docker Compose Setup

Este repositorio contiene una configuración lista para desplegar **MongoDB 6.0** en un contenedor Docker usando Docker Compose, ideal para entornos de desarrollo y producción.

## Características

- MongoDB 6.0 (LTS) con autenticación habilitada
- Configuración optimizada para producción
- Volúmenes persistentes para datos, logs y configuración
- Variables de entorno manejadas mediante `.env`
- Compatible con CI/CD (GitHub Actions ejemplo incluido)

## Instalación Rápida

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/robertovalladolid/docker-mongodb.git
   cd docker-mongodb
