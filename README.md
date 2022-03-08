
# Laboratorio de algoritmo y estructura de datos

## Unidad 1 - Introducción al laboratorio

### Variables
1.	Mostrar el promedio de dos números ingresados por usuario.
2.	Calcular el área de un triángulo siendo la base y la altura ingresadas por el usuario (recordatorio: area_t = (base * altura) / 2 para cualquier tipo de triángulo).
3.	Realizar las cuatro operaciones básicas con dos números ingresados por el usuario.
4.	Calcular cuántos años cumple una persona este año (no importa si ya los cumplió) conociendo el año de su nacimiento.
5.	Mostrar en pantalla el % de hombres y el % de mujeres que integran un grupo. La cantidad de hombres y mujeres son valores ingresados por el usuario.
<!-- ### Estructuras de control
6.	Realizar un programa donde el usuario ingrese dos números y se muestre cuál es el mayor.
7.	Modificar el programa del ejercicio 3 para que se muestre un mensaje de error si se intenta dividir por cero (recordatorio: 0/k = 0, k/0 = indefinido para cualquier k).
8.	Realizar un programa donde el usuario ingrese una cantidad de libros en una librería en la cual todos los libros cuestan $300 pero llevando más de 5 libros cuestan $250 c/u y que retorne el monto total.
9.	Realizar un programa donde el usuario ingrese números constantemente y se vayan mostrando en pantalla multiplicados por 2. Si el usuario ingresa 0 el programa deberá finalizar.
10.	Realizar un programa donde el usuario ingresa números. Al ingresar el número 0, deberá mostrar la suma total de todos los números ingresados por pantalla.
11.	Realizar un programa donde se ingresen dos números (primero el menor, luego el mayor) y se muestren todos los números intermedios (incluyendo los extremos).
12.	Realizar un programa donde el usuario ingrese un número y que muestre por pantalla si el mismo es par o impar.

## Unidad 2 - Tipos de datos

1.	Realizar un programa donde el usuario ingrese un número y que muestre por pantalla si el mismo es par o impar utilizando el operador módulo (recordatorio: 5%2 => 1).
2.	Mismo problema que antes solo que ahora no se pueden usar ni el operador módulo ni la estructura while (pista: ¿qué pasaba cuando dividíamos un entero por otro y el resultado tenía decimales?).
3.	Realizar un programa donde el usuario ingrese un número real y se muestre por pantalla si el número está entre 0 y 10 (sin incluir los extremos).
4.	Mismo problema que antes pero ahora excluimos el intervalo [4,6]. Es decir, queremos ver si el número ingresado está entre 0 y 4 o entre 6 y 10 (pista: ¿un if puede pedir más de una condición?).
5.	Realizar un programa que le pida un carácter al usuario y muestre por pantalla su número ascii asociado.
6.	Realizar un programa que le pida una letra al usuario y muestre por pantalla si la letra es mayúscula o minúscula. Si el usuario ingresa un carácter que no sea una letra (un número o símbolo) pedir que se vuelva a ingresar (pista: ¿cuáles son los números ascii asociados a las letras mayúsculas y cuáles a las minúsculas?).

## Unidad 3 - Strings

1.	Realizar un programa donde el usuario ingrese una palabra y se muestren todas las letras de la palabra separadas por un salto de línea (una letra por renglón).
2.	Realizar un programa donde el usuario ingrese dos cadenas de texto y el programa compare la última letra de ambas cadenas y muestre si son o no iguales.
3.	Realizar un programa en donde el usuario ingrese una cadena de texto y luego una letra. Se deberá mostrar la cadena con su última letra cambiada por la ingresada.
4.	Realizar un programa que reciba una cadena de texto y devuelva el número de minúsculas y mayúsculas.
5.	Realizar un programa que muestre el reverso de una cadena de texto. Por ejemplo: el reverso de “asado” es “odasa”.
6.	Realizar un programa que haga manualmente lo que haría ‘==’ para cadenas: retornar si ambas son iguales o no en función de sus caracteres.
7.	Realizar un programa que reciba una cadena de texto y una letra minúscula y cambie a mayúsculas todas las letras de la cadena que sean iguales a ésta. Luego mostrar la cadena modificada.
8.	Dadas dos palabras de igual longitud, se deben intercalar y mostrar por pantalla. Por ejemplo: “hola” y ”casa” debería dar “hcoalsaa”.
9.	Dada una palabra, revisar si se lee igual de adelante para atrás que de atrás para adelante (palíndromo).
10.	Dadas dos palabras p1 y p2, comprobar si p1 está en p2. Ejemplo: p1 = “no” y p2 = “océano”.

