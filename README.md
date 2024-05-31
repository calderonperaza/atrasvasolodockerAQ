# atrasvasolodockerAQ





## Acceso a las opciones de administración
Si desea entrar a las opciones de administracion primero debe registrarse como admin, para ello debe ejecutar la siguiente peticion POST
```
curl -X POST http://admin:diplomado@localhost:3333/atrasvasolo-administradores -H "Content-Type: application/json" -d '{
    "tipo": "ADMINISTRADOR",
  "nombre": "minombre",
  "apellido": "miapellido",
  "email": "micorreo@gmail.com"
}'
```



