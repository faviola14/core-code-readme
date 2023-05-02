## WEEK 3 

### MONDAY
### 1. Simple Calculator
<p>Algoritmo SimpleCalculator <br>
	Escribir "Ingrese el primer número: " <br>
	Leer num1 <br>
	Escribir "Ingrese el segundo número: " <br>
	Leer num2 <br>
	Escribir "Ingrese una operación: +,-,*,/" <br>
	Leer operacion <br>
	si operacion=="+" <br>
		res=num1+num2 <br>
		Escribir "Procesando: "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2) <br>
		Escribir "Resultado: "+ConvertirATexto(res) <br>
	SiNo <br>
		si operacion=="-" <br>
			res=num1-num2 <br>
			Escribir "Procesando: "+ConvertirATexto(num1)+ " - "+ConvertirATexto(num2) <br>
			Escribir "Resultado: "+ConvertirATexto(res) <br>
		SiNo <br>
			si operacion=="*" <br>
				res=num1*num2 <br>
				Escribir "Procesando: "+ConvertirATexto(num1)+ " * "+ConvertirATexto(num2) <br>
				Escribir "Resultado: "+ConvertirATexto(res) <br>
			SiNo <br>
				si operacion=="/" <br>
					res=num1/num2 <br>
					Escribir "Procesando: "+ConvertirATexto(num1)+ " / "+ConvertirATexto(num2) <br>
					Escribir "Resultado: "+ConvertirATexto(res) <br>
				SiNo <br>
					Escribir "El simbolo es incorrecto" <br>
				FinSi <br>
			FinSi <br>
		FinSi <br>
	FinSi <br>
FinAlgoritmo <br></p>





### 2. Special Number

Algoritmo specialNumber <br>
	Leer n <br>
	Si n == 100 Entonces <br>
		Imprimir 'This is a special number' <br>
	SiNo <br>
		Si n < 1000 & n % 10 == 0   Entonces <br>
			Imprimir 'This number is almost special' <br>
		SiNo <br>
			Imprimir 'Just a regular number' <br>
		FinSi <br>
	FinSi <br>
FinAlgoritmo <br>


### TUESDAY
### 1. Simple calculator with Switch

Algoritmo SimpleCalculatorSwitch <br>
	Escribir "Ingrese el primer número: " <br>
	Leer num1 <br>
	Escribir "Ingrese el segundo número: " <br>
	Leer num2 <br>
	Escribir "Ingrese una operación: +,-,*,/" <br>
	Leer operacion <br>
	Segun operacion Hacer <br>
		"+": <br>
			res=num1+num2 <br>
			Escribir "Procesando: "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2) <br>
			Escribir "Resultado: "+ConvertirATexto(res) <br>
		"-": <br>
			res=num1-num2 <br>
			Escribir "Procesando: "+ConvertirATexto(num1)+ " - "+ConvertirATexto(num2) <br>
			Escribir "Resultado: "+ConvertirATexto(res) <br>
		"*": <br>
			res=num1*num2 <br>
			Escribir "Procesando: "+ConvertirATexto(num1)+ " * "+ConvertirATexto(num2) <br>
			Escribir "Resultado: "+ConvertirATexto(res) <br>
		"/": <br>
			res=num1/num2 <br>
			Escribir "Procesando: "+ConvertirATexto(num1)+ " / "+ConvertirATexto(num2) <br>
			Escribir "Resultado: "+ConvertirATexto(res) <br>
		De Otro Modo: <br>
			Escribir "El simbolo es incorrecto" <br>
	Fin Segun <br>
FinAlgoritmo <br>

### 2. Multi Option Program

Algoritmo MultiOptionProgram <br>
	Escribir "=======MULTIOPCION=======" <br>
	Escribir "Opciones Disponibles" <br>
	Escribir "1. Suma de dos números" <br>
	Escribir "2. Imprimir día de la semana" <br>
	Escribir "3. Calcular la longitud del texto" <br>
	Escribir "Ingrese la opción seleccionada: " <br>
	Leer opc <br>
	Segun opc Hacer <br>
		"1": <br>
			Escribir "Ingrese el primer número: " <br>
			Leer num1 <br>
			Escribir "Ingrese el segundo número: " <br>
			Leer num2 <br>
			res=num1+num2 <br>
			Escribir "Procesando: "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2) <br>
			Escribir "Resultado: "+ConvertirATexto(res) <br>
		"2": <br>
			Escribir "Ingrese el día de la semana: (1-7)" <br>
			Leer dia <br>
			Segun dia Hacer <br>
				"1": <br>
					Escribir "Lunes" <br>
				"2": <br>
					Escribir "Martes" <br>
				"3": <br>
					Escribir "Miércoles" <br>
				"4": <br>
					Escribir "Jueves" <br>
				"5": <br>
					Escribir "Viernes" <br>
				"6": <br>
					Escribir "Sábado" <br>
				"7": <br>
					Escribir "Domingo" <br>
				De Otro Modo: <br>
					Escribir "Opción Incorrecta" <br>
			Fin Segun <br>
		"3": <br>
			Escribir "Ingrese el texto" <br>
			Leer txt <br>
			resp=Longitud(txt) <br>
			Escribir "La longitud es: "+ ConvertirATexto(resp) <br>
		De Otro Modo: <br>
			Escribir "Opción Incorrecta" <br>
	Fin Segun <br>
FinAlgoritmo <br>

### WEDNESDAY
### 1. Multiplication Tables <br>

Algoritmo MultiplicationTables <br>
	Escribir "Ingrese la tabla a multiplicar" <br>
	leer num <br>
	contador=1 <br>
	Escribir "Tabla del "+ num <br>
	Mientras contador<11 Hacer <br>
		res=ConvertirANumero(num)*contador <br>
		Escribir num+" * "+ ConvertirATexto(contador)+ " = "+ ConvertirATexto(res) <br>
		contador=contador+1 <br>
	Fin Mientras <br>
FinAlgoritmo <br>


### 2.  Simple calculator with Do While

Algoritmo SimpleCalculatorSwitch <br>
	Repetir <br>
		Escribir "Ingrese el primer número: " <br>
		Leer num1 <br>
		Escribir "Ingrese el segundo número: " <br>
		Leer num2 <br>
		Escribir "Ingrese una operación: +,-,*,/" <br>
		Leer operacion <br>
		Segun operacion Hacer <br>
			"+": <br>
				res=num1+num2 <br>
				Escribir "Procesando: "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2) <br>
				Escribir "Resultado: "+ConvertirATexto(res) <br>
			"-": <br>
				res=num1-num2 <br>
				Escribir "Procesando: "+ConvertirATexto(num1)+ " - "+ConvertirATexto(num2) <br>
				Escribir "Resultado: "+ConvertirATexto(res) <br>
			"*": <br>
				res=num1*num2 <br>
				Escribir "Procesando: "+ConvertirATexto(num1)+ " * "+ConvertirATexto(num2) <br>
				Escribir "Resultado: "+ConvertirATexto(res) <br>
			"/": <br>
				res=num1/num2 <br>
				Escribir "Procesando: "+ConvertirATexto(num1)+ " / "+ConvertirATexto(num2) <br>
				Escribir "Resultado: "+ConvertirATexto(res) <br>
			De Otro Modo: <br>
				Escribir "El simbolo es incorrecto" <br>
		Fin Segun <br>
		Escribir "Deseas Continuar con la operación? Si/No" <br>
		Leer continuar <br>
	Hasta Que continuar=="No" | continuar=="no" <br>
FinAlgoritmo <br>


### THURSDAY
### 1. Multiplication Tables with For

Algoritmo MultiplicationTablesFor <br>
	Escribir "Ingrese la tabla a multiplicar" <br>
	leer num <br>
	contador=1 <br>
	Escribir "Tabla del "+ num <br>
	Para x<-1 Hasta 10 Con Paso 1 Hacer <br>
		res=ConvertirANumero(num)*x <br>
		Escribir num+" * "+ ConvertirATexto(x)+ " = "+ ConvertirATexto(res) <br>
	Fin Para <br>
FinAlgoritmo <br>

### 2. Ascending and Descending Numbers

Algoritmo AscendingDescendingNumbers <br>
	Escribir "Ingrese un número" <br>
	Leer num <br>
	Escribir "Operaciones Disponibles" <br>
	Escribir "Imprimir en Orden Ascendente" <br>
	Escribir "Imprimir en Orden Descendente" <br>
	Escribir "Ingrese operación a ejecutar" <br>
	Leer opc <br>
	Segun opc Hacer <br>
		"1": <br>
			Para x<-0 Hasta num Con Paso 1 Hacer <br>
				Escribir x <br>
			Fin Para <br>
		"2": <br>
			Para x<-num Hasta 0 Con Paso -1 Hacer <br>
				Escribir x <br>
			Fin Para <br>
		De Otro Modo: <br>
			Escribir "No ingreso una opción correcta" <br>
	Fin Segun <br>
FinAlgoritmo <br>


### 3. Greetings

Algoritmo Greetings <br>
	Repetir <br>
		Escribir  "Ingrese la hora actual (0-23)" <br>
		Leer  hora <br>
		si ConvertirANumero(hora)<=23 &ConvertirANumero(hora)>=0 entonces <br>
			si ConvertirANumero(hora)<=12 Entonces <br>
				Escribir  "Buenos Días!" <br>
			FinSi <br>
			si ConvertirANumero(hora)<=18 &  ConvertirANumero(hora)>12 Entonces <br>
				Escribir  "Buenas Tardes!" <br>
			FinSi <br>
			si ConvertirANumero(hora)<=23  & ConvertirANumero(hora)>18 Entonces <br>
				Escribir  "Buenas Noches!" <br>
			FinSi <br>
		SiNo <br>
			Escribir "La hora fue ingresada incorrectamente" <br>
		FinSi <br>
		Escribir "Desea Continuar? Si/No" <br>
		Leer resp <br>
	Mientras Que resp<>"No" | resp<>"no" | resp<>"NO" <br>
FinAlgoritmo <br>
