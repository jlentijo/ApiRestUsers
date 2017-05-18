Set up
------

1. Instala NodeJS (LTS) desde el siguiente link https://nodejs.org/es/download/.
2. Instala MongoDB (Community Server) desde el siguiente link https://www.mongodb.com/download-center#community. 
3. Crea una carpeta donde se almacenará la base de datos de MongoDB.
4. Abre el terminal y ejecuta el comando: <code>"C:\Program Files\MongoDB\Server\3.4\bin\mongod" --dbpath="path/to/db"</code>
5. Abre otro terminal, situate dentro de la carpeta ApiRest y ejecuta los siguiente comando:
 - Instalamos las librería necesarias de NodeJS: <code>npm install</code>
 - Levantamos el proyecto APIRest con NodeJS: <code>npm run start</code>
6. Ahora tenemos la APIRest preparada para ser consumida...

Endpoints
---------

- Obtener todo los usuarios: <code>[GET] http://localhost:3000/users</code>
- Insertar un nuevo usuario: <code>[POST] http://localhost:3000/users</code>
- Obtener un usuario: <code>[GET] http://localhost:3000/users/:id</code>
- Actualizar un usuario: <code>[PATCH] http://localhost:3000/users/:id</code>
- Borrar un usuario: <code>[DELETE] http://localhost:3000/users/:id</code>

Must to have:
-------------

Se requiere un User Manager que consuma de la Api que se proporciona con las siguientes funcionalidades:
- Se debe poder borrar, listar, editar y guardar los usuarios.
- La tabla de usuarios se debe poder paginar, ordenar y filtrar.
- El formulario de usuario debe contener validaciones, campos requeridos, formatos correctos, etc.

Nice to have:
-------------

- Utilizar Angular 1 para la constucción de proyecto.
- Utilizar SaSS para el pre procesado de CSS.
- Configurar y utilizar bower para la gestión de las librerias de JS.
- Todo lo que quieres añadir demás será bienvenido.