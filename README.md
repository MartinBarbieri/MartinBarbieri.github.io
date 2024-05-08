# Laboratorio de programación orientada a objetos


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
   - diasMes(int mes): Devolverá el número de días del mes que se le indique.
   - corta(): mostrará la fecha en formato corto (02-10-2022)
   - larga(): mostrará la fecha en formato largo (viernes 10 de marzo de 2023)
   - siguiente(): pasará al día siguiente.
   - anterior(): pasará al día anterior.
   - igualQue(Fecha fecha): indica si la fecha es igual a la que recibe por parámetro.
   - menorQue(Fecha fecha): indica si la fecha es anterior a la que recibe por parámetro.
   - mayorQue(Fecha fecha): indica si la fecha es posterior a la que recibe por parámetro.

6.	Crea una clase llamada "Libro" que tenga como atributos el título, el autor (usá la clase Persona), el ISBN, cantidad de páginas, editorial y fecha de publicación(usá la clase Fecha). La clase debe tener métodos para mostrar la información del libro y para comprobar si el libro es anterior a otro libro dado. Incluir 3 constructores distintos a elección, los getters y setters.

7. Vamos a modelar una Cafetera teniendo en cuenta que tiene una cantidad máxima(la cantidad máxima de café que puede contener la cafetera) y una cantidad actual(la cantidad actual que hay en la cafetera). Implementá los siguientes métodos:
    - Constructor por defecto: Establece la cantidad máxima en 1000 (c.c) y la actual en cero(cafeter vacía)
    - Constructor con la cantidad máxima de la cafetera. Inicializa la cantidad actual de café igual a la capacidad máxima.
    - Constructor con la cantidad máxima y la actual. Si la cantidad actual es mayor que la cantidad máxima que la cafeteraa le ajustará el máximo.
    - llenarCafetera(): Hace que la cantidad actual sea igual a la maxima.
    - servirTaza(int capacidad): Método que recibe la capacidad de la taza a la que se le va a servir café y llena la taza. Si la cantidad actual de café no alcanza para lenar la taza, se sirve lo que queda.
    - vaciarCafetera(): pone la cantidad de café actual en cero.
    - agregarCafe (int cantidad): añade a la cafetera la cantidad de café indicada.

8. Hacer una clase Cancion con los siguientes atributos: titulo y autor. Hacer un constructor parametrizado, un constructor por defecto que inicialice el titulo y el autor a cadenas vacias y los getters y setters de todos los atributos.

 

## Unidad 2 - Clase ArrayLists y for each

1.	Crear un ArrayList de números enteros y mostrar su suma.

2.	Crear un ArrayList de cadenas y mostrar solo los elementos que empiezan con una letra específica.

3.	Crear un ArrayList de objetos "Persona" y mostrar solo las personas que tienen más de 30 años.

4.	Crear una clase CD que esté compuesta de muchas canciones e implemente los siguientes métodos:
	-	Constructor por defecto.
	- 	Getters y setters.
	- 	numeroCanciones(): devuelve la cantidad de canciones en el CD.
	- 	verCancion(int posicion): Devuelve la canción que se encuentra en la posición que recibe por parámetro 
	- 	grabaCancion(int posición, Cancion nuevaCancion): Cambia la canción que está en esa poscion por la nueva canción que recibe por parámetro.
	- 	agrega(Cancion cancion): agrega al final del Array la canción que recibe po parámetro.
	- 	elimina(int posición): elimina la Cancion que se encuentra en la posición indicada.
        
5.	Crear una clase que represente a un alumno de una escuela. Los atributos que debe tener el alumno son:
	-	Nombre.
        -	Apellido.
        -	Fecha de nacimiento.
        -	Lista de notas.

	Se deben crear los métodos:
	-	Get de todos los atributos.
        -	Set de todos los atributos.
        -	Agregar Nota
        -	Menor Nota
        -	Mayor Nota
	

