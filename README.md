# Bootstrap HTML Form

Formulario diseñado para la utilización y relleno de datos personales del usuario a la hora de registrarse en nuestra página web.

## Estructura del proyecto

```
bootstrap-html-form
├── src
│   ├── index.html
│   └── css
│       └── styles.css
├── README.md
```

## Que fai o fomulario?

Nos permite que cualquier usuario introducza su nombre, correo electrónico y mensaje a través de nuestra página de empresa y solicitar así nuestros productos o recursos, incluye un formato de valiación en caso de que el usuario o cliente no introduzca los datos correctos en el sistmea.

##

1. **Clonar el repositorio**:## URLs do proxecto

- **Repositorio remoto:**  
  [https://sandrac123.github.io/EXAMEN-GIT/bootstrap-html-form/src/]

- **Repositorio en GitHub:**  
  [https://github.com/sandrac123/EXAMEN-GIT.git]

- **Páxina publicada en GitHub Pages:**  
  [https://sandrac123.github.io/EXAMEN-GIT/index.html]

  ```bash
  git clone
  cd bootstrap-html-form
  ```

2. **Abrir el proyecto**:
   Abriri la carpeta `src/index.html` del archivo para ver el formulario

## Dependencies

Este proyecto usa Bootstrap para el estilo. Puedes incluir Bootstrap via CDN en el `index.html` archivo:

```html
<link
  rel="stylesheet"
  href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
/>
```

## Validación del formulario

El formulario basic HTML5 valida los siguientes atributos:

- `required`: obriga a cumplir o campo
- `type="email"`: comprueba que el correo estea bien introducido y funcione correctamente
- `maxlength`: especifica una longitud maxima para introducir el mensaje que deseamos escribir en la pagina web.

## Como usar

1. Abre o fichero 'src/index.html' nun navegador web.
2. Completa o formulario e comproba a validación automática dos campos.
3. Personaliza os estilos en 'src/css/styles.css' se o desexas.

## Estilos

cambiar la aparencia del archivo en `src/css/styles.css`.

## Deploying with GitHub Pages

To deploy your form using GitHub Pages, follow these steps:

1. Push your code to a GitHub repository.
2. Go to the repository settings.
3. Scroll down to the "GitHub Pages" section.
4. Select the branch you want to deploy (usually `main` or `master`).
5. Click "Save".

Your form will be available at `https://yourusername.github.io/bootstrap-html-form/`.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
