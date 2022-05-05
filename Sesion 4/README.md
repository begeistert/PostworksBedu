<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/Cognizant_logo_2022.svg" alt="Logo">
  </a>

<h3 align="center">Java Testing V2</h3>
<h4 align="center">Sesion 4 - Mockito Tool</h4>

## Integrantes

- Roberto Bertrand Lizárraga
- Iván Montiel Cardona
- Mungarro Echeverría Héctor
- Salmerón González Victor

## Desarollo

Durante nuestro work, desarrollamos algunas funcionalidades en la clase `SomeBusinessLogic` y comenzamos a familiarizarnos con el uso de `Mockito`. Ahora en este post work continuaremos con el desarrollo de esta clase y exploraremos algunas funcionalidades de Mockito realizando el siguiente ejercicio:

- Añade la funcionalidad de restar en la clase `SomeBusinessLogic`.
- El método debe utilizar `SomeDataService`.
- Debemos probar al menos 3 casos: con un arreglo de múltiples números, con un arreglo vacío y con un arreglo de un solo número.
- Implementa los mocks con múltiples valores de retorno.
- Explora las posibilidades de utilizar mocks que regresan valores específicos de acuerdo a los parámetros que reciben.

### Instrucciones

- En el archivo `SomeBusinessLogic.java` añade una función llamada `calculateSubstractionWithADataService`
- Para su implementación basate en lo realizado con `calculateSumWithADataService`
- En el archivo `SomeBusinessLogicMockTest.java` crea tres metodos con los siguientes nombres: `calculateSubstractionUsingDataService_basic`, `calculateSubstractionUsingDataService_empty` y `calculateSubstracionUsingDataService_oneValue`
- Implementa los mocks con múltiples valores de retorno

### Resultados

### Reflexiones Finales

Una vez que hayas terminado la actividad responde las siguientes preguntas:

- ¿Cómo decidiste inyectar el mock?
- ¿Implementaste un solo método de prueba con múltiples valores de retorno o implementaste múltiples pruebas? ¿Por qué?
- ¿Crees que existe diferencia entre los mocks que inyectamos manualmente y los inyectados con mockito? ¿Cuáles?

## Licencia

Distribuido bajo la licencia MIT. Consulte `LICENCE` para obtener más información.

##### Equipo 2