6.	Tomar el ejercicio anterior (pudiéndole hacer las modificaciones que crean necesarias) e incorporar un atributo a la clase alumno llamado materias (lista de Materia). Tener en cuenta que Materia es una nueva clase que deberá tener los siguientes atributos:
	-	Nombre
	-	Lista de notas.

	Analizar cómo y dónde crear los métodos:

	-	Agregar Materia
	-	Promedio notas  de materia
	-	Promedio notas del alumno

7. Realizar un sistema que controle campeonatos de curling. Los equipos se deben anotar en el campeonato indicando sus jugadores y disponibilidad horaria del equipo dividida en turnos: mañana, tarde y noche de lunes a sábados. Los mismos tendrán un nombre, un barrio de procedencia, 10 jugadores y uno de ellos debe ser el capitán del equipo.
De los jugadores se debe saber el nombre, fecha de nacimiento y el número de camiseta. Los números de camiseta no se pueden repetir dentro de un mismo equipo.
El torneo es todos contra todos y el sistema debe definir los horarios de los partidos dependiendo de la disponibilidad horaria de los equipos. Se debe armar un fixture completo una vez que todos los equipos estén anotados. El fixture del torneo consta de partidos los cuales tienen un día, horario y equipos que jugarán.



## Unidad 3 - Herencia

1.	Realizar un sistema que maneje la flota de vehículos de una empresa. De todos los vehículos (autos, camionetas y bicicletas) se debe conocer su marca, modelo, color, cantidad de ruedas y año de fabricación.
	Para los autos y las camionetas hay que guardar la patente. En el caso del último mencionado, se debe conocer la capacidad de carga de la misma en kg y, para los autos, además hay que diferenciar si son descapotables o no.
	Cada empresa posee una lista de camionetas y una lista de autos. La empresa querrá saber de qué vehículos tiene más cantidad, debe poder añadirle carga a una camioneta (siempre y cuando no supere su capacidad) y le importa conocer el porcentaje de autos descapotables de su empresa.

	Aclaración: Si tienen que hacer modificaciones en clases que ya han creado, háganlas.

2.	Realizar un sistema para las bufes de pedidos de almuerzos. Los pedidos se pueden realizar por alumnos o profesores. 

	Para los alumnos los datos a incluir son: Nombre, Apellido y División. Para los profesores Nombre, Apellido y Porcentaje de Descuento.
	
	Existen diferentes platos que se pueden solicitar, para ellos los datos a incluir son: Nombre y Precio. Al cargarse un pedido se incluye la fecha de creación, el plato, la persona que lo pidió, hora de entrega y si ya se entregó o no.
	
	Debe existir un menú donde se puedan agregar, modificar y eliminar platos y pedidos y se debe poder extraer un listado de los platos a cocinar en el día con su precio considerando el descuento aplicado.

3.	Crear las clases con sus atributos y métodos necesarios para un sitio web de compra de computadoras personalizadas que quiere automatizar ciertos procesos de la empresa.

	Uno entra a la página y puede ir eligiendo distintos componentes para armarse su propia computadora (una CPU y varios periféricos).
	
	La mínima compra tiene que darse con una CPU, un dispositivo de entrada y otro de salida. Para crear la compra habrá que asegurarse que tenga esos componentes mínimos y se puede modificar la configuración en cualquier momento añadiendo, quitando o cambiando exclusivamente periféricos.  
	
	Al efectuarse una compra se quiere guardar el nombre, apellido y un celular del cliente así como también el método de pago. Si es en efectivo no hace falta pedir nada más y si es con tarjeta habrá que hacerle un recargo al precio final del 5% y guardar también el número de tarjeta, de qué banco es y si es crédito o débito.
	
	Todos los componentes que se le pueden agregar al ordenador tienen  información sobre el nombre del fabricante, el modelo, el precio de venta que va variando acorde a la inflación del país y el stock.
	
	Los dispositivos de entrada que hay actualmente son el teclado y el mouse de los cuales necesitamos saber el tipo de conector que utiliza y los puertos válidos. Por otro lado, los dispositivos de salida que hay actualmente son las pantallas y las impresoras de los cuales nos interesa saber únicamente los puertos válidos y, en el caso de las impresoras, qué método de impresión usa  (Inyección o láser). 

	Es importante aclarar que el sistema debe estar preparado para que se puedan ir agregando más periféricos

	El programa deberá:

		- Realizar una compra, es decir, agregar una computadora a la lista de computadoras vendidas y hacer las modificaciones necesarias en cuanto a stock.

		- Calcular el precio total de la computadora con todos los periféricos. 

		- Mostrar la cantidad de componentes de entrada y de salida que tiene una computadora en específico.

4.	Un edificio tiene un sistema de alarmas que incluye detectores de humo, sensores de temperatura y sensores de presión. Todos estos elementos tienen un estado: conectado/desconectado y son capaces de proporcionar una medida (un valor real) en el momento que son consultados y tienen un valor umbral que se fija inicialmente al crear el elemento. Además, de cualquier dispositivo importa saber el año en que se adquirió ya que de esa forma se sabrá cuando corresponde cambiarlo.

	El sistema recorre en un bucle continuo todos sus elementos conectados. Cuando la medida de uno de ellos supera su valor umbral el sistema dispara la alarma. En el caso del detector de humo la alarma consiste en hacer un print que indique que llama a los bomberos, el sensor de temperatura deberá imprimir: “¡Cuidado! La temperatura sube”  y el sensor de presión: “Sensor de presión activado”.

	Para evitar falsas alarmas, varios elementos se pueden unir formando grupos de sensores y para este sensor complejo que se forma la alama sólo se dispara si el valor medio de los elementos del grupo supera el umbral definido para ese elemento compuesto. 

	Implementar todo lo relacionado con el disparo de la alarma, de los sensores por separado así como también para el sensor complejo.
	
5.	Realizar un sistema que controle las llamadas telefónicas de una empresa.
        
	Cada empleado de la empresa tiene un nombre, apellido, DNI, país y número de teléfono. Los empleados pueden realizar llamadas entre ellos. Para realizarlas deben introducir el número de teléfono al cual quieren llamar. Una vez finalizada la llamada el usuario debe introducir la duración de la misma.
        
	El sistema debe conservar un registro de todas las llamadas realizadas indicando: empleado origen, empleado destino, fecha de la llamada, duración de la llamada. Luego, el sistema debe ser capaz de entregar un listado de llamadas realizadas por cada empleado y el ranking de empleados que más tiempo llamaron al exterior.


## Unidad 4 - Enums

1. 	Hacer que las únicas editoriales de los libros que se crean puedan ser: Kapelusz, Sudamericana, Atlántida, el Ateneo, Interzona, Sur, Alianza.
2. 	Realizar las modificaciones necesarias en el ejercicio 7 de la unidad 2 para que los únicos turnos posibles sean: Mañana, tarde o noche y los días vayan de lunes a domingo.
3. 	Crear una clase enumerable donde se describan los colores junto a su código hexadecimal e implementarlo en las clases en las que pidan colores.
4. 	¿En otros enunciado de los que ya hicimos podes modificar los valores para crear clases enumerables? Hacelo en todos los que puedas
5. 	En una tienda de electrónica venden distintos tipos de productos. Si bien todos tienen un nombre, precio y un stock, según en qué sección se encuentran son los datos que interesa almacenar.
	Los equipos de sonido, que pertenecen a la sección Multimedia, tienen un atributo para indicar si tienen el modulo Bluetooth integrado o no. Además, en la misma sección encontramos televisores de los cuales interesa saber, además del nombre, precio y stock, qué tecnología utilizan (ultraHd – 4K - FullHd) y la resolución en pixeles.
	Por otro lado, los cargadores portátiles que son de la sección cargadores, almacenarán también la cantidad de cargas que pueden hacer sin necesidad de recargarlos.
	La tienda administra todos estos productos por lo que deberán crear los métodos necesarios que permitan agregar nuevos productos, modificarlos y eliminarlos. Además, la tienda quiere conocer cuál es su producto con mayor stock y cual el de menor.


## Unidad 5 - HashMaps y HashSets

1. 	Realizar un sistema que controle la asistencia de un empleado a su trabajo. El empleado debe tener un nombre, apellido, teléfono, fecha de nacimiento y qué días de lunes a viernes debe asistir. 
	
	Cada empleado tiene una lista de asistencias, esto quiere decir que cuando el empleado ingresa a la empresa, se registra y dicho registro ingresa a una lista conteniendo la fecha y hora de ingreso. (implementar tipo de dato DateTime) 
 	
	El empleado debe tener una forma de comprobar el porcentaje de asistencia en un mes en particular. 
	
	Los empleados deben pertenecer a una empresa y se debe tener la posibilidad de extraer la cantidad de empleados que superan el 80% de asistencia en un mes dado. 


2.	Realizar un sistema que controle la altura y peso de una persona a través del tiempo. La persona debe tener un nombre, apellido y fecha de nacimiento. 

	Cada persona cuando se pesa y mide debe registrar su peso y altura justo con la fecha.La persona debe tener una forma de conocer su peso y altura en una fecha en particular. 

	Se debe poder conocer además: 
		- El promedio de peso y de altura en un año. 
		- El porcentaje de crecimiento de un año a otro (indicando un periodo en años) 

3.	Realizar un sistema que controle las calorías consumidas por una persona. Existirán platos los cuales tendrán nombre y cantidad de calorías que poseen.  De las personas se desea conocer el nombre y fecha de nacimiento. Las personas se almacenarán en una entidad denominada familia, es decir, una familia va a tener muchas personas. 

	Cada vez que la persona come un plato se debe guardar ese dato para luego saber: 
	
		-  Cantidad de calorías consumidas en total por la persona. 
    		-  Promedio de calorías por familia. 
    		-  Persona que consumió más calorías en la familia. 
    		-  Persona que consumió menos calorías en la familia. 
    		
4.	Realizar un sistema que controle las llamadas telefónicas de una empresa. 

	Cada empleado de la empresa tiene un nombre, apellido, DNI, país y número de teléfono. Los empleados pueden realizar llamadas entre ellos. Para realizarlas deben introducir el número de teléfono al cual quieren llamar. Una vez finalizada la llamada el usuario debe introducir la duración de la misma. 

	El sistema debe conservar un registro de todas las llamadas realizadas indicando: empleado origen, empleado destino, fecha de la llamada, duración de la llamada. 

	Luego, el sistema debe ser capaz de entregar un listado de llamadas realizadas por cada empleado y el ranking de empleados que más tiempo llamaron al exterior. 

5.	Realizar un ABM de lugares. Los mismos pueden ser:Barrio, Ciudad, Provincia o Estado, País,Continente 

	Todos los tipos de lugares tienen un nombre, código y una lista de coordenadas (latitud y longitud) que unidas representan el contorno del lugar. 

	Las reglas de composición son: 

    		- Una ciudad está compuesta por barrios 
    		- Una provincia o estado está compuesta por ciudades 
    		- Un país está compuesto por provincias o estados
   		- Un continente está compuesto por países 

	Para el caso de los barrios tendrán un atributo llamado “población”, el mismo indica la cantidad de habitantes del barrio. En los otros casos este atributo no existe pero se desea calcular la población de forma automática. 

Realizar: 

    	- ABM de lugares 

    	- Consulta de población de lugares por código de lugar 

    	- Pantalla de información con: 

    	- País con más población 

    	- País con menos población 

    	- Continente con más población 

    	- Continente con menos población 

<!--

## Unidad 6 - Modificadores

1) Hacer las modificaciones necesarias en cada una de las clases ya resueltas durante el año para que sean abstractas si es necesario o impementen métodos o atributos estáticos.

2) a) Realizar un ABM de mascotas. Los mismos pueden ser: 

    Perros 
    Gatos 
    Pajaritos
   
Todas las mascotas tienen un nombre y un dueño (el nombre de la mascota debe ser único). Cada una tiene un saludo en particular: 

    Para los perros el saludo es “guau” 
    Para los gatos el saludo es “miau” 
    Para los pajaritos el saludo es “pio” 

Los pajaritos tienen una característica adicional, pueden ser o no cantores. Si son cantores hay que especificar cuál es su canto (diferente de “pio”). 

Se debe poder realizar un alta de mascotas donde se indique el nombre, dueño y tipo. También se deben poder eliminar mascotas y modificar mascotas. 

Dentro del menú de la aplicación debe existir la opción “Saludar”, la misma solicita el nombre al usuario y el nombre de la mascota. El programa debe responder: 

    Si el usuario es el dueño de la mascota: se saluda con el saludo de la mascota (por ejemplo: guau) 
    Si el usuario no es el dueño de la mascota: se saluda con el saludo de la mascota en mayúsculas y con un signo de exclamación (por ejemplo: GUAU!) 

En el caso de los pajaritos la situación cambia, si el usuario no es el dueño no debe responder nada. 

Realizar el diagrama de clases y el código necesario en Java sin utilizar bases de datos (utilizar una lista para almacenar a las mascotas) 


b) Se agregan peces como mascotas. Los peces no tienen saludo, pero cada vez que los saluda el dueño pierden una vida, de lo contrario, si los saluda un NO dueño mueren. Para sumar vidas deben alimentarse mediante el método alimentar, cada vez que se llama a dicho método se suma una vida. 
Si el pez se queda sin vida se debe eliminar automáticamente del listado de mascotas. 
Vidas iniciales: 10 


c) Para los perros, gatos y pajaritos también existe un método alimentar. Ese método suma alegría a la mascota. Por cada punto de alegría que tenga la mascota el saludo se prolonga. Por ejemplo, para un gato que tiene 3 puntos de alegría el saludo es “miau miau miau”. 

En los casos donde la alegría es mayor a 1 al saludar se resta un punto de alegría. Por ejemplo: 
 
    Un gato tiene 3 puntos de alegria. 
    Saluda una vez con “miau miau miau” y se le resta 1 a su alegría quedando en 2. 
    Saluda nuevamente, esta vez con “miau miau” y se le resta 1 a su alegría quedando en 1. 
    Saluda nuevamente, esta vez con “miau” pero como su alegría ya estaba en 1 no se modifica. 
    
Cada tipo de mascota debe tener un método el cual devuelve qué tipo de mascota es (Perro, Gato, Pajarito o Pez) 

## Unidad 7 - Manejo de excepciones

1.	Ejecutar el siguiente fragmento de código: 

		public class Main{
			public static void Main(String[] args){
				String nombre = null;
  				System.out.println("El largo del nombre es:"+ nombre.length)
			}
		}

	Resolver la excepción de cuatro formas diferentes. Siempre al final del programa habrá que mostrar el nombre de ustedes a modo de firma: 

	    Bloque try/catch. 
	    Throw. 
	    Throws. 
	    Clase personalizada. 

3.	Dado el ejercicio de sistema de alarmas que tiene un edificio (ejercicio 4, unidad 3), habrá que permitirle al usuario que pueda elegir de cuál 	de todos los dispositivos quiere obtener más información. Para esto habrá que pedirle al usuario que ingrese un número desde el 0 hasta la cantidad 	de alarmas que estén registradas. Acorde al número que elija es el dispositivo que se mostrará. 

	Deberán tener en cuenta en la implementación si el usuario no ingresa un número entero o ingresa un número mayor a la cantidad de dispositivos que 	hay instalados en el edificio. No se deberá cortar la ejecución del programa por alguno de estos errores. 

3. 	Agregarle al sistema de compras de componentes de computadora (ejercicio 3, unidad 3) las excepciones necesarias para que el usuario sepa si no hay stock de los componentes que eligió y lanzar una excepción en caso de que al hacer la compra falte uno de los componentes principales (una CPU, un dispositivo de entrada y uno de salida).

