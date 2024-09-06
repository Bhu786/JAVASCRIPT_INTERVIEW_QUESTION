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



# JavaScript String Questions
## Q1. Count Characters
You are given a string S, and your task is to return an array B(having a size of 2), where B[0] contains the count of
character A (uppercase) in string S and B[1] contains the count of character D (uppercase) in string S.
Note: You have to complete countCharacters function. No need to take any input.
Input Format
The first and the only line of the input contains a string S.
Output Format
Return array B as output.
Constraints
1≤|S|≤100, where |S| denotes the length of string S. S contains both lowercase and uppercase alphabets.
Example
Sample Input
AbaDd
Sample Output
1 1



```javascript

   let count=0;
   let count1=0;

   let str="AbaDd";
   for(let i=0;i<str.length;i++){
    if(str[i]=='A'){
        count++;
        }
        else if(str[i]=='D'){
            count1++;
            }

   }

   console.log(count);
   console.log(count1);




```





## Q2. Count the Heads
Tina is given a string S which contains the first letter of all the student names in her class. She got a curiosity to check how
many people have their names starting from the same alphabet. So given a string S, she decided to write a code that finds
out the count of characters that occur more than once in the string.
Note: You have to complete Count Head function. No need to take any input.
Input Format
The first and the only line of the input contains a string S (with no space and contains only lowercase letters).
Output Format
Return updated String S as output, where the string contains the charcter followed by their occurrence (if greater than 1) in
alphabetical order.
Constraints
1≤|S|≤100, where |S| denotes the length of string S. S contains only lowercase alphabets.
Example
Sample Input
prepbytes
Sample Output
e2p2





```javascript

let str="prepbytes";






```






## Q3. Count the Vowels
You are given a string S containing both uppercase and lowercase letters. You need to find out the number of vowels in the
given string.
Note: You have to complete Count_Vowel function. No need to take any input.
Input Format
The first and only line of the input contains string S.
Output Format
Return the number of Vowels in the string S as output.
Constraints
1≤|S|≤100, where |S| denotes the length of string S.
Example
Sample Input
Prepbytes
Sample Output
2



```javascript

  let str="wefuhKJBJBndnnefiejfjefn";
  function countVowel(str) {
    let count = 0;
    for (let i = 0; i < str.length; i++) {
           if(str.Uppercase(str[i])){
        if (str[i]=="A"||str[i]=="I"||str[i]=="O"||str[i]=="U"||str[i]=="E"){
            count++;
        }

           }

          
    }
 return count;
  }

  console.log(countVowel);


```



## Q4. Concatenate the Strings
You are given two strings S1 and S2 (containing both uppercase and lowercase letters), You need to retrun a string which is the
concatenation of both the given strings.
Note: You have to complete Concatenate_Strings function. No need to take any input.
Input Format
The first line of the input contains the first string S1 and the second line of input contains the second string S2.
Output Format
Return the String S3 as output, which is the concatenation of given both strings.
Constraints
1≤|S1|,|S2|≤100, where |S|denotes the length of string S.
Example
Sample Input
Prep bytes
Sample Output
Prepbytes


```javascript

let str="ram";
let str2="bytes";
function Concatenate_Strings(str,str2) {
    return str+str2;
    }
    console.log(Concatenate_Strings(str,str2));





```



## Q5. Find Length
You are given a string S, and your task is to return the length of the string S.
Note: You have to solve it without using length method. You have to complete findLength function. No need to take any input.
Input Format
The first and the only line of the input contains a string S.
Output Format
Return the length of the string S.
Constraints
1≤|S||≤100, where |S| denotes the length of string S. S contains both lowercase and uppercase alphabets.
Example
Sample Input
CeDqe
Sample Output
5




```javascript


     let str="hello";
     console.log(str.length);




```




## Q6. Find the Winner
You are given a string S consisting of two letters A and D,where each character represent the winner of N games played between Aditya
and Danish, where letter A represents the win of Aditya and letter D represents the win of Danish. You need to find out the that which
player wins the maximum number of games or there is a draw between them.
Note: You have to complete Game_Winner function. No need to take any input.
Input Format
The first and only line of the input contains string S.
Output Format
Return the name of the player who have won the maximum number of games, if both player won same number of games return Draw.
Constraints
1≤|S|≤100, where |S| denotes the length of string S.
Example
Sample Input 1
ADDAAADDDDD
Sample Output 1
Danish
Sample Input 2
ADDAAADD
Sample Output 2
Draw





```javascript







```






