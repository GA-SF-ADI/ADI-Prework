# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project


This project is a way for us to verify that every student knows *minimum required Java basics* to be successful in this course. 

You are required to complete this project and have it working by the first day of class.
Make sure to follow the [Submission Requirements](#requirements) below.

#### The Challenge

You are tasked with creating a Java program that will decode a hidden message inside of an array of Strings.

Here is the array:
```
String[] hiddenMessage = {  
							"hello", "bigly", "co#", "wel", "bat", 
							"come", "tog", "cat", "inan", "en", "er", 
							"meta", "alas", "paw", "i", "docs", "super", 
							"mvp", "sem", "couch", "blys", "and", "meow", 
							"moo", "ro", "id", "msjd", "imm", "cawcaw", 
							"awe", "feir", "refs", "ewce", "ers", "jaz", 
							"ive", "pro", "ram", "mcd", "gr", "am", "h"
						 }; 
```

You can find the hidden message by printing Strings from the array at the following indexes:
- All indexes that are divisible by 3
- All indexes that are divisible by 5
- If an index is divisible by both 3 AND 5, do not print anything

<details>
	<summary>If you get stuck, click here for a hint!</summary>

Make use of the <b>modulus (%)</b> operator. If you don't know what modulus is or how it works, take a look at this <a href="https://www.youtube.com/watch?v=M193Md_fhYY">video</a>

</details>


<h3 id="requirements"></h3>
#### Submission Requirements

Make sure you create a *working Java program*. 

This means creating the following:
- A Java class called `HiddenMessage.java`
- A `main()` method inside of your `HiddenMessage.java` class
- A `findHiddenMessage()` method that will be called from `main()`

You can either pass the hiddenMassage array into the `findHiddenMessage()` method or make it a global class field. 

**You will submit your code via the [Quiz](01-task/quiz/readme.md)**.