4. 	 En la clase 'Main' crea instancias de autores, libros electrónicos, usuarios y bibliotecarios, realiza operaciones de préstamo y devolución, y maneja las excepciones adecuadamente.

	 Vamos a hacer un programa que me permita gestionar una biblioteca virtual con libros electrónicos, autores, usuarios y préstamos.

	 Los géneros de los libros pueden ser: ficción, no ficción, aventura, ciencia ficción, saga, trilogía y tres más a elección suya. Los libros van a ser escritos por un autor del cual interesa conocer el nombre, la fecha de nacimiento, el dni y su bibliografía (todos los libros que escribió).

	 De cada libro electrónico se guardará el título, el autor, el género, el nombre del archivo pdf y la cantidad de descargas disponibles que tiene (es igual para todos los libros).

	 Los usuarios de la plataforma se registran ingresando nombre, fecha de nacimiento, dni,mail, los libros prestados y el tipo de membresía que tiene. Si es bronce podrá tener hasta 5 libros prestados, Plata como mucho 15 libros y si es oro 50 préstamos activos.

	 El sistema  debe gestionar los préstamos y devoluciones de libros electrónicos. Si un usuario intenta tomar prestado un libro que ya ha alcanzado el límite, se debe lanzar una excepción personalizada (`LimiteDePrestamosAlcanzadoException`). Así como hay que lanzar la excepción (‘MembresiaException’) si el usuario ya alcanzó su cupo de libros que puede tomar prestados simultáneamente.

	 Además, hacer los métodos necesarios para poder agregar, borrar o modificar nuevos libros.

5.	Realizar un sistema que controle el consumo de bebidas de personas. Cada persona debe tener un nombre, apellido y DNI (el DNI debe ser único).
   
 	Las bebidas tienen un nombre y un coeficiente de positividad y uno de negatividad. Existen 3 clases de bebidas:

		Bebidas neutras: en estas bebidas los coeficientes se establecen manualmente.

		Bebidas azucaradas: en estas bebidas se establece un atributo llamado “cantidad de azúcar”, el coeficiente de positividad es siempre 1 y el de negatividad se calcula multiplicando 		la cantidad de azúcar por 10.

		Bebidas alcohólicas: en estas bebidas se establece un atributo llamado “cantidad de alcohol”, el coeficiente de positividad es siempre cero y el de negatividad se calcula 			multiplicando la cantidad de alcohol por 20.
 
 	Cada persona tienen una lista de bebidas que consumió, indicando bebida y cantidad. Se debe poder calcular el coeficiente de hidratación resultante de cada persona. Por ejemplo: 
 
		Agua (coef. de negatividad = 0, coef. de positividad = 20) 
		Coca (cantidad de azúcar = 5) 
		 
		Si Juan tomó 3 aguas y 2 cocas: 
		 
		Coeficiente resultante para 3 aguas = 3 x (20 - 0) = 60 
		Coeficiente resultante para 2 cocas = 2 x [1 - (5 x 10)] = -98 
		 
		Coeficiente resultante total = 60 + (-98) = -38
 
 	Adicionalmente se debe poder calcular la persona con mejor y con peor coeficiente de hidratación y un método para que el usuario elija que bebida consumir y la cantidad.

	Utilizar el manejo de excepciones para corroborar que:

			Al añadir personas al sistema todos los dni sean distintos.
			Encuentre la bebida que quiere consumir y tenga esa cantidad que solicita.
			Existen personas registradas para determinar el de mejor y peor coeficiente de hidratación.

## Unidad 8 - Interfaces polimórficas

