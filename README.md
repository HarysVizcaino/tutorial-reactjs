
# Tutorial ReactJS
Este tutorial está diseñado para las personsa que aprenden mientras hacen. La idea es hacer una applicación de frontend "simple", con la complejidad necesaria para agarrar y aprender a usar React en el nivel en que se está usando en el mercado actual.

Las técnicas que aprenderás en el tutorial son fundamentales para crear cualquier aplicación React, y dominarla te dará una comprensión profunda de React.

El tutorial está dividido en varias secciones:

- Setup — Configuración para el tutorial
- Overview — Visión General y fundamentos de una aplicación en React: components, props, and state.
- Analysis — Conociendo el proyecto, UX y el desarrollo en base a components.
- Development & TDD — Manos a la obra con la app. Buenas prácticas y desarrollo en base a TDD.
- Next steps — Qué sigue después de aquí. 

No es "necesario" completar todas las secciones a la vez para obtener el valor de este tutorial. Intenta llegar lo más lejos que puedas, incluso si se trata de una o dos secciones. 

Está bien copiar y pegar el código como lo está siguiendo a lo largo del tutorial, pero le recomendamos que lo escriba a mano. Esto te ayudará a desarrollar una memoria muscular y una comprensión más sólida.

## ¿Qué estamos construyendo?

**Escenario**
Eres es un desarrollador web en Compañía Marca ACME. Se te pidió que construyas un prototipo pulido de una aplicación para buscar GIFs. Dado que el back-end aún no se ha creado, se te solicitó que comiences utilizando una API disponible públicamente.

**Tarea**
Tu tarea es crear una aplicación [*SPA](https://en.wikipedia.org/wiki/Single-page_application) que aproveche los datos de la API de [Giphy](https://github.com/Giphy/GiphyAPI). Una vez que lo hagas, la aplicación estará disponible en http://localhost:8000/

**Requisitos**
Tu proyecto será revisado manualmente por mentores de acuerdo con los siguientes requisitos:
- La página nunca debe recargar.
- Proporciona un formulario para que el usuario realice una búsqueda de palabra(s) clave en la base de datos GIF a través de la API.
- Mostrar los resultados como miniaturas estáticas en la página en un diseño que tenga sentido. Un gran volumen de resultados debe cargarse con buen rendimiento pensado.
- Al hacer clic en una miniatura debe iniciarse una vista modal/ventana emergente de estilo lightbox que le permita al usuario navegar por GIF individuales como una presentación de diapositivas. Los GIFs en esta vista deben estar completamente animados.
- Crear un diseño visual pulido y UX.
- Codifique de forma limpia y legible siguiendo todas las convenciones normales que conozca.
- El objetivo es que usted cree su propia aplicación de presentación de diapositivas, no use una solución precompilada.
- Todo el desarrolle y prueba de tu trabajo será evaluado utilizando un Chrome/Chromium de escritorio.
- Si tiene alguna nota o instrucciones sobre el ejercicio, crea un issue a este repositorio.


## Prerequisitos
Conocimientos básicos de HTML y JavaScript, pero debería poder seguir adelante incluso si viene de un lenguaje de programación diferente. También asumiremos que está familiarizado con conceptos de programación como funciones, objetos, matrices y, en menor medida, clases.

Si necesitas repasar JavaScript, te recomendamos que leas esta [guía](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript). Ten en cuenta que también estamos usando algunas características de ES6, una versión reciente de JavaScript. En este tutorial, estamos usando [arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions), [classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes), [let](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) y [const](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const) statements. Puedes utilizar el [REPL de Babel](https://babeljs.io/repl/#?presets=react&code_lz=MYewdgzgLgBApgGzgWzmWBeGAeAFgRgD4AJRBEAGhgHcQAnBAEwEJsB6AwgbgChRJY_KAEMAlmDh0YWRiGABXVOgB0AczhQAokiVQAQgE8AkowAUAcjogQUcwEpeAJTjDgUACIB5ALLK6aRklTRBQ0KCohMQk6Bx4gA) para comprobar a qué compila el código ES6.

Es importante que conozcas [NPM](https://docs.npmjs.com/), pues lo estaremos utilizando durante el trayecto. Te recomendamos [esta guía](https://www.sitepoint.com/beginners-guide-node-package-manager/).
También se espera que conozcas cómo usar Git, así que aquí te dejamos algunos recursos como guía:
- https://www.atlassian.com/git/tutorials
- https://guides.github.com/

Muy bien, dicho todo esto, manos a la obra! Clona este repositorio y una vez descargado, cambia al branch `setup`, luego revisa el archivo setup.MD para el próximo contenido.

    git clone https://github.com/richardblondet/tutorial-reactjs.git
    git cd tutorial-reactjs
    git checkout setup

