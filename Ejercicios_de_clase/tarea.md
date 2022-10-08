Algoritmo ordenar
	
	Definir num1,num2,num3,prim,seg,ter Como real;
	
	//Escribir "Ingresa 3 números diferentes:";
	//Leer num1;
	//Leer num2;
	//Leer num3;
	
	Escribir "Ingresa el primer número:";
	Leer num1;
	
	Escribir "Ingresa el segundo número:";
	Leer num2;
	
	Escribir "Ingresa el tercer número:";
	Leer num3;
	
	
	si	(num1>num2 y num1>num3) Entonces
		prim=num1;
		si	(num2>num3) Entonces
			seg=num2
			ter=num3
		SiNo
			seg=num3
			ter=num2
		FinSi
	FinSi
	
	si	(num2>num1 y num2>num3) Entonces
		prim=num2;
		si	(num1>num3) Entonces
			seg=num1
			ter=num3
		SiNo
			seg=num1
			ter=num3
		FinSi
	FinSi
	
	si	(num3>num2 y num3>num1) Entonces
		prim=num3;
		si	(num2>num1) Entonces
			seg=num2
			ter=num1
		SiNo
			seg=num1
			ter=num2
		FinSi
	FinSi
	
	Escribir "Tus números de mayor a menor son: ",prim,"-",seg,"-",ter;
	
FinAlgoritmo
.
.
.
.
.
.
.
.
![image](https://user-images.githubusercontent.com/113804556/194731057-326301f2-30d2-409b-98be-7fb73f747c78.png)
.
.
.
.
..
.
Algoritmo ordenar2
	
	Definir num1,num2,num3,prim,seg,ter Como real;
	
	//Escribir "Ingresa 3 números diferentes:";
	//Leer num1;
	//Leer num2;
	//Leer num3;
	
	Escribir "Ingresa el primer número:";
	Leer num1;
	
	Escribir "Ingresa el segundo número:";
	Leer num2;
	
	Escribir "Ingresa el tercer número:";
	Leer num3;
	
	
	si	(num1>num2 y num1>num3) Entonces
		prim=num1;
		si	(num2>num3) Entonces
			seg=num2
			ter=num3
		SiNo
			seg=num3
			ter=num2
		FinSi
		
	SiNo
		si	(num2>num1 y num2>num3) Entonces
			prim=num2;
			si	(num1>num3) Entonces
				seg=num1
				ter=num3
			SiNo
				seg=num1
				ter=num3
			FinSi
		SiNo
			si	(num3>num2 y num3>num1) Entonces
				prim=num3;
				si	(num2>num1) Entonces
					seg=num2
					ter=num1
				SiNo
					seg=num1
					ter=num2
				FinSi
			FinSi
		FinSi
	
		
		
	FinSi
	
	
	
	
	
	Escribir "Tus números de mayor a menor son: ",prim,"-",seg,"-",ter;
	
FinAlgoritmo
.
.
.
.
.
.

.
..

![image](https://user-images.githubusercontent.com/113804556/194731068-ff2ef7a5-9d81-4f86-a9ac-91d2e09fa3f5.png)

