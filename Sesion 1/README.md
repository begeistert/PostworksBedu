<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/Cognizant_logo_2022.svg" alt="Logo">
  </a>

<h3 align="center">Java Testing V2</h3>
<h4 align="center">Sesion 1 - Introduction to Java Testing</h4>

## Integrantes

* Roberto Bertrand Lizárraga
* Iván Montiel Cardona
* Mungarro Echeverría Héctor
* Salmerón González Victor

## Desarollo
Durante el work, desarrollamos las primeras funcionalidades de nuestro software de entrevistas y nos comenzamos a familiarizar con el uso de `JUnit`. Ahora en este postwork continuaremos con el desarrollo del software de entrevistas y exploraremos algunas funcionalidades de JUnit realizando el siguiente ejercicio.

El project manager ha definido como objetivo para este sprint añadir las siguientes características a nuestro sistema actual:

* La información de los entrevistadores se puede modificar desde terminal.
* La definición de hecho (Definition of Done) establece que todo el código generado debe contar con pruebas unitarias.

### Instrucciones

* Añade la opción número 3 al menú, con el texto: "3. Modificar un entrevistador".
* Dentro de nuestro switch generar el case con valor 3 y llamar a la función `modifyInterviewer` que crearemos a continuación.
* Crear la función `modifyInterviewer` solicitar el email del entrevistador y en caso de no encontrarlo imprimir el mensaje: "Entrevistador no encontrado".
* Solo se debe continuar en este flujo si el entrevistador fue encontrado.
* Solicitar a continuación el nuevo nombre, apellido y email, mencionando que se debe apretar Enter para mantener el valor actual. Preguntar si el entrevistador se encuentra activo.
* Guardar los datos del entrevistador llamando a la función `save` de nuestro objeto `interviewer`.
* Añadir las pruebas unitarias correspondientes para validar el correcto funcionamiento de la funcionalidad de editar entrevistadores.
Indicaciones generales

### Resultados

### Reflexiones Finales

* ¿Cómo estás creando la prueba para validar que se guardan correctamente los archivos?
* ¿Decidiste probar directamente en los métodos de la clase interviewer o estás probando en el menú?
* ¿Crees que existe diferencia entre las pruebas hechas directamente a la clase interviewer y las realizadas al menú? ¿Por qué?

## Licencia
Distribuido bajo la licencia MIT. Consulte `LICENCE` para obtener más información.

##### Equipo 2