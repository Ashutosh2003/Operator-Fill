﻿Welcome to Operator Fill

This is a console based MATH program/game made in C++ which in current stage has 700+ lines of code.(I have plans to make it object oriented for easy maintenance and making it shorter)

In this program/game you will be given a linear arithmetic equation out of which the arithmetic operators will be left to you to fill to satisfy the given equation.  


ABOUT THE PROGRAM

The questions are randomly generated but the division parts in the questions are kind of controlled so as to make them not so hard. You wouldnt want to put a division sign between say 99 and 98 but have a possibility that there will be a division sign between say 25 and 5 or 13 and 2 (Easy divisions easy to anticipate).

Calculation is done based on BODMAS rule but '+' and '-' are given equal priority as the Calculator will convert any subtraction into a negative number and add those numbers.
FOR EXAMPLE: 34 - 21 will be calculated as 34 + (-21) = 13.

INSTRUCTIONS

Write what will go in the place of a blank and to switch to the next blank use a space. An example is given below for better understanding of the answer format.


Example 1 : 1_2_5_6.. = 5

Here the ans will be: + * -

The above ans will turn this eqn into 1+2*5-6 which is equal to 5. (BODMAS RULE)


HOW TO ADD BRACKETS IN YOUR ANSWER

Example 2: 3_6_5_3.. = 6

Here the ans will be: *( - )+

This will turn this eqn into 3*(6-5)+3 which is equal to 6. (Again BODMAS Rule)

Example 3: 20_10_8_4.. = 6

Answer: / +( - )

This will turn this eqn into 20/10+(8-4) which is equal to 6.



As you saw in Example 3 we filled 4 blanks instead of 3 in other examples. This will become clear in the TYPES OF BLANKS category.


TYPES OF BLANKS

1. '_' 

This is the compulsory blank. All of the compulsory blanks must be filled.

This blank accepts either an operator like '+', '-' , * , or '/' OR a bracket with an operator combo like '+(' or ')*' etc.

2. '..'

This is an optional blank present at the end of every question.

You can Fill it or leave it as it is.

If you wish to Fill it, it only accepts ')'.

We filled this blank in Example 3 but we left it alone in all other examples.



COMMANDS

1."SKIP"

If you dont know the answer to a question or wish to skip that question you can write "skip" or "SKIP" or "Skip" (without quotes of course) to skip the current question.

The program will display one of the correct answers for the question you skipped and switch to the next question.

2."END"

This command will End the game and view your results.

Just type "end" or "End" or "END" (without quotes) to END the game and display how many questions you answered correctly.



NOTE

All Character displayed above with quotes like '+' or '*(' are to be typed without quotes like + or *(.

Don't omit multiplying operator if trying to multiply thinking that 2 numbers in brackets placed side to side will multiply both numbers.

For Example: 

(4)(4) will not multiply 4 and 4 to give 16. (4)*(4) will though.

3(-5) will not give -15. Valid format is 3*(-5).

PS:

BTW this was my First code that I uploaded to github and I was new to programming and didnt know about code styles and formatting hence the code is a mess. I will try to add comments so that it would be a bit more understandable in the near future. I hope you guys would like it.

Also I am aware that this code is not even close to as efficient as it can be so I am open to suggestions. I did this for fun and also severley underestimated the sheer time and complexity of this program.

Feel free to post any feedback or bug you encounter in the issues tab.

Read the Troubleshoot.txt if you encounter any problems.



 















