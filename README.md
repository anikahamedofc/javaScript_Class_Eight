#### javaScript_Class_Eight
JavaScript Function, Events, Strings, String Methods, String Search

// Function Calling Other Function
const claculateAge = function (birthDay) {
  return 2022 - birthDay;
};
// const age1 = claculateAge(1993);
// console.log(age1);
const jobLeft = function (birthDay) {
  const age = claculateAge(birthDay);
  return 65 - age;
};

const aJobLeft = jobLeft(1993);
console.log(aJobLeft);

// javaScript Events
//Click Events
function displayText() {
  console.log("Hello i am AnikAhmed ! How are You Doing Today");
}

function myAlert() {
  alert("hello it me please give me Ok");
}
//Mouse Events
function alertHover() {
  alert("hello it me please give me Ok");
}
// Input Event
function confirmInput() {
  alert("you are rediractiong to www.google.com");
}
// javaScript String
const firstName = "AnikAhmed";
console.log(firstName);
//example
const text = "I Love Bangladesh";
console.log(text);
// we want to write Bangladesh in dubble coation
const text1 = 'I Love "Bangladesh"!';
console.log(text1);
// we want to write Bangladesh in single coation
const text2 = "I Love 'Bangladesh'!";
console.log(text2);
// Escape character
// const txt = "We are the so-called \"Vikings\" from the north.";
// Escape character
// first \ will Escape and second \ will show "We are the so-called \ Vikings from the north."
// const txt = "We are the so-called \\Vikings from the north.";

// string Method
const x = "Anik Ahmed";
console.log(x.length);
//slice in positive index Start from 0
const fruit = "Apple, Banana, Pineapple, Orange";
console.log(fruit);

const fruits = fruit.slice(0, 5);
console.log(fruits);

const fruits1 = fruit.slice(7, 13);
console.log(fruits1);

const fruits2 = fruit.slice(15, 24);
console.log(fruits2);

const fruits3 = fruit.slice(26, 32);
console.log(fruits3);

//slice in Negative index Start from 0
const aFruit = "Apple, Banana, Pineapple, Orange";
console.log(aFruit);

const aFruits = fruit.slice(-6);
console.log(aFruits);

const aFruits1 = fruit.slice(-17, -8);
console.log(aFruits1);

const aFruits2 = fruit.slice(-25, -19);
console.log(aFruits2);

const aFruits3 = fruit.slice(-32, -27);
console.log(aFruits3);

// substring and Slice is same Start from 0
const vege = "Potato, Tomato, cabbage";
console.log(vege);

const vege1 = vege.substring(0, 6);
console.log(vege1);

const vege2 = vege.substring(8, 14);
console.log(vege2);

// substr and Slice is same Start from 0

// Replace
const city = "I Love Shahjadpur";
console.log(city);
console.log(city.replace("Shahjadpur", "Dhaka"));

// const city2 = city.replace("Shahjadpur", "Dhaka");
// console.log(city2);

// UpperCase
const car = "i love to drive car";
console.log(car.toUpperCase());
//Lowercase
const eat = "I Love To Eat";
console.log(eat.toLowerCase());

// Trim
const text5 = "      Hello World        ";
console.log(text5);
console.log(text5.trim());

// string search
const peopleName = "Anik, Ishan, Rafia, Rubayia";
console.log(peopleName.indexOf("Ishan"));
console.log(peopleName.lastIndexOf("Rubayia"));

// repeat
const text6 = "hello world! ";
console.log(text6.repeat(4));
