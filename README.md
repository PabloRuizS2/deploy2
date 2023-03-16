# DESPLEGAR NUESTRO PROYECTO EN LA NUBE

### Consigna parte
Crear un proyecto en Heroku.com para subir el servidor que venimos realizando, reformando todo lo necesario para su correcto funcionamiento en la nube.
Subir el código a Heroku.com, sin olvidar incluir el archivo .gitignore para evitar subir los node_modules. Comprobar que el proyecto inicie de manera correcta en la nube. Verificar que en su ruta raíz se encuentre la página pública del servidor.
El servidor debe seguir funcionando en forma local.
Realizar un cambio a elección en alguna vista, probar en forma local y subir nuevamente el proyecto a Heroku, verificando que la nueva reforma esté disponible online.
Revisar a través de una consola local, los mensajes enviados por nuestro servidor en Heroku a su propia consola.

### Rutas principales

| Ruta         | Función     |
|--------------|-----------|
| / | Login |
| /signup | Crear una cuenta |
| /logout | Cerrar sesión |
| /productos | Listado de productos con chat |

### Otras rutas
| Ruta         | Función     |
|--------------|-----------|
| /info | Listado de valores usados por node.js |
| /info-json | Listado de valores usados por node.js en formato json |
| /info-json-gzip | Listado de valores usados por node.js en formato json con compress|
| /api/randoms | Devuelve un objeto de valores aleatorios de acuerdo al parámetro "cant", Ej. /api/randoms?cant=200. |

### Notas
Por default, los usuarios usan mongodb y se conecta a una base de datos llamada "ecommerce" en **mongodb://127.0.0.1:27017/ecommerce**
Para cambiar esta conexión se requiere crear un archivo .env en el root del proyecto y agregar una variable llamada **MONGO_URI**
Se puede cambiar el puerto para el servidor express agregando una variable con nombre **PORT**

Variables contempladas en el archivo .env :
- MONGO_URI=
- PORT=
