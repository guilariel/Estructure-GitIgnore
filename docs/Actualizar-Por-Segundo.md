# Actualizacion por segundo

## Resuelve el bug de la actualizacion de dbs no es automatica

para hacer esto se actualizan las bases de datos cada segundo en vez de cada minuto para asegurar que los cambios se vean correctamente y no se generen errores porque no se encuentran datos

## Como lo hicimos 

hicimos un cambio en el servicio de DBJob para que se ejecute cada segundo en vez de cada minuto