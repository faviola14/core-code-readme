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



### TUESDAY
### 1. Get started with Codewars

![image](https://github.com/faviola14/core-code-readme/assets/98840536/3b0ed6fb-02ec-4dae-8ac2-7ff84536156e)
![image](https://github.com/faviola14/core-code-readme/assets/98840536/d6c4b5c2-b037-4341-9fa6-605ac06d4df3)

### 2. Objects

function animal(obj){ <br>
    const animales =obj <br>
    let color=animales.color <br>
    let name= animales.name <br>
    let legs= animales.legs <br>
    return "This "+color+" "+name+" has "+legs+" legs." <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/f84114c7-7832-4dc7-abe5-f53dcb6deec4)


### 3. Return to sanity

function mystery() { <br>
    var results = <br>
    {sanity: 'Hello'}; <br>
    return results; <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/745f3d7a-3782-49e4-a448-3a336e171feb)


### 4. Object syntax debug

var rooms = { <br>
    first: { <br>
    description: 'This is the first room', <br>
    items: { <br>
        chair: 'The old chair looks comfortable', <br>
        lamp: 'This lamp looks ancient' <br>
    }}, <br>
    second: { <br>
    description: 'This is the second room', <br>
    items: { <br>
        couch: 'This couch looks like it would hurt your back', <br>
        table: 'On the table there is an unopened bottle of water' <br>
    } <br>
    } <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/f53c989a-826c-40d9-9ba7-fff55e30844f)



### WEDNESDAY
### 1. Count strings in objects

function strCount(obj){ <br>
    let contador =0 <br>
    for (x in obj)} <br>
        if (typeof obj[x] == "string"){ <br>
            contador++ <br>
        } <br>
        if (typeof obj[x] == "object"){ <br>
            contador= contador + strCount(obj[x]) <br>
        } <br>
    } <br>
    return contador <br>
    } <br>
    
![image](https://github.com/faviola14/core-code-readme/assets/98840536/1ee95df1-13ed-47da-bc9f-75f35ba207dc)


### 2. Extending JavaScript Objects: Get First & Last Array Element

Array.prototype.first = function() {<br>
    return this[0] <br>
} <br>
Array.prototype.last = function() { <br>
    return this[this.length-1] <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/aec46e8c-d7a4-464a-b5e7-78e8aa6f710e)

### 3. Object Oriented Piracy

function Ship(draft,crew) { <br>
    this.draft = draft; <br>
    this.crew = crew; <br>
    this.isWorthIt = function (){ <br>
        peso=crew*1.5 <br>
        if (draft-peso>20){ <br>
            return true <br>
        } <br>
        else{ <br>
            return false <br>
        } <br>
    } <br>
} <br>
![image](https://github.com/faviola14/core-code-readme/assets/98840536/48b118a6-201f-4210-ac21-37c80a6dee22)


### THURSDAY 
### 1. Convert a String to a Number!

const stringToNumber = function(str){ <br>
    // put your code here <br>
    return Number(str) <br>
    return null; <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/499d3f0b-8aa9-4bc1-969e-099cb660d48d)

### 2. Convert number to reversed array of digits

function digitize(n) { <br>
    //code here <br>
    let y=n.toString() <br>
    let x=y.split("") <br>
    let salida=[] <br>
    for (z=x.length-1;z>-1;z--){ <br>
        salida.push(Number(y[z]) ) <br>
    } <br>
    return salida <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/8c68215f-3855-490f-b164-da342240c897)

### 3. Truthy and Falsy

const truthy = []; <br>
const falsy = []; <br>
truthy.push(1) <br>
truthy.push("true") <br>
truthy.push(2) <br>
truthy.push(true) <br>
truthy.push({}) <br>
falsy.push(0) <br>
falsy.push("") <br>
falsy.push(undefined) <br>
falsy.push(false) <br>
falsy.push(null) <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/065dc2f2-dfcc-4643-957f-d9cc6bde06b6)

### 4. Training JS #4: Basic data types--Array

function getLength(arr){ <br>
  //return length of arr <br>
  return arr.length <br>
} <br>
function getFirst(arr){ <br>
  //return the first element of arr <br>
  return arr[0] <br>
} <br>
function getLast(arr){ <br>
  //return the last element of arr <br>
  return arr[arr.length-1] <br>
} <br>
function pushElement(arr){ <br>
  var el=1; <br>
  //push el to arr <br>
  arr.push(el) <br>
  return arr <br>
} <br>
function popElement(arr){ <br>
  //pop an element from arr <br>
  arr.pop() <br>
  return arr <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/74720f3a-b5a4-4091-8962-0e1097fd8f64)
