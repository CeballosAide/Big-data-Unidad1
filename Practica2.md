//Ejercicio 1 Lista

import scala.collection.mutable.ListBuffer
var lista = collection.mutable.ListBuffer("rojo","blanco","negro")

//Ejercicio 2 Añadir elementos a una lista

import scala.collection.mutable.ListBuffer
var lista = collection.mutable.ListBuffer("rojo","blanco","negro")

lista += "verde"
lista += "amarillo"
lista += "azul"
lista += "naranja"
lista += "perla"

//Ejercicio 3 Traer elementos

lista slice (3,6)

//Ejercicio 4 Arreglo

Array.range(1, 1000, 5)

//Ejercicio 5 Elementos unicos

import scala.collection.mutable.ListBuffer
var lista = collection.mutable.ListBuffer(1,3,3,4,6,7,3,7)

lista.toSet

//Ejercicio 6 Mapa Mutable
var mutmap = collection.mutable.Map(("Jose", 20), ("Luis", 24), ("Susana", 27))

//6a Lllaves
println(mutmap)

//6b agregar valor
mutmap += ("Miguel" -> 23)
