# The-Sum-Selector-a-function-that-sum-all-numbers-in-an-array-until-it-encounters-a-negative-number.c

The Sum Selector: You are working on a function that should sum all numbers in an array until it encounters a negative number. Write a function that performs this summation.

sum=0;
let arr=[2,3,4,5,6,7,-5,-4];
for(let no of arr){
    if(no>=0)
     sum=sum+no;
}
console.log(sum);
