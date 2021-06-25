# VPS
### El creador original de este proyecto fue suspendido en GitHub.
> ## [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/c9ffin/vps/blob/main/.github/workflows/c9ffin.yml)
***
### Especificaciones.
- OS : Ubuntu 20.04
- 2-core vCPU
- 7 GB RAM
***

## Configuración:
1. "Fork" este proyecto, al hacer el "Fork"
2. Ve a la configuración y selecciona "Secrets" y rellenas lo siguiente como en la siguiente tabla.

Secrets Nombre | Uso | Lo que debes de poner
----- | ----- | -----
`NGROK_AUTH_TOKEN` | Para el tunel de **ngrok** | Ve a https://dashboard.ngrok.com/auth/your-authtoken y copia el codigo
`LINUX_USERNAME` | Username de la maquina | Lo que tu quieras
`LINUX_USER_PASSWORD` | Contraseña de la VPS `root password` | Lo que tu quieras
`LINUX_MACHINE_NAME` | Nombre del equipo `Computer` | Lo que tu quieras.
`GIT_NAME` | Nombre de usuario que quieres que se ponga en github | El nombre de usuario de github.
`GIT_EMAIL` | Este correo será para configurar github | El correo de github.
***
## Como iniciarlo?
    
1. Ve a `Actions` y selecciona la workflow.

2. Clickea en `Run Workflow` boton junto a  `This workflow has a workflow_dispatch event trigger` 

3. Espera

4. Ve a https://dashboard.ngrok.com/endpoints/status y checha si todo sirve correctamente.

5. Copia el link(**sin tcp://**) y ve a **PuTTY**

6. Y rellena los campos y todo listo.

7. Disfruta de tu maquina.

