para poder iniciar en una estructura de desarrollo web automatica nececitamos tener instalado previamente algunos programas 
node.js
npm
gulp instalado globalmente(npm install --save-dev gulp)
iniciamos la linea de codigo npm init
y rellenamos lo que se nos pregunta
y esto nos creara el archivo pacjage.json
luego ejecutamos la linea de codigo
npm install --save-dev gulp 
para agregar las dependecias del proyecto.
esto agregara node_modules y un archivo package.log.json
siguentemente agregaremos un archivo y le pondremos el nombre de gulpfile.js 
aqui programaremos javascrypt plano.
gulp trabaja tareas asincrona
en gul declararemos las funciones 
ahora instalamos la dependenia gulp sass
con el comando npm install --save-dev gulp-sass

para poder ver los cambios que se van realizando mientras se programa importar watch en las funciones especificas de la API del gulp
luego de eso tenemos que hacer una funcion que reconosca cuando suceda un cambio en cualaquier archivo de tipo x ya se html scss
luego modifica la tarea por defecto  para que ejecute el watch
para automatizar la recarga de la pagina despues de cada actualizacion tenemos que instalar browser-sync con la linea de codigo npm install --save-dev browser-sync
browswer sin sirve para montar un servidor local y para poder actualizar el navegador al momento de tener un cambio.

