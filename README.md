# Práctica 3: Despliegue de Software

Este repositorio contiene el código y la documentación correspondiente a la **Práctica 3: Publicación de Aplicaciones Web**, 
enfocada en el despliegue de soluciones en entornos On-Premises (IIS) y en la nube (Azure App Service).

## Integrantes Equipo Big Whale

* Yulieth Urrego Restrepo
* Franyelica Garcia
* Santiago Castaño Torres
* Juan David Palacio
* Maria Jose Yepes

## Video de Evidencia

Explicación detallada del proceso de despliegue y funcionamiento en el siguiente enlace: 
https://youtu.be/gNvl6hARLzI?si=aKceIVMOkRY5wdXa

---

## Descripción del Proyecto
`Multi Link Opener` es una herramienta web diseñada para automatizar la apertura de múltiples enlaces de manera eficiente.

### Parte 1: Publicación en IIS (On-Premises)
Se realizó la configuración completa en un entorno Windows 11 utilizando **Internet Information Services (IIS)**:
1.  **Habilitación de Rol:** Activación de las características de IIS en Windows.
2.  **App Pool Dedicado:** Creación de `AppPoolEjercicio` para el aislamiento de la aplicación.
3.  **Configuración del Sitio:** Despliegue en el puerto `8082` con la ruta física apuntando al directorio del proyecto.
4.  **Endpoint de Salud:** Verificación exitosa del estado del servicio a través de la ruta `/health`.

### Parte 2: Publicación en Azure App Service
1. Configuración de recursos en Azure, activación de **HTTPS Only** y gestión de **Application Settings**.

---

## Estructura de Evidencias
Las capturas de pantalla que validan el cumplimiento de los criterios de la rúbrica se encuentran organizadas en el siguiente documento:
[https://docs.google.com/document/d/1gpU2RWOoT5I1xgOpu5go0R3Z0dZzLTDs/edit?usp=sharing&ouid=101759624993509524104&rtpof=true&sd=true]

---
