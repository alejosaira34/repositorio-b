# GTAV

##  Instalar 
 
 
Descargaer el "curl","emqx" y configurar el emqx.
curl -s https://assets.emqx.com/scripts/install-emqx-deb.sh | sudo bash

apt-get install curl
curl -s https://assets.emqx.com/scripts/install-emqx-deb.sh | sudo bash
apt-get install emqx
apt-get install screen
 

## Redis Setup  - Autenticacion
 
HMSET users:alejo password_hash 123
HMSET users:leo password_hash 123


## Redis Setup  - Autorizacion
 
HMSET auth:alejo XXXXX XXXX
HMSET auth:leo XXXXX XXXX

## TODOS

- Guardar Mesanjes
- Guardar Archivos
- Crear/Borrar/Actualizar usuarios 
