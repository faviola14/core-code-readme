## WEEK 5

### MONDAY

### 1. Time Converter 

Algoritmo exampleTimeConverter <br>
	Imprimir timeConverter(4000) <br>
FinAlgoritmo <br>

Funcion  result <- timeConverter (number) <br>
	definir result como caracter <br>
	definir dias,horas,minutos,s Como Entero <br>
	dias=TRUNC(number/86400) <br>
	Escribir ConvertirATexto(dias) <br>
	horas=TRUNC(number/3600)%24 <br>
	Escribir ConvertirATexto(horas) <br>
	minutos=TRUNC(number/60) % 60 <br>
	Escribir ConvertirATexto(minutos) <br>
	s=number%60 <br>
	Escribir ConvertirATexto(s) <br>
	result="days: "+ ConvertirATexto(dias)+  ", hours: "+ ConvertirATexto(horas)+ ", minutes: "+ ConvertirATexto(minutos)+ ", and seconds: "+ ConvertirATexto(s) <br>
  FinFuncion <br>

### 2. Compare Distances

Funcion res <- compareDistances (  )  <br>
	definir positivos,negativos Como Entero <br>
	positivos=0 <br>
	negativos=0 <br>
	Para x<-1 Hasta 5 Con Paso 1 Hacer <br>
		Imprimir "Escriba un número" <br>
		Leer num1 <br>
		si num1>0 Entonces <br>
			positivos=positivos+num1 <br>
		sino <br>
			negativos=negativos+abs(num1) <br>
		FinSi <br>
	Fin Para <br>
	si positivos>negativos Entonces <br>
		res="true" <br>
	SiNo <br>
		res="false" <br>
	FinSi <br>
Fin Funcion <br>

Algoritmo exampleCompareDistances <br>
	Imprimir CompareDistances() <br>
FinAlgoritmo <br>


### TUESDAY

### 1. Sum of Pairs

Funcion retorno <- sumOfPairs () <br>
	retorno=0 <br>
	num=0 <br>
	Repetir <br>
		Escribir  "Write a number between 1 and 100" <br>
		Leer  num <br>
		si num<1 | num>100 <br>
			Imprimir 'invalid number' <br>
		SiNo <br>
			si num%2==0 Entonces <br>
				retorno=retorno+num <br>
			FinSi <br>
		FinSi <br>
	Mientras Que (num>=1 & num<=100) <br>
Fin Funcion <br>
Algoritmo exampleSumOfPairs <br>
	Imprimir sumOfPairs() <br>
FinAlgoritmo <br>


### 2. Mid Point

Funcion res <- midPoint ( num1,num2 ) <br>
	si num1>0 Entonces <br>
		si num2>0 Entonces <br>
			si num2>num1 Entonces <br> <br>
				suma=num1-num2 <br>
				res=(suma/2)+num2 <br>
			SiNo <br>
				suma=num2-num1 <br>
				res=(suma/2)+num1 <br>
			FinSi <br>
		SiNo <br>
			suma=abs(num2)+num1 <br>
			res=num1-(suma/2) <br>
		FinSi <br>
	SiNo <br>
		si num2>0 Entonces <br>
			suma=abs(num1)+num2 <br>
			res=(suma/2)+num1 <br>
		SiNo <br>
			si abs(num1)>abs(num2) Entonces <br>
				suma=abs(num1)-abs(num2) <br>
				res=(suma/2)+num1 <br>
			SiNo <br>
				suma=abs(num2)-abs(num1) <br>
				res=(suma/2)+num2 <br>
			FinSi <br>
		FinSi <br>
	FinSi <br>
Fin Funcion <br>

Algoritmo exampleMidpPoint <br>
	Imprimir midPoint(40,80) <br>
FinAlgoritmo <br>

### WEDNESDAY

### 1. Cashier

Funcion d <- deposit (  ) <br>
	Escribir "how much do you want to deposit:" <br>
	leer d <br>
Fin Funcion <br>

Funcion d <- withdraw (  ) <br>
	Escribir "how much do you want to withdraw:" <br>
	leer d <br>
Fin Funcion <br>

Funcion saldo <- cashier (  ) <br>
	saldo=1000 <br>
	Repetir <br>
		Escribir "Select an option:" <br>
		Escribir "a. To deposit." <br>
		Escribir "b. Withdraw." <br>
		Escribir  "c. Go out" <br>
		Leer opc <br>
		Segun opc Hacer <br>
			"a"| "A": <br>
				saldo=saldo+ConvertirANumero(deposit()) <br>
			"b"| "B":<br>
				saldo=saldo-ConvertirANumero(withdraw()) <br>
			De Otro Modo:<br>
				Escribir" opción incorrecta" <br>
		Fin Segun<br>
	Mientras Que opc<>"c" & opc<>"C" <br>
Fin Funcion<br>

Algoritmo exampleCashier <br>
	Imprimir cashier() <br>
FinAlgoritmo <br>
	

### 2. Weather average

Funcion celciu <- farenheit (  ) <br>
	Definir celsius Como Real <br>
	Definir degrees Como Caracter <br>
	leer degrees <br>
	celciu= (ConvertirANumero(degrees)-32)/1.8 <br>
Fin Funcion <br>

Funcion celciu <- celcius (  ) <br>
	Definir celsiu Como Real <br>
	Definir degrees Como Caracter <br>
	Leer degrees <br>
	celciu=ConvertirANumero(degrees) <br>
Fin Funcion <br>

Algoritmo exampleWeatherAverage <br>
	Definir celciu Como Real <br>
	definir promedio Como Real <br>
	definir opc Como Caracter <br>
	contador=0 <br>
	celciu=0 <br>
	Repetir <br>
		Escribir "Select an Option" <br>
		Escribir "a. Enter degrees celcius" <br> <br>
		Escribir "b. Enter degrees farenheit" <br>
		Escribir "x. Go out" <br>
		Leer opc <br>
		Segun opc Hacer <br>
			"a" | "A": <br>
				celciu=celciu+celcius() <br>
				contador=contador+1 <br>
			"b" | "B": <br>
				celciu=celciu+farenheit() <br>
				contador=contador+1 <br>
			"c" | "C": <br>
				promedio=celciu/contador <br>
				Imprimir ConvertirATexto(promedio) <br>
			De Otro Modo: <br>
				Escribir "opción incorrecta" <br>
		Fin Segun <br>
	Mientras Que opc<>"c" & opc<>"C" <br>
FinAlgoritmo <br>

### THURSDAY

### 1. If

let x <br>
x=11 <br>
if (x>10) { <br>
    resp= "Es mayor a 10" <br>
    } else { <br>
        resp= "Es menor a 10" <br>
    } <br>

### 2. While

let x <br>
x=0 <br>
while (x<10) { <br>
    resp="Es menor a 10" <br>
    x=x+1 <br>
} <br>

### 3. For

for (let i = 0; i < 10; i++) { <br>
    resp= "Es menor a 10" <br>
} <br>
