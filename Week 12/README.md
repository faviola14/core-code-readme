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

It is a set of computers capable of receiving requests from a client and sending 
a response to the client.

### 2. What is a Client?

A computer or software that connects to a server and makes requests. 

### 3. Is a server just another physical computer?

A server can also be just a computer program.

### Why do we refer to a certain class of applications as Servers?

They can respond to requests made by a client.

### What is the difference?

The difference is that a server usually has more capacity than an application.

### 4. Is there any similarity between human communication and the client-server model?
### List some examples

In communication a person can ask for some information.
In communication a person can make requests.

### 5. Is the client-server model applicable only to the Web?

No, it can also be used in others apps or in real life.

### Do desktop applications use the client-server model?

Some applications that are connected to internet can also use the client-server model or 
some applications thatare connected with things like a printer or a scanner.

### Can you mention any other example of this model outside the Web?

A printer can use the client-server model to print documents.

***
## 2. HTTP Learning Exercise
### 1. What is HTTP?

It is the hypertext transfer protocol used in some Internet addresses.

### 2. What is a Communication Protocol?

These are norms or rules that regulate communication on the Internet.

### Do humans use communication protocols?

Yes, humans use communication protocols with other people.

### 3. What is a Request in HTTP?

It is a message that the client sends to request information.

### 4. What is a Response in HTTP?

It is the response that the server gives to the client's request.

### 5. What is an HTTP method?

They are the ones that allow you to communicate to the server what you want to do.

### 6. What are HTTP request headers?

It is an intermediary involved between APIs and communication with servers.


***
## 3. APIs Core Understanding
### 1. What is an API?

It is the code that allows applications to communicate with each other.

### 2. What is a Protocol?

These are the rules for communication between APIs.

### 3. Is the term API only applicable to the communication of programs over the Internet?

No, they can also be used to communicate locally.

### 4. Why is structured communication between two programs important?

It is important to avoid errors and to control the handling of them if they occur.

### Do we humans use APIs when communicating without technology?

No, nosmally we don't.

### 5. Is an API just another program or a standard?

An API is a standard of data interchange.

### 6. Do you know any API? Can you list at least 5 examples of APIs?

Open Weather Map
Love Calculator
URL Shortener Service
PokéAPI
NASA APIs

***

## 4. From JSON to REST
### 1. What is JSON?

JSON is a simple text format for data exchange.

### Is JSON the same as a plain Javascript object?

No, is differrent due to quotation marks.

### 2. What is REST?
REST is a communication interface between information systems using the Hypertext 
Transfer Protocol (HTP).

### Is REST a programming language, framework, technology, or architecture pattern?

Is a architecture pattern.

### 3. What is a Resource in REST?

It is a very important element within the REST API.

### What is a resource identifier?

It is a unique URl that identifies the API.

### 4. How are HTTP and REST related?

REST is based in HTTP.

### What HTTP methods does REST use within its architecture rules?

REST use POST, PUT, GET, DELETE, PATCH.

### Why do we use HTTP methods in REST and how do they relate to resources?

We use it because REST is based on HTTP and HTTP also use resources.

### 5. Is REST the same as HTTP?
No, HTTP allows more functions that REST

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

![image](https://github.com/faviola14/core-code-readme/assets/98840536/b49e528b-7cf9-4b82-ad78-df43c1a1b89a)

![image](https://github.com/faviola14/core-code-readme/assets/98840536/e58455f6-7d5b-424e-a6c4-c5483ece41c4)


***
### 3. Delayed Response API ⏳:
![image](https://github.com/faviola14/core-code-readme/assets/98840536/2b32b1c3-3019-4d21-b830-881939e99a0f)
![image](https://github.com/faviola14/core-code-readme/assets/98840536/3f7c387d-12ed-4528-8b10-af49c1f09ea8)


