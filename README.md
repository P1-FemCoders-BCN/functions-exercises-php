# 🎡 Ejercicios de funciones en PHP

## ES

### Introducción
- PHP tiene más de 1000 funciones propias llamadas Built-in functions, puedes mirarlas <a href='https://www.w3schools.com/php/php_ref_overview.asp'>aquí.</a>
- Además de aquellas funciones, puedes crear las tuyas propias para poder usarlas repetidamente dentro del programa, teniendo en cuenta que las funciones no se ejecutan automáticamente, para ello tendrás que llamar o ejecutar la función.
- Una función se declara empezando por la palabra <i>function</i> de la siguiente manera:

function nombreDeLaFuncion(){</br>
  código a ser ejecutado;</br>
};

- El nombre de una función debe empezar con una letra o un guión bajo y puede recibir argumentos a través de parámetros. 

### Instrucciones

1. Para instalar phpUnit: composer require --dev phpunit/phpunit
2. Para correr el test: ./vendor/bin/phpunit tests/NombreDelArchivoDelTest.php
3. Para este ejercicio no será necesario usar un servidor, por lo que no se requiere tener xampp o mamp encendido.


### Reglas

1. Empieza con el archivo Functions.php, una vez lo tengas terminado pasa al archivo Store.php y finalmente completa el ejercicio del archivo Item.php
2. Solo se debe escribir la función dentro de los archivos de la carpeta src.
3. Puedes mirar lo que hay en los archivos de la carpeta tests pero no podrás modificarlos.
4. Se deberán usar parámetros.
5. Deberás ir mirando lo que devuelve la consola cada vez que corras los tests.
6. El objetivo final es que pasen todos los tests de los 3 archivos.
---

## EN

### Introduction
- PHP has over 1000 built-in functions, you can take a look at them <a href='https://www.w3schools.com/php/php_ref_overview.asp'>here.</a>
- In addition to those functions, you can create your own to be able to use them repeatedly within the program, taking into account that the functions are not executed automatically, for this you will have to call or execute the function.
- A function is declared starting with the keyword <i>function</i> as follows:

function functionName(){</br>
  code to be executed;</br>
};

- A function name must start with a letter or an underscore and can receive arguments via parameters.


### Instructions
1. To install phpUnit: composer require --dev phpunit/phpunit
2. To run a test: ./vendor/bin/phpunit tests/TestFileName.php
3. For this exercise it will not be necessary to use a server, so it's not required to have xampp or mamp turned on.

### Rules
1. Start with the Functions.php file, once you have finished it move on to the Store.php file and finally complete the Item.php file exercise.
2. The function should only be written inside the files in the src folder.
3. You can see what's in the files in the tests folder but you shouldn't modify them.
4. Parameters must be used.
5. You should be looking at what the console returns each time you run the tests.
6. The final goal is that all the tests of the 3 files pass.
