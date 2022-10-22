Algoritmo adivinarnúmero
	
	Definir numSec,num1 Como Real;
	
	numSec = azar(100);
			
	Hacer
		Escribir "Escribe un número:";
		Leer num1;
		
		si num1<numSec Entonces
			escribir "Tu número es menor";
		SiNo
			si num1>numSec Entonces
				Escribir "Tu número es mayor";
			FinSi
		FinSi
	Hasta Que num1 == numSec
	
	Escribir "CORRECTO: el número secreto es: ",numSec;
	
	
FinAlgoritmo
 .
 .
 
 .
 .
 .
 .
 .![image](https://user-images.githubusercontent.com/113804556/197362537-6170b8c7-45e0-49c1-a376-091c839948c3.png)
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

.
.
Algoritmo adivinarnúmero2
	
	Definir numSec,num1,intentos Como Real;
	
	intentos = 5;
	numSec = azar(100);
	Escribir numSec;
	
	
	
	
	
	
	

	Mientras num1 <> numSec y intentos>0 Hacer
		
		Escribir "Vidas = ",intentos;
		Escribir "Escribe un número:";
		Leer num1;
		
		Mientras  num1 > 100  o  num1 < 0 Hacer
			
			Escribir "El número debe estar en el rango de 0-";
			Escribir "Escribe un número:";
			Leer num1;
		FinMientras
		
		
		
		si num1<numSec Entonces
			escribir "Tu número es menor";
		SiNo
			si num1>numSec Entonces
				Escribir "Tu número es mayor";
			FinSi
		FinSi
		
		intentos = intentos - 1;
	FinMientras
	
	
	si intentos == 0 Entonces
		Escribir " ";
		Escribir "Sin vidas.";
		Escribir "-Juego terminado-";
		
	SiNo
		Escribir "CORRECTO: el número secreto es: ",numSec;
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
 
 ..
 .
 ![image](https://user-images.githubusercontent.com/113804556/197363955-d89370e7-873e-4103-9417-8fa27745ef34.png)