## Q7. Join Strings
You are given two strings S and P, and your task is to concatenate them and return the concatenated string.
Note: You have to complete joinStrings function. No need to take any input.
Input Format
The first and the only line of the input contains two space-separated strings S and P.
Output Format
Return the final concatenated string.
Constraints
1≤|S|,|P|≤100, where |S|and |P| denote the length of string S and P, respectively. S and P contain both lowercase and uppercase
alphabets.
Example
Sample Input
PrepBytes Technologies
Sample Output
PrepBytesTechnologies




```javascript
function joinStrings(S, P) {
    return S + P;
}


let ans=joinStrings("ram","shyam");
console.log(ans);




```





## Q8. Plaindrome Check
You are given a string S, Your task is to check wether the given string is a Palindrome or not.
A Palindrome is a string, which turnout same when read in reverse direction. Example: "naman" is a Palindrome. String can contain
both upppercase lowercase letters.
Note: You have to complete Plain_Check function. No need to take any input.
Input Format
The first and the only line of the input contains a string S.
Output Format
Return "True" if the given string is Palindrome else return "False" (without " ") .
Constraints
1≤|S|≤100, where |S| denotes the length of string S. S contains both lowercase and uppercase alphabets.
Example
Sample Input 1
Naman
Sample Output 1
False
Sample Input 2
naman
Sample Output 2
True




```javascript

let str="Naman";
let str1="";
let i=str.length-1;

while(i>=0)
{
    str1=str1+str[i];
    i--;
    }
    if(str==str1)
       {
        console.log(true);
        }






```







## Q9. Reverse the String
You are given a string S, Your task is to Reverse the string. String can contain both upppercase lowercase letters. Note: You have to
complete Reverse_String function. No need to take any input.
Input Format
The first and the only line of the input contains a string S.
Output Format
Return the reversed String.
Constraints
1≤|S|≤100, where |S| denotes the length of string S. S contains both lowercase and uppercase alphabets.
Example
Sample Input
I am utkarsh raj
Sample Output
jar hsraktu ma I





```javascript

let str="hello";
let str1="";
let i=str.length-1;
while(i>=0)
{
    str1=str1+str[i];
    i--;
    }
    console.log(str1);





```






## Q10. Match the Strings
You are given two strings S1 and S2, Your task is to print YES if both strings are same else print NO.
Note: You have to complete String_Match function. No need to take any input.
Input Format
The first line of the input contains a string S1. The second line of the input contains a string S2.
Output Format
Return YES if S1 and S2 are same, else return NO.
Constraints
1≤|S1|,|S2|≤100, where |S| denotes the length of string S. S1 and S2 contains both lowercase and uppercase alphabets.
Example
Sample Input
Prepbytes Prepbytes
Sample Output
YES





```javascript







```







## Q11. String Replace
You are given a string S, along with a pattern string and a text string. You need to repalce the pattern string in S to the text string.
Note: You have to complete Replace function. No need to take any input.
Input Format
The first and the only line of the input contains a string S.
Output Format
Return updated String S as output.
Constraints
1≤|S|≤100, where |S| denotes the length of string S. S contains both lowercase and uppercase alphabets.
Example
Sample Input
Hi, I am You. You Prepbytes
Sample Output
Hi, I am Prepbytes.





```javascript







```








## Q12. Split the String
You are given a string S, Your task is to split the string with respect to spaces.
Note: You have to complete Split_the_String function. No need to take any input.
Input Format
The first and the only line of the input contains a string S.
Output Format
Return the array of splitted strings of S.
Constraints
1≤|S|≤100, where |S|denotes the length of string S. S contains both lowercase and uppercase alphabets.
Example
Sample Input
I am utkarsh raj
Sample Output
I
am
utkarsh
raj



```javascript

// we used split function

  let str="I am utkarsh raj";
  let result=str.split(" ");
  console.log(result);





```















## Q13. Count the Vowels and Consonants
You are given a string S containing both uppercase and lowercase letters. You need to find out the number of vowels and the number of
consonants in the given string.
Note: You have to complete Count_Vowels function and Count_Consonants function. No need to take any input.
Input Format
The first and only line of the input contains string S.
Output Format
Return the number of Vowels and the number of Consonants in the string S in the functions.
Constraints
1≤|S|≤100, where |S|denotes the length of string S.
Example
Sample Input
Prepbytes
Sample Output
2 7





```javascript


 let str="wefuhKJBJBndnnefiejfjefn";

    let count = 0;
    let count1=0;
    for (let i = 0; i < str.length; i++) {
           if(str.Uppercase(str[i])){
        if (str[i]=="A"||str[i]=="I"||str[i]=="O"||str[i]=="U"||str[i]=="E"){
            count++;
        }else{
            count1++;
        }

           }
    }

          
  console.log(count);
  console.log(count1);






```
---
---
---














