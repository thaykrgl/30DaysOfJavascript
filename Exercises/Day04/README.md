### 1) Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback:'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he neds to turn 18.

Enter your age: 30
You are old enough to drive.

Enter your age:15
You are left with 3 years to drive.

```
let age = prompt("Enter your age: ");
if(age >= 18){
  console.log(`You are old enough to drive`);
}
else{
  console.log(`You are left with ${18 - age} years to drive`);
}
```

### 2) Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

Enter your age: 30
You are 5 years older than me.`

```
let myAge = 22;
let yourAge = parseInt(prompt("Enter your age: "));

if(yourAge > myAge){
  console.log(`You are ${yourAge - myAge} years older than me.`);
}
else{
  console.log(`You are ${myAge - yourAge} years younger than me.`);
}
```

### 3) If a is greater than b return 'a is greater than b' else 'a is less than b'. Try to implement it in to ways

using if else
ternary operator.

let a = 4
let b = 3
4 is greater than 3

```
let a = 4;
let b = 3;

if(a<b){
  console.log("a is less than b");
}
else{
  console.log("a is greater than or equal to b");
}

a > b ? console.log("a is greater than b") : console.log("a is less than b");
```

### 4) Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

Enter a number: 2
2 is an even number

Enter a number: 9
9 is is an odd number.

```
let number = parseInt(prompt("Enter a number: "));
if(number % 2 === 0){
  console.log(`${number} is an even number`);
}
else{
  console.log(`${number} is an odd number`);
}
```

### 5) Write a code which can give grades to students according to theirs scores:

90-100, A
70-89, B
60-69, C
50-59, D
0-49, F

```
let score = parseInt(prompt("Enter your score: "));
if(score > 90 && score <= 100){
  console.log("Your grade is A");
}
else if(score >= 70 && score <= 89){
  console.log("Your grade is B");
}
else if(score >= 60 && score <= 69){
  console.log("Your grade is C");
}
else if(score >= 50 && score <= 59){
  console.log("Your grade is D");
}
else if(score > 0 && score <= 49){
  console.log("Your grade is F");
}
else{
  console.log("Enter a valid score");
}
```

### 6) Check if the season is Autumn, Winter, Spring or Summer. If the user input is :

September, October or November, the season is Autumn.
December, January or February, the season is Winter.
March, April or May, the season is Spring
June, July or August, the season is Summer

```
let season = prompt("Enter a month: ");
if(season === "September" || season === "October" || season === "November"){
  console.log("Season is Autumn");
}
else if(season === "December" || season === "January" || season === "February"){
  console.log("Season is Winter");
}
else if(season === "March" || season === "April" || season === "May"){
  console.log("Season is Spring");
}
else if(season === "June" || season === "July" || season === "August"){
  console.log("Season is Summer");
}
```

### 7) Check if a day is weekend day or a working day. Your script will take day as an input.

What is the day today? Saturday
Saturday is a weekend.

What is the day today? saturDaY
Saturday is a weekend.

What is the day today? Friday
Friday is a working day.

What is the day today? FrIDAy
Friday is a working day.

```
let day = prompt("What is the day today: ");
day = day.toLowerCase();

if(day === "monday" || day === "tuesday" || day === "wednesday" || day === "thursday" || day === "friday"){
  console.log(`${day.charAt(0).toUpperCase() + day.slice(1)} is a working day`);
}
else {
  console.log(`${day.charAt(0).toUpperCase() + day.slice(1)} is a weekend`);
}
```

### 8) Write a program which tells the number of days in a month.

Enter a month: January
January has 31 days.

Enter a month: JANUARY
January has 31 days

Enter a month: February
February has 28 days.

Enter a month: FEbruary
February has 28 days.

```
let month = prompt("Enter a month: ");
month = month.toLowerCase();

switch(month){

  case "january":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 31 days`);
  break;
  case "february":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 28 days`);
  break;
  case "march":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 31 days`);
  break;
  case "april":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 30 days`);
  break;
  case "may":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 31 days`);
  break;
  case "june":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 30 days`);
  break;
  case "july":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 31 days`);
  break;
  case "august":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 31 days`);
  break;
  case "september":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 30 days`);
  break;
  case "october":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 31 days`);
  break;
  case "november":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 30 days`);
  break;
  case "december":
  console.log(`${month.charAt(0).toUpperCase() + month.slice(1)} has 31 days`);
  break;
  default:
}
```
