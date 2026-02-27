# Docker-compose

## Instrucciones de deployment

### 1. Descargamos Docker Desktop para Windows/Ubuntu o Docker Engine para Linux

https://www.docker.com

Y luego de instalar y verificar que todo este correcto levantamos el engine o abrimos docker desktop para que este funcionando correctamente

<img width="1911" height="548" alt="image" src="https://github.com/user-attachments/assets/cc38363b-1a74-4dae-abb0-42e97ba342f3" />

-----

### 2. Clonar los repositorios necesarios y descargarmos el compose de este repositorio


FrontEnd: https://github.com/Cloud-Security-G4/p1-menu-digital-frontend

BackEnd:  https://github.com/Cloud-Security-G4/p1-menu-digital-api

Dockercompose: https://github.com/Cloud-Security-G4/Docker-compose/blob/main/docker-compose.yml

-----

### 3. Organizamos el proyecto para evitar conflictor de rutas


**--- Proyecto 1:** \
&nbsp;&nbsp;&nbsp; **| --- p1-menu-digital-api** \
&nbsp;&nbsp;&nbsp; **| --- p1-menu-digital-frontend** \
&nbsp;&nbsp;&nbsp; **| --- Docker-compose.yml**

Tambien asi es como se ve deberia estar como en las siguientes imagenes de referencia:

<img width="702" height="244" alt="image" src="https://github.com/user-attachments/assets/225eb10c-fb4b-4bf6-a8f1-4119ce07510a" />


<img width="622" height="117" alt="image" src="https://github.com/user-attachments/assets/6a91b4b6-5bd5-4894-82ab-0957ca272a12" />

### 4. Hacer el deployment

Aca simplemente nos ubicamos en la carpeta indicada en el paso anterior y ya con Docker Engine corriendo o Docke Desktop abierto, realizamos el siguiente comando:

```
docker-compose up --build
```

<img width="1086" height="385" alt="image" src="https://github.com/user-attachments/assets/4f34cb63-b1c6-4c4d-84dc-b0a9e846b5c2" />

Y ya finalmente deberiamos ver algo asi

<img width="1106" height="621" alt="image" src="https://github.com/user-attachments/assets/dd459523-1037-4fb8-a776-716e37bff5af" />

<img width="1615" height="356" alt="image" src="https://github.com/user-attachments/assets/2f2b30e8-9705-45f7-8bc7-b5dc6e3425f0" />


