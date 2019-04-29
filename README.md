# Arrow-Functions
A brief understanding of arrow function in javascript

# Introduction
Arrow functions are quite a beauty in javascript, which allows programers to take off the burden of defining the functions/methods with a function keyword.

# Syntax
As the name defines this functions are defined by a symbol of arrow not this -> but this => "equal too followed by a greaterthan symbol"
```javascript
 //arrow  functions without arguments.
 ()=>{ /*Statements*/ }
 
 //arrow functions with a single statement
 () => /*Statement*/
 
 //arrow functions with arguments
 (Argument1,Argument2,....) => { /*Statements*/ }
 
 //arrow function with a single argument and single statement can be written as
 Argument => /*Statement*/
 
 //arrow function with a single argument and many statements can be written as
 Argument => { /*Statements*/ }
 
 //arrow function while assiging a variable
 var (or) let (or) const variablename = (Arguments) =>{ /*Statements*/ }
 variablename();
 
 //a normal return to a arrow function
 ()=>{return(value);}
 
 //for a single statement with a return
 ()=>/*value (or) expression*/
 
 //sample
 addten= (a) => a+10
 addten(40) //this returns 50
 
 //more complex Example which return a arrow function is. 
 hello=()=>value=>value=>value
 hello()()("hello world")
 
 //Output Would be hello world
```

# Usecase Example
```javascript
//Without using a Arrow Key Word                                   
                                                              
var helloworld = function(){ console.log("Hello world"); }     
helloworld();                                                 
                                                              
//With using a Arrow function 

var helloworld = () => { console.log("Hello world"); }
helloworld();
```
Both the codes give the same output "Hello world", But you can see the difference in there syntax.

I feel it's a little cute and readable and easy to use, over a regular functions.

And for a single statement functions like the above code can be shortened to

```javascript
//Arrow functions for a single statement functions

var helloworld => console.log("Hello World");
helloworld();

```
