## WEEK 5

## MONDAY

### 1. Time Converter <br>

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
