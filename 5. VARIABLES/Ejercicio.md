## EJERCICIO 1

¿Qué tipo de dato debe tener una variable para representar la calificación promedio de un
curso?

     float- numerica

¿Qué tipo de dato debe tener una variable para representar el número de personas en un
hogar?

      int-numerica

¿Qué tipo de dato debe tener una variable para contener el nombre de pila de una persona?

      string-alfanumerica

¿Qué tipo de dato debe tener una variable para registrar si está lloviendo o no?

      boolano

¿Qué tipo de dato debe tener una variable para representar la cantidad de dinero que
tienes?

     float-numerica
      
## EJERCICIO 2

Realiza un algoritmo que calcule el promedio de un alumno el cual tiene cuatro calificaciones, una por periodo, de cada materia.

     Algoritmo promedio
	
	Definir nombre Como Cadena;
	
	Definir cal1,cal2,cal3,cal4,prom Como Real;
	
	
	Escribir "Ingresa el nombre del alumno";
	Leer nombre;
	
	Escribir "Ingresa la calificación 1";
	Leer cal1;

	Escribir "Ingresa la calificación 2";
	Leer cal2;
	
	Escribir "Ingresa la calificación 3";
	Leer cal3;
	
	Escribir "Ingresa la calificación 4";
	Leer cal4;
	
	prom = (cal1+cal2+cal3+cal4) / 4;
	
	Escribir "El promedio de " , nombre , " es: " ,prom;
	
	
FinAlgoritmo






Algoritmo promedio2
	
	Definir nombre Como Cadena;
	
	Definir califs,sumas,prom,div Como Real;
	
	Escribir "Ingresa el nombre del alumno:";
	Leer nombre;
	
	Escribir "Ingresa el número de calificaciones:";
	Leer califs;
	
     div=califs;
	
	Para i<-califs Hasta 1 Con Paso -1 Hacer
		Escribir "Ingresa la calificación #",i,":";
		Leer cal;
		sumas= sumas + cal;
	Fin Para
	
	prom = sumas / div;
	
		
	Escribir "El promedio de " , nombre , " es: " ,prom;
	
	
FinAlgoritmo

      
      
## EJERCICIO 3

Realiza un algoritmo para un programa que solicite al usuario su nombre y le salude usando ese nombre

     Algoritmo saludo
	
	Definir nombre Como Cadena;
      
      Escribir "Ingresa tu nombre de usuario:";
	Leer nombre;
      
      Escribir "Hola ",nombre," te mando un saludo.";
     
     
     FinAlgoritmo

## EJERCICIO 4

Realiza un algoritmo para  un programa que solicite al usuario ingresar la cantidad de kilómetros recorridos por una motocicleta y la cantidad de litros de combustible que consumió durante ese recorrido. El consumo por kilómetro es de 20.8


      Algoritmo calculadoradegasolina
	
	Definir nombre Como Cadena;
	Definir km,consumo,ltsGasolina como REAL;
	
	consumo=20.8;
	
	Escribir "Ingresa tu nombre de usuario:";
	Leer nombre;
	
	Escribir "Hola ",nombre,", ingresa la cantidad de kilómetros recorridos:";
	Leer km;
	
	ltsGasolina= consumo/km;
	
	Escribir nombre, ", la cantidad de gasolina consuimida es de: ", ltsGasolina," lts.";
	
FinAlgoritmo



Ahora llevalos a PSINT
