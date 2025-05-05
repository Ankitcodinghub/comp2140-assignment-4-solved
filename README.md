# comp2140-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [COMP2140 Assignment 4 Solved](https://www.ankitcodinghub.com/product/comp2140-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101071&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2140 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Question 1: Expression Trees

This question can be done after Week 8 of the course but reviewing Week 9 before beginning is recommended.

Read through all of the instructions for question 1 before beginning.

You will use an expression tree to store and manipulate algebraic expressions. Your expression tree will be constructed from nodes, as described below.

Examples of expression trees are shown in the Week 8 class materials. Some additional examples of expression trees are

+** /\/\/\

A-A^+- /\ /\ /\/\

BC B+ ABCD /\

CD

(A+(B-C)) (A*(B^(C+D))) ((A+B)*(C-D))

One advantage of postfix and prefix notations is that parentheses are not needed to specify order of operations. In this question you will create expression trees from both postfix and prefix forms of algebraic expressions. You will also simplify the expression trees and print infix, postfix, and prefix versions of the expressions stored in the trees. Your program will read commands from a file and output the result of executing those commands.

Input

The input file will consist of one command per line, where the command will be one of the 6 options below. If additional information is needed, it will follow on the same line. Possible commands are:

<ul>
<li>COMMENT – A line beginning with “COMMENT” should be echoed to the console. No manipulation of the tree is required.</li>
<li>NEW – A line beginning with “NEW” will construct a new expression tree. Any existing tree will be discarded and replaced with the new tree. The expression that follows “NEW” will be either prefix or postfix notation. Your program should be able to determine which notation is used. All operands and operators will be separated by spaces, so that you may split the line read from file into tokens, where each token contains a String that will correspond to a node in the tree.
Output a single statement, “New tree constructed”, when a tree is successfully created. Please see the sections below on constructing expression trees for some hints on how to read in expressions and construct trees.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 4

DEPARTMENT AND COURSE NUMBER: COMP 2140

<ul>
<li>PRINTPREFIX – A line beginning with “PRINTPREFIX” will print the current tree using prefix notation. Similar to the prefix notation used when reading from the input file, separate all operands and operators with a space.</li>
<li>PRINTPOSTFIX – A line beginning with “PRINTPOSTFIX” will print the current tree using postfix notation. Similar to the postfix notation used when reading from the input file, separate all operands and operators with a space.</li>
<li>PRINTINFIX – A line beginning with “PRINTINFIX” will print the current tree using infix notation. Infix notation requires parentheses to indicate the order of operations, and you will print a fully parenthesized expression, where each operand-operator-operand is enclosed in parentheses. Examples of fully parenthesized expressions are
( ( 8 + 6 ) * ( 4 – 5 ) ) and ( ( ( B + 5 ) * 4 ) ^ 3 ).
</li>
<li>SIMPLIFY – A line beginning with “SIMPLIFY” will simplify the current tree, following
common arithmetic rules, and output the statement “Tree simplified” when complete. Traverse the tree and stop to consider each node containing an operator. (You need to determine which type of traversal is best to use.) Look at the subtree consisting of the operator node and its left and right subtrees, and simplify where possible. Some examples to get you started:
</li>
</ul>
o If both children of an operator are numeric values, perform the operation and replace that subtree with the result stored in a single node.

o A * 1 = A. If the operator is * and one of the children is 1, replace the subtree with the other child.

o A * 0 = 0. If the operator is * and one of the children is 0, replace the subtree with 0.

o A ^ 1 = A. If the operator is ^ and the right child is 1, replace the subtree with the left child.

Nodes for Expression Trees

The nodes in the expression tree will have the ability to hold three types of information: operators, variables, or constants. Possible operators will be +, -, *, and ^. We will omit division so that we can deal only with integers.

The fields in your nodes should be:

<ul>
<li>A type that identifies the node as an operator, variable, or a number. Something similar to enum NodeType{OPERATOR, VARIABLE, NUMBER;} is appropriate.</li>
<li>A char that will store the operator for operator nodes. The only valid characters are ‘+’, ‘-‘, ‘*’, and ‘^’.</li>
<li>A String that will store the variable name for variable nodes.</li>
<li>An int that will store the value for numerical nodes.</li>
<li>Two Node references, that refer to the left child and the right child. For leaf nodes these
will be null.

Note: Even though we will use ‘^’ as the symbol (e.g. x ^ y to represent xy), use the pow()

method in your program. ^ in Java is a bitwise XOR.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 4

DEPARTMENT AND COURSE NUMBER: COMP 2140

The Expression Tree Class

