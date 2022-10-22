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