## Unidad 4 - Archivos

1.	Realizar un programa en el cual el usuario ingrese por consola el nombre de un archivo a abrir, lo lea completamente e imprima su información tal cual está escrita, por pantalla. 
2.	Realizar un programa en el cual el usuario ingrese por consola el nombre de un archivo a abrir y otro string con un nombre de persona. El archivo contendrá nombres separados por comas. Se deberá indicar por pantalla cuantas veces aparece ese nombre en el archivo (pista: la función getline permitía leer hasta un carácter determinado por nosotros, ¿cual deberíamos usar en este caso?).
3.	Realizar un programa en el cual el usuario ingrese por consola el nombre de un archivo a crear/abrir. El usuario deberá ingresar números de a pares y calcular la suma de cada par: el programa deberá guardar en cada línea del archivo los dos sumandos y el resultado (todo separado por espacios).
4.	Realizar un programa en el cual el usuario ingrese por consola el nombre de un archivo a abrir y lea las sumas escritas en el formato del ejercicio anterior. Por cada línea que no sea correcta, deberá indicar por pantalla “La línea X es incorrecta. Debía sumar A + B = C y dió D”.

## Unidad 5 - Funciones

1.	Realizar una función que muestre el siguiente menú: 	
        1. Suma
        2. Resta
        3. Multiplicación
        4. División
        5. Salir
2.	Realizar una función que reciba dos valores: horas y minutos y muestre por pantalla cuánto tiempo falta para las 12:05 hs.
3.	Realizar una función que reciba como argumento dos números y retorne su suma.
4.	En el mismo programa que el ejercicio 1, realizar una función que reciba como argumento dos números y una operación matemática (+, -, *, /) y retorne el resultado de la operación.
5.	Realizar una función que muestre el menú que desarrollamos antes (utilizando la misma función), pida dos números al usuario y una opción del menú y muestre en pantalla el resultado (utilizar la función del ejercicio anterior).
### Pasaje por referencia
6.	Realizar una función que reciba una variable numérica. La función debe pedir al usuario un número y almacenarlo en la variable.
7.	Realizar una función que reciba una cadena de texto y un carácter. La función debe añadir al final de la cadena el carácter enviado.
8.	Realizar una función que reciba un número real y un operador aritmético (+, -). En el caso de recibir ‘+’ la función debe sumarle uno al número y en el caso de recibir ‘-’ debe restarle uno.

## Unidad 6 - Vectores

