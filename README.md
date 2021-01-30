# Hackaton-8
Algoritmo Psuma 
	//variable de entrada
	Definir a Como Entero
	Definir b Como Entero
	//captura de datos 
	Escribir " Ingrese el primer numero"
	leer a
	Escribir " Ingrese el segundo numero"
	leer b
	//Proceso 
	suma=a+b
	//salida 
	Escribir "El resultado es " suma 
	
FinAlgoritmo


Algoritmo p2promedio 
	//variable de entrada
	Definir n1 Como Entero
	Definir n2 Como Entero
	//captura de datos 
	Escribir " Ingrese la primera nota "
	leer n1
	Escribir " Ingrese la segunda nota"
	leer n2
	Escribir " Ingrese la segunda nota"
	leer n3
	Escribir " Ingrese la segunda nota"
	leer n4
	//Proceso 
     promedio=(n1+n2+n3+n4)/4
	//salida 
	Escribir "El promedio de notas es " promedio
	
FinAlgoritmo




Algoritmo p3rectangulo
	//variable de entrada
	Definir base,altura Como real 
	//variable de salida
	Definir area como real 
	//captura de datos 
	Escribir " Ingrese la base del rectangulo "
	leer b
	Escribir " Ingrese la altura del rectangulo"
	leer h
	//Proceso 
     area=(b*h)
	//salida 
	Escribir "El area del triangulo es  " area
	
FinAlgoritmo


Algoritmo p4triangulo 
	//variable de entrada
	Definir base,altura Como real 
	//variable de salida
	Definir area como real 
	//captura de datos 
	Escribir " Ingrese la base del triangulo "
	leer b
	Escribir " Ingrese la altura del triangulo"
  leer h
  //Proceso 
     area=(b*h)/2
	//salida 
	Escribir "El area del triangulo es  " area
	
FinAlgoritmo

Algoritmo p5circulo
	//variable de entrada
	Definir radio, K Como real 
	//variable de salida
	Definir area como real 
	//captura de datos 
	Escribir " Ingrese el radio del circulo"
	leer r
  	//Proceso 
	k=3.14
	area<-(r*r)*3.14
	//salida 
	Escribir "El area del circulo es  " area
	
FinAlgoritmo

lgoritmo p6sueldo
	//variable de entrada
	Definir phora Como real 
	Definir  htrabajadas como entero
	//variable de salida
	Definir sueldo como real 
	//captura de datos 
	Escribir " Ingrese el pago por hora "
	leer phora
	Escribir " Ingrese las htrabajadas "
	leer htrabajadas
	//Proceso 
	sueldo<-phora*htrabajadas
	//salida 
	Escribir "El sueldo del trabajador es " sueldo 
	
FinAlgoritmo


Algoritmo p7pulgadas
	//variable de entrada
	definir medidadm como real
	//varialble de salida 
	Definir mpulgadas como real
	//captuda de datos 
	Escribir "Escribe la medida en metros "
	Leer medidam
	//Proceso 
	mpulgadas = medidadm * 39.37
	//salida 
	Escribir "Los metros convertidos a pulgadas es: ",mpulgadas
FinAlgoritmo

Algoritmo p8dolar
	//variable de entrada
	definir soles como real
	//varialble de salida 
	Definir dolares como real
	//captuda de datos 
	Escribir "Ingrese la cantidad a convertir en sole "
	Leer soles
	//Proceso 
	dolares = soles/(3.61)
	//salida 
	Escribir "La cantidad que obtiene es de : " "$ ",dolares
FinAlgoritmo


Algoritmo p9fecha
	//variable de entrada
	definir añonaci como real
	//varialble de salida 
	Definir edad  como real
	//captuda de datos 
	Escribir "Ingrese el el año de naciemiento  "
	Leer añonaci
	//Proceso 
	edad = 2021-añonaci
	//salida 
	Escribir "Su edad es de : ",edad
FinAlgoritmo


