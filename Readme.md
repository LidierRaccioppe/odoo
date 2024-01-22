# Manejando Odoo

## Instalación con Docker Compose

Ejecutar un `docker compose up -d` en la terminal en la ubicacion del archivo docker-compose.yml para poder ejecutar levantar el postgres y el odoo.


## Error puerto Ocupado

De estar el puerto 5432 ocupado se puede usar los siguientes comandos para poder limpiarlo:

Se obtendra el servicio que esta usando el puerto, mirar la ultima columna .

`sudo netstat -putan | grep 5432`

Para eliminar el proceso que este usando ese puerto 

`sudo pkill nombreDelUsuario`

Con esto se habra despejado el puerto