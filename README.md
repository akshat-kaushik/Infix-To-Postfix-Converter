<h1>INFIX-TO-POSTFIX-CONVERTOR</h1>
<BR>
<<<<<<< HEAD
<p>This is a program to convert infix notation to postfix.</p>
<BR>
<p>
Q1: What is Infix Notation ?
=======
DISCLAIMER : I have made this with stack & conditional statement but if you guy know how to make it more efficent or have any suggestions on this, then please let me know. 
<BR>
This is a program into convert infix notation to postfix.
<BR>
Q1: What is Infix Notation ?<BR>
>>>>>>> b0dc045247dedb10a5fbf1661abcaf05dba44195
Ans: Infix notation is a way of writing mathematical or logical expressions where the operator (such as +, -, *, /) is placed between the operands. For example ( A + B ) * C - D / E
<BR>
Q2: What is Postfix Notation ?<BR>
Ans: Postfix notation is a way of writing mathematical expressions where the operator appears after the operands. This eliminates the need for parentheses and operator precedence rules, making it easier for computers to evaluate expressions using a stack. For example A B + C * D E / -
<BR>
Q3: Why use Postfix Notation ?<BR>
Ans: Postfix notation (Reverse Polish Notation) is used because of its practical advantages, especially in computing and mathematical evaluation. Here's why it stands out:
Key Reasons to Use Postfix Notation:
1. No Need for Parentheses 

In infix notation, we need parentheses to show which part of the expression to solve first.

In postfix notation, the order of operations is already clear, so we don’t need parentheses.

Example:

Infix: ( A + B ) * C

Postfix: A B + C *

2. Easier for Computers to Solve 

Computers can evaluate postfix expressions easily using a stack.

No need for complex rules about operator precedence.

Example (Step-by-Step Stack Evaluation):

Expression: 2 3 + 4 *
Step 1: Push 2
Step 2: Push 3
Step 3: Apply '+' → (2 + 3 = 5), push 5
Step 4: Push 4
Step 5: Apply '*' → (5 * 4 = 20), push 20
Result: 20

3. No Confusion in Solving Equations 

In infix notation, we have to follow precedence rules (like solving multiplication before addition).

In postfix notation, we simply solve from left to right, making it easier to follow.

4. Used in Compilers & Calculators 

Many programming languages convert infix expressions into postfix before solving them.

Some scientific calculators (like HP calculators) use postfix notation because it's simpler to process.
<<<<<<< HEAD
</p>
Q4: Conclusion ?
=======
<BR>
Q4: Conclusion ?<BR>
>>>>>>> b0dc045247dedb10a5fbf1661abcaf05dba44195
Ans: Postfix notation (Reverse Polish Notation) is a simple and efficient way to write and solve mathematical expressions. Unlike infix notation, it doesn’t need parentheses or rules for operator precedence because the order of operations is always clear. This makes it easier for computers and calculators to process.
It’s commonly used in programming, compilers, and embedded systems because it’s faster and avoids confusion. While humans may find infix notation easier to read, postfix notation is better for machines because it works with stacks, which are simple to use for calculations.
Overall, postfix notation helps make calculations faster and simpler, especially for computers.
<BR>
====================THANKYOU====================
