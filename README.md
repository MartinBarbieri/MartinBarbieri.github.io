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
    - llenarCafetera(): Hace que la cantidaad actual sea igual a la maxima.
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
4. 	Tener en cuenta que la tecnología de las televisores del ejercicio de repaso solo pueden ser las descriptas en el enunciado.

## Unidad 5 - HashMaps y HashSets

1. 	Realizar un sistema que controle la asistencia de un empleado a su trabajo. El empleado debe tener un nombre, apellido, teléfono, fecha de 	nacimiento y qué días de lunes a viernes debe asistir. 
	
	Cada empleado tiene una lista de asistencias, esto quiere decir que cuando el empleado ingresa a la empresa, se registra y dicho registro ingresa a una lista conteniendo la fecha y hora de ingreso. (implementar tipo de dato DateTime) 
 	
	El empleado debe tener una forma de comprobar el porcentaje de asistencia en un mes en particular. 
	
	Los empleados deben pertenecer a una empresa y se debe tener la posibilidad de extraer el porcentaje de asistencia del total en un mes de empleados de la empresa. 


2.	Realizar un sistema que controle la altura y peso de una persona a través del tiempo. La persona debe tener un nombre, apellido y fecha de nacimiento. 

	Cada persona cuando se pesa y mide debe registrar su peso y altura justo con la fecha.La persona debe tener una forma de conocer su peso y altura en una fecha en particular. 

	Se debe poder conocer además: 
		- El promedio de peso y de altura en un año. 
		- El porcentaje de crecimiento de un año a otro (indicando un periodo en años) 

3.	Realizar un sistema que controle las calorías consumidas por una persona. Existirán platos los cuales tendrán nombre y cantidad de calorías que poseen.  De las personas se desea conocer el nombre y fecha de nacimiento. Las personas se almacenarán en una entidad denominada familia, es decir, una familia va a tener muchas personas. 

	Cada vez que la persona come un plato se debe guardar ese dato para luego saber: 
		- Cantidad de calorías consumidas en total por la persona. 
    		- Promedio de calorías por familia. 
    		- Persona que consumió más calorías en la familia. 
    		- Persona que consumió menos calorías en la familia. 
    		- 
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

 