1.	Realizar un programa donde el usuario ingrese 10 números, luego se ingresa otro numero, el programa debe comprobar si ese número está en la lista de los 10 números anteriores.
2.	Realizar un programa donde se ingresen números hasta ingresar el 0. Estos números se almacenan en un vector y luego se deben mostrar el mayor y el menor de ellos por pantalla.
3.	Realizar una función que reciba un vector y lo muestre por pantalla de manera prolija. Es recomendable guardar esta función para problemas futuros.
4.	Realizar una función que reciba un vector de números e imprima por pantalla si está ordenado de forma ascendente. Por ejemplo: [1,1,2,3] está ordenado ascendentemente.
5.	Realizar una función que reciba dos vectores, corrobore que son del mismo tamaño y si es así, guarde la suma (posición a posición) en un nuevo vector e imprima la suma por pantalla. De lo contrario imprime que son de distinto tamaño. Por ejemplo: [1,2,3] + [4,5,6] = [5,7,9]
6.	Realizar una función que reciba un vector de tipo float e imprima su reverso. Por ejemplo: [5.3, 4.5, 3.9, 8.1] -> [8.1, 3.9, 4.5, 5.3]
7.	Realizar una función que reciba un vector ordenado de menor a mayor de números enteros y un entero y devuelva true si el número se encuentra en el vector. Por ejemplo: [1,5,7,8,13], 5 -> true, [1,5,7,8,13], 2 -> false.
8.	Realizar una función que reciba dos vectores ordenados y devuelva el vector resultante de concatenarlos de manera que esté ordenado. Por ejemplo: [1,4,7,10], [2,5,6,8] -> [1,2,4,5,6,7,8,10]. Complejidad requerida: O(n1 + n2), siendo ni la cantidad de elementos del vector i.
9.	Suponer que tenemos tres vectores ordenados y que sabemos que hay un elemento en común entre ellos. Programar una función que reciba los tres vectores y retorne un vector con los índices donde está dicho elemento. Por ejemplo: [1,3,4], [3,5,7], [1,2,3] -> [1,0,2]. Complejidad requerida: O(n1 + n2 + n3), siendo ni la cantidad de elementos del vector i.
10.	Realizar una función que reciba un vector de números enteros entre 1 y 3 y lo devuelva ordenado. Por ejemplo: [1,2,1,1,3,3] -> [1,1,1,2,3,3]. Complejidad requerida: O(n), siendo n la cantidad de elementos del vector.
11.	Realizar una funcion que reciba un entero y devuela un vector con los factores primos del mismo. Los factores primos de un número entero son los números primos divisores exactos de ese número entero. Ejemplos: los factores primos de 6 son 2 y 3. Factores primos de 7 es 7.
12.	Realizar una función que dado un vector de enteros devuelva ese mismo vector, pero sin los numeros duplicados. Por ekemplo: [1,1,2,1,1,2,3,2,3,3] -> [1,2,3]
13.	Realizar una función que reciba un vector y un entero y devuelva el vector dado rotadas las posiciones de los elementos tantas veces como haya indicado el entero del vector. Por ejemplo: [1,2,3,4,5,6] y el número 2 debería dar: [3,4,5,6,1,2]
14.	Decimos que tres números a,b y c son triangulares si se cumple que:
a.	a < b+c
b.	b < a+c
c.	c < a+b
Programar una función que reciba un vector y retorne si en el mismo existen números triangulares. Complejidad requerida: O(n2). Pista: ¿qué algoritmo vimos que tenía complejidad cuadrática?


## Unidad 7 - Estructuras

1.	Crear un struct Persona, que contenga nombre, apellido y edad. Se deberá:
  a.	Implementar una función que le pida al usuario que ingrese nombre, apellido y edad (chequeando que la edad sea una edad válida) y retorne una variable de tipo Persona.
  b.	Implementar una función que reciba por parámetro una Persona e imprima por pantalla de forma        prolija sus datos.
