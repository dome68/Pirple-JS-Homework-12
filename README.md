# Pirple-JS-Homework-12

Object Oriented Programming
Object Oriented Programming (OOP) is preferable to use when dealing with real objects such as a car, book, etc. These real objects have specific characteristics such as make, model, color for a car, title, author, gender for a book, name, surname, age, course for a student.
Additionally, these items can perform actions such as speed up or slow down for the car and be sold or loaned for the book.
An "object" is a data type formed by a set of properties and is implemented in JS as an associative array where each property is the key to access its value, which can be of any type.

User stories
The "Student" object is created to enter data relating to the student (name, age) who will participate in one or more courses.

Pseudocode
//Function constructor Student
Function Student (name. Age, course) {
	this.name = name;
	this.age = age;
	this.talk = function() {return “Hi, my name is ” + this.name};
	this.courses = course;
}

//Object new mark
var mark = new Student(“Mark”, 25, [“JS”, “C#”];
console.log(mark.age); //25

//Object carl
var carl = new Student(“Carl”, 21, [“CSS”, “HTML”, “JS”];
console.log(carl.courses); // [“CSS”, “HTML”, “JS”]


