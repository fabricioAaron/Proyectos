# Portfolio estático en Azure App Service

Proyecto personal para practicar despliegue de una web estática (HTML/CSS) en Microsoft Azure usando una suscripción de estudiante.

## Objetivo

- Afianzar conceptos básicos de Git y GitHub.
- Entender el flujo de despliegue a Azure App Service.
- Preparar una base para futuros laboratorios con CI/CD y más servicios de Azure.

## Tecnologías

- HTML5 y CSS3.
- Git y GitHub.
- Microsoft Azure App Service (suscripción Azure for Students).

## Arquitectura

- El código vive en este repositorio de GitHub.
- Una Web App de Azure App Service está conectada a este repo mediante el Deployment Center.
- Cada vez que hago `git push` a `main`, Azure actualiza automáticamente la web.

## Pasos principales

1. Crear la web estática (HTML + CSS).
2. Inicializar repositorio Git local y primer commit.
3. Crear repositorio en GitHub y hacer push.
4. Crear Web App en Azure App Service.
5. Conectar la Web App con el repositorio de GitHub (Deployment Center).

## Qué he aprendido

- Flujo básico de trabajo con Git (`init`, `add`, `commit`, `remote`, `push`).
- Conceptos básicos de Azure: grupo de recursos, App Service, plan de App Service.
- Configuración de un flujo de despliegue automático desde GitHub a Azure.

## Próximos pasos

- Añadir una canalización CI/CD con GitHub Actions o Azure DevOps Pipelines.
- Incluir más proyectos y secciones en el portfolio.
- Explorar integración con servicios como Azure Storage, Azure Functions o Azure SQL.
