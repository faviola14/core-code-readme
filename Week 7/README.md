## WEEK 7

### MONDAY
### 1. String: substr()

function firstWord(palabra){ <br>
    let palabra1 = palabra.split(" ")  <br>
    let palabra2= palabra1[0]  <br>
    return palabra.substr(0,palabra2.length)  <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/b1858ed2-5420-4aa1-a9d2-8b035c28844f)

### 2. String: replace()

function normalize(parameter){ <br>
    let date =parameter.replace('-','/') <br>
    date=date.replace('-','/') <br>
    return date <br>
    } <br>
    
![image](https://github.com/faviola14/core-code-readme/assets/98840536/1a72c08a-bb73-4a0c-9a99-e5acbf2b3b61)


### 3. Increment

![image](https://github.com/faviola14/core-code-readme/assets/98840536/347f5116-f6e6-4de1-a35e-521b76f61160)

### 4. Fahrenheit

function toFahrenheit(celcius){ <br>
return ((9*celcius)/5)+32 <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/d85fa60b-574c-4c30-aefa-f740bd2c236c)

### 5. Boolean

function nand(parameter1,parameter2){ <br>
  if (parameter1 == true & parameter2 == true){ <br>
    return false <br>
  } <br>
  else{ <br>
    return true <br>
  } <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/51c00417-8fe2-448e-9159-219e2574ddc2)
