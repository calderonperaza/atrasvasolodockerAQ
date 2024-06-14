# atrasvasolodockerAQ
Este es un proyecto para realizar pruebas

## Instalación
Debes tener instalado docker y docker-compose en tu maquina

## Uso
Para ejecutar y levantar el proyecto debes ejecutar el siguiente comando ubicado en la raiz del proyecto
```bash 
docker compose up -d
```
Para detener el proyecto ejecuta el siguiente comando
```bash
docker compose down
```


## Acceso a la aplicación
una vez levantado puedes acceder desde el navegador a la siguiente url a la apps
```
http://localhost:8080
```



## Acceso a las opciones de administración (opcional)
Si desea entrar a las opciones de administracion primero debe registrarse como admin, para ello debe ejecutar la siguiente peticion POST
```
curl -X POST http://admin:diplomado@localhost:3333/atrasvasolo-administradores -H "Content-Type: application/json" -d '{
    "tipo": "ADMINISTRADOR",
  "nombre": "minombre",
  "apellido": "miapellido",
  "email": "micorreo@gmail.com"
}'
```



