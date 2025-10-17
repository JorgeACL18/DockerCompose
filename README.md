# Docker Compose
En esta tarea tenemos que montar con Docker Compose un sistema de gestión empresarial, en este caso aprenderemos a establecer la Prestashop mediante el uso de su imagen y phpAdmin.

## Paso 1
El primer paso es realizar el archivo .yml, el cual servirá para que el comando `docker compose up --build` funcione.
Para esto, creamos el archivo y tenemos que añadir el siguiente código:

<img width="610" height="1077" alt="Captura de pantalla 2025-10-17 161119" src="https://github.com/user-attachments/assets/a13f5e63-4a95-4036-970e-5217e01687fd" />

Una vez introducido el código, tenemos que dirigirnos a la terminal donde ejecutaremos el código `docker compose up --build` el cual nos habilitará acceder a [http://localhost:8080](http://localhost:8080) (8080 para el Prestashop) y a [http://localhost:8081](http://localhost:8081) (8081 para el phpAdmin)


## Paso 2
Ahora que ya tenemos el programa funcionando solo queda probar. Accedemos a [http://localhost:8081](http://localhost:8081) para ver la página de nuestro servidor, iniciamos sesión y vemos que todo está en orden.

<img width="2047" height="1135" alt="Captura de pantalla 2025-10-17 163812" src="https://github.com/user-attachments/assets/24672ef5-4d38-49cf-bf21-cb3c922d4a68" />

Después, entramos a [http://localhost:8080](http://localhost:8080) para iniciar sesión y configurar la página de Prestashop

<img width="1294" height="752" alt="Captura de pantalla 2025-10-17 161218" src="https://github.com/user-attachments/assets/278dd637-61cb-46be-8f6c-5c9a3c5ffcdc" />

Cuando ya termines este proceso, solo recargaremos la página y veremos que funciona correctamente.


<img width="1526" height="657" alt="Captura de pantalla 2025-10-17 163840" src="https://github.com/user-attachments/assets/5e9919b3-f1ef-4a98-8c93-35fdedd67e87" />
