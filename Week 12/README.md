# WEEK 12

## TUESDAY

### 1. Node.JS Core Understanding
### 1. What is Node.JS?

Node.JS is a Javascript-based runtime environment used in the creation of web applications.

### What is NPM?

It is a management system for Node packages.

### 2. What problem does Node.JS solve (Is there any problem that can be solved with Node.JS 🤔)?

Node.JS solves the problem of memory usage for spawning threads by avoiding creating new threads by 
executing events within the execution process.

### 3. What is the V8 Javascript Engine?

It is an open source engine created for Javascript. It allows to execute Javascript code.

### 4. Is Node.JS really necessary in the Development ecosystem?

It is very necessary because it is currently one of the best options for web development and 
is widely used by big companies.

### Why not use PHP or Golang?

Because Node.JS brings together all the positive characteristics of both in a single environment.

### 5. What is the difference between Node.JS and any other browser?

The difference is that Node.JS is highly scalable and event-driven.

### Are Node.JS and a browser the same?

No, unlike the browser where Javascript is sandboxed for your safety, node. js has full access to 
the system like any other native application.

### 6. What is NVM and Why is it useful for Node.JS developers?

NVM is a software that allows to download and manage Node.JS versions, 
it is useful because it helps to solve typical npm problems. 


***
## 2. Node.JS Module System
### 1. What is a Javascript Module?

It is a Javascript code file that can be ported from other parts of the 
application. parts of the application.

### 2. Why are Javascript Modules necessary?
They are necessary to be able to reuse code efficiently.

### 3. What module standards are available in Node.JS?

Some of the modules are fs, path, querystring, http and https, etc.


### 4. What are the differences between ESModules and CommonJS modules?

The difference is that CommonJS only allows to load modules synchronously and 
ESModules allows to load modules synchronously and asynchronously.

### 5. Which types of modules exist in Node.JS?

Node.JS includes three types of modules: Core Modules, Local Modules y Third Party Modules.


***
## 3. Node.JS Hello World - Practice
![image](https://github.com/faviola14/core-code-readme/assets/98840536/0e0d37a2-be78-42b4-bb5e-c07498ff0157)
### 0. Why do we run the npm init command and not node init to create a new Node.JS project?

Because npm is used to update or create Node packages.

### 1. When you entered the npm init command and answered the questions you saw in the terminal, a new file called packacke.json was generated.

### What does this file do?

Maintains the history of installed packages.

### Why is this file generated?

It is automatically generated to optimize the way dependencies are generated.
***
## 4. Node.JS Module System - Practice

### main.js
```javascript
const { sum, subtract }  = require("./operations");

console.log(sum(1, 2))
console.log(subtract(1, 2))
```

### operations.js

```javascript
const sum = (num1, num2) => {
    return num1 + num2;
}
const subtract = (num1, num2) => {
    return num1 - num2;
}

module.exports = { sum, subtract };
```
![image](https://github.com/faviola14/core-code-readme/assets/98840536/08cdcbb0-bd95-49dd-9463-22f8be9c87e8)


***


## WEDNESDAY

## 1. Client-Server Model
### 1. What is a Server?


### 2. What is a Client?


### 3. Is a server just another physical computer?


### Why do we refer to a certain class of applications as Servers?


### What is the difference?


### 4. Is there any similarity between human communication and the client-server model?


### List some examples


### 5. Is the client-server model applicable only to the Web?


### Do desktop applications use the client-server model?


### Can you mention any other example of this model outside the Web?


***
## 2. HTTP Learning Exercise
### 1. What is HTTP?


### 2. What is a Communication Protocol?


### Do humans use communication protocols?


### 3. What is a Request in HTTP?


### 4. What is a Response in HTTP?


### 5. What is an HTTP method?


### 6. What are HTTP request headers?


***
## 3. APIs Core Understanding
### 1. What is an API?


### 2. What is a Protocol?


### 3. Is the term API only applicable to the communication of programs over the Internet?


### 4. Why is structured communication between two programs important?


### Do we humans use APIs when communicating without technology?


### 5. Is an API just another program or a standard?


### 6. Do you know any API? Can you list at least 5 examples of APIs?


***
## 4. From JSON to REST
### 1. What is JSON?


### Is JSON the same as a plain Javascript object?


### 1. What is REST?


### Is REST a programming language, framework, technology, or architecture pattern?


### 1. What is a Resource in REST?


### What is a resource identifier?


### 1. How are HTTP and REST related?


### What HTTP methods does REST use within its architecture rules?


### Why do we use HTTP methods in REST and how do they relate to resources?


### 1. Is REST the same as HTTP?


***
### 5. REST API Clients
### 1. Install Postman in your computer, follow this guide

![image](https://github.com/faviola14/core-code-readme/assets/98840536/834b53f6-ceb6-474c-b0bf-129c476f1beb)

### 2. Watch this course about how to use Postman to interact with APIs
![image](https://github.com/faviola14/core-code-readme/assets/98840536/0382333d-177d-4f30-9863-3a0408ee081c)

### 3. Answer the questions:
### Postman only works with REST APIs?

Yes, it only work with REST APIs.

### Is there an alternative to Postman?

Yes, there is a lot of alternatives like Katalon, SoapUI, JMeter, etc.

## THURSDAY

### 1. Express.JS Core Understanding
### 1. Read about the Chain of Responsibility design pattern here.

![image](https://github.com/faviola14/core-code-readme/assets/98840536/267d9448-2251-4efe-aef0-bf72a111fece)

### 2. Express JS Hello World:
### Create a new Node.JS project using NPM.
### Install Express.JS as an external dependency in your project following this guide.

![image](https://github.com/faviola14/core-code-readme/assets/98840536/ad19211e-5ff2-4d2b-b883-ca41208b4811)

#### Create an Express.JS Hello World application following this guide.
![image](https://github.com/faviola14/core-code-readme/assets/98840536/6cbc0c00-bfda-4524-8f2f-000818c1a296)

***

### 2. Forrest Gump Ping-Pong API 🏓:

***
### 3. Delayed Response API ⏳:
