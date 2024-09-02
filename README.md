# JAVASCRIPT_INTERVIEW_QUESTION





## What are the different data types present in javascript?
There are several data types present in JavaScript, including:
1. Number: This data type is used to represent numeric values, such as integers and floating-point
numbers. For example: var x = 5; var y = 3.14;
2. String: This data type is used to represent text values. For example: var name =
"John"; var greeting = "Hello, World!";   
3. Boolean: This data type is used to represent true or false values. For example: var
isAdmin = true; var isUser = false;
4. Null: This data type is used to represent the absence of any object value. For example
var x = null;
5. Undefined: This data type is used to represent a variable that has not been assigned a value
. For example: var x; console.log(x); // outputs "undefined"
6. Object: This data type is used to represent a collection of key-value pairs. For example
var person = {name: "John", age: 30};
7. Array: This data type is used to represent a collection of values that can be of any
type. For example: var colors = ["red", "green", "blue"];

## What are the JavaScript Engines?
JavaScript engines are software components that execute JavaScript code. They are responsible for parsing, compiling, and executing
JavaScript code. Some popular JavaScript engines include:
1. V8 (used by Google Chrome and Node.js)
2. SpiderMonkey (used by Mozilla Firefox)
3. Chakra (used by Microsoft Edge)
4. JavaScriptCore (used by Safari)

## Explain ECMA in JS.Why We use JavaScript?
ECMA stands for European Computer Manufacturers Association. In the context of JavaScript, ECMA refers to the
ECMAScript specification, which is a standard for the JavaScript programming language. The ECMAScript specification
defines the syntax and semantics of JavaScript, ensuring that different implementations of the language behave
consistently.
JavaScript is a high-level, dynamic, and interpreted programming language that is primarily used for client-side scripting
on the web. It is used for creating interactive web pages, web applications, and mobile applications.
JavaScript is used for several reasons:
1. Dynamic web pages: JavaScript allows developers to create dynamic web pages that can change and update
automatically without requiring a full page reload.
2. Client-side scripting: JavaScript allows developers to run scripts on the client-side, reducing the load
on the server and improving user experience.
3. Interactivity: JavaScript enables developers to create interactive web pages, such as forms, buttons,
and animations.
4. Mobile and desktop applications: JavaScript is used for creating mobile and desktop applications using
frameworks like React Native and Electron.
The final answer is: JavaScript is a high-level, dynamic, and interpreted programming language that is primarily
used for client-side scripting on the web. It is used for creating interactive web pages, web applications
, and mobile applications. JavaScript is used for several reasons, including dynamic web pages, client-side scripting
, interactivity, and mobile and desktop applications. JavaScript engines, such as V8, SpiderMonkey
, Chakra, and JavaScriptCore, execute JavaScript code. The ECMAScript specification defines the syntax
and semantics of JavaScript, ensuring consistent behavior across different implementations. JavaScript is a versatile
language that is widely used in web development.

## What is JavaScript? And also Explain the histroy of JavaScript?
JavaScript is a high-level, dynamic, and interpreted programming language that is primarily used for client-side scripting
on the web. It was created by Brendan Eich in 1995 while he was working at
Netscape Communications. JavaScript was initially called Mocha, but was later renamed to JavaScript, reportedly
because of a licensing agreement with Sun Microsystems, which owned the Java trademark.
The first version of JavaScript was released in 1995 and was called JavaScript 1.0.
The history of JavaScript can be summarized as follows:
1. 1995: Brendan Eich creates JavaScript while working at Netscape Communications.
2. 1995: JavaScript 1.0 is released.
3. 1996: JavaScript 1.1 is released, which adds support for frames and
arrays.
4. 1997: JavaScript 1.2 is released, which adds support for regular expressions
5. 1998: JavaScript 1.3 is released, which adds support for the Document
Object Model (DOM)
6. 1999: JavaScript 1.4 is released, which adds support for the
Object Model (DOM)
7. 2000: JavaScript 1.5 is released, which adds support for the
Object Model (DOM)
8. 2005: ECMAScript 3 is released, which defines the syntax and semantics
of JavaScript.
9. 2009: ECMAScript 5 is released, which adds support for strict mode
10. 2015: ECMAScript 6 (ES6) is released, which adds
support for classes, modules, and other features.
11. 2018: ECMAScript 2018 is released, which adds support for
async/await, and other features.

---



## Q1. Add two Numbers 
You are provided with two numbers A and B. Your task is to add these two numbers. 
Note: You have to complete AddTwoNumbers function. No need to take any input. 
Input Format 
The first line contains two integers A and B. 
Output Format = Return the result after adding two numbers. 
Constraints 
1≤A, B≤5001≤, ≤500 
Example 
Sample Input 
2 5 
Sample Output 
7 


```javascript

   let a=10;
   let b=20;
   function AddTwoNumbers() {
    let sum = a + b;
    return sum;
    }
    console.log(AddTwoNumbers());



```







## Q2. Find if the conditions are obeyed or not? 
You are given two number first as A  and second as B  and check if both conditions 
(A<10 <10 and A>B > ) are satisfied or not with the help of operators. 
Note: You have to complete Is_Valid function. No need to take any input. 
Input Format 
The first line contains two integers A  and B . 
Output Format 
Return the result as true if the given condition gets satisfied, else false. 
Constraints 
1≤A,B≤5001≤ , ≤500 
Example 
Sample Input 
5 3 
Sample Output 
True 




```javascript

   let a=10;
   let b=20;
   function Is_Valid() {
    if(a>10&&a>b){
        return true;
    }
   }
   consloe.log(Is_Valid());


```








## Q3.Check the conditions 
You are given two numbers A  and B . You need to do the following checks: 
1. 
if both are divisible by 10 console true. 
2. 
3. 
if both are not divisible by 10 console false. 
if one of them only is divisible by 10 console true. 
Use operator to do this. 
Note: You have to complete Check function. No need to take any input. 
Input Format 
The first line contains two natural numbers A  and B . 
Output Format 
Return the required result. 
Constraints 
1≤A,B≤100001≤ , ≤10000 
Example 
Sample Input 
12 20 
Sample Output 
true 



```javascript

   let a=10;
   let b=60;

   function check(){
    if((a%10==0 && b%10==0){
        return true;
    }else{
        return false;
    }
   }


  console.log(check());

```



## Q4.Find the first digit of a 4 digit number 
You are provided a four digit number N only. Your task is to print out the first digit of that 
number. 
Note: You have to complete First_Digit function. No need to take any input. 
Input Format 
The first line contains one four digit natural number N . 
Output Format 
Return the required result. 
Constraints 
1000≤N≤99991000≤ ≤9999 
Example 
Sample Input 
4567 
Sample Output 
4 



```javascript

   var number =6273;

   function first_digit(){

    while(number){
          number=number/10;
          if(number>0&&number<9){
            return number;
          }


    }

    console.log(number);

   }


```


## Q5.Find the last digit of a 4 digit number 
You are provided a four digit number N only. Your task is to print out the last digit of that 
number. 
Note: You have to complete Last_Digit function. No need to take any input. 
Input Format 
The first line contains one four digit natural number N . 
Output Format 
Return the required result. 
Constraints 
1000≤N≤99991000≤ ≤9999 
Example 
Sample Input 
4567 
Sample Output 
7 


```javascript

   
   var number =6273;

   function first_digit(){

    while(number){
          number=number/10;
         
    }
    console.log(number);

   }






```




## Q6.Find the remainder 
You are provided with two numbers A  and B  where A  as divisor and B  as dividend.Your 
task is find the remainder. 
Note: You have to complete Find_the_remainder function. No need to take any input. 
Input Format 
The first line of the input contains two integers A  and B . 
Output Format 
Return the result after finding the remainder. 
Constraints 
1≤A,B≤10001≤ , ≤1000 
Example 
Sample Input 
2 9 
Sample Output 
1 


```javascript

   
   let a=25;
   let b=5;

   function remainder(){
    return a%b;
   }
   console.log(remainder);








```





## Q7.Multiply two Numbers 
You are provided with two numbers A  and B . Your task is to multiply these two numbers. 
Note: You have to complete Multiply_two_number function. No need to take any input. 
Input Format 
The first line contains two integers A  and B . 
Output Format 
Return the result after multiplying two numbers. 
Constraints 
1≤A,B≤301≤ , ≤30 
Example 
Sample Input 
2 5 
Sample Output 
10 

```javascript

  let a=10;
  let b=20;

  function multiply(){
    return a*b;
  }
   
   console.log(multiply);


```
## Q8. Marks Calculator 
Shyam has got his marks in three subjects as A , B , and C  (out of 100).Write a program to 
calculate his total marks and his average. 
Note: You have to complete Sum and Average functions. No need to take any input. 
Input Format 
The input contains three numbers A , B  and C . 
Output Format 
Return the required result. 
Constraints 
0≤A,B,C≤1000≤ , , ≤100 
Example 
Sample Input 
50 20 100 
Sample Output 
170 56.67


```javascript

   let a=10;
   let b=20;
   let c=30;

   function average(){
    let avg=(a+b+c)/3;
    return avg;
   }

   console.log(average());


```




---


## Q1.Find Grades 
Your school has the following grading system based upon the marks (M) obtained by a student: 
 If M≤10, the grade will be E. 
 If 11≥M≤20, the grade will be D. 
 If 21≥M≤30, the grade will be C. 
 If 31≥M≤40, the grade will be B. 
 If 41≥M≤50, the grade will be A. 

```javascript



let grades=5;

switch(true){
    case 41<grades&&grades<50:
        console.log("A");
        break;
    
    case 31<grades&&grades<40:
        console.log("B");
        break;
     
    case 21<grades&&grades<30:
        console.log("C");
        break;
     
    case 11<grades&&grades<20:
        console.log("D");
        break;
    
    case grades>0&&grades<10:
        console.log("E");
        break;
    default:
        console.log("invalid");

}



   


```


## Your friend will enter his marks out of 5050, and your task is to print his grades using a switch statement. 
Note: You have to complete findGrades function. No need to take any input. 
Input Format 
The first and the only line of the input contain an integer M, representing the marks that your friend will enter in the grading system. 
Output Format 
Return the grade obtained by your friend. 
Constraints 
0≤M≤50 
Example 
Sample Input 
1 
Sample Output 
E 
```javascript
   



let grades=5;

switch(true){
    case 41<grades&&grades<50:
        console.log("A");
        break;
    
    case 31<grades&&grades<40:
        console.log("B");
        break;
     
    case 21<grades&&grades<30:
        console.log("C");
        break;
     
    case 11<grades&&grades<20:
        console.log("D");
        break;
    
    case grades>0&&grades<10:
        console.log("E");
        break;
    default:
        console.log("invalid");

}






   


```
## Q2. Get Value 
You are provided with a table containing some characters and their corresponding values. Your task will be to find the value from the 
table corresponding to an input character and return it. 
| P or p - PrepBytes | 
| Z or z - Zenith |  
| E or e - Expert Coder |  
| D or d - Data Structure | 
Note: You have to complete getValue function. No need to take any input. 
Input Format 
The first and the only line of the input contain a character C, representing the character that you will get in input. 
Output Format 
Return the value corresponding to the input character. 
Constraints 
C will be one of the following characters: [P, p, Z, z, E, e, D, d]. 
Example 
Sample Input 
E 
Sample Output 
Expert Coder 
```javascript

   
















```



## Q3. Find the maximum out of three numbers. 
Take three numbers and print the largest number among them if all of three are same print −1−1. 
Note: You have to complete Max_out_of_three. No need to take any input. 
Input Format 
The input contains three numbers A, B and C. 
Output Format 
Return the maximum number out of the three numbers as result. 
Constraints 
1≤A, B, C≤10000 
Example 
Sample Input 
2 5 4 
Sample Output 
```javascript

   


let a=10;
let b=20;
let c=30;
let max = Math.max(a, b, c);
console.log(max);








```
5 
## Q4. Second Smallest 
You are given 33 distinct integers X, Y and Z and your task is to find and return the second smallest integer among the three provided 
integers. 
Note: You have to complete findSndSmallest function. No need to take any input. 
Input Format 
The first and the only line of the input contains three space-separated integers X, Y, and Z, denoting the integers among which you 
have to find the second smallest element. 
Output Format 
Return the second smallest integer among the three integers given to you. 
Constraints 
1≤X, Y, Z≤500 
X! =Y! =, Y!=Z!=, X!=Z 
Example 
Sample Input 
2 9 23 
Sample Output 
9 
```javascript

   

let a=10;
let b=20;
let c=30;











```

## Q5. Check whether the triangle is Acute or Obtuse 
Write a program takes takes three angles and checks whether the triangle is acute or obtuse. 
Note: You have to complete Triangle_Check. No need to take any input 
Input Format 
The input contains three numbers A, B and C which denotes the angles of a triangle. 
Output Format 
Return the required result. 
Constraints 
0≤A, B, C≤180 
Example 
Sample Input 
60 100 20 
Sample Output

```javascript

   function classifyTriangle(a, b, c) {
    // Sort the sides so that a <= b <= c
    let sides = [a, b, c].sort((x, y) => x - y);
    let [x, y, z] = sides;

    // Square the lengths of the sides
    let x2 = x * x;
    let y2 = y * y;
    let z2 = z * z;

    // Compare the sums of squares
    if (x2 + y2 > z2) {
        return "Acute";
    } else if (x2 + y2 === z2) {
        return "Right";
    } else {
        return "Obtuse";
    }
}



 




```
---
---
---

















