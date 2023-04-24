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


### WEDNESDAY
### 1. Multiplication Tables
### 2.  Simple calculator with Do While

### THURSDAY
### 1. Multiplication Tables with For
### 2. Ascending and Descending Numbers
### 3. Greetings
