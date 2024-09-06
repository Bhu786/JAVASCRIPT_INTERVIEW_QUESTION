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

# JavaScript Array
## Q1. Find the Product.
Write a program that takes an array as input from the user and find out the product of the elements.
Note: You have to complete Find_Prod. No need to take any input.
Input Format
The input contains a single number N, followed by N numbers as array elements.
Output Format
Return the required answer.
Constraints
1≤N≤201≤ElementoftheArray≤100
Example
Sample Input
5 1 2 3 4 5
Sample Output
120



```javascript

   let arr=[5,2,5,66,7];
// 
  let product=arr.reduce((acc,current)=>acc*current);

  console.log(product);


```





## Q2. Find the Sum.
Write a program which takes an array as input from the user and find out the sum of the array elements.
Note: You have to complete Find_Sum. No need to take any input.
Input Format
The input contains a single number N, followed by N numbers as array elements.
Output Format
Return the required answer.
Constraints
1≤N≤1001≤ElementoftheArray≤1000
Note: You have to complete Find_Sum function. No need to take any input.
Example
Sample Input
5 1 2 3 4 5
Sample Output
15




```javascript

  let arr=[5,2,5,66,7];
// 
  let product=arr.reduce((acc,current)=>acc+current);

  console.log(product);


```




## Q3. Count Occurrences
You are given an array A containing N integer elements and an integer K, and your task is to return the count of
occurrences of K in array A.
Note: You have to complete findCount function. No need to take any input.
Input Format
The first line of the input contains two space-separated integers N and K, denoting the number of elements in the array A
and the element whose count needs to be determined, respectively. The second line of the input contains N space-separated
integers, denoting the elements of the array A.
Output Format
Return the count of occurrences of K in array A.
Constraints
1≤N≤1001≤K≤1001≤Ai≤1000≤100
Example
Sample Input
4 3 3 3 1 2
Sample Output
2




```javascript

let arr=[4,3,3,3,1,2];
let k=3;
let count=0;

  for(let i=0;i<arr.length;i++){
    if(arr[i]==k){
        count++;
    }
  }
console.log(count);



```



## Q4. Even Odd
You are given an array A containing N integer elements, and your task is to return an array B ((having a size equal to 22)),
where B[0] contains the sum of all even elements of array A and B[1] has the sum of all odd elements of the array A.
Note: You have to complete findEvenOdd function. No need to take any input.
Input Format
The first line of the input contains an integer N, denoting the number of elements in the array A. The second line of the input
contains N space-separated integers, denoting the elements of array A.
Output Format
Return array B as output.
Constraints
1≤N≤1001≤100 0≤Ai≤1000≤100
Example
Sample Input
7 1 2 3 4 5 6 7
Sample Output
12 16


```javascript


let arr=[2,4,3,6,9,1,7,33];

    let even=0,odd=0;
    for(let i=0;i<arr.length;i++){
        if(arr[i]%2==0){
            even+=arr[i];
            }
            else{
                odd+=arr[i];
                }
    }


console.log(even );
console.log(odd );
    






```




## Q5. Find whether the number is present or not
Write a program which takes an array as input from the user and a number. Check whether the number is present or not.
Note: You have to complete Find_Num. No need to take any input.
Input Format
The first line contains an integer N, denoting the size of the array. The second line contains N space-separated integers,
denoting the elements of the array. The third line contains an integer M, denoting the element that needs to be searched.
Output Format
Return the "YES" (without quotes) else return "NO" (without quotes).
Constraints
1≤N≤1001≤ElementoftheArray≤1000
Example
Sample Input
5 1 2 3 4 5 2
Sample Output
YES



```javascript

   
   let arr=[5,6,3,8,9,3];
   let num=3;
   function Find_Num(arr,num){

    for(int i=0;i<arr.length;i++){
        if(arr[i]==num){
            return "YES";
        }
    }
    return "NO";

   }

console.log(Find_Num);


```




## Q6. Higher Age
You are given an array A containing the age of persons in your locality, and your task is to find and return an array
containing the age of persons that are over 1818 (18(18 included)).
Note: Also, in the output array, the age should be in the same order as in the input array. You have to complete highAge
function. No need to take any input.
Input Format
The first line of the input contains an integer N, denoting the number of person in your locality. The second line of the input
contains N space-separated integers, denoting the age of persons in your locality.
Output Format
Return the array containing the age of persons that are over 1818 (18(18 included)).
Constraints
1≤N≤1001≤100 0≤Ai≤1000≤100
Example
Sample Input
6 11 23 3 45 72 68
Sample Output
23 45 72 68




