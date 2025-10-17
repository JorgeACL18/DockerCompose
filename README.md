# Docker Compose
En esta tarea tenemos que montar con Docker Compose un sistema de gestión empresarial, en este caso aprenderemos a establecer la Prestashop mediante el uso de su imagen y phpAdmin.

## Paso 1
El primer paso es realizar el archivo .yml, el cual servirá para que el comando `docker compose up --build` funcione.
Para esto, creamos el archivo y tenemos que añadir el siguiente código:

<img width="610" height="1077" alt="Captura de pantalla 2025-10-17 161119" src="https://github.com/user-attachments/assets/a13f5e63-4a95-4036-970e-5217e01687fd" />

Una vez introducido el código, tenemos que dirigirnos a la terminal donde ejecutaremos el código `docker compose up --build` el cual nos habilitará acceder a [http://localhost:8080](http://localhost:8080) (8080 para el Prestashop) y a [http://localhost:8081](http://localhost:8081) (8081 para el phpAdmin)
