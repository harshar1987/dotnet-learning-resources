# Javascript

## [Variable Scopes](https://css-tricks.com/javascript-scope-closures/) 

A scope in javaScript defines what variables you have access to. There are three kinds of scope – global scope and local scope and block scope. To know in-depth about how scope lookup works refer to book from series `You dont know JS from Kyle Simpson`


### [Shadowing](https://simpletutorials.com/c/2239/Variable+Shadowing+in+JavaScript)

If there's a variable in the global scope, and you'd like to create a variable with the same name in a function, that's not a problem in JavaScript.The variable in the inner scope will temporarily shadow the variable in the outer scope if you are using `var` keyword. However if you use `const` or `let` keyword then it throws error.

## [Closures](https://javascript.info/closure)


## Hoisting

## Strict Equals vs Looose Equals

## Objects 


1. Variable Scope & Closures - 

2. Hoisting - If you use "var" keyword when declaring variable then its hoisted to top and variable will be available globally. 
	   If you want variables to be in function scope then use "let" or "const"

3. Strict Equals(===) vs Loose Equals (==)

4. Objects 
	1. Creation
		1. Using object literals to create object - This is the simplest way we normally use like let cat = {Name="tom"}
		2. Using constructor - This is using new keyword
			
			function Cat(name){this.Name = name}
			let cat = new Cat("tom");


		3. Using Object.create()
		4. Using ES6 classes

	2. Creating getters and setters in javascript - (Check Object functions Object.defineProperty
	3. Making a property readonly or as not enumerable - Check Object properties Writeable,Configurable,Enumerable etc.
	4. Making objects non modifyable - Object.freeze 	

	 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object

	2. Prototypes - Thoroughly understand prototype and prototype inheritance. This will be a sure      question in any Javascript interview

	    http://www.tutorialsteacher.com/javascript/prototype-in-javascript 	

5. IIFE and How Arrow functions make IIFE easy
 https://jack.ofspades.com/es6-iife-with-fat-arrow-functions/

6. for-of and for-in statement - Don't miss this one.

7. Error handling - using try catch

8. Dictionary and Collection in javascript - Map, Set and WeakSet

9. Generators and Iterators - Thorougly understand this. This can be a sure question. Generators and Iterators are almost used everywhere in many JS libraries. Should be fairly simple to understand
if you know "yield" keyword in C#

10. ES6
    1. Arrow Functions - Most used, dont miss
    2. let,const and block scoping - Most used, dont miss
    3. Spread operator - Most used, dont miss
    4. Template Literals - Ditto of string format in new C# 7
    5. Modules in Javascript - Using Export and Import - Dont miss, very much required.
    6. Creating class in ES6 
    7. Static members in ES6 classes
    8. throw vs return
    9. Promises, async and await - Dont miss Promises. Any Ajax call returns a promise. 

11. Transpiling and Polyfilling - Important concept. Browser cannot run ES6 code so they have
    to be transpiled to browser understandable javascript. Babel is good example. 
    Some new features of plain javascript are still not understandable by old browser. For example
    some function may not be available on old browser. Then it has to be polyfilled with alternative
    code. Again babel is good example. 
    
11. Making Ajax calls
    1. Normal XmlHttpRequest Object
    2. Fetch API
    3. Axios API - (Simpler and more people using nowadays)




			