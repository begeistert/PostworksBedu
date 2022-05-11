<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/Cognizant_logo_2022.svg" alt="Logo">
  </a>

<h3 align="center">Java Testing V2</h3>
<h4 align="center">Sesion 4 - Mockito Tool</h4>

## Integrantes

* Roberto Bertrand Lizárraga
* Iván Montiel Cardona
* Mungarro Echeverría Héctor
* Salmerón González Victor

## Desarollo

Durante nuestro work, desarrollamos algunas funcionalidades en la clase `SomeBusinessLogic` y comenzamos a familiarizarnos con el uso de `Mockito`. Ahora en este post work continuaremos con el desarrollo de esta clase y exploraremos algunas funcionalidades de Mockito realizando el siguiente ejercicio:

* Añade la funcionalidad de restar en la clase `SomeBusinessLogic`.
* El método debe utilizar `SomeDataService`.
* Debemos probar al menos 3 casos: con un arreglo de múltiples números, con un arreglo vacío y con un arreglo de un solo número.
* Implementa los mocks con múltiples valores de retorno.
* Explora las posibilidades de utilizar mocks que regresan valores específicos de acuerdo a los parámetros que reciben.

### Instrucciones

* En el archivo `SomeBusinessLogic.java` añade una función llamada `calculateSubstractionWithADataService`
* Para su implementación basate en lo realizado con `calculateSumWithADataService`
* En el archivo `SomeBusinessLogicMockTest.java` crea tres metodos con los siguientes nombres: `calculateSubstractionUsingDataService_basic`, `calculateSubstractionUsingDataService_empty` y `calculateSubstracionUsingDataService_oneValue`
* Implementa los mocks con múltiples valores de retorno

### Resultados

A continuacion video de evidencias: [Video](https://github.com/begeistert/PostworksBedu/raw/master/Sesion%205/Evidencias_postwork_modulo04_Sesion_05.mp4)

Códgio fuente: [Descarga](https://github.com/begeistert/PostworksBedu/raw/master/Sesion%205/postwork_sesion05.zip)

### Reflexiones Finales

Una vez que hayas terminado la actividad responde las siguientes preguntas:

* ¿Cómo decidiste inyectar el mock?
  Por inyeccion de dependencias.
* ¿Implementaste un solo método de prueba con múltiples valores de retorno o implementaste múltiples pruebas? ¿Por qué?
  Ambas, primero se hicieron casos de prueba con un arreglo de multiples numeros, con un arreglo de un solo numero y un arreglo vacío y después se implementó
una prueba con multiples valores de retorno.
* ¿Crees que existe diferencia entre los mocks que inyectamos manualmente y los inyectados con mockito? ¿Cuáles?
  Si, porque las inyecciones con mockito son más simples pues las instancias son creadas previamente por el Framework.

## Licencia
Distribuido bajo la licencia MIT. Consulte `LICENCE` para obtener más información.

##### Equipo 2