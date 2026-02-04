🔁 Reverse a String in JavaScript

📌 Description

This program reverses a given string using JavaScript.
It is a common beginner and interview-level problem that helps in understanding string manipulation.

🧩 Problem Statement

Given a string:

Reverse the characters and return the reversed string.

Example:

Input: "hello"
Output: "olleh"

✅ Code
function reverseString(str) {
  return str.split("").reverse().join("");
}

console.log(reverseString("hello"));

🧠 Explanation

split("") converts the string into an array of characters

reverse() reverses the array

join("") combines the characters back into a string

The reversed string is returned and printed

🖨 Example Output
olleh

🛠 Concepts Used

JavaScript Functions

String methods

Array methods (split, reverse, join)

Console output (console.log)

🎯 Use Cases

Beginner JavaScript practice

Interview preparation

String manipulation problems

Learning built-in methods

🚀 Possible Improvements

Reverse string without using built-in methods

Handle sentences with spaces

Take user input dynamically

👨‍💻 Author

Pranay Jadhao
