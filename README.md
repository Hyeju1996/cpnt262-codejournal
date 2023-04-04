# code Journal of CPNT262 for class.

## Feb 06,2023 Monday 

- title: Intro.js
- we are learning about Intro.js which mean how to add JavaScript file in to HTML and make it work.

## prove of work:
[Hello-world] (https://github.com/Hyeju1996/262-achivement1);

## How you did: 

 In **index.html** file, try to add JavaScript file **app.js**. 
 For example: 
<title> Hello-world</title>
<script src = "js/app.js" type= "module"></script>
hit save!!

### prep of class
[slides of preb](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-introduction.html)

# Feb 07, 2023 Tuesday
## Varibles-erros

-  Today, we are talked about varibles-erroes. What is varible erroes mean? varible erroes mean the varibility of a subkact's eslimates of an objective magnitude meassured by their average deviation.

- Secondly, in JavaScript file call app.js we put varibles.
Example: 

```
//strings
let lunch = "sushie";
console.log(lunch);

//numbers
let ag = 47;
console.log(age);

age = 48;
console.log(age);

// let Booleans
let hungry = true;

if (hungry) {
    console.log(Time for more lunch!);
}

// Null
let foofInStomach = null;
console.log(foodInStomach);
```
- check of this github live [gitHub](https://github.com/sait-wbdv/dailies-w23/blob/main/2023-02-07-variables-errors/02-primitive-types/js/app.js)

## prove of work
[Achivement2](https://github.com/Hyeju1996/cpnt262_achivement2)
[desktop] (https://hyeju1996.github.io/cpnt262_achivement2/)

## preb of Febuary 7,20203
[slides-prep](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-variables.html)
[handling-erroes](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-errors.html)

MDN:
shttps://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Variables
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Strings
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals

## take it look for video
- [1hours learning JavaScript](https://youtu.be/W6NZfCO5SIk)
- [varibles](https://youtu.be/W6NZfCO5SIk)
- [Primitive Types](https://youtu.be/W6NZfCO5SIk)

# Feb 08,2023 Wedsnday

## Numbers and Arithmetic Operators

- Today we learn about bug huting. Which mean sometimes when you type JavaScript in Desktop of console show you errors.It means its not good sign. 
- What we working on today, when Tony give us work todo, and when we see it got lots of errores and bugs around it, so we need to look at **console** which line gets errores in VScode.

## prep of class today:
[slide1](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-useful-objects.html)
[slide2](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-numbers-math.html)

## prep of MDN:
[MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps)
[Basic math in JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Math)

## video to watch
[JavaScript For Beginner](https://youtu.be/TD3Pfuxgnuc)

## Achivement today:
[Achivement-3](https://github.com/Hyeju1996/cpnt262-achivement3)
[GitHub live](https://hyeju1996.github.io/cpnt262-achivement3/)



# Feb,10,2023  Friday
## Process Flowcharts

Today we are learn about flowchart, why we learn this because in real life of work, 
you make websites for customer and you need to explaining about it. 

## important to know:
When you start flowchart, always "start" is first of symbole.

## Preb 
[slides](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-flowcharts.html)

### Important to know:

1. Always have to add "start" and "end" in rounded rectangle.
2. Input/Output shape need to parallelogram.
3. indicate a menual operation is needed.
4. when you want a "Decision" shape is should be rhombus or diamond.
5. Outcome is a Yes or no 
6. In Gereral: yes should be go left and no should go down.
7. "Sub-process" has to be indicate an independent process with its own start and end.

## prep:
![img_6496_720](https://user-images.githubusercontent.com/56320722/221997676-69684fd1-1b08-41fa-bdf7-15a4c943b6e7.png)



# Feb 17,2023 Friday
## Booleans and Conditional Code

Today we learned about booleans and Conditional code. How it works example, you only use 
"if" "else if" "else".

## Example of code
```
if (Day === Mon && dinner){
    answer = "Chickenh"
}
else if (condition){
    answer = "dog"
}

else if 
```
## Preb
[slide1](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-conditional-code.html)
[slide2](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-forms.html)

## Daily of work:
[Today of code](https://github.com/sait-wbdv/dailies-w23/tree/main/2023-02-17-conditional-code)


# Feb,21,2023 Tuesday
## Logical Operators and Type Validation

Today, we are review about conditional with if... else.. statement.
Also, we are talking about spoilers with number Range too.

[review slides](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-conditional-code.html)
[stater code](https://github.com/sait-wbdv/dailies-w23/tree/main/2023-02-17-conditional-code/01-achievement-6-starter)
[value Vailation slides](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-value-validation.html)
Tony give us example code about flowchart: How to make tea.

# Feb 22,2023




# March 01,2023 Wednsday
## Function return statements

Today, we learn about function return statement and Tony gave us code call "greeting".
Aslo, he gave us assignment4 and we need to creating our self of imagination with function code.
Other fact, he was talking about **console.log()** code has to be outside of function. Therefore, 
"function return statement" is you should put 
```
const gstRate = 0.05

const calculateGST = function(subTotal) {

  // Use of `gstRate` makes this an impure function because
  // it's not passed as an
  const gst = subTotal * gstRate;
  const total = subTotal + gst;

  // console.log(`$${subTotal} plus ${gstRate * 100}% GST is $${total.toFixed(2)}.`);
  return `$${subTotal} plus ${gstRate * 100}% GST is $${total.toFixed(2)}.`;
}

// Sub Total 1
const subTotal1 = 40;
const paymentSummary1 = calculateGST(subTotal1);

console.log(paymentSummary1);

// Sub Total 2
const subTotal2 = 55;
const paymentSummary2 = calculateGST(subTotal2);

console.log(paymentSummary2);

// Sub Total 3
const subTotal3 = 32.45;
const paymentSummary3 = calculateGST(subTotal3);

console.log(paymentSummary3);
```
Than you need to do 
<img width="1728" alt="Screenshot 2023-03-01 at 11 05 46 AM" src="https://user-images.githubusercontent.com/56320722/222224692-3984f9dd-e261-4d31-9cc3-6eaf9b13679a.png">

Secondly, he told us about when we all master of basic JavaScript, we are doing lots of math stuff, and will be know more.
He pushes GitHub and pull and than add some file of JavaScript.

1. We are runing debugging in to VSCode and see why our code is undefined, and why calculateGST  get some result.
## Tony's code:
[Tony's code](https://github.com/sait-wbdv/dailies-w23/tree/main/2023-03-01-pure-functions)

## activity of achivements 10g:
https://gist.github.com/acidtone/6b27ecd6f5cdb05e57f93a5f137dcb2f#file-capitalize-js
## Instruction: 
1. Copy the code you choose what Tony gave us activity.
2. Fix the code what you have to do than you can submit the drop box of achivement 10.

This is all of the JavaScript do, and this is the class today and 
-the end-.
## preb
[function](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-functions.html)

## MDN
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Build_your_own_function'
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Return_values

## video
https://www.youtube.com/watch?v=qed2cjdF-30&feature=youtu.be
### The homework:
1. read the Loops to read and we are going to have test.
2. Assignment4 creating index.html with function and if... else... else if condtion statment.

## challange:
Today of achivement 10 I need to make function, but I have bit challange about I need to make return code too.

# March 03,2023 Friday
Today, I am going to working on Assignment4 of CPNT 262. Its next week of Thursday March 09,2023 but I want a thinking about 
how to creating JavaScript and more time to think about figire it out the JavaScrip of function.

## plans of making website today.
1. Make file Index.html 
2. Add JS folder, and add app.js file.
3. started JavaScript code tomorrow

## concept to doing it:
- title: Return a conditional result
- code of function:

```
function example() {
    if (condition1){
        return value1;
    } else if (condition2) {
        return value 2;
    }
}
```

# March 8, 2023 Wednsday
## CPNT 262- The `for` loops

- If you create function after, you always need to put return values. Otherwise, you can also running code.
- The for loop is ubiquitous in the programming world. Almost every programming language has one and many employers will use a for loop challenge in their hiring process.

## prep of power point: 

- [for Loop](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-for-loops.html)

## prove of work: 
[Achivement11](https://github.com/Hyeju1996/CPNT262--Achievement-11);

## description: 

- This time, achivement 11 is group project and using "Fizz, Buzz" with `for` loop and print 1 to 100. 

# March 08,2023 Thursday
## Arrays and array methods

- Javascript Arrays Nerds start counting at 0

## prep: 
[power point](https://sait-wbdv.github.io/slides/w23/cpnt-262/js-arrays.html)









