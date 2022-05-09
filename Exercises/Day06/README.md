const countries = ['Albania', 'Bolivia', 'Canada', 'Denmark', 'Ethiopia', 'Finland', 'Germany', 'Hungary', 'Ireland', 'Japan', 'Kenya'
]

const webTechs = ['HTML', 'CSS', 'JavaScript', 'React', 'Redux', 'Node', 'MongoDB'
]

const mernStack = ['MongoDB', 'Express', 'React', 'Node']

### 1) Iterate 0 to 10 using for loop, do the same using while and do while loop

```
// For
for(let i = 0; i < 10; i++){
  console.log(i);
}

// While
let i = 0;
while(i < 10){
  console.log(i);
  i++;
}

// Do-While
let i = 0;
do{
  console.log(i);
  i++;
} while(i < 10)
```

### 2) Iterate 10 to 0 using for loop, do the same using while and do while loop

```
// For
for(let i = 10; i > 0; i--){
  console.log(i);
}

// While
let i = 10;
while(i > 0){
  console.log(i);
  i--;
}

// Do-While
let i = 10;
do{
  console.log(i);
  i--;
} while(i > 0)
```

### 3) Iterate 0 to n using for loop

```
for(let i = 0; i < 16; i++){
  console.log(i);
}
```

### 4) Write a loop that makes the following pattern using console.log():

\# <br>
\## <br>
\### <br>
\#### <br>
\##### <br>
\###### <br>
\####### <br>

```
let symbol = "#";
for(let i = 1; i < 8; i++){
  console.log(symbol);
  symbol += "#";
}
```

### 5) Use loop to print the following pattern:

0 x 0 = 0 <br>
1 x 1 = 1 <br>
2 x 2 = 4 <br>
3 x 3 = 9 <br>
4 x 4 = 16 <br>
5 x 5 = 25 <br>
6 x 6 = 36 <br>
7 x 7 = 49 <br>
8 x 8 = 64 <br>
9 x 9 = 81 <br>
10 x 10 = 100 <br>

```
for(let i = 0; i <= 10; i++){
  console.log(`${i} x ${i} = ${i*i}`);
}
```

### 6) Using loop print the following pattern

i &emsp; i^2 &emsp; i^3 <br>
0 &nbsp; &nbsp; 0 &emsp; &nbsp; 0 <br>
1 &nbsp; &nbsp; 1 &emsp; &nbsp; 1 <br>
2 &nbsp; &nbsp; 4 &emsp; &nbsp; 8 <br>
3 &nbsp; &nbsp; 9 &emsp; &nbsp; 27 <br>
4 &nbsp; &nbsp; 16 &emsp; 64 <br>
5 &nbsp; &nbsp; 25 &emsp; 125 <br>
6 &nbsp; &nbsp; 36 &emsp; 216 <br>
7 &nbsp; &nbsp; 49 &emsp; 343 <br>
8 &nbsp; &nbsp; 64 &emsp; 512 <br>
9 &nbsp; &nbsp; 81 &emsp; 729 <br>
10 &nbsp; 100 &nbsp; &nbsp;1000 <br>

```
console.log("i" + "  i^2" + "  i^3");
for(let i = 0; i <= 10; i++){
  console.log(`${i}  ${i*i}  ${i*i*i}`);
}
```

### 7) Use for loop to iterate from 0 to 100 and print only even numbers

```
for(let i = 0; i < 100; i++){
  if(i % 2 == 0){
    console.log(i);
  }
}
```

### 8) Use for loop to iterate from 0 to 100 and print only odd numbers

```
for(let i = 0; i < 100; i++){
  if(i % 2 !== 0){
    console.log(i);
  }
}
```

### 9) Use for loop to iterate from 0 to 100 and print only prime numbers

```
for (let i = 0; i <= 100; i++) {
    let flag = 0;

    for (let j = 2; j < i; j++) {
        if (i % j == 0) {
            flag = 1;
            break;
        }
    }

    if (i > 1 && flag == 0) {
        console.log(i);
    }
}
```

### 10) Use for loop to iterate from 0 to 100 and print the sum of all numbers.

```
let total = 0;
for(let i = 0; i <= 100; i++){
  total += i;
}
console.log(`The sum of all numbers from 0 to 100 is ${total}.`);
```

### 11) Use for loop to iterate from 0 to 100 and print the sum of all evens and the sum of all odds.

```
let oddTotal = 0;
let evenTotal = 0;
for(let i = 0; i <= 100; i++){
  if(i % 2 === 0)
    evenTotal += i;
  else{
    oddTotal += i;
  }
}
console.log(`The sum of all evens from 0 to 100 is ${evenTotal}. And the sum of all odds from 0 to 100 is ${oddTotal}.`);
```

### 12) Use for loop to iterate from 0 to 100 and print the sum of all evens and the sum of all odds. Print sum of evens and sum of odds as array

```
let array = [];
let oddTotal = 0;
let evenTotal = 0;
for(let i = 0; i <= 100; i++){
  if(i % 2 === 0)
    evenTotal += i;
  else{
    oddTotal += i;
  }
}
array.push(oddTotal);
array.push(evenTotal);
console.log(array);

```

### 13) Develop a small script which generate array of 5 random numbers

```
let array = [];
for(let i = 0; i < 5; i++){
  array.push(Math.random());
}
console.log(array);
```

### 14) Develop a small script which generate a six characters random id

```
function generateId() {
  var id = "";
  var possible = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";

  for (let i = 0; i < 6; i++)
    id += possible.charAt(Math.floor(Math.random() * possible.length));

  return id;
}

console.log(generateId());
```
