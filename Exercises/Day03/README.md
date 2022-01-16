### 1) Declare firstName, lastName, country, city, age, isMarried, year variable and assign value to it and use the typeof operator to check different data types.

```
let firstName = "Taha";
let lastName = "Aykiroglu";
let country = "Turkey";
let city = "Istanbul";
let age = 22;
let isMarried = false;
let year = 2022;

typeof(firstName); // string
typeof(age); // number
typeof(isMarried); // boolean
```

### 2) Check if type of '10' is equal to 10

```
if(typeof('10') === typeof(10)){
  console.log("Equal");
}
else{
  console.log("Not Equal");
}
```

### 3) Check if parseInt('9.8') is equal to 10

```
if(typeof(parseInt('9.8')) === typeof(10)){
  console.log("Equal");
}
else{
  console.log("Not Equal");
}
```

### 4) Boolean value is either true or false.

Write three JavaScript statement which provide truthy value.
Write three JavaScript statement which provide falsy value.

```
console.log(3 != 2)             // true
console.log(3 == '3')           // true
console.log(3 === '3')          // false
console.log(3 !== '3')          // true
console.log(3 != 3)             // false
console.log(3 !== 3)            // false
```

### 5) Figure out the result of the following comparison expression first without using console.log(). After you decide the result confirm it using console.log()

4 > 3
4 >= 3
4 < 3
4 <= 3
4 == 4
4 === 4
4 != 4
4 !== 4
4 != '4'
4 == '4'
4 === '4'
Find the length of python and jargon and make a falsy comparison statement.

```
console.log(4 > 3); // true
console.log(4 >= 3); // true
console.log(4 < 3); // false
console.log(4 <= 3); // false
console.log(4 == 4); // true
console.log(4 === 4); // true
console.log(4 != 4); // false
console.log(4 !== 4); // false
console.log(4 != '4'); // false
console.log(4 == '4'); // true
console.log(4 === '4'); // false
let word1 = "python";
let word2 = "jargon";
console.log(word1.length > word2.length); // false
```

### 6) Figure out the result of the following expressions first without using console.log(). After you decide the result confirm it by using console.log()

4 > 3 && 10 < 12
4 > 3 && 10 > 12
4 > 3 || 10 < 12
4 > 3 || 10 > 12
!(4 > 3)
!(4 < 3)
!(false)
!(4 > 3 && 10 < 12)
!(4 > 3 && 10 > 12)
!(4 === '4')
There is no 'on' in both dragon and python

```
console.log(4 > 3 && 10 < 12); // true
console.log(4 > 3 && 10 > 12); // false
console.log(4 > 3 || 10 < 12); // true
console.log(4 > 3 || 10 > 12); // true
console.log(!(4 > 3)); // false
console.log(!(4 < 3)); // true
console.log(!(false)); // true
console.log(!(4 > 3 && 10 < 12)); // false
console.log(!(4 > 3 && 10 > 12)); // true
console.log(!(4 === '4')); // true
let word1 = "python";
let word2 = "dragon";

console.log(word1.includes('on') && word2.includes('on')); // true
```

### 7) Use the Date object to do the following activities

What is the year today?
What is the month today as a number?
What is the date today?
What is the day today as a number?
What is the hours now?
What is the minutes now?
Find out the numbers of seconds elapsed from January 1, 1970 to now.

```
let today = new Date();
today.getFullYear(); // 2022

today.getMonth() + 1; // 1 (January)

today.getDate(); // 16

today.getDay() + 1; // 1 (Sunday)

today.getHours(); // 12

today.getMinutes(); // 6

today.getTime(); // 1642324028537
```

### 8) Write a script that prompt the user to enter base and height of the triangle and calculate an area of a triangle (area = 0.5 x b x h).

```
let base = prompt("Enter base: ");
let height = prompt("Enter height: ");

console.log(`The area of the triangle is ${(base*height) / 2}`);
```

### 9) Write a script that prompt the user to enter side a, side b, and side c of the triangle and and calculate the perimeter of triangle (perimeter = a + b + c)