1. Hay un grupo de amigos que hicieron un sistema para empezar a intercambiarse libros, revistas, remeras y camperas entre ellos. A medida que iban sumando posibles objetos se les hacía más complicado llevar registro de qué había sido prestado por lo que pensaron en realizar un sistema que administre las cosas prestadas. 

	Las características comunes que se almacenan tanto para las revistas como para los libros son el código, el título, y el año de publicación. Los libros tienen además que guardar la cantidad de páginas por cada capítulo y, las revistas, la fecha en la que fue publicada. 

	Las prendas de ropa están calificadas por color, material (algodón, poliéster, seda, etc.), marca y estado (si tiene alguna mancha o rotura). Si es un pantalón tendrá también las medidas de la cintura, cadera y largo y, en el caso de las remeras, se necesitan las medidas de espalda, contorno y largo del torso. 

	Todos los objetos deben tener  un método toString {} que devuelve el valor de todos los atributos en una cadena de caracteres. 

	Para prevenir posibles cambios en el programa se tiene que implementar una interfaz Prestable con los métodos prestar() y agregarElemento().  

	El método prestar deberá mostrar un mensaje de la forma: “El/La *nombreObjeto* se dará prestado” si cumple con determinados criterios según qué se de en préstamo. Los libros si la cantidad de capítulos es impar, las revistas tienen que tener una fecha de publicación anterior al trimestre actual y las prendas de ropa no tienen que tener ninguna mancha ni rotura. Si no se cumplen las condiciones establecidas para cada objeto se deberá mostrar un mensaje que diga: “El/La *nombreObjeto* no se prestará”. 

	El método agregarElemento corrobora si el objeto que recibe cumple con las condiciones descriptas anteriormente para ser prestado. De ser así, imprimirá por pantalla un mensaje que dice: “El artículo ingresado puede ingresar al circuito de préstamos” y sino “El articulo ingresado no podrá ingresar a nuestro sistema”. 

2. Un prestigioso y muy exigente centro educativo requiere una aplicación para decidir quiénes se graduarán. Se dispone de alumnos que guardan su DNI, apellido, nombre y los exámenes realizados. 

	De todos los exámenes se sabe su fecha de realización. Los exámenes escritos también tienen una duración (en minutos) y una nota numérica entre 0 y 10. Los exámenes orales cuentan con un nivel de satisfacción (insuficiente, suficiente o excelente).  

	Para considerar aprobado a un alumno, éste debe aprobar todos sus exámenes. Los exámenes escritos se aprueban con una calificación de 6 o más, siempre en un tiempo inferior a 90 minutos. Por otro lado, los exámenes orales deben ser todos, como mínimo, suficientes. 

	Basado en el enunciado descripto, realizar: 

		A. El diagrama de clases que lo modelice, con sus relaciones, atributos y métodos. 
   		B. La implementación del método cantAprobados que retorne cuántos alumnos han aprobado. 

3. En época de elecciones, tenemos un sistema que administra la organización de los partidos políticos del país. Estos se manejan haciendo campaña de 3 formas como son las palomas mensajeras, los teléfonos móviles y los trabajadores.  

	Sabemos que las palomas mensajeras son un tipo específico de ave donde, además de guardar el color, nombre y especie que es común a todas las aves,  se guardará también una variable que indique si ya aprendió el mapa para volar sola o no.  

	Por otro lado, los teléfonos móviles pertenecen al grupo de dispositivos por lo que, si bien es común para todo dispositivo el número de serie, fabricante y  modelo, el teléfono móvil deberá guardar en particular a qué compañía telefónica pertenece {Claro, Personal, Movistar o Tuenti} y el número celular.  

 	En el caso de los trabajadores habrá que conocer no sólo el nombre, apellido, dni, fecha de nacimiento sino también el número de cuil, el sueldo y la dirección de residencia. 

	Las personas, los teléfonos móviles y las palomas mensajeras para cumplir con lo que les pide su partido político envían mensajes en apoyo de los dirigentes del partido al cual militan. Cada partido tiene un nombre, un dirección donde se encuentra la oficina central,  una cantidad de afiliados y una lista de los enviadores de mensajes. 

	Se deberá hacer un método para que se pueda agregar un mensajero a dicha lista y otro titulado: hacer campaña. Este consiste en recorrer todos los mensajeros afiliados y  por cada uno enviar un mensaje que diga: “Vote por el partido para un mejor futuro”.
	Este mensaje, si es dado por una paloma mensajera deberá ser precedido por el siguiente lema: “Lanzando un papelito que dice:”. Eso sí, hay que tener en cuenta que el mensaje sólo lo puede enviar si ya aprendió a volar. Si el mensaje se transmitE por un teléfono móvil al mensaje oficial del partido le antecederá: “Conectando con la antena más cercana” siempre y cuando el teléfono esté prendido y tenga crédito disponible. Por último, si un trabajador transmite el mensaje, primero habrá que verificar si está en su horario laboral y luego deberá decir antes del mensaje común: “Yo, *nombreTrabajador* te invito a que…”