Algoritmo EDADMENOR
	edadL,edadM,edadP Son Enteros
	Escribir ("Ingrese Edad de Luis: ")
	leer edadL
	Escribir ("Ingrese Edad de María: ")
	leer edadM
	Escribir ("Ingrese Edad de Paco: ")
	leer edadP
	Si  edadL <= edadM y edadL <= edadP  
		Escribir  "El menor es Luis con: ",edadL," años"
	Sino
		Si  edadM < edadP
			Escribir  "La menor es María con: ",edadM," años"
		Sino
			Escribir  "El menor es Paco con: ",edadP," años"  
		Finsi
	Finsi
	
FinAlgoritmo


Algoritmo p11bono 
	//variable de entrada
	Definir antiguedad Como Entero
	//variable de salida 
	Definir bono  Como Entero
	//captura de datos 
	Escribir "Ingrese la antiguedad del trabajador "
	leer antiguedad
	bono = 0
	//Proceso 
	si antiguedad == 1 Entonces
		bono = 100
	SiNo
		si antiguedad == 2 Entonces
			bono = 200
		SiNo
			si antiguedad == 3 Entonces
				bono = 300
			SiNo
				si antiguedad == 4 Entonces
					bono = 400
				SiNo
					si antiguedad <= 5 Entonces
						bono = 500
					SiNo
						bono = 1000
					FinSi
				FinSi
			FinSi
		FinSi
	FinSi
	//salida
	Escribir "El bono que se le da al trabajador es de: $",bono
FinAlgoritmo


Algoritmo PROFESALARIO
	//variable de entrada
	Definir salario Como Real
	Definir x Como Entero
	//CAPTURA DE DATOS
	salario = 1500
	//PROCESO 
	para x = 1 Hasta 6 Con Paso 1 Hacer
		salario = salario + (salario * .10)
		Escribir "El salario en el año ",x," es: $",salario
	FinPara
	Escribir "---------------------------------------"
	Escribir " "
	//SALIDA 
	Escribir "El salario en 6 años es: $",salario
FinAlgoritmo


Algoritmo Nnotas
	//VARIABLE DE ENTRADA 
	Definir nota Como Real
	cont<-0
	cont1<-0
	//Proceso 
	Repetir
		Escribir "Ingresar la nota del alumno :"
		Leer nota
		Si (nota<10.5) Entonces
			cont=cont+1
		SiNo
			cont1=cont1+1
		Fin si
		Escribir "¿Desea agregar una nueva nota?"
		Escribir "1. Sí"
		Escribir "2. No"
		Leer agregar
	Hasta Que agregar=2
	//SALIDA 
	Escribir "Los aprobados son : ",cont1
	Escribir "Los desaprobados son : ",cont
FinAlgoritmo

Algoritmo detarea
	Definir n,color,verde,blanco,rojo Como Entero
	Escribir "Ingresa la cantidad total de focos"
	leer n
	verde = 0
	blanco = 0
	rojo = 0
	Mientras n > 0 Hacer
		Escribir "Selecciona un color"
		Escribir "1 = verde"
		Escribir "2 = blanco"
		Escribir "3 = rojo"
		leer color
		si color >= 1 y color <= 3 Entonces
			si color == 1 Entonces
				verde = verde + 1
			SiNo
				si color == 2 Entonces
					blanco = blanco + 1
				SiNo
					rojo = rojo + 1
				FinSi
			FinSi
			n = n - 1
		SiNo
			Escribir "Ingresa un color correcto"
		FinSi		
	FinMientras
	Escribir "El total de focos verdes es: ",verde
	Escribir "El total de focos blancos es: ",blanco
	Escribir "El total de focos rojos es: ",rojo
FinAlgoritmo




Algoritmo Avoto
	//Variable de entrada 
    Definir edad Como Entero;
	//captura de datos 
    Escribir "Ingrese su edad: " Sin Saltar;
    Leer edad;
	//Proceso y salida 
    Si edad >=18 Entonces
        Escribir "Puede votar en las próximas elecciones.";
    SiNo
        Escribir "No puede votar en las próximas elecciones.";
    FinSi
FinAlgoritmo
