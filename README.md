#javascript basics

==> javascript is synchronous and single threded language

==> synchronous ==> it's blocking code, it will check line by line

==> single threaded ==> it will execute one task at a time

==> javscript is open source, cross platform [we acn able to run JavaScript in any browser]

==> ECMA Script ==> ECMA [european computers manufacturer association]

==> ECMA Script is a standard for javscript, based upon ecma script rules browers companies updated their own browsers

==> in javscript ther's no data types , but values have types in Javscript

==> Data Types ==> primitive, non-primitive

==> primitive ==> String, Number, Boolean, Undefined, NAN, null

==> non-primitive ==> Array, Object, RegEXp[regular expressions]

==> to check the type of any value we're using "typeof" property in JavScript

==> eg : var a =10;

<!-- console.log(a)// number -->

==> declarations in javscript  
==> we are declaring variables in three different ways
==> 1. var, 2. let , 3. const

<!-- var keyword -->
<!--

console.log(a);//undefined
var a;// initialzation
console.log(a);// undefined
a=100000000000; // assigning
console.log(a); //100000000000
var a=10;// re-declaration
console.log(a);//10
var a=99; // re-declaration
console.log(a);//99
 a=10000000; // re-assigning
console.log(a);//10000000


 -->

 <!-- let keyword -->

 <!-- // console.log(b);//"ReferenceError: Cannot access 'b' before initialization
 let b;// initalization

console.log(b)

b=100; // assigning
console.log(b)

b=999;
console.log(b)

let b=1999;
console.log(b); //"SyntaxError: Identifier 'b' has already been declared
 -->

 <!-- const keyword -->

 <!-- 
 
 // console.log(c); //"SyntaxError: Missing initializer in const declaration
// const c;
// console.log(c);//"ReferenceError: Cannot access 'c' before initialization
const c=100;
console.log(c);
const c=10;
console.log(c);//"TypeError: Assignment to constant variable.
 
  -->

  <!-- 
  
  scope==> life time visibility of variable

function ==> logical group of one or more expressions

   -->

==> hoisting ==>Hoisting is JavaScript's default behavior of moving all declarations to the top of the current scope

==> temporial deadzone ==>temporial deadzone cannot access variable before initialization ,it can only access the variable after initialization

==> scope ==> visibility of variable, area of access of an variable,

==> js code execution flow

==> closure

<!-- code space -->

==> IDE ==> Integrated development environment [visual studion code, notepad, ecclipse]


<!-- string methods -->

// var str="hello World";
// var str1="welcome"
// str.charAt(0)
// console.log(str.charAt(1)); it will specifies index of the character 

// console.log(str.indexOf("hello"));it will specifies the initial index based upon character

// console.log(str.lastIndexOf("l"))it will specifies the last index based upon character

// console.log(str.split('')); it will convert string into array of elements


// console.log(str.trim());//it will removes white spaces from strating and ending

// console.log(str.concat(str1g)); it will concatinate two strings in single

// console.log(str.toLowerCase());it will converts string into lower case

// console.log(str.toUpperCase());it will converts string into upper case


// console.log(str.replace("l","3"))it will replace the mentioned character in the initial;

// console.log(str.replaceAll("l",6));it will replace the mentioned character in all places in the string;
// slice, it will selct from one point to another point
// str=str.slice(-6,-2); 
//  console.log(str)


// let arr=[1,2,3,4,5,6]
// variable.slice(start index, end index)
// arr.slice(0,2)
// console.log(str.charCodeAt(3))

// console.log(str.includes("h"))

// console.log(str.substring(0,5))

// console.log(str.length)