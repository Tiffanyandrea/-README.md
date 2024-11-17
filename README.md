# -README.md
Proyecto de PSeInt Este repositorio es para practicar el uso de Git y GitHub con ejemplos de pseudocódigo en PSeInt.
//1. Mayor de cinco números: Solicita tres números y determina cuál es el mayor de ellos.
Algoritmo MayorDeTresNumeros
		Definir num1, num2, num3, mayor Como Real
		// Solicitar al usuario que ingrese tres números
		Escribir "Ingrese el primer número:"
		Leer num1
		Escribir "Ingrese el segundo número:"
		Leer num2
		Escribir "Ingrese el tercer número:"
		Leer num3
		// Si decimos que el primer número es el mayor inicialmente
		mayor = num1
		// Comparar el segundo número con el mayor actual
		Si num2 > mayor Entonces
			mayor = num2
		FinSi
		// Comparar el tercer número con el mayor actual
		Si num3 > mayor Entonces
			mayor = num3
		FinSi
		// Mostrar el resultado
		Escribir "El mayor de los tres números es:", mayor
FinAlgoritmo
//2. Edad mínima para votar: Pregunta la edad del usuario y verifica si es elegible para votar (18 años o más).
funcion votar
	Definir edad Como Entero
	// Solicitar al usuario que ingrese su edad
	Escribir "Ingrese su edad:"
	Leer edad
	// Verificar si la edad es suficiente para votar
	Si edad >= 18 Entonces
		Escribir "Usted es elegible para votar."
	Sino
		Escribir "Usted no es elegible para votar."
	FinSi
	votar
FinFuncion
