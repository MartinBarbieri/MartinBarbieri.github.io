# Laboratorio de programación orientada a objetos
 
## Repaso structs 2 CSTC

1)	a.	Crear las estructuras Musico y Banda:
    - El músico tiene un nombre, un apellido y el instrumento que toca.
    - La banda tiene espacio para 4 músicos, pero podría extenderse a más personas en otro momento.

    b.	Crear la función agregarMusico que recibe por parámetro una banda. La función debe pedir los datos del músico y comprobar:
     - Que haya lugar en la banda para el músico.
     - Que en la banda no haya otro musico que toca el mismo instrumento.
    
    Si se cumplen ambas condiciones agregarlo a la banda y retornar true. Caso contrario mostrar el error por pantalla y retornar false.
    
    c. Crear la función mostrarMusicos que recibe por parámetro todas las bandas que están registradas en el sistema y muestra por cada una de ellas el nombre de la       banda y luego el nombre de todos los integrantes. 


## Unidad 0 - Introducción y repaso al laboratorio

1.	Escribe un programa Java que realice lo siguiente: declarar una variable N de tipo int, una variable A de tipo double y una variable C de tipo char y asigna a cada una un valor. A continuación muestra por pantalla:
    - El valor de cada variable.
    -	La suma de N + A
    -	La diferencia de A - N
    -	El valor numérico correspondiente al carácter que contiene la variable C.

Si por ejemplo le hemos dado a N el valor 5, a A el valor 4.56 y a C el valor ‘a’, se debe mostrar por pantalla:

    Variable N = 5
    Variable A = 4.56                                                                                                 
    Variable C = a
    5 + 4.56 = 9.559999999999999
    4.56 - 5 = -0.4400000000000004
    Valor numérico del carácter a = 97                                                                                

2.	Declara 2 variables numéricas he indica cuál es mayor de los dos. En caso de que sean iguales indicarlo también. (NumeroMayor) 

3.	Muestra los números del 1 al 100 (ambos incluidos) divisibles entre 2 y 3. (DivisibleFor/DivisibleWhile)

4.	Crea una aplicación que nos pida un día de la semana y nos diga si es un día laboral o no. Los días laborales se consideran de lunes a viernes. (DiaLaboral)

5.	Del siguiente String: “Ayer me compré muñecos de la marca ‘Colchitas’ por internet” contar cuantas vocales hay en total y mostrarlo por pantalla. (vocales)

6.  Reemplazar todas las ´e´ del ejercicio anterior por la letra que ingrese el usuario. (ReemplazoLetra).

7.  Crear una aplicación que nos permite insertar números hasta que insertemos un -1. Mostrar la cantidad de números introducidos. 

8.  Al ejercicio anterior, además de la cantidad de números introducidos se debe mostrar:
  
  -	Mayor numero introducido.
  - Menor número introducido.
  -	Suma de todos los números.
  -	Suma de los numeros positivos.
  -	Suma de los numeros negativos.
  
9.  Pedir dos palabras al usuario e indicar si son iguales o no. (PalabrasIguales)
 
## Unidad 1 - Clases y objetos

1.	Crea una clase llamada "Círculo" que tenga como atributos el radio. Hacer un constructor por defecto donde el radio sea 2 y otro parametrizdo. La clase debe tener getter y setter,  un método que calcule el área del círculo (pi * r^2) y otro método que calcule el perímetro del círculo (2 * pi * r).

2.	Crea una clase llamada "Rectángulo" que tenga como atributos la base y la altura. La clase debe tener un constructor parametrizado, getters y setters, método que calcule el área del rectángulo y otro que calcule el perímetro del rectángulo.

3.	Crea una clase llamada "Coche" que tenga como atributos la marca, el modelo y el color. Ademas de los getters y setters y un constructor parametrizado con todos sus atributos, la clase debe tener métodos para acelerar, frenar y mostrar la velocidad actual del coche.

4.	Crea una clase llamada "Persona" que tenga como atributos el nombre, la edad y la dirección. La clase debe tener un método para imprimir los datos de la persona en pantalla.

5. Crea una clase Fecha con atributos para el día, el mes y el año de la fecha. Incluye los siguientes métodos: 
   - Constructor por defecto.
   - Constructor parametrizado con dia, mes y año.
   - valida(): Comprobará si la fecha es correcta. En el caso de que el día no sea correcto, lo pondrá a 1. Si el mes no es correcto, lo pondrá a 1 y si el año no es correcto, lo pondrá a 1900. Será un método auxiliar que se llamará en el constructor parametrizado.
   -diasMes(int mes): Devolverá el número de días del mes que se le indique.
   -corta(): mostrará la fecha en formato corto (02-10-2022)
   -larga(): mostrará la fecha en formato largo (viernes 10 de marzo de 2023)
   -siguiente(): pasará al día siguiente.
   -anterior(): pasará al día anterior.
   -igualQue(Fecha fecha): indica si la fecha es igual a la que recibe por parámetro.
   -menorQue(Fecha fecha): indica si la fecha es anterior a la que recibe por parámetro.
   -mayorQue(Fecha fecha): indica si la fecha es posterior a la que recibe por parámetro.

6.	Crea una clase llamada "Libro" que tenga como atributos el título, el autor (usá la clase Persona), el ISBN, cantidad de páginas, editorial y fecha de publicación(usá la clase Fecha). La clase debe tener métodos para mostrar la información del libro y para comprobar si el libro es anterior a otro libro dado. Incluir 3 constructores distintos a elección, los getters y setters.

7. Vamos a modelar una Cafetera teniendo en cuenta que tiene una cantidad máxima(la cantidad máxima de café que puede contener la cafetera) y una cantidad actual(la cantidad actual que hay en la cafetera). Implementá los siguientes métodos:
    - Constructor por defecto: Establece la cantidad máxima en 1000 (c.c) y la actual en cero(cafeter vacía)
    - Constructor con la cantidad máxima de la cafetera. Inicializa la cantidad actual de café igual a la capacidad máxima.
    - Constructor con la cantidad máxima y la actual. Si la cantidad actual es mayor que la cantidad máxima que la cafeteraa le ajustará el máximo.
    - llenarCafetera(): Hace que la cantidaad actual sea igual a la maxima.
    - servirTaza(int capacidad): Método que recibe la capacidad de la taza a la que se le va a servir café y llena la taza. Si la cantidad actual de café no alcanza para lenar la taza, se sirve lo que queda.
    - vaciarCafetera(): pone la cantidad de café actual en cero.
    - agregarCafe (int cantidad): añade a la cafetera la cantidad de café indicada.

    

