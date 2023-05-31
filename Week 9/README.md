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
### 2. "Who likes it?"
### 3. Convert string to camel case

## WEDNESDAY
### 1. Easy mathematical callback
### 2. Moving Zeros To The End
### 3. Valid Parentheses


## THURSDAY
### 1. The Hashtag Generator
### 2. String incrementer