Your expression tree class must have methods that allow it to carry out the expected commands. Recursion should be used when appropriate.

A Queue to store Nodes

You will need a queue of Nodes (i.e. a queue where each item stored in the queue is a Node) to aid in the construction of an expression tree from prefix notation.

You may choose the underlying implementation for your queue that you think is most appropriate (linked list or array). The implementation that you choose should be hidden from a user of the class. That is, the user will enqueue and dequeue Nodes, and will not know how they are managed inside the queue.

Your queue must have the following methods:

<ul>
<li>A constructor that creates an empty queue.</li>
<li>A boolean isEmpty() method that returns a boolean, indicating whether the queue is
empty.
</li>
<li>A boolean enqueue(Node toAdd) method that will insert the given Node into the
queue. This method will return true if the enqueue is successful, and return false if the

enqueue fails.
</li>
<li>A Node dequeue() method that will dequeue and return the Node at the front of the
queue. This method removes the returned Node from the queue. This method should

return null if the user tries to dequeue from an empty queue.
</li>
<li>A Node peek() (or front) method that returns the Node at the front of the queue. This
method does not remove the returned Node from the queue. This method should return null if the user tries to peek at an empty queue.

A Stack to store Nodes

You will need a stack of Nodes (i.e. a stack where each item stored in the stack is a Node) to aid in the construction of an expression tree from postfix notation.

As for the queue class, you may choose the underlying implementation for your queue that you think is most appropriate (linked list or array). The implementation that you choose should be hidden from a user of the class. That is, the user will push and pop Nodes, and will not know how they are managed inside the stack.

Your stack must have the following methods:
</li>
</ul>
<ul>
<li>A constructor that creates an empty stack.</li>
<li>A boolean isEmpty() method that returns a boolean, indicating whether the stack is
empty.
</li>
<li>A boolean push(Node toAdd) method that will insert the given Node into the stack.
This method will return true if the push is successful, and return false if the push fails.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 4

DEPARTMENT AND COURSE NUMBER: COMP 2140

<ul>
<li>A Node pop() method that will pop and return the Node on the top of the stack. This method removes the returned Node from the stack. This method should return null if the user tries to pop from an empty stack.</li>
<li>A Node peek() (or top) method that returns the Node on the top of the stack. This method does not remove the returned Node from the stack. This method should return null if the user tries to peek at an empty stack.
Constructing An Expression Tree From Postfix Notation

