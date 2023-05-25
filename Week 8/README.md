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
        case 7: <br> <br>
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
### 2. A wolf in sheep's clothing
### 3. Decode the morse code
## WEDNESDAY
### 1. Who likes it?
### 2. Bit counting
### 3. Your order, please
## THURSDAY
### 1. Counting duplicates
### 2. Encrypt this!
### 3. Valid parentheses
### 4. Convert string to camel case
