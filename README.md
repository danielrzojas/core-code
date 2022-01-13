# Introduction to programming & Javascript - Week 1

## Tuesday

#### 1. Watch this video about compilation and interpretation

#### 2. Search and answer the question: Java language is compiled or interpreted?

* Java is a particular language because it is compiled, but it is compiled into an intermediate language called bytecode, which is then interpreted.

#### 3. Create an algorithm to calculate the equivalent of your local currencty to USD
```
Converter Algorithm

write: "convert quetzals to dollars"
write: "Enter the amount in quetzals"
read: x;
dollar = x / 7.8;
Write: "The equivalent in dollars is:", dollar;

Final Algorithm
```

#### 4. Read about Pseudocode here, you can also find some examples here

#### 5. Anwser to the question: Why is pseudocode helpful?

* Pseudocode helps us understand tasks in a language independent way.

#### 6. Create a pseudocode to calculate the aproximated age of a user base on the year they born, (you can define a variable with the actual year if you need it, like for example i could define Y <-- 2022)
```
Step 1: Enter the year of birth (1992)
Step 2: Save to variable "x"
Step 3: Enter the current year (2022)
Step 4: Save to variable "y"
Step 5: Run "y - x"
Step 6: Result (30)
```

#### 7. Read about flowcharts here

#### 8. Answer to the question: Why are flowcharts important to us as developers?

* It allows us to easily graphically see a certain logical process that can be useful for some type of task.

#### 9. Search about High-level languages and Low-level languages, you can start with this video
* A high-level language is a programming language designed to simplify computer programming.
* A low-level language is a type of programming language that contains basic instructions recognized by a computer.

## Wednesday
#### 1. Learn about binary, decimal and hexadecimal numbers
* Decimal system: It is a positional numbering system in which quantities are represented by the arithmetic base of the number ten. As the base is the number ten, we will have the ability to build all the figures using ten numbers that are what we all know. 0, 1,2 3, 4, 5, 6, 7, 8 and 9. These numbers will be used to represent the position of the powers of 10 in the formation of any number.

* Binary system: The binary system is a numbering system in which the arithmetic base 2 is used. This system is used internally by computers and digital systems to carry out absolutely all processes. This numbering system is only represented by two digits, 0 and 1, that is why it is based on 2 (two digits). With it, all value chains will be built. 

* Hexadecimal system: The hexadecimal numbering system is a positional numbering system based on the number 16. The numbers that we will have here will be: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, and F. This makes a total of 16 different terms.

#### 2. Translate the year you where born to binary, decimal and hexadecimal
* Decimal: 1990.  
* Binary: 11111000110.  
* Hexadecimal: 7C6
#### 3. Translate 51966 into hexadecimal and binary
* Binary: 1100101011111110.  
* Hexadecimal: CAFE

#### 4 Use a Low-level language, for example MIPS aseembler, to do so, you will need to follow this guide. We recomend to check the guide first but also this presentation could be helpful.
#### 5. Base on the examples and the guide of the low-level language:  

##### 5.1 Create a program to add two numbers given by the user
```
.data
	number1: .asciiz "\nIngrese el primer numero: "
	number2: .asciiz "\nIngrese el segundo numero: "
.text
	main:
		li $v0, 4
		la $a0, number1
		syscall

		li $v0, 5
		syscall

		move $t0, $v0

		li $v0, 4
		la $a0, number2
		syscall

		li $v0, 5
		syscall

		move $t1, $v0

		li $v0, 1
		move $a0, $t0
		syscall

```

##### 5.2 Create a program that display your name
```
.data
    message: .asciiz "\nDaniel Rojas!\n"
  .text
    main:
      li $v0, 4
      la $a0, message
      syscall
```
## Thursday
#### 1. Search for real word applications of Javascript
Common examples of JavaScript uses and applications include:
* Presentations
* webdevelopment
* Server Applications
* Web Applications
* Games
* Mobile Applications
#### 2. (optional but great) Watch this video
#### 3. (optional but great) Watch this video
#### 4. Follow the github course, you can find it here
* GitHub is a platform that allows us to save Git repositories that we can use as remote servers and execute some commands visually and interactively. After creating our account, we can create or import repositories, create organizations and work projects, discover other people's repositories, contribute to those projects, give stars, and many other things. Common Git Commands: git init, git add, git commit, git status, git config, git branch, git checkout, git merge.
