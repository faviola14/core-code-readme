## WEEK 8

## MONDAY
### 1. Training JS #7: if..else and ternary operator

function saleHotdogs(n){ <br>
    if (n<5){<br>
    price=n*100 <br>
    } <br>
    if (n >= 5 && n < 10){ <br>
        price=n*95 <br>
    } <br>
    if (n >= 10){ <br>
        price=n*90 <br>
    }<br>
    return price <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/ef7612b9-7d7c-4ee8-a313-6a77dd0022de)


### 2. Training JS #8: conditional statement--switch

function howManydays(month){ <br>
    var days; <br>
    switch (month){ <br>
        case 1: <br>
            days=31; <br>
            break; <br>
        case 3: <br>
            days=31; <br>
            break; <br>
        case 5: <br>
            days=31; <br>
            break; <br>
        case 7: <br>
            days=31; <br>
            break; <br>
        case 8: <br>
            days=31; <br>
            break; <br>
        case 10: <br>
            days=31; <br>
            break; <br>
        case 12: <br>
            days=31; <br>
            break; <br>
        case 4: <br>
            days=30; <br>
            break; <br>
        case 6: <br>
            days=30; <br>
            break; <br>
        case 9: <br>
            days=30; <br>
            break; <br>
        case 11: <br>
            days=30; <br>
            break; <br>
        case 2: <br>
            days=28 <br>
            break; <br>
    } <br>
    return days; <br>
} <br>
![image](https://github.com/faviola14/core-code-readme/assets/98840536/c881364d-11ca-46f1-9e5e-6bb30dc98ef0)

### 3. Basic calculator

function calculate(num1, operation, num2) { <br>
    var res; <br>
    switch(operation){ <br>
        case "+": <br>
            res=num1+num2; <br>
            break; <br>
        case "-": <br>
            res=num1-num2; <br>
            break; <br>
        case "*": <br>
            res=num1*num2; <br>
            break; <br>
        case "/": <br>
            if (num1==0 || num2==0){ <br>
                res=null <br>
            } <br>
            else{ <br>
                res=num1/num2; <br>
            } <br>
            break; <br>
        default: <br>
            res=null <br>
    } <br>
    return res <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/63745972-00a7-4547-897a-e602f947a2b1)


## TUESDAY
### 1. Even or odd

function evenOrOdd(number) { <br>
    switch(number%2){ <br>
        case 0: return "Even" <br>
        default: return "Odd" <br>
        } <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/2bf40bbe-239b-433b-94ac-f1cfec237bf0)


### 2. A wolf in sheep's clothing

function warnTheSheep(queue) { <br>
    for (const i in queue){ <br>
        var z=Number(i)+1 <br>
        if (queue[i]=="wolf" ){ <br>
            if (z==queue.length  ){ <br>
                return "Pls go away and stop eating my sheep"; <br>
            } <br>
            else{ <br>
                var y=Number(queue.length )-z; <br>
            return "Oi! Sheep number "+ y+"! You are about to be eaten by a wolf!"; <br>
            } <br>
        } <br>
    } <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/e74d6035-af2e-4cf2-ac96-7afa5f5b39d1)

### 3. Decode the morse code

decodeMorse = function(morseCode){ <br>
    let palabras=morseCode.trim().split('   '); <br>
    let letras=[]; <br>
    let fraseS =[]; <br>
    for (let i = 0; i < palabras.length; i++){ <br>
        letras = palabras[i].split(' '); <br>
        for (let j = 0; j < letras.length; j++) { <br>
            letras[j] = MORSE_CODE[letras[j]]; <br>
        } <br>
    fraseS.push(letras.join('')); <br>
    } <br>
    let salida =fraseS.join(' ').trim() <br>
    return salida <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/3b9816fd-a5e3-4a78-909f-0d8a7f641a57)


## WEDNESDAY
### 1. Who likes it?

function likes(names) { <br>
    switch(names.length){ <br>
        case 0: return "no one likes this" <br>
        case 1: return names[0]+ " likes this" <br>
        case 2: return names[0]+  " and "+names[1]+" like this" <br>
        case 3: return names[0]+ ", "+names[1]+" and "+names[2]+" like this" <br>
        default: <br>
            var x=names.length-2 <br>
            return  names[0]+ ", "+names[1]+" and "+x+" others like this" <br>
    } <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/fbc5b326-f5ce-49d1-b06f-91bb72bee407)


### 2. Bit counting



### 3. Your order, please


## THURSDAY
### 1. Counting duplicates
### 2. Encrypt this!
### 3. Valid parentheses
### 4. Convert string to camel case
