Algoritmo if
	
	Definir num como entero;
	
	
	Escribir "Ingresa un número";
	Leer num;
	
	si (num>0) Entonces
		
		Escribir "Tu número es positivo";
	FinSi
	
FinAlgoritmo


![image](https://user-images.githubusercontent.com/113804556/193431064-3e64deac-8be9-4a4c-865d-cfb8d25d93ad.png)
![image](https://user-images.githubusercontent.com/113804556/193431095-67a636f8-aa32-4d79-8e3a-8843875ab168.png)







si - sino

![image](https://user-images.githubusercontent.com/113804556/193431146-97c32d58-58e4-4e58-a979-18378d311f59.png)
![image](https://user-images.githubusercontent.com/113804556/193431172-374aa1a2-7949-457a-bd77-e5f36a75a926.png)




.
.
.
.
.
.
EJEMPLO:

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
	
	
		Si(prom>=6) Entonces
			Escribir nombre," tu promedio es: ",prom," por lo tanto APROBASTE";
		SiNo
			Escribir nombre," tu promedio es: ",prom," por lo tanto REPROBASTE";
		Fin Si
	
	

	
	
	
FinAlgoritmo


![image](https://user-images.githubusercontent.com/113804556/193431390-a1465292-d602-4afc-bddb-d8f586cfe4cf.png)

Algoritmo if
	
	Definir num como entero;
	
	
	Escribir "Ingresa un número";
	Leer num;
	
	si (num==0) Entonces
		Escribir "Tu número es neutro";
		
	SiNo
		si(num>0) Entonces
			Escribir "Tu número es positivo";
		SiNo
			Escribir "Tu número es negativo";
		FinSi
			
	FinSi
		
	
FinAlgoritmo
.
.

..
![image](https://user-images.githubusercontent.com/113804556/194727855-6390a589-c07f-4ed5-9c0f-5e81040bccab.png)


.
.
.
.
.
.
.
.
 promedio if añadido
 
 
 Algoritmo promedio
	
	Definir nombre Como Cadena;
	
	Definir cal1,cal2,cal3,cal4,prom Como Real;
	
	
	Escribir "Ingresa el nombre del alumno";
	Leer nombre;
	
	Escribir "Ingresa la calificación 1";
	Leer cal1;
	Si(10>cal1 y cal1>0) Entonces
		
		Escribir "Ingresa la calificación 2";
		Leer cal2;
		Si (10>cal2 y cal2>0) Entonces
			Escribir "Ingresa la calificación 3";
			Leer cal3;
			Si (10>cal3 y cal3>0) Entonces
				Escribir "Ingresa la calificación 4";
				Leer cal4;
				Si (10>cal4 y cal4>0) Entonces
					prom = (cal1+cal2+cal3+cal4) / 4;
					Si(prom>=6) Entonces
						Escribir nombre," tu promedio es: ",prom," por lo tanto APROBASTE";
					SiNo
						Escribir nombre," tu promedio es: ",prom," por lo tanto REPROBASTE";
					Fin Si
				SiNo
					Escribir "Error!";
				Fin Si
			SiNo
				Escribir "Error!";
			Fin Si
	
		SiNo
			Escribir "Error!";
		Fin Si
		
	
	SiNo
		Escribir "Error!";
	Fin Si
	

	
FinAlgoritmo



![image](https://user-images.githubusercontent.com/113804556/193431771-629e41f1-e353-4673-bb74-f58fc3366a72.png)

.
.

.
.
.
..
...
.
.
.
.
.

![image](https://user-images.githubusercontent.com/113804556/194727842-b11f297b-2ca8-4114-81df-8cf31902e38f.png)
.
.
![image](https://user-images.githubusercontent.com/113804556/194727876-e4d09796-8322-4134-b10b-ac495237e3b4.png)

.

Algoritmo if
	
	Definir num como entero;
	
	
	Escribir "Ingresa un número";
	Leer num;
	
	si (num==0) Entonces
		Escribir "Tu número es neutro";
		
	SiNo
		si(num>0) Entonces
			Escribir "Tu número es positivo";
		SiNo
			Escribir "Tu número es negativo";
		FinSi
			
	FinSi
		
	
FinAlgoritmo

.
.

.
.
.
.
.
.
.
.
..
.
.
.
.

.
.


Algoritmo vocales
	
	Definir letra Como Caracter;
	
	
	Escribir "Ingresa una letra";
	Leer letra;
	
	
	
	si (letra== "a" o letra== "A" o letra== "e" o letra== "E" o letra== "i" o letra== "I" o letra== "o" o letra== "O" o letra== "u" o letra== "U") Entonces
		Escribir "La letra ",letra," es una vocal" ;
		
	SiNo
		Escribir letra," no es una vocal" ;
			
	FinSi
		
	
FinAlgoritmo
.

.
.
.

![image](https://user-images.githubusercontent.com/113804556/194728579-f30efcf7-4065-4d56-a10d-ee06e4e2a9e6.png)
.
.

.
.
..

..

.
Algoritmo vocales2
	
	Definir letra Como Caracter;
	
	
	Escribir "Ingresa una letra";
	Leer letra;
	
	
	
	si (letra== "a" o letra== "A" ) Entonces
		Escribir "La letra ",letra," es una vocal" ;
		
	SiNo
		si(letra== "e" o letra== "E" ) Entonces
			Escribir "La letra ",letra," es una vocal" ;
		SiNo
			si(letra== "i" o letra== "I") Entonces
				Escribir "La letra ",letra," es una vocal" ;
			SiNo
				
				si (letra== "o" o letra== "O") Entonces
					Escribir "La letra ",letra," es una vocal" ;
				SiNo
					si(letra== "u" o letra== "U")
						Escribir "La letra ",letra," es una vocal" ;
					SiNo
						Escribir letra," no es una vocal" ;
					FinSi
				FinSi
			FinSi
		FinSi
		
		
	FinSi
	
	
FinAlgoritmo



.
.
.
.

.
.
.
.
..

..

.
.
![image](https://user-images.githubusercontent.com/113804556/194728590-b871f277-5be8-4272-acfb-9d7c14306747.png)

