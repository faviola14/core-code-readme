## WEEK 9

## MONDAY
### 1. "this" is a problem

function NameMe(first, last) { <br>
    this.firstName = first; <br>
    this.lastName = last; <br>
    this.name= this.firstName + ' ' + this.lastName; <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/4649e37c-9458-4089-8076-cd0979b1db66)


### 2. "Thinkful - List and Loop Drills: Lists of lists"

function processData(data) { <br>
    let add = [] <br>
    let out = 1 <br>
    for (let x of data) { <br>
        add.push(Number(x[0]-Number(x[1])))  <br>
    } <br>
    for (let y of add) { <br>
        out = out * Number(y)   <br>
    } <br>
    return out <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/0795c033-bb59-4ec9-add0-d4bf1d6616c9)


### 3. Stop gninnipS My sdroW!

function spinWords(string){ <br>
    let words = string.split(' '); <br>
    let strings = ""; <br> <br>
    let word = ""; <br>
    let drow = ""; <br>
    for (let x in words) { <br>
        if (words[x].length > 4) { <br>
            word = words[x]; <br>
            for (let y = word.length - 1; y > -1; y--){ <br>
                drow = drow + word[y]; <br>
            } <br>
            words[x] = drow; <br>
            word = ""; <br>
            drow = ""; <br>
        } <br>
        if (x > 0) { <br>
            strings = strings + " " + words[x]; <br>
        } else { <br>
            strings = strings + words[x]; <br>
        } <br>
    } <br>
    return strings <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/ec069944-e9c5-4317-bc1d-83a9c1962c4a)


## TUESDAY
### 1. "this" is an other problem

function NamedOne(first, last) { <br>
    this.firstName = first; <br>
    this.lastName = last; <br>
    Object.defineProperty(this, 'fullName', { <br>
        get: function() { <br>
            return this.firstName + " " + this.lastName; <br>
        }, <br>
        set: function(name) { <br>
            const parts = name.split(' '); <br>
            if (parts.length === 2) { <br>
                this.firstName = parts[0]; <br>
                this.lastName = parts[1]; <br>
            } <br>
        } <br>
    }) <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/d61443fa-b5c0-4e0e-9868-89a7b8cf4480)


### 2. "Who likes it?"

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
![image](https://github.com/faviola14/core-code-readme/assets/98840536/59ecd8ec-1edd-4f03-a9c0-7928c9ddae82)


### 3. Convert string to camel case

function toCamelCase(str){ <br>
  if (str==="") return "" <br>
    str=str.replace(/_/g,"-") <br>
    let words= str.split("-") <br>
    let res="" <br>
    for (let x of words) { <br>
        x=x.toLowerCase() <br>
        x=x.replace(x[0],(x[0].toUpperCase())) <br> <br>
        res=res+x <br>
    } <br>
    return res <br>
} <br>

## WEDNESDAY
### 1. Easy mathematical callback

function processArray(arr, callback) { <br>
    let arrD <br>
    for (let i = 0; i < arr.length; i++) { <br>
        arrD[i]=callback(arr[i]) <br>
    } <br>
    return arrD <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/ad94e015-5daf-40e1-b70a-bc87ff4b713c)


### 2. Moving Zeros To The End

function moveZeros(arr) { <br>
    let arrNo0 = arr.filter(x => x !== Number(0)) <br>
    let arr0 = arr.filter(x => x === Number(0)) <br>
    arr=arrNo0.concat(arr0) <br>
    return arr <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/f1cf33fe-6228-49eb-8226-2c65a7abc982)

### 3. Valid Parentheses

function validParentheses(parens) { <br>
    let x=parens.split(""); <br>
    let res=0 <br>
    for (let n of x){ <br>
        if (n==="\(") res++ <br>
        if (n==="\)") res-- <br>
        if (res<0) return false <br>
    } <br>
    return res==0 <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/ab8d68ca-b878-408f-a874-b7a7d2a87c58)


## THURSDAY
### 1. The Hashtag Generator

function generateHashtag(str) { <br>
    str=str.toLowerCase() <br>
    if (str.replace(/ /g, "") === "") return false <br>
    if (str.replace(/ /g, "").length +1 > 140) return false <br>
    let hashtag = "#"; <br>
    let words = str.split(' '); <br>
    words=words.filter(x => x !== ' ') <br>
    words=words.filter(x => x !== '') <br>
    for (let i = 0; i < words.length; i++){ <br>
        let word = words[i]; <br>
        word = word.replace(word[0], word[0].toUpperCase()); <br>
        hashtag = hashtag + word; <br>
    } <br>
    return hashtag <br>
} <br>

![image](https://github.com/faviola14/core-code-readme/assets/98840536/14aa355e-333f-433f-b4f1-e640ae434bdd)


### 2. String incrementer