2.	Usando el struct Punto, se quiere implementar una función que reciba un vector de puntos y retorne si hubo al menos un par de puntos iguales o no.
3.	Se tiene una muestra de 10 especímenes animales. Cada espécimen tiene dos características importantes: si respira aire o no y cuántos ojos tiene. Se quiere diseñar esto. Para eso se deberá implementar una función que tome como parámetro un vector de 10 especímenes, les asigne los valores que les corresponden a sus atributos y luego retorne la cantidad de ojos promedio entre los especímenes que respiran.
4.	Crear el tipo de datos Alumno, que tendrá nombre, apellido, edad y espacio para guardar notas de tipo float. Implementar una función que tome un vector de alumnos y muestre el listado de manera prolija.
5.	Usando el tipo de datos Alumno, implementar una función que devuelva el promedio más alto de notas de entre todos los alumnos y el nombre del alumno que lo tiene (de haber varios que lo compartan, dar el de menor apellido).
6.	Usando el tipo de datos Alumno, implementar una función que reciba por parámetro una edad e imprima por pantalla la nota más alta que tenga algún alumno con dicha edad. De no haber ningún alumno con dicha edad o no haber notas, indicarlo por pantalla.
7.	Vamos a crear un diccionario Español-Inglés. Una de las muchas formas de representar un diccionario de forma muy básica es creando una matriz de 2xN. De esta forma, habrá tantas palabras como N y se puede tomar como convención que la primera fila sean las palabras españolas y la segunda sus traducciones inglesas. Crear un diccionario de máximo 1000 palabras (que tenga una variable tamaño que vaya indicando cómo se llena).Una vez hecho esto, implementar las siguientes funciones:
  a.	void definir(Diccionario miDiccionario, string palabraEsp, string palabraIng) que toma el diccionario y define una nueva entrada.
  b.	bool existe(Diccionario miDiccionario, string palabra, int modo) que indica si la palabra existe dependiendo del modo (si modo vale 1 indica que es española, si vale 2 será inglesa).
  c.	bool traducir(Diccionario miDiccionario, string palabra, int modo) que imprime por pantalla la traducción de la palabra dependiendo del modo que se ingrese. Además, se indicará con un booleano si es que la traducción se realizó satisfactoriamente o no.

## Unidad 8 - Matrices

1.	Realizar una función que reciba por parámetro una matriz de 3x3 e imprima por pantalla la suma de todos sus elementos.
2.	Realizar una función que tome por parámetro una matriz de enteros de 3x3 e imprima por pantalla el elemento más chico, el más grande y las posiciones de ambos.
3.	Realizar una función que tome por parámetro una matriz de enteros de 3x3 y un número N e imprima por pantalla si el número se encontró en la matriz o no.
4.	Se quiere jugar al famoso Telekino. Para esto, realizaremos una función que por dentro tiene una matriz ya precargada, de la pinta
                                          [01][03][04][07]
                                          [08][11][15][16]
                                          [18][20][21][22]
                                          [26][30][31][35]
Ese es el resultado del sorteo de ayer. Ahora la función debe pedir al usuario que ingrese los 16 números que tiene en su cartón. Si le pegó a todos, imprimir que ganó el primer lugar, si le pegó a 15 que ganó el segundo lugar, 14 el tercero y 13 o menos no ganó nada.
En todo momento debe pedir valores menores a 40, de lo contrario se debe volver a pedir ingresar ese número erróneo.
5.	Realizar una función que tome por parámetro dos matrices de 3x3, A y B e intercambie el valor mínimo de A por el valor máximo de B y viceversa. Luego debe imprimir ambas matrices.
6.	Realizar una función que tome por parámetro una matriz de 3x3, invierta su diagonal principal y la muestre por pantalla. La diagonal principal en una matriz de 3x3 es:
                                              [1][2][4]
                                              [1][5][3]
                                              [4][2][7]
7.	Realizar una función que tome por parámetro dos matrices de 3x3 e imprima por pantalla todos sus elementos en común.
8.	Realizar una función que tome por parámetro un vector de 5 posiciones, una matriz de 5 columnas y un entero que indique la cantidad de filas de la matriz. Se debe buscar si existe una fila en la matriz que sea exactamente el vector e imprimir la respuesta.
9.	Realizar una función similar a la anterior, aunque esta vez la matriz será de 4x4, el vector de 4 posiciones y se debe imprimir si el vector es exactamente igual a alguna columna de la matriz o no.
10.	Realizar una función que tome por parámetro una matriz de 4x4, sume sus filas como si fueran vectores (recordar que en matemática, si sumamos los vectores (a,b,c)+(d,e,f) nos da (a+d,b+e,c+f)). Debe almacenar la suma en un vector e imprimirlo
 -->
