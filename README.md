# Readme Guide

- [Elevator Pitch](#elevator-pitch)
- [Tecnologias y herramientas](#Tecnologias-y-herramientas-usadas)
- []()
- [Guía de Uso del Repositorio](#guía-de-uso-del-repositorio)
  - [Ramas del Repositorio](#ramas-del-repositorio)
    - [Rama main](#1-main)
    - [Rama experimental](#2-experimental)
    - [Rama hotfix](#3-hotfix)
    - [Rama release](#4-release)
    - [Rama bugfix](#5-bugfix)
    - [Rama feature](#6-feature)

# Elevator Pitch.
## Name: HelpDesk System.
## For: Medium Companies.
## Objetivo: Brindar Soluciones Eficientes para Problemas de Productos/Servicios.
## Características: Gestión de Usuarios, Proceso de Soporte Optimizado, Experiencia de Usuario Intuitiva.

El Sistema de Soporte HelpDesk es una solución diseñada para empresas medianas y grandes que buscan formas eficientes y rápidas de abordar consultas relacionadas con productos o servicios. Mediante la gestión fluida de usuarios —clientes, asistentes y administradores— el sistema agiliza el proceso de soporte. Con un enfoque en la simplicidad y la facilidad de uso, nuestra HelpDesk System garantiza asistencia rápida y sin complicaciones, mejorando la experiencia global del usuario.

# Tecnologias y herramientas usadas.

 Colaborativas:
 Discord
 Slack
 Jira software
 Git
 Github
 Trello

 Diseño: 
 Figma/photoshop

 BD?
 BACK?
 FRONT?

# Guía de Uso del Repositorio.

En este repositorio, utilizamos el idioma ingles, y diferentes ramas para organizar y gestionar el desarrollo de nuestro proyecto. Cada rama tiene un propósito específico y su uso adecuado ayudará a mantener un flujo de trabajo ordenado y colaborativo. A continuación, se detalla el propósito y el uso recomendado para cada una de las ramas disponibles:

## Ramas del Repositorio.

## 1. **main:**
La rama `main` es la rama principal y estable del repositorio. Debería contener únicamente el código que ha sido probado, revisado y considerado listo para ser desplegado en producción. Los commits en esta rama deben estar relacionados con versiones estables del software.

**Uso recomendado:** No se debe hacer commit directamente en esta rama. Los cambios se integran a través de pull requests provenientes de otras ramas.

## 2. **experimental:**
La rama `experimental` es el espacio para experimentar y probar nuevas funcionalidades o cambios importantes que aún no están listos para ser incluidos en la rama principal. Puede contener código en desarrollo y no necesariamente estable.

**Uso recomendado:** Los desarrolladores pueden crear ramas a partir de `experimental` para trabajar en nuevas características. Al finalizar, se debe crear un pull request hacia `experimental` para su revisión.

## 3. **hotfix:**
La rama `hotfix` se utiliza para solucionar problemas críticos en producción que requieren una corrección urgente. Estos arreglos deben aplicarse a la versión actual en producción y luego fusionarse en la rama `main`.

**Uso recomendado:** Se deben crear ramas a partir de `main` para realizar correcciones de errores críticos. Una vez corregido, se hace un pull request hacia `main` y, una vez aprobado, se debe fusionar tanto en `main` como en `experimental`.

## 4. **release:**
La rama `release` se utiliza para preparar una versión estable para su lanzamiento. Aquí se pueden hacer ajustes finales, pruebas exhaustivas y documentación antes de desplegar en producción. Una vez lista, se fusiona en `main` y se etiqueta con la versión correspondiente.

**Uso recomendado:** Se crea a partir de `main` y se realizan ajustes finales y pruebas. Luego, se hace un pull request hacia `main` y, una vez aprobado, se fusiona en `main` y `experimental`.

## 5. **bugfix:**
La rama `bugfix` se utiliza para abordar errores que no son críticos pero que necesitan ser corregidos en futuras versiones. Estos cambios se hacen en paralelo a otras características en desarrollo.

**Uso recomendado:** Los desarrolladores pueden crear ramas a partir de `experimental` para solucionar errores no críticos. Una vez resuelto, se hace un pull request hacia `experimental`.

## 6. **feature:**
La rama `feature` se utiliza para desarrollar nuevas características o mejoras en el proyecto. Aquí es donde se trabaja en la implementación de nuevas funcionalidades.

**Uso recomendado:** Los desarrolladores pueden crear ramas a partir de `experimental` para trabajar en nuevas características. Una vez completada la implementación y pasadas las pruebas, se hace un pull request hacia `experimental`.

Recuerda que antes de hacer cualquier cambio en las ramas principales, es importante crear ramas separadas, trabajar en ellas, y luego fusionar los cambios a través de pull requests. Esto permite una revisión adecuada y garantiza que el código que llega a las ramas principales sea de alta calidad y esté probado.
