# Webpack configuración

## Comandos utilizados
Arrancar el proyecto con la configuración modo desarrollo y con un puerto indicado:
### `npm start`
Construimos la build de producción:
### `npm run build`
Construimos la build de desarrollo:
### `npm run build:dev`

*Nota: Para poder comprobar la ejecución de las builds necesitamos un servidor en local, una manera muy fácil es esta:
### `http-server -o` en la carpeta de la build
(Tienes que tener instalado http-server npm de modo global en tu máquina)

## Arreglando un error con npm start y window 10
He tenido que fixear un error que ocurre con npm start en windows 10
Error: Error: spawn cmd ENOENT
[Colocar Variables de Entorno en Windows 10](https://i.stack.imgur.com/xqYmM.jpg)

## Funcionalidades Webpack
1. Módulos para dividir el código en fragmentos para escalar aplicaciones (Importación/Exportación de módulos)
2. La implemetación de módulos también permite llamar a librerias de terceros
3. Minimizar/Ofuscar código (código más optimizado y entre otras cosas también quita por ejemplo comentarios del código)
4. Construye una build con los archivos que tu le indiques (Html, Css, Js, Contenido estático)
5. Permite montar un servidor local (localhost) para un live reload
6. Se pueden cargar estilos de forma dinámica y globalmente
7. Crea Hast para las builds para que cada vez que se cree una tenga identificador (Además cada vez se crea una build se limpia la anterior)
8. Permite crear una carpeta de "assets" aparte para la build de producción
9. Puedes crear un entorno de desarrollo y un entorno de producción
10. Te permite implementar Babel para que el código tenga compatibilidad con todos los navegadores y con versiones más antigüas de JS
11. Puedes implementar Sass para que automaticamente te lo compile a Css en la build
12. Te permite utilizar TypeScript y transpilarlo a JS en la generación de la build

### Angular, React y Vue entre otros frameworks utilizan Webpack en su ecosistema!