4. 	Crea un programa en Java para gestionar un equipo de fútbol argentino. De cada Jugador se almacenará el nombre, la fecha de nacimiento, la posición, provincia, historial de equipos por los que pasó y el número de camiseta.

	Los arqueros tendrán como atributos adicionales el porcentaje de atajadas y la cantidad de goles recibidos, mientras que los demás jugadores del campo tendrán como atributos adicionales el porcentaje de los goles convertidos y  cantidad de asistencias realizadas.

	Para poder fichar a un jugador se implementara una interfaz llamada Contrato con un método contratar() y otro que es renovar().

	El método contratar deberá mostrar un mensaje de la forma: “El nombreJugador (con sus respectivos datos) se contrató en el nombreClub.” si cumple con determinados criterios, sino deberá lanzar una excepción personalizada. El criterio para poder contratar a todos los jugadores es que nunca haya jugado en el Club que ofrece el contrato. Ademas, en el caso de los arqueros, el porcentaje de atajadas deberá ser mayor a 60% y  los goles recibidos menor de 10. Para el resto de jugadores el porcentaje de los goles convertidos mayor a 30%  y mas de 10 asistencias realizadas.

	El método renovar deberá mostrar un mensaje de la forma: “El nombreJugador (con sus respectivos datos) se renovó en el nombreClub.” si cumple con lo siguiente: Que el actual club donde esté jugando sea el mismo club que ofrece el contrato y que la edad del jugador no sea mayor de 35 años. En caso de que alguna no se cumpla, lanzar la excepción correspondiente dando detalle de por qué no se pudo realizar la renovación 

	Para poder actualizar los porcentajes, goles en contra y asistencias de cada jugador en el sistema, se guardarán todos los partidos que fueron jugados. De esa forma, al agregar un partido se actualizará la información de los jugadores.

5.	Crea un programa en Java para gestionar un restaurante. En este programa, se administrarán diferentes platos que se sirven en el restaurante. De cada plato se almacenarán los siguientes datos: nombre, descripción, precio y tipo (que puede ser "ENTRADA", "PLATO PRINCIPAL", "POSTRE", u otro tipo).

	Como cualquier restaurante, contará con un menú que tiene todos los platos que ofrece el establecimiento. Para garantizar la calidad de estos y su incorporación al menú, se debe seguir un criterio específico para la contratación de chefs y la inclusión de nuevos platos.

	Para poder hacer efectiva la contratación se deberá mostrar un mensaje de la forma: "El chef [nombreChef] se unió al equipo de [nombreRestaurante]." si cumple con determinados criterios: Los chefs deben tener experiencia culinaria previa y ser mayores de 18 años. Si no cumplen con estos requisitos, se debe lanzar una excepción personalizada.

	Si quiero agregar un plato se deberá mostrar un mensaje de la forma: "El plato [nombrePlato] se agregó al menú de [nombreRestaurante]." si cumple con lo siguiente: el plato no debe estar ya en el menú y el chef a cargo del plato debe estar contratado en el restaurante. Si no se cumple alguna de estas condiciones, se debe lanzar la excepción correspondiente, proporcionando detalles sobre por qué no se pudo agregar el plato.

	Desarrollar las clases con sus atributos y métodos necesarios para cumplir con todas las funcionalidades que se piden. Tener en cuenta que se pueden reutilizar clases ya creadas en otros ejercicios.
 -->