Constructing an expression tree from postfix notation is similar to evaluating a postfix expression (discussed in Week 6, slides #142-157). However, instead of storing operands on the stack, you store entire subtrees. Read along the postfix expression from left to right, as we did when evaluating a postfix expression. When you encounter an operand (a number or a variable name):
</li>
</ul>
<ul>
<li>Make a Node that holds the operand.</li>
<li>Push that Node onto the stack.
When you encounter an operator:
</li>
</ul>
<ul>
<li>Pop two operands/subtrees (B and C) off the stack.</li>
<li>Create a new Node (A) that holds the operator.</li>
<li>Attach B (the first node popped) as the right child of A.</li>
<li>Attach C (the second node popped) as the left child of A.</li>
<li>Push A onto the stack. Note that this effectively pushes the entire subtree onto the stack,
because the stack holds node A, and A is linked to B and C.

When you’re done processing the postfix expression, pop the one remaining item off the stack, which will be the root node of the tree that depicts the entire postfix expression.

Hint: Before writing any code, run through this algorithm on paper for a few examples. For example, the postfix expression DEF+* should produce the tree for the infix expression D*(E+F).

Constructing An Expression Tree From Prefix Notation

To construct an expression tree from prefix notation, make use of a queue of nodes to temporarily store subtrees as you build the full tree. Begin by reading the prefix expression from left to right and placing the entire expression into the queue. That is, for each operand or operator, create a node containing that token and put it into the queue. Then, until the queue contains only a single item, remove the item at the front of the queue:
</li>
</ul>
<ul>
<li>If the item is an operand or an operator that already has children, enqueue it again at the back/end of the queue without any modification.</li>
<li>If the item is an operator without children, examine the next two items in the queue.

o If those two items are each either an operand or operator with children, remove

them from the queue.

▪ Set the first item removed as the left child of the operator.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 4

DEPARTMENT AND COURSE NUMBER: COMP 2140

▪ Set the second item removed as the right child of the operator.

▪ Enqueue the operator again at the back/end of the queue (it is now

linked to two children).

o If they are not both operands or operators with children, do not remove them

from the queue (you’ll process them on the next iterations of the loop), and enqueue the operator (without children) again at the back/end of the queue.

Hint 1: Note that while operator nodes should always have two non-null children in a valid tree, you will sometimes want to queue operator nodes temporarily without children while building the tree.

Hint 2: Notice that we want to be able to peek at (examine) two items in the queue without dequeuing them. For this assignment (even though it is not a real queue operation), add a peek2 method to your Queue class. This method should return (without removing) the second item in the queue (and return null if a second item does not exist).

Hint 3: Before writing any code, run through this algorithm on paper for a few examples. For example, the prefix expression *D+EF should produce the tree for the infix expression D*(E+F).

Application (Main) Class – named &lt;your last name&gt;&lt;your first name&gt;A4Q1

Your application class should process commands from an input file, as described above, until the end of the file. You may assume that the data file will be named A4Q1input.txt and will be located in the same directory as your .java file. (A file is not provided – you should create your own tests as you write your program.)

Sample Program Input

<pre>  COMMENT Starting tests...
  NEW C 3 + 5 4 - *
  PRINTINFIX
  SIMPLIFY
</pre>
<pre>  PRINTINFIX
  PRINTPOSTFIX
  PRINTPREFIX
  COMMENT Second Test
  NEW firstVble 1 ^ secondVble 0 * firstVble secondVble + 5 * - +
  PRINTINFIX
</pre>
<pre>  SIMPLIFY
  PRINTINFIX
  COMMENT End of tests.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 4

DEPARTMENT AND COURSE NUMBER: COMP 2140

Sample Program Output

<pre>  Starting tests...
</pre>
<pre>  New tree constructed
</pre>
((C+3)*(5-4))

<pre>  Tree simplified
</pre>
(C+3)

C3+

+C3

Second Test

<pre>  New tree constructed
</pre>
<pre>  ( ( firstVble ^ 1 ) + ( ( secondVble * 0 ) - ( ( firstVble +
  secondVble ) * 5 ) ) )
</pre>
<pre>  Tree simplified
  ( firstVble - ( ( firstVble + secondVble ) * 5 ) )
  End of tests.
</pre>
Additional Notes

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>You may assume that the input file is free of errors. That is, you may assume that the file contains one command per line, that all tokens within a line will be separated by a space, and that only valid commands are provided. You may also assume that given expressions are valid expressions (i.e. the number and order of operands and operators are such that they construct a valid algebraic expression).</li>
<li>Place all classes for question 1 in the same file.</li>
<li>Submit ONE .java file containing all the source code for question 1. The .java file MUST be named &lt;your last name&gt;&lt;your first name&gt;A4Q1.java (e.g. SmithJohnA4Q1.java). Do not submit any output. Your code will be run during marking. Make sure that your code</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
compiles without errors (see the Assignment Information file for some common issues).

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
[Programming Standards are worth 8 marks]

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 4

DEPARTMENT AND COURSE NUMBER: COMP 2140

Question 2: 2-3-4 Trees [12 marks]

This question requires material from Week 10.

Similar to the examples seen in Week 10 for 2-3 and 2-3-4 trees, you will redraw a 2-3-4 tree after each insertion listed below. No code is required for this question.

In this question we are looking at the type of 2-3-4 tree that contains data in both interior and leaf nodes. Recall that 2-3-4 trees contain nodes with up to 3 data items/4 children per node.

Begin with an empty 2-3-4 tree. Insert the values listed below, in the order listed, re-drawing the entire tree after EACH insertion. (You may also draw an intermediate stage when node splitting is required, if you find that helpful.) Use a top-down 2-3-4 tree, where full nodes are split on the way down to the insertion point.

You may use Photoshop, Powerpoint, or other software to draw your trees, or you may draw your trees by hand on paper and scan or photograph your solution. Whatever method you choose, convert your solution into a pdf file. Your answer must be legible after conversion to pdf,

</div>
</div>
<div class="layoutArea">
<div class="column">
and be

1. 2. 3. 4. 5. 6. 7. 8. 9. 10. 11. 12. 13. 14. 15. 16. 17.

</div>
<div class="column">
well-organized so that it can be easily marked.

Begin with an empty 2-3-4 tree. Insert 28.

Insert 15.

Insert 22.

Insert 24. Insert 41. Insert 33. Insert 31. Insert 36. Insert 25. Insert 44. Insert 42. Insert 48. Insert 40. Insert 37. Insert 39. Insert 47.

</div>
</div>
<div class="layoutArea">
<div class="column">
Your pdf file must be named &lt;your last name&gt;&lt;your first name&gt;A4Q2.pdf (e.g. SmithJohnA4Q2.pdf). Submit your pdf file to the Assignment 4 submission folder in UM Learn, along with your solution to question 1.

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
