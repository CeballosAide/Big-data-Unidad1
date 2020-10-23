//Exercise 1 Calculate the area of a circle

var pi=3.1416
var p=14.2563
var radio=(p/(2*pi))

//Exercise 2 Prime Numbers

def isPrime2(i :Int) : Boolean = {
|     if (i <= 1)
|       false
|     else if (i == 2)
|       true
|     else
|       !(2 to (i-1)).exists(x => i % x == 0)
|   }
// isPrime2: (i: Int)Boolean
(1 to 10).foreach(i => if (isPrime2(i)) println("%d is prime.".format(i)))

//Exercise 3 "tweet"

var bird = "tweet"
string conexion "Estoy escribiendo un Twwet"
println("Estoy escribiendo un %s",bird)

// Excersise 4 "Hola Luke yo soy tu padre"

var mensaje = "Hola Luke yo soy tu padre!"
mensaje.slice(5,9)

// Exercise 5 ¿Cual es la diferencia entre value y una variable scala?

//value (val) se le asigna un valor definido y no puede ser cambiado en cambio una variable (var) puede ser cambiada en cualquier moment

// Exercise 6 Tuplas

var x = (2,4,5,1,2,3,3.1416,23)

println(x._7)
