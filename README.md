# My firts React App

Puedes ver este proyecto publicado [AQUI](https://jonato96.github.io/jonathansanchez).

## Pasos

Primero tener lista nuestra aplicación para desplegar. 

-Github Pages solo despliega páginas estáticas. 

Segundo crear un nuevo repositorio. 

-Puede ser a través de la consola o en el sitio web. 

Tercerp instalar gh-pages:

### `npm install gh-pages --save-dev`

Cuarto en el archivo package.json agregar las siguientes líneas:

### `"homepage": "https://{Github Username}.github.io/{NombreRepo}"`
### `"predeploy": "npm run build"`
### `"deploy": "gh-pages -d build"`

    Con "homepage" indicamos dónde se va a desplegar el sitio. 
    Con predeploy compilamos la aplicación. 
    Con deploy lo desplegamos en github.

LISTO, en el repositorio tendrás un nuevo branch de gh-pages
y en la configuracion podrás ver la url publicada.

Creditos: Nick Paz (YT)
