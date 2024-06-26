# REVAMP_ASSIGN-16

# JavaScript Array Methods Examples

This repository contains simple JavaScript examples demonstrating the use of array methods `map()` and `filter()`.

## 1. Multiply Each Value of an Array by Ten

### Problem Statement
Given an array `myArray` of numbers, write a JavaScript program to multiply the values of `myArray` by 10 using the array method `map()`.

### Input
The input will be a single line containing an array `myArray`. For example:
```
[12, 2, 2, 4, 1]
```

### Output
The output should be an array with each value of `myArray` multiplied by 10. For example:
```
[120, 20, 20, 40, 10]
```

### Constraints
Each value in the array must be a number.

### Code
```javascript
// Function to multiply each value of an array by ten
function multiplyByTen(myArray) {
    // Use the map() method to create a new array with each element multiplied by 10
    const resultArray = myArray.map((e) => {
        return e * 10;
    });
    return resultArray;
}

// Sample Input 1
const input1 = [12, 2, 2, 4, 1];
const output1 = multiplyByTen(input1);
console.log("Sample Output 1:", output1);
```

### Sample Output
```
Sample Output 1: [120, 20, 20, 40, 10]
```

## 2. Filter Even Numbers

### Problem Statement
Given an array `myArray` of numbers, write a JavaScript program to filter out the even numbers using the array method `filter()`.

### Input
The input will be a single line containing an array `myArray`. For example:
```
[12, 5, 7, 8, 3, 2]
```

### Output
The output should be an array containing only the even numbers from `myArray`. For example:
```
[12, 8, 2]
```

### Constraints
Each value in the array must be a number.

### Code
```javascript
// Function to filter out even numbers from an array
function filterEvenNumbers(myArray) {
    // Use the filter() method to create a new array with only the even numbers
    const resultArray = myArray.filter((e) => {
        return e % 2 === 0;
    });
    return resultArray;
}

// Sample Input 1
const input1 = [12, 5, 7, 8, 3, 2];
const output1 = filterEvenNumbers(input1);
console.log("Sample Output 1:", output1);
```

### Sample Output
```
Sample Output 1: [12, 8, 2]
```


This `README.md` file includes a description of each problem, the sample input and output, and the complete JavaScript code to solve the problems using `map()` and `filter()`.
