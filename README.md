# Prueba técnica — React developer
![Grupo Aspasia](https://grupoaspasia.com/wp-content/uploads/2022/02/Logo350x70-2.png)
## Evalución Práctica - Desarrollo de una aplicación de lectura de libros

El objetivo de esta evaluación práctica es que utilices tus habilidades de desarrollo en React y JavaScript/TypeScript para construir una aplicación web que permita a los usuarios buscar, filtrar y explorar una lista de libros.

Nuestro foco es el obtener un **código simple, bien diseñado y organizado, eficaz y testeado**, así como también el cumplimiento de los requerimientos solicitados.

### Requisitos:
- Deberás consumir la [API publica An API of Ice And Fire](https://anapioficeandfire.com) para consumir datos.
- La aplicación debe estar escrita en React con JavaScript. **Si utilizas TypeScript en modo estricto obtienes puntos extra**.
- Para crear el proyecto, puedes utilizar herramientas como `vite`, `create-react-app` o similares.
- La navegación de la aplicación debe ser manejada con **react-router-dom**.
- Puedes utilizar componentes **Headless UI** para la interacción del usuario.
- Si los estilos de la aplicación son implementados con **Tailwind ganas puntos extra**.
- Utiliza **React-Table** para mostrar los datos y permitir al usuario ordenarlos, buscarlos y filtrarlos.
- Puedes utilizar **Formik** para la validación y manejo de formularios en la aplicación.
- **Jest** debe ser utilizado para escribir pruebas unitarias.
- Utiliza **Storybook** debe ser utilizado para documentar y testear cada uno de los componentes de la aplicación, y **ganas puntos extra**.
- Utilización de **React Context** o **Redux** para el manejo del estado de la aplicación.
- Puedes utilizar alguna librería adicional que consideres apropiada, pero justifícala. **Si nos parece bien justificada, podrías ganar puntos extra**.
- También necesitaras manejar los estados de carga/loading y error de obtener los datos desde el archivo JSON.

### Requisitos funcionales:
- La aplicación debe ser capaz de buscar y filtrar libros por título y autor.
- La aplicación debe utilizar React-Table para mostrar la lista de libros y permitir al usuario ordenar, filtrar y buscar dentro de ella.
- La aplicación deberá contar con un formulario para añadir nuevos libros. Este formulario deberá tener al menos los campos de título, autor, género y fecha de publicación. *Como la API que utilizas no implementa esta funcionalidad, solo debes maquetear el formulario.*
- La aplicación debe contar con vistas "detalles" para cada libro que muestren información adicional como la sinopsis y la calificación de los usuarios.
- La aplicación deberá contar con una vista de "favoritos" para que el usuario pueda guardar los libros que desea recordar o leer en el futuro.

### Entrega:
- La entrega deberá ser un repositorio de GitHub con un README que explique cómo ejecutar la aplicación y las pruebas. Además, agrega la siguiente información a su archivo `README`:
    - ¿Cómo decidiste las opciones técnicas y arquitectónicas utilizadas como parte de su solución?
    - ¿Hay alguna mejora que dejaste pendiente de hacer en su envío?
    - ¿Qué harías de manera diferente si se le asignara más tiempo?
- El proyecto deberá incluir un archivo `.storybook` con la documentación de cada uno de los componentes.
- La evaluación considerará el periodo de una semana desde el envío del repositorio.
- Envía la url de tu repo a brian.guzman@grupoaspasia.com para su evaluación.

Esperamos que esta evaluación práctica te permita demostrar tus habilidades y conocimientos ¡Buena suerte!