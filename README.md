# Basics-of-Javascript-with-comments
Here is one of the best source to learn javascript basics with comments.
console.log('Wellcome to the Java script');// print this in single inverted in inspect console
alert ('Move on shivam');// Popup this message.  variables
 var b = 'Learn js'
 console.log(b);
 var sumNumber = 45;
 console.log(sumNumber); 
 document.getElementById('some text').innerHTML= 'Har har Mahadev';//join to the html file 
var age = prompt('What is your age?')
console.log(age);// It shows age in Inspect console you entered.
document.getElementById('some text').innerHTML= age;// it shows age on screen you entered.
// Number
var num1 = 10;
//Increment Number.
num1++;
console.log(num1);
// Decrement Number.
num1--;
console.log(num1);
// Devide / multipy* and remainder%
console.log(num1%3);
console.log(num1*5);
console.log(num1/5);
// Increment and decrement by any number
num1+=20;
console.log(num1);
num1-=6;
console.log(num1);

/*Functions
1.Create a function
2.Call the function.
*/
//Create a function.
function fun(){
    alert('This is a function');

}
fun();// call a function

/* Let's create a function that take in a name
and says hello followed by your name
For example
Name : "Jayesh"
Return: "Hello Jayesh"
 */
function greeting(){
   var name= prompt('What is your name?');
   var result= 'Hello' + ' ' + name; // String contactination.
   console.log(result);
}
   greeting();
// How do arguments work in function
