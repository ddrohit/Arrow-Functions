# Arrow-Functions
A brief understanding of arrow function in javascript

# Introduction
Arrow functions are quite a beauty in javascript, which allows programers to take off the burden of defining the functions/methods with a function keyword.

# Sample Example
As the name defines this functions are defined by a symbol of arrow not this -> but this => "equal too followed by a greaterthan symbol"
```javascript
//Without using a Arrow Key Word                                   
                                                              
var helloworld = function(){ console.log("Hello world"); }     
helloworld();                                                 
                                                              
//With using a Arrow function 

var helloworld = () => { console.log("Hello world"); }
helloworld();
```
Both the codes give the same output Hello world but you can see the difference in there syntax.
i feel it's a little cute and readable and easy to use over a regular functions.

And for a single statement functions like the above code can be shortened to

```javascript
var helloworld => console.log("Hello World");
helloworld();
```
