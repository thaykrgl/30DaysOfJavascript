### 1) Declare an empty array;

```
const arr = [];
```

### 2) Declare an array with more than 5 number of elements

```
const webTechs = ['HTML', 'CSS', 'JS', 'React', 'Redux', 'Node', 'MongDB'];
```

### 3) Find the length of your array

```
webTechs.length; // 7
```

### 4) Get the first item, the middle item and the last item of the array

```
webTechs[webTechs.length - 1]; // last item
webTechs[0]; // first item
webTechs[Math.round((webTechs.length - 1) / 2)]; // middle item
```

### 5) Declare an array called mixedDataTypes, put different data types in the array and find the length of the array. The array size should be greater than 5

```
const mixedDataTypes = [
    'Taha',
    250,
    true,
    { country: 'Finland', city: 'Helsinki' },
    { skills: ['HTML', 'CSS', 'JS', 'React', 'Python'] },
    'Aykiroglu'
]
mixedDataTypes.length; // 6
```

### 6) Declare an array variable name itCompanies and assign initial values Facebook, Google, Microsoft, Apple, IBM, Oracle and Amazon

```
  const itCompanies = ["Facebook", "Google", "Microsoft", "Apple", "IBM", "Oracle", "Amazon"];
```

### 7) Print the array using console.log()

```
console.log(itCompanies);
```

### 8) Print the number of companies in the array

```
console.log(itCompanies.length);
```

### 9) Print the first company, middle and last company

```
itCompanies[itCompanies.length - 1]; // last item
itCompanies[0]; // first item
itCompanies[Math.round((itCompanies.length - 1) / 2)]; // middle item
```

### 10) Print out each company

```
console.log(itCompanies);
```

### 11) Change each company name to uppercase one by one and print them out

```
itCompanies[0] = itCompanies[0].toUpperCase();
itCompanies[1] = itCompanies[1].toUpperCase();
itCompanies[2] = itCompanies[2].toUpperCase();
itCompanies[3] = itCompanies[3].toUpperCase();
itCompanies[4] = itCompanies[4].toUpperCase();
itCompanies[5] = itCompanies[5].toUpperCase();
itCompanies[6] = itCompanies[6].toUpperCase();
console.log(itCompanies);
```

### 12) Print the array like as a sentence: Facebook, Google, Microsoft, Apple, IBM,Oracle and Amazon are big IT companies.

```
console.log(`${itCompanies[0]}${","} ${itCompanies[1]}${","} ${itCompanies[2]}${","} ${itCompanies[3]}${","} ${itCompanies[4]}${","} ${itCompanies[5]}${","} ${itCompanies[6]} ${"are big IT companies"}`);
```

### 13) Check if a certain company exists in the itCompanies array. If it exist return the company else return a company is not found

```
let exist = itCompanies.includes("Facebook");

if(exist){
  console.log("Facebook");
}
else{
  console.log("Company is not found");
}
```

### 14) Filter out companies which have more than one 'o' without the filter method

```

```

### 15) Sort the array using sort() method

```
itCompanies.sort();
```

### 16) Reverse the array using reverse() method

```
itCompanies.reverse();
```

### 17) Slice out the first 3 companies from the array

```
itCompanies.slice(0,3);
```

### 18) Slice out the last 3 companies from the array

```
itCompanies.slice(itCompanies.length - 3,itCompanies.length);
```

### 19) Slice out the middle IT company or companies from the array

```
itCompanies.slice(Math.round((itCompanies.length - 1) / 2), Math.round(((itCompanies.length -1) / 2) + 1));
```

### 20) Remove the first IT company from the array

```
itCompanies.shift();
```

### 21) Remove the middle IT company or companies from the array

```
itCompanies.splice(Math.round((itCompanies.length - 1)) / 2,1);
```

### 22) Remove the last IT company from the array

```
itCompanies.pop();
```

### 23) Remove all IT companies

```
itCompanies.splice();
```

### 24) First remove all the punctuations and change the string to array and count the number of words in the array

let text = 'I love teaching and empowering people. I teach HTML, CSS, JS, React, Python.'
console.log(words)
console.log(words.length)

["I", "love", "teaching", "and", "empowering", "people", "I", "teach", "HTML", "CSS", "JS", "React", "Python"]

13

