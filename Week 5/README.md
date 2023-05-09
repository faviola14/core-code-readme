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

### WEDNESDAY

### THURSDAY