```
let sideA = parseInt(prompt("Enter side a: "));
let sideB = parseInt(prompt("Enter side b: "));
let sideC = parseInt(prompt("Enter side c: "));
console.log(`The perimeter of the triangle is ${sideA + sideB + sideC}`);
```

### 10) Get length and width using prompt and calculate an area of rectangle (area = length x width and the perimeter of rectangle (perimeter = 2 x (length + width))

```
let length = parseInt(prompt("Enter length: "));
let width = parseInt(prompt("Enter width: "));

console.log(`The area of the triangle is ${length * width}`);
```

### 11) Get radius using prompt and calculate the area of a circle (area = pi x r x r) and circumference of a circle(c = 2 x pi x r) where pi = 3.14.

```
let radius = parseInt(prompt("Enter radius: "));
const PI = 3.14;
console.log(`Area of circle ${PI * radius * radius}`);
```

### 12) Write a script that prompt a user to enter hours and rate per hour. Calculate pay of the person?

```
let hours = parseInt(prompt("Enter hours: "));
let rate = parseInt(prompt("Enter rate per hour: "));

console.log(`Your weekly earning is ${hours * rate}`);
```

### 13) If the length of your name is greater than 7 say, your name is long else say your name is short.

```
let name = prompt("Enter your name: ");

if(name.length > 7){
  console.log("Your name is long");
}
else{console.log("Your name is short");}
```

### 14) Compare your first name length and your family name length and you should get this output.

let firstName = 'Asabeneh'
let lastName = 'Yetayeh'
Your first name, Asabeneh is longer than your family name, Yetayeh

```
let name = "Taha";
let lastName = "Aykiroglu";

if(name.length > lastName.length){
  console.log(`Your first name, ${firstName} is longer than your family name, ${lastName}`);
}
else{
  console.log(`Your first name, ${firstName} is shorter than your family name, ${lastName}`);
}
```

### 15) Declare two variables myAge and yourAge and assign them initial values and myAge and yourAge.

let myAge = 250
let yourAge = 25
I am 225 years older than you.

```
let myAge = 22;
let yourAge = 20;
console.log(`I am ${myAge - yourAge} years older than you`);
```

### 16) Using prompt get the year the user was born and if the user is 18 or above allow the user to drive if not tell the user to wait a certain amount of years.

Enter birth year: 1995
You are 25. You are old enough to drive

Enter birth year: 2005
You are 15. You will be allowed to drive after 3 years.

```
let birthDate = parseInt(prompt("Enter birth year: "));
let date = new Date();
date = date.getFullYear();
let age = date - birthDate;

if(date - birthDate >= 18){
  console.log(`You are ${age}. You are old enough to drive`);
}
else {
  console.log(`You are ${age}. You will be allowed to drive after ${18 - age} years`);
}
```

### 17) Write a script that prompt the user to enter number of years. Calculate the number of seconds a person can live. Assume some one lives just hundred years

Enter number of years you live: 100
You lived 3153600000 seconds.

```
let year = parseInt(prompt("Enter number of years you live: "));
let secondInYear = 31556926;
console.log(`You lived ${secondInYear * year} seconds`);
```

### 18) Create a human readable time format using the Date time object

YYYY-MM-DD HH:mm

```
let d = new Date();
d = new Date(d.getTime() - 3000000);
let date_format_str = d.getFullYear().toString()+"-"+((d.getMonth()+1).toString().length==2?(d.getMonth()+1).toString():"0"+(d.getMonth()+1).toString())+"-"+(d.getDate().toString().length==2?d.getDate().toString():"0"+d.getDate().toString())+" "+(d.getHours().toString().length==2?d.getHours().toString():"0"+d.getHours().toString())+":"+((parseInt(d.getMinutes()/5)*5).toString().length==2?(parseInt(d.getMinutes()/5)*5).toString():"0"+(parseInt(d.getMinutes()/5)*5).toString());
console.log(date_format_str);
```
