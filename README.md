# typescriptNodeJsMysql

reconstruir las librerias de node con el comando

npm i package.json

despues de esto crear una base de datos utilizando XAMPP

con las contraseñas y los datos de conexion que se muestran a continuacion

            host     : 'localhost',
            user     : 'node_user2',
            password : '123456',
            database : 'node_db'

con esto ya se puede ejecutar el comando 

    npm run build

el cual es un comando custom que crea los archivos en la carpeta public, junto con la transpilacion de tyscript a archivos javascript
con esto ya se puede ejecuar el comando 

    nodemon dist/index

para levantar el servidor de javascript.

