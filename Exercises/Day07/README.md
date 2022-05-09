### 1) Declare a function fullName and it print out your full name.

```
function fullName(){
  console.log("Taha Aykiroglu");
}
fullName()
```

### 2) Declare a function fullName and now it takes firstName, lastName as a parameter and it returns your full - name.

```
function fullName(firstName, lastName){
  console.log(firstName + " " + lastName);
}
fullName("Taha", "Aykiroglu")
```

### 3) Declare a function addNumbers and it takes two two parameters and it returns sum.

```
function addNumbers(num1, num2){
  return num1 + num2;
}

addNumbers(3,5)
```

### 4) An area of a rectangle is calculated as follows: area = length x width. Write a function which calculates areaOfRectangle.

```
function areaOfRectangle(width, length){
  return width * length
}
areaOfRectangle(4,7)
```

### 5) A perimeter of a rectangle is calculated as follows: perimeter= 2x(length + width). Write a function which calculates perimeterOfRectangle.

```
function perimeterOfRectangle(length, width){
  return 2 * width * length;
}
perimeterOfRectangle(10,12);
```

### 6) A volume of a rectangular prism is calculated as follows: volume = length x width x height. Write a function which calculates volumeOfRectPrism.

```
function volumeOfRectPrism(length, width, height){
  return width * length * height;
}
volumeOfRectPrism(3,6,9);
```

### 7) Area of a circle is calculated as follows: area = π x r x r. Write a function which calculates areaOfCircle

```
const PI = 3.14;
function areaOfCircle(radius){
  return radius * radius * PI;
}
areaOfCircle(4)
```

### 8) Circumference of a circle is calculated as follows: circumference = 2πr. Write a function which calculates circumOfCircle

```
const PI = 3.14;
function circumOfCircle(radius){
  return 2 * PI * radius
}
circumOfCircle(5)
```

### 9) Density of a substance is calculated as follows:density= mass/volume. Write a function which calculates density.

```
function density(mass, volume){
  return mass / volume
}
density(28, 40)
```

### 10) Speed is calculated by dividing the total distance covered by a moving object divided by the total amount of time taken. Write a function which calculates a speed of a moving object, speed.

```
function speed(distance, time){
  return distance / time
}
speed(1000, 59)
```

### 11) Weight of a substance is calculated as follows: weight = mass x gravity. Write a function which calculates weight.

```
function weight(mass, gravity){
  return mass * gravity
}
weight(34, 10)
```

### 12) Temperature in oC can be converted to oF using this formula: oF = (oC x 9/5) + 32. Write a function which convert oC to oF convertCelsiusToFahrenheit.

```
function convertCelsiusToFahrenheit(celcius){
  return (celcius * 1.8) + 32
}
convertCelsiusToFahrenheit(50);
```

### 13) Body mass index(BMI) is calculated as follows: bmi = weight in Kg / (height x height) in m2. Write a function which calculates bmi. BMI is used to broadly define different weight groups in adults 20 years old or older.Check if a person is underweight, normal, overweight or obese based the information given below.

The same groups apply to both men and women. <br>
Underweight: BMI is less than 18.5 <br>
Normal weight: BMI is 18.5 to 24.9 <br>
Overweight: BMI is 25 to 29.9 <br>
Obese: BMI is 30 or more <br>

```
function bodyMassIndex(weight, height){
  let bmi = weight / (height * height);
  if(bmi < 18.5){
    console.log("Underweight");
  }
  else if(bmi > 18.5 && bmi < 25){
    console.log("Normal Weight");
  }
  else if(bmi >= 25 && bmi < 30){
    console.log("Overweight");
  }
  else if(bmi > 30){
    console.log("Obese");
  }
}

bodyMassIndex(58, 1.65)
```

### 14) Write a function called checkSeason, it takes a month parameter and returns the season:Autumn, Winter, Spring or Summer.

```
function checkSeason(number){
  if(number === 1 || number === 2 || number === 12 ){
    console.log("Winter");
  }
  else if(number === 3 || number === 4 || number === 5 ){
    console.log("Spring");
  }
  else if(number === 6 || number === 7 || number === 8 ){
    console.log("Summer");
  }
  else if(number === 9 || number === 10 || number === 11 ){
    console.log("Autumn");
  }
}
checkSeason(10);
```

### 15) Math.max returns its largest argument. Write a function findMax that takes three arguments and returns their maximum with out using Math.max method.

```
function findMax(num1, num2, num3){
  if(num1 > num2 && num1 > num3){
    return num1
  }
  else if(num2 > num1 && num2 > num3){
    return num2
  }
  else{
    return num3
  }
}
findMax(7,9,10)
```
