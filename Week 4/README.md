## WEEK 4

### MONDAY
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

### TUESDAY

### 1. Predefined Functions
### 2. Full Name
### 3. Throw Dice

### WEDNESDAY 
### 1. Distance to Zero
### 2. Toss Coin

### THURSDAY
### 1. Structure of a function
### 2. Total Price
### 3. Reverse Direction and Size
