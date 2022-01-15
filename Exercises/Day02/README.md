### 1) Declare a variable named challenge and assign it to an initial value '30 Days Of JavaScript'.

```
let challenge = "30 Days Of JavaScript"
```

### 2) Print the string on the browser console using console.log()

```
console.log(challenge);
```

### 3) Print the length of the string on the browser console using console.log()

```
console.log(challenge.length);
```

### 4) Change all the string characters to capital letters using toUpperCase() method

```
challenge = challenge.toUpperCase();
```

### 5) Change all the string characters to lowercase letters using toLowerCase() method

```
challenge = challenge.toLowerCase();
```

### 6) Cut (slice) out the first word of the string using substr() or substring() method

```
challenge = challenge.substring(0,2);
```

### 7) Slice out the phrase Days Of JavaScript from 30 Days Of JavaScript.

```
challenge = challenge.slice(3, challenge.length);
```

### 8) Check if the string contains a word Script using includes() method

```
let result = challenge.includes("Script"); // true
```

### 9) Split the string into an array using split() method

```
challenge.split(" "); // split with spaces
```

### 10) Split the string 30 Days Of JavaScript at the space using split() method

```
challenge.split(" "); // split with spaces
```

### 11) 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' split the string at the comma and change it to an array.

```
let techCompanies = 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon';
techCompanies.split(",");
```

### 12) Change 30 Days Of JavaScript to 30 Days Of Python using replace() method.

```
challenge = challenge.replace("JavaScript", "Python");
```

### 13) What is character at index 15 in '30 Days Of JavaScript' string? Use charAt() method.

```
challenge.charAt(15);
```

### 14) What is the character code of J in '30 Days Of JavaScript' string using charCodeAt()

```
challenge.charCodeAt("J");
```

### 15) Use indexOf to determine the position of the first occurrence of a in 30 Days Of JavaScript

```
challenge.indexOf("a");
```

### 16) Use lastIndexOf to determine the position of the last occurrence of a in 30 Days Of JavaScript.

```
challenge.lastIndexOf("a");
```

### 17) Use indexOf to find the position of the first occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

```
let sentence = "You cannot end a sentence with because because because is a conjunction"
sentence.indexOf("because");
```

### 18) Use lastIndexOf to find the position of the last occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

```
sentence.lastIndexOf("because");
```

### 19) Use search to find the position of the first occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

```
sentence.search("because");
```

### 20) Use trim() to remove any trailing whitespace at the beginning and the end of a string.E.g ' 30 Days Of JavaScript '.

```
let challengeWithSpaces = "  30 Days Of JavaScript  ";
challengeWithSpaces.trim();
```

### 21) Use startsWith() method with the string 30 Days Of JavaScript and make the result true

```
challenge.startsWith("30");
```

### 22) Use endsWith() method with the string 30 Days Of JavaScript and make the result true

```
challenge.endsWith("ipt");
```

### 23) Use match() method to find all the a’s in 30 Days Of JavaScript

```
challenge.match("a");
```

### 24) Use concat() and merge '30 Days of' and 'JavaScript' to a single string, '30 Days Of JavaScript'

```
let days = "30 Days of";
let language = JavaScript;
days.concat(" ", language);
```

### 25) Use repeat() method to print 30 Days Of JavaScript 2 times

```
challenge.repeat(2);
```

### 26) Using console.log() print out the following statement:

The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.

```
console.log("The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.");
```

### 27) Using console.log() print out the following quote by Mother Teresa:

"Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead."

```
console.log('"Love is not patronizing and charity isn\'t about pity, it is about love. Charity and love are the same -- with charity you give love, so don\'t just give money but reach out your hand instead."');
```

### 28) Check if typeof '10' is exactly equal to 10. If not make it exactly equal.

```
let type1 = typeof('10'); // string
let type2 = typeof(10); // number
type1Number = Number(type1);
```

### 29) Check if parseFloat('9.8') is equal to 10 if not make it exactly equal with 10.

```
let type1 = typeof(parseFloat('9.8')); // number
let type2 = typeof(10); // number
```

### 30) Check if 'on' is found in both python and jargon

```
let word1 = "python";
let word2 = "jargon";
word1.includes("on"); // true
word2.includes("on"); // true
```

### 31) I hope this course is not full of jargon. Check if jargon is in the sentence.

```
let sentence = "I hope this course is not full of jargon.";
sentence.includes("jargon"); // true
```

### 32) Generate a random number between 0 and 100 inclusively.

```
let num = Math.floor(Math.random () * 101)
console.log(num);
```

### 33) Generate a random number between 50 and 100 inclusively

```
let num = Math.floor(Math.random () * 50) + 50;
console.log(num);
```

### 34) Generate a random number between 0 and 255 inclusively.

```
let num = Math.floor(Math.random () * 257)
console.log(num);
```

### 35) Access the 'JavaScript' string characters using a random number.

```
let word = "Javascript";
word[Math.floor(Math.random () * 1)]; // 'J'
word[Math.floor(Math.random () * 1) + 1]; // 'a'
word[Math.floor(Math.random () * 1) + 2]; // 'v'
word[Math.floor(Math.random () * 1) + 3]; // 'a'
word[Math.floor(Math.random () * 1) + 4]; // 'S'
word[Math.floor(Math.random () * 1) + 5]; // 'c'
word[Math.floor(Math.random () * 1) + 6]; // 'r'
word[Math.floor(Math.random () * 1) + 7]; // 'i'
word[Math.floor(Math.random () * 1) + 8]; // 'p'
word[Math.floor(Math.random () * 1) + 9]; // 't'
```

### 36) Use console.log() and escape characters to print the following pattern.

1 1 1 1 1

2 1 2 4 8

3 1 3 9 27

4 1 4 16 64

5 1 5 25 125

```
console.log(" 1 1 1 1 1 \n 2 1 2 4 8 \n 3 1 3 9 27 \n 4 1 4 16 64 \n 5 1 5 25 125");
```

### 37) Use substr to slice out the phrase because because because from the following sentence:'You cannot end a sentence with because because because is a conjunction'

```
let sentence = "You cannot end a sentence with because because because is a conjunction";
sentence = sentence.substr(0, 30) + sentence.substr(54, sentence.length);
```

### 38) 'Love is the best thing in this world. Some found their love and some are still looking for their love.' Count the number of word love in this sentence.

```
let sentence = "Love is the best thing in this world. Some found their love and some are still looking for their love.";

let pattern = /love/gi;
console.log(sentence.match(pattern). length);
```

### 39) Use match() to count the number of all because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

```
let sentence = "You cannot end a sentence with because because because is a conjunction";

let pattern = /because/gi;
console.log(sentence.match(pattern). length);
```

### 40) Clean the following text and find the most frequent word (hint, use replace and regular expressions).

let sentence = '%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'

```
sentence.replace(/\W/g, ''); // clean the text
```

### 41) Calculate the total annual income of the person by extracting the numbers from the following text. 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'

```
let annualSalary = 5000 * 12; // 6000
let annualCourseIncome = 15000 * 12; // 180000
let annualBonus = 10000;

let annualIncome = annualSalary + annualCourseIncome + annualBonus;
console.log(annualIncome); // 250000
```
