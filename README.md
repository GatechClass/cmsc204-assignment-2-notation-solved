# cmsc204-assignment-2-notation-solved
**TO GET THIS SOLUTION VISIT:** [CMSC204 Assignment #2-Notation Solved](https://mantutor.com/product/cmsc204-solved-7/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113913&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC204 Assignment #2-Notation  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Infix notation is the notation commonly used in arithmetical and logical formulae and statements. It is characterized by the placement of operators between operands – “infixed operators” – such as the plus sign in “2 + 2”.

Postfix notation is a notation for writing arithmetic expressions in which the operands appear before their operators. There are no precedence rules to learn, and parentheses are never needed.

You will be creating a utility class that converts an infix expression to a postfix expression, a postfix expression to an infix expression and evaluates a postfix expression.

Concepts tested:

Generic Queue

Generic Stack

Exception handling

Data Element

String

Data Structures

1. Create a generic queue class called NotationQueue. NotationQueue will implement the QueueInterface given you. You will be creating NotationQueue from scratch (do not use an internal object of the Queue class from java.util)

2. Create a generic stack class called NotationStack. NotationStack will implement the Stack Interface given you. You will be creating NotationStack from scratch (do not use an internal object of the Stack class from java.util)

Utility Class

The Notation class will have a method infixToPostfix to convert infix notation to postfix notation that will take in a string and return a string, a method postfixToInfix to convert postfix notation to infix notation that will take in a string and return a string, and a method to evaluatePostfix to evaluate the postfix expression. It will take in a string and return a double.

In the infixToPostfix method, you MUST use a queue for the internal structure that holds the postfix solution. Then use the toString method of the Queue to return the solution as a string.

For simplicity sake:

a. operands will be single digit numbers

b. the following arithmetic operations will be allowed in an expression:

+ addition

– subtraction

* multiplication

/ division

Exception Classes

Provide the following exception classes:

1. InvalidNotationFormatException – occurs when a Notation format is incorrect

2. StackOverflowException – occurs when a top or pop method is called on an empty stack.

3. StackUnderflowException – occurs when a push method is called on a full stack.

4. QueueOverflowException – occurs when a dequeue method is called on an empty queue.

5. QueueUnderflowException – occurs when a enqueue method is called on a full queue.

ALGORITHMS

Infix expression to postfix expression:

Read the infix expression from left to right and do the following:

If the current character in the infix is a space, ignore it.

If the current character in the infix is a digit, copy it to the postfix solution queue

If the current character in the infix is a left parenthesis, push it onto the stack

If the current character in the infix is an operator,

1. Pop operators (if there are any) at the top of the stack while they have equal or higher precedence than the current operator, and insert the popped operators in postfix solution queue

2. Push the current character in the infix onto the stack

If the current character in the infix is a right parenthesis

1. Pop operators from the top of the stack and insert them in postfix solution queue until a left parenthesis is at the top of the stack, if no left parenthesisthrow an error

2. Pop (and discard) the left parenthesis from the stack

When the infix expression has been read, Pop any remaining operators and insert them in postfix solution queue.

Postfix expression to infix expression:

Read the postfix expression from left to right and to the following:

If the current character in the postfix is a space, ignore it.

If the current character is an operand, push it on the stack

If the current character is an operator,

1. Pop the top 2 values from the stack. If there are fewer than 2 values throw an error

2. Create a string with 1st value and then the operator and then the 2nd value.

3. Encapsulate the resulting string within parenthesis

4. Push the resulting string back to the stack When the postfix expression has been read:

If there is only one value in the stack – it is the infix string, if more than one value, throw an error

Evaluating a postfix expression

Read the postfix expression from left to right and to the following:

If the current character in the postfix expression is a space, ignore it.

If the current character is an operand, push on the stack

If the current character is an operator,

1. Pop the top 2 values from the stack. If there are fewer than 2 values throw an error

2. Perform the arithmetic calculation of the operator with the first popped value as the right operand and the second popped value as the left operand 3. Push the resulting value onto the stack When the postfix expression has been read:

If there is only one value in the stack – it is the result of the postfix expression, if more than one value, throw an error

Grading Rubric – CMSC 204 Project #2

Name _____________________________ .

PROGRAMMING (100 pts)

Compiles 40 pts _____

Accuracy

Passes public JUnit tests 15 pts _____

Passes STUDENT JUnit tests 10 pts _____

Execution: runs without errors (either run-time or logic errors) 20 pts _____

Possible Sub-total 100 pts _____

REQUIREMENTS (Subtracts from Programming total)

Documentation:

Javadoc was not provided for all student generated classes – 5 pts _____

Documentation within source code was missing or incorrect – 5 pts _____

Description of what class does was missing

Author’s Name, @author, was missing

Methods not commented properly using Javadoc @param, @return

JUnit STUDENT methods were not implemented -5 pts _____

Learning Experience (text document) -4 pts _____

In 3+ paragraphs, highlight your lessons learned and learning experience from working on this project. What have you learned? What did you struggle with? What would you do differently on your next project?

Programming Style:

Incorrect use of indentation, statements, structures

Design: Classes do not have the functionality specified, i.e., -10 pts _____

1. Data Structures classes

• Generic Stack class

• Generic Queue class – 16 pts_____

2. Utility class – Notation

• Does not follow provided Javadoc -15 pts_____

• Does not correctly handle exceptions

Possible decrements: -60 pts _____

Possible total grade: 100 pts _____