```
var text = "This., -/ is #! an $ % ^ & * example ;: {} of a = -_ string with `~)() punctuation";
var punctuationless = text.replace(/[.,\/#!$%\^&\*;:{}=\-_`~()]/g,"");
var finalString = punctuationless.replace(/\s{2,}/g," ");

let array = [];
array = finalString.split(" ");
array.length; // 9
```

### 25) In the following shopping cart add, remove, edit items

const shoppingCart = ['Milk', 'Coffee', 'Tea', 'Honey']

- add 'Meat' in the beginning of your shopping cart if it has not been already added
- add Sugar at the end of you shopping cart if it has not been already added
- remove 'Honey' if you are allergic to honey
- modify Tea to 'Green Tea'

```
if(!shoppingCart.includes("Meat")){
  shoppingCart.unshift("Meat");
}

if(!shoppingCart.includes("Sugar")){
  shoppingCart.push("Sugar");
}

let value = shoppingCart.indexOf("Honey");
shoppingCart.splice(index, 1);

let index = shoppingCart.indexOf("Tea");
shoppingCart[index] = "Green Tea";
```

### 26) In countries array check if 'Ethiopia' exists in the array if it exists print 'ETHIOPIA'. If it does not exist add to the countries list.

const countries = ['Albania', 'Bolivia', 'Canada', 'Denmark', 'Ethiopia','Finland', 'Germany', 'Hungary', 'Ireland', 'Japan', 'Kenya']

```
if(countries.includes("Ethiopia")){
  console.log("Ethiopia");
}
else{
  countries.push("Ethiopia");
}
```

### 27) In the webTechs array check if Sass exists in the array and if it exists print 'Sass is a CSS preprocess'. If it does not exist add Sass to the array and print the array.

const webTechs = ['HTML', 'CSS', 'JavaScript', 'React', 'Redux', 'Node','MongoDB']

```
if(webTechs.includes("Sass")){
  console.log("Sass is a CSS preprocessor");
}
else{
  webTechs.push("Sass");
}

console.log(webTechs);
```

### 28) Concatenate the following two variables and store it in a fullStack variable.

const frontEnd = ['HTML', 'CSS', 'JS', 'React', 'Redux']
const backEnd = ['Node','Express', 'MongoDB']

console.log(fullStack)

["HTML", "CSS", "JS", "React", "Redux", "Node", "Express", "MongoDB"]

```
const fullStack = frontEnd.concat(backEnd);
console.log(fullStack);
```

### 29) The following is an array of 10 students ages:

const ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]

- Sort the array and find the min and max age
- Find the median age(one middle item or two middle items divided by two)
- Find the average age(all items divided by number of items)
- Find the range of the ages(max minus min)
- Compare the value of (min - average) and (max - average), use abs() method

```
// Sort Min Max
ages.sort();
Math.min(...ages);
Math.max(...ages);

// Median
let median = 0;
if(ages.length % 2 == 0){
  median = (ages[(ages.length / 2)] + ages[(ages.length / 2) - 1]) / 2;
}
else{
  median = ages[Math.round((ages.length / 2) - 1)]
}

// Average
let sum = ages.reduce(function(a,b){
  return a + b;
}, 0);

let average = sum / ages.length;
console.log(average);

// Range
let range = Math.max(...ages) - Math.min(...ages);
console.log(range);

// Abs Method
let minAvg = Math.abs(Math.min(...ages) - average);
let maxAvg = Math.abs(Math.max(...ages) - average);

console.log(minAvg);
console.log(maxAvg);
```

### 30) Find the middle country(ies) in the countries array

```
let middle = "";

if(countries.length % 2 == 0){
  middle = (countries[(countries.length / 2)] + " " + countries[(countries.length / 2) - 1]);
}
else{
  middle = countries[Math.round((countries.length / 2)) - 1];
}
```

### 31) Divide the countries array into two equal arrays if it is even. If countries array is not even , one more country for the first half.

```
let middle = 0;
let firstHalf = [];
let secondHalf = [];

if(countries.length % 2 == 0){
    middle = countries.length / 2;
    firstHalf = countries.splice(0, middle);
    secondHalf = countries.splice(-middle);
}
else{
  middle = Math.round(countries.length / 2);
  firstHalf = countries.splice(0, middle);
  secondHalf = countries.splice(-middle);
}
```
