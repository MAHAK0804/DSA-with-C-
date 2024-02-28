<h1>DSA(C++)</h1>

<h3>• Datatypes:-</h3>
<br>
<li>
Primitive   --- Integer,float,character,Boolean</li>                                              
<li>Derived     ---  function,array,pointer,reference   </li>                   
<li>User-defined --- class,structure,union,enum
</li>
INT:- The first bit show the sign of number , first bit also called MSB(most significant bit), if MSB=1 then number is –ve else number is +ve.


<h3>• C++:-</h3>
<br>
<pre>
#include<iostream><br>
int main(){<br>
std::cout<<”hello”;<br>
return 0;<br>
}<br>
		 </pre>
In above c++ program there is some basic concept:<br>
• #include:- Preprocessor Directives used to include files<br>
• Iostream:- Header file for taking inpt and printing output<br>
• Main:-  the execution of code begins from main function<br>
• Cout: used to display ouput in quotation marks<br>
• Return 0: exit status of a function<br>

<h3>• Operator:</h3><br>

Operator are he symbols that tell the compiler to perform some specific operations.
 <h4>1.	Arithmetic Operators:</h4><br>
	Binary Operators (+,-,*,/,%)<br>
	Unary Operators(++{Incrementer},--{Decrementer})<br>

<mark>Pre Incrementer(++a)</mark>
<pre>
int a=10;<br>
I\int b;<br>
b=++a;<br>
Cout<<a<<””<<b;<br>

Ouput:<br>
A=11<br>
B=11<br>
	     </pre>

		<mark>Post Incrementer(a++)</mark>
  <pre>
Int a=10;<br>
Int b;<br>
B=a++;<br>
Cout<<a<<’’’<<b;<br>

Output:<br>
A=11<br>
B=10<br>
	</pre>

<h4>2. Relational operators:</h4>
Return the Boolean values(==,!=,<,>,<=,>=)<br>
<h4>3. Logical operators:</h4>
Used to connect multiple conditions together or to reverse logical value.<br>
• &&: AND gives us true if both operands are true , else false.<br>
• ||: OR gives  us true if at least one of the operands are true.<br>
• ! :  NOT give the opposite logical value of the operand.<br>
<h4>4. Bitwise operator:</h4>
Operate on bits and perform bit by bit operations.<br>
AND(&), OR(|), XOR(^), Ones complement(~),Left shift operator(<<), Right shift operator(>>)<br>
<h4>5. Assignment operator</h4>
<h4>6. Miscellaneous operators:</h4>
 Sizeof(): Returns the size of variables.<br>
 Condition?X:Y  - Returns value of X if condition is true or else value of Y.<br>
 Cast :  Convert one data type to another.<br>
 Comma(,):  Causes a sequence of operations to be performed.<br>
 & :  Returns the address of a variable.<br>
 * :  Pointer to a variable.<br>


Operator Precedence:<br>
	 
 

 

<h3>• Functions:</h3> <br>

Functions is a piece of code that perform a specific task.<br>

Syntax: <br>
returnType functionName(parameter1, parameter2,…..){<br>
//function body}<br>
NOTE:<br>
1.	Only names of variables are passed and not their type while calling a function.<br>
2.	We pass the values, not variables themselves. Local variables are created in functions which are destroyed on returning from them.<br>
3.	A function can be called from any other function and main function.<br>
