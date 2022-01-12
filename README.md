# variable present in product of two numbers in array?

Given a list of numbers and a variable, return whether any two numbers from the list add up to the variable.

For example, given [10, 15, 3, 7] and x of 17, return true since 10 + 7 is 17.

Solution:

let x = 22;
let array = [10, 15, 3, 7];

// Function START
if ( 
    array[0] + array[1] === x || 
    array[0] + array[2] === x || 
    array[0] + array[3] === x ||
    array[1] + array[2] === x ||
    array[1] + array[3] === x ||
    array[2] + array[3] === x 
    ) {
    console.log("true")
} else {
    console.log("false")
}
// Function END