```javascript



  let arr=[6,22,4,45,78,88];

  let ans=arr.filter(ele=>ele>18);
  console.log(ans);







```




## Q7. Increment the Array Elements
You are provided an array of integers and you have to increment all array elements by 1 and then print whole array.
You have to complete Inc_Arr. No need to take any input.
Input Format
The input contains a single number N, then N array elements as input.
Output Format
Print the required answer in the function itself.
Constraints
1≤N≤1001≤ElementoftheArray≤1000
Example
Sample Input
5 1 2 3 4 5
Sample Output
2 3 4 5 6



```javascript

  let arr=[1,2,3,4,5,6,7];

  let ans=arr.map(ele=>ele+1);
  console.log(ans);
    




```



## Q8. Pass or Fail
You are given an array A containing the maths marks of students in your class, and your task is to determine if all the
students pass in your class or not. A student is declared pass if his maths marks are greater than or equal to 3232.
If all the students pass in your class, return "YES" (without quotes); otherwise, return "NO" (without quotes).
Note: You have to complete isAllPass function. No need to take any input.
Input Format
The first line of the input contains an integer N, denoting the number of students in your class. The second line of the input
contains N space-separated integers, denoting the maths marks of students in your class.
Output Format
Return "YES" (without quotes) if all the students pass in your class; other wise, print "NO" (without quotes).
Constraints
1≤N≤1001≤100 0≤Ai≤1000≤100
Example
Sample Input
7 13 89 45 98 67 45 54
Sample Output
NO



```javascript


  let arr=[3,56,643,67,24,64,65,33];

  let ans=arr.reduce((acc,curr)=>acc+curr);
  if(ans>=3232){
    console.log("yes");
  }else{
    console.log("no");
  }





```




## Q9. Unique Color Shirt
Prepbuddy is very tasteful of clothes. He has N numbers of shirts hanging in the hanger in his wardrobe. Prepbuddy likes to
wear different colored clothes. So, whenever he see there are two or more shirts with the same color, he removes all the shirt
of that color from his wardrobe. Now, he wants to know how many M unique color shirts are left in the wardrobe. Prepbuddy
wants you to find M.
Note: As there are many shades of a color so consider integers as a color name. i.e, color of shirt is 0,1,2, … , N.
Input Format
The first line of the input contains an integer N denoting the number of shirts in the wardrobe. The second line of the input
contains N integers C1,C2,C3,C4,...,CN1,2,3,4,..., color of shirts (separated by space).
Output Format
Return a single integer M denoting the unique colored shirts left in the wardrobe.
Constraints
1<=N<=1031<=103 1<=C[i]<=1031<=[]<=103
Example
Input
6 3 2 4 1 2 3
Output
2
Sample test case explanation
Input: C=3, 2, 4, 1, 2, 3
Output: 2



```javascript

  let arr=[5,6,2,7,6,5];

  

    
    


```




There are two 2-color shirts, and two 3-color shirts. So, after removing 2-color and 3-color shirts, the remaining shirts are one
4-color shirt and one 1-color shirt i.e, 4, 1.
Hence, the output will be 2.



Q10. Min and Max
Congratulations on making up to this question. Let us give you a fairly simple array problem to solve. If you know how to
iterate through the array, you will easily be able to solve this. The problem statement is simple- given N elements, find the
minimum and maximum numbers among those elements.
Input format
First-line contains N representing the length of the array. The second line contains N space-separated integers.
Output format
Return minimum and maximum elements.
Constraints
1<=N<1071<=<107 0<=A[i]<=1070<=[]<=107
Example
Input
66 33 11 44 66 22 77
Output
11 77
Sample Test Case Explanation
In the first test case minimum element = 11 and maximum element = 77
In the second test case minimum element = 00 and maximum element = 00


```javascript

 let arr = [34, 45, 343, 2, 66, 2, 222];

let min = Math.min(...arr);
let max = Math.max(...arr);

console.log(min);
console.log(max);





```


---
---
---












