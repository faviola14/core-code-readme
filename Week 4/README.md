## WEEK 4

## MONDAY
### 1. Average Sales and Commissions 

Algoritmo AverageSalesCommissions <br>
	Escribir "Escriba el número total de ventas" <br>
	Leer ventas <br>
	si ventas>5 Entonces <br>
		comisionX=0.15 <br>
	SiNo <br>
		comisionX=0.10 <br>
	FinSi <br>
	ventasTotal=0 <br>
	comision=0 <br>
	Para x=1 Hasta ventas Con Paso 1 Hacer <br>
		Escribir "Ingrese la venta "+ ConvertirATexto(x) <br>
		Leer ventaX <br>
		ventasTotal= ventasTotal+ ConvertirANumero(ventaX) <br>
	Fin Para <br>
	ventasPromedio= ventasTotal/ventas <br>
	comision=ventasTotal*comisionX <br>
	Escribir "El promedio de ventas es: "+ ConvertirATexto(ventasPromedio) <br>
	Escribir  "La comisión recibida por el vendedor es: "+ ConvertirATexto(comision) <br>
FinAlgoritmo <br>

### 2. Even or Odd

Algoritmo EvenOrOdd <br>
	opc=0 <br>
	Repetir <br>
		Escribir "Escriba un número entre 1 y 50" <br>
		Leer num <br>
		si num>50 | num<1 Entonces <br>
			Escribir "Número inválido" <br>
			opc=0 <br>
		SiNo <br>
			si num%2==0 Entonces <br>
				Para x<-2 Hasta num Con Paso 2 Hacer <br>
					Escribir ConvertirATexto(x) <br>
				Fin Para <br>
			SiNo <br>
				Para x<-1 Hasta num Con Paso 2 Hacer <br>
					Escribir ConvertirATexto(x) <br>
				Fin Para <br>
			FinSi <br>
			opc=1 <br>
		FinSi <br>
	Mientras Que opc=0 <br>
FinAlgoritmo <br>

## TUESDAY

### 2. Full Name

Algoritmo FullName <br>
	Escribir  "Ingrese su primer nombre" <br>
	Leer nombreP <br>
	Escribir  "Ingrese su segundo nombre" <br>
	Leer nombreS <br>
	nombreP=Minusculas(nombreP) <br>
	nombreS=Minusculas(nombreS) <br>
	nombreP=Mayusculas(Subcadena(nombreP,0,0))+Subcadena(nombreP,1,Longitud(nombreP)) <br>
	nombreS=Mayusculas(Subcadena(nombreS,0,0))+Subcadena(nombreS,1,Longitud(nombreS)) <br>
	Escribir nombreP+" "+nombreS <br>
FinAlgoritmo <br>

### 3. Throw Dice

Algoritmo ThrowDice <br>
	Para z=1 Hasta 10 Con Paso 1 Hacer <br>
		x=Aleatorio(1,6) <br>
		y=Aleatorio(1,6) <br>
		si x==y Entonces <br>
			Escribir ConvertirATexto(x) +" "+ConvertirATexto(y) + "Los dados son iguales" <br>
		SiNo <br>
			Escribir ConvertirATexto(x) +" "+ConvertirATexto(y) <br>
		FinSi <br>
	Fin Para <br>
FinAlgoritmo <br>


## WEDNESDAY 
### 1. Distance to Zero

Algoritmo DistanceToZero <br>
	mayor=0 <br>
	Para x=1 Hasta 5 Con Paso 1 Hacer <br>
		Escribir "Escriba un número" <br>
		Leer num <br>
		si abs(num)>mayor Entonces <br>
			mayor=trunc(num) <br>
		FinSi <br>
	Fin Para <br>
	Escribir "Más alejado de 0: " + ConvertirATexto(mayor) <br>
FinAlgoritmo <br>

### 2. Toss Coin

Algoritmo TossCoin <br>
	Escribir "Ingrese el nombre del primer jugador" <br>
	Leer play1 <br>
	Escribir "Ingrese la cantidad a jugar" <br>
	Leer cantidad1 <br>
	Escribir "Ingrese el nombre del segundo jugador" <br>
	Leer play2 <br>
	Escribir "Ingrese la cantidad a jugar" <br>
	Leer cantidad2 <br>
	si cantidad1<1 |cantidad2<1 Entonces <br>
		si cantidad1<1 & cantidad2<1 <br>
			Escribir "Juego cancelado" <br>
		SiNo <br>
			si cantidad1<1 Entonces <br>
				Escribir "Jugador Ganador: " Mayusculas(play2) + " Cantidad Ganada: 0" <br>
			SiNo <br>
				Escribir "Jugador Ganador: " Mayusculas(play1) + " Cantidad Ganada: 0" <br>
			FinSi <br>
		FinSi <br>
	SiNo <br>
		si Aleatorio(1,2)=1 Entonces <br>
			Escribir "Jugador Ganador: " Mayusculas(play1) + " Cantidad Ganada: " + ConvertirATexto(cantidad2) <br>
		SiNo <br>
			Escribir "Jugador Ganador: " Mayusculas(play2) + " Cantidad Ganada: " + ConvertirATexto(cantidad1) <br>
		finsi <br>
	FinSi <br>
FinAlgoritmo <br>

## THURSDAY

### 2. Total Price

Funcion total <-TotalPrice ( precio,iva ) <br>
	Definir total Como Real <br>
	total=0 <br>
	si precio>3000 Entonces <br>
		total= precio+ ((precio*iva)/100) <br>
		total= total- ((total*10)/100) <br>
	SiNo <br>
		total= (precio*iva)/100 <br>
	FinSi <br>
Fin Funcion <br>

Algoritmo TotalPricex <br>
	imprimir TotalPrice(5000,21) <br>
FinAlgoritmo <br>

### 3. Reverse Direction and Size

Funcion palabraA <- ReverseDirectionAndSize ( palabra ) <br>
	definir palabraA Como Caracter <br>
	palabraA="" <br>
	Para x=Longitud(palabra) Hasta -1 Con Paso -1 Hacer <br>
		letra= Subcadena(palabra,x,x) <br>
		si letra == Mayusculas(letra) Entonces <br>
			letra= Minusculas(letra) <br>
		sino  <br>
			letra= Mayusculas((letra)) <br>
		FinSi <br>
		palabraA= Concatenar(palabraA,letra) <br>
	Fin Para <br>
Fin Funcion <br>

Algoritmo example_ReverseDirectionAndSize <br>
	Imprimir ReverseDirectionAndSize("Hello") <br>
FinAlgoritmo <br>
