<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/Cognizant_logo_2022.svg" alt="Logo">
  </a>

<h3 align="center">Java Testing V2</h3>
<h4 align="center">Sesion 3- JUnit & TestNG</h4>

## Integrantes

* Roberto Bertrand Lizárraga
* Iván Montiel Cardona
* Mungarro Echeverría Héctor
* Salmerón González Victor

## Desarollo
Continuaremos con el desarrollo del software de entrevistadores y exploraremos la paralelización de pruebas con JUnit realizando el siguiente ejercicio:

* Configura tu proyecto e instala las dependencias necesarias
* Paralelizar la ejecución de tus pruebas

### Instrucciones

* En tu archivo `build.grade` asegurate de tener junit en su versión 5.3 o superior
* En el mismo archivo asegurate que la configuración test luzca de la siguiente forma
```gradle
 test {
    useJUnitPlatform()
    systemProperty 'junit.jupiter.execution.parallel.enabled', 'true'
}
```
* Ejecuta las pruebas
* Cambia la configuración anterior a false y observa las diferencias en los tiempos de ejecución
### Resultados


## Licencia
Distribuido bajo la licencia MIT. Consulte `LICENCE` para obtener más información.

##### Equipo 2