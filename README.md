# Taller11

* Para el taller se debe usar los conceptos de funciones y procedimientos

### Problema 01

Generar una solución que implemente 3 funciones. Que permitan calcular el área de un cuadrado, área de un triángulo y área de un rectángulo.

Cada función debe solicitar los datos necesarios y devolver el valor correspondiente. Se debe invocar a las funciones desde un método principal. Si el usuario ingresa 1 se llama a la función obtenerAreaCuadrado; 2 se llama al función obtenerAreaTriangulo; 3 se llama al función obtenerAreaCuadrado.

```
El área del cuadrado es igual a lado x lado x lado x lado
El área del triángulo es igual a (base x altura)/2
El área del rectángulo es igual a base x altura
```

En el método principal se debe presentar la información que devuelva la función respectiva; ejemplo, si el usuario ingresa la opción 2, se debe presentar un mensaje, obtenido desde la función, que exprese: "El área del triángulo de base: ? y altura ? es ?"

***
### Problema 02
Generar una función que tenga 4 parámetros de tipo decimal y devuelva el promedio cualitativo de los parámetros.

Si el promedio es:
* De 0 a 5 el promedio cualitativo es Regular
* De 5.1 a 8 el promedio es Bueno
* De 8.1 a 9 el promedio es Muy Bueno
* De 9.1 a 10 el promedio es Sobresaliente.

A la función se la debe llamar desde un método principal. Los parámetros necesarios para llamar a la función, deben ser ingresados solicitados al usuario.

En la función principal se debe imprimir los siguiente:

```
El promedio de las notas: 10, 5, 8, 7 es Bueno
```
***

### Problema 03
Generar una solución que permita presentar el siguiente reporte, como el siguiente ejemplo:

El ciudadano Luis Jara, con cédula de identidad 110412603 con año de nacimiento 1990 tiene una edad de 34 años. Su sueldo básico es de $500 y su sueldo final con el aporte de seguro es de $590.

El programa debe permitir ingresar varios datos en un ciclo repetitivo, hasta que el usuario lo requiera.

Para el aporte del seguro usar el 18% del sueldo básico.
Los datos por cada ingreso son:

* Nombres
* Apellidos
* Cédula
* Año de nacimiento
* Sueldo básico

Para los casos en los que debe calcular valores como: edad y sueldo final, usar funciones.

La idea es que se haga uso de una cadena acumuladora para presentar los valores ingresados en el ciclo repetitivo.

### Problema 04

* Generar un procedimiento para calcular el valor de la planilla de luz y otro procedimiento para calcular el valor del predio de un bien inmueble.
Cada procedimiento debe tener 2 parámetros (tipo cadena para nombre del cliente, cédula del cliente).

En el procedimiento de planilla de luz se debe pedir los siguiente datos valor del kilowatio y el número de kilowatios del mes. Y se presenta en pantalla el siguiente reporte:
Cliente Ana Contreras con cédula 1100112233 debe cancelar el valor de $10

En el procedimiento del predio se debe pedir el valor de inmueble y el para obtener el valor del predio se saca el 2% del valor del inmueble. Y se presenta el siguiente reporte:

Cliente Ana Contreras con cédula 1100112233 tiene un bien inmueble valorado en $30000 y tiene que pagar de predio $ 6000.

En el método principal se debe generar un ciclo repetitivo, donde si el usuario ingresa 1 se llama al procedimiento calcularValorLuz; 2 se  llama al procedimiento calcularPredio. El ciclo termina cuando el usuario lo decida.

Los datos que se necesita en cada procedimiento se los debe ingresar por teclado.


### Problema 05

* Generar un procedimiento, el objetivo del procedimiento es ingresar los valores de un arreglo unidimensional de tipo cadena, el número de elementos del arreglo debe ser enviado desde el método principal, previo ingreso por teclado, en el procedimiento usar otro ciclo repetitivo para presentar los valores del arreglo. Al procedimiento se lo debe invocar desde la función principal.
***

### Problema 06

* Generar una solución que implemente 3 procedimientos. Que permitan calcular el área de un cuadrado, área de un triángulo y área de un rectángulo. Cada procedimiento debe solicitar los datos necesarios y presentar o imprimir el valor correspondiente. Se debe invocar a los procedimientos desde un método principal; Si el usuario ingresa 1 se llama al procedimiento obtenerAreaCuadrado; 2 se llama al procedimiento obtenerAreaTriangulo; 3 se llama al procedimiento obtenerAreaCuadrado.
