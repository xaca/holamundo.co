# Slide 1:

Programming Notebook

# Slide 2:

## Table of Contents

+ 03  Variables
+ 08  Operators
+ 12 Control structures
+ 17 Bestiary of Variables
+ 20 Vectors
+ 23 Matrices
+ 25 Strings
+ 28 Types of Functions

# Slide 3:

## Variable

A variable is an empty container, like a glass.

# Slide 4:

In programming, before you can use a variable, it is necessary to perform two operations:
- declare the variable (create the glass) to reserve the space where the data is to be stored.
- initialize the variable (put the contents into the glass) in order to use the value.

# Slide 5:

To create a variable you must use a type.
The type determines how much space is required to represent the data.
For example, we are talking about numbers - the data types are like matryoshka dolls. A larger container can hold a smaller one.

# Slide 6:

## Very important:

If the content to be saved in the variable exceeds its capacity, there is an overflow.
If we want to save the contents of a larger container in a smaller container, it will not be possible because there will be an overflow or loss of data.

## Slide 7:

It is common sense not to eat toast, with an empty glass, when we are thirsty because ... 
it does not quench thirst.
Using a variable without initializing it is a serious error.

cartoon:
I'm thirsty!
I'm still thirsty

# Slide 8:

## Operators

Arithmetic - add, subtract, multiply, divide
Use them, they're free. They will save you.
Parentheses (hero)
They are evaluated from left to right.

### Order of evaluation

1. () parentheses
2. `*` and /
3. `+` and -

# Slide 9:

Relationship: kiss!

Greater than, equal to, less than, greater than or equal to, not equal to, less than or equal to
Compares the relationship between two numbers and tells us if it's true or false
Yeah, 5 is bigger than 2

# Slide 10:

Watch out!
Don't confuse the assignment operator with the equality comparison operator.

- b = 5 assigns to b the value 5.
- You == You
- Are you equal to yourself? Yes (true).

# Slide 11:

Logic
Behind one of these doors is the woman of your life

and or not

and: returns true if both values are true. Otherwise, false.
or: returns false if both values are false. Otherwise, true.
not: returns the opposite. true if the value is false. false if the value is true.

# Slide 12:

Control structures

if:

`

      Start  
        |  
    Condition? - No > - -  
        | Yes           |  
        v               |  
    [Do something]      |  
        |  <  -  -  -  -|    
        v  
       End  
   
`

If I have the key, I get in

`
    if (condition)
    {
       // Cool code here!
    }
`

### Slide 13: ###

if - else:

If I have money, I eat pizza
Else, I drink water

`
(Start)
    |
Condition - no  -  -  - |
    | Yes           run code 2
run code 1              |
    |  - - - - - - - - -|
   end
`
`
if (condition)
{
    //Cool code 1
}
else
{
    //Cool code 2
}`


# Slide 14:

Loops

while: 

If I am not tired, I go

`
(start)
    |
[condition] - no -> end
    | Yes
  execute

while (condition)
{
    // cool code here!
}
`

# Slide 15:

Until:

Until I win money!

Start
Execute
Condition?
Yes, No
End

`
do
{
    //cool code here!

}while (condition);
`

# Slide 16:

for:

One shot for every target

Start
Yes, No
End
Condition
Execute

Increase or decrease
Cool code.

# Slide 17:

Bestiary of Variables

Flag: a key that controls how the program flow is executed

get outta here!


# Slide 18:

Guard: Watches and waits to have a certain value

Enter a value into added_value

Guard = added_value;

Checks if input value equals -1. If it does, the cycle ends.

# Slide 19:

Counter
Counts a value, usually one by one.

Accumulator
Similar to a counter, but accumulates multiples, divisions, sums and more.


# Slide 20:

Vectors

A programming structure that groups a fixed number of variables of the same type.

                components
data ----- 35 ................
indexes    1   ...............
                length 4

# Slide 21:

Data
(dialogues): The train is created, 
             Without wagons, the train is useless.
             It saves the space for 4 wagons

# Slide 22:

The content is being added
Careful! If you put content in a position that doesn't exist, you lose the content.

Error

# Slide 23:

Matrices
are structures that allow us to store data of the same type like a table, with N rows and M columns

8 columns
6 rows
cell

# Slide 24:

dato = Data
It is possible to declare and initialize an vector or matrix like this: 
(dialogue): Assigns a value to the cell

# Slide 25:

Strings

A string is an alphanumeric value, or a set of characters. It works like a vector.
"Hello world"
Indexes
10 total characters

# Slide 26:

s[0] returns a char. It is how we represent a character at a certain index. In this case, 0
s[0] -> h

Strings are immutable, but they still have some powers that we'll call commands.
'hello'  'HELLO'

Fabulous, Impressive, Wow

# Slide 27:

Some Commands:
hello
world
goodbye

to see all commands, consult the language API on the Internet

(box):  Watch out! 
        == mustn't be used to compare
        if two strings are equal. You 
        should use Equals

# Slide 28

## Functions

These are reusable modules of code. When you have code that is used several times in the program, you can create a function to reuse the behaviour.

Sum
sin / sin x / Sine

# Slide 29

Types of Function

Does not recieve input and does not output data.

0 - greet - 0    greet();

Recieves input data without returning data.

325 - save - 0   save();

Has input data and returns output data

3, 5 - sum - 8   total = sum(3, 5);

# Slide 30

Appendix

Programming Structures

Switch - a way to have a variety of nested 'if' statements.

switch(option) {
case 1: //code 1

default: Incorrect option.

Ternary Operator - it's an abbreviated if statement.

variable = (condition)? value 1 : value 2;

break - a reserved word for exiting a loop or other structure.

foreach - variation for looping over the vector

Exit the loop.

# Slide 31

The best way to learn is to teach.



