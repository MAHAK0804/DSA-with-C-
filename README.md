DSA(C++)

•	Datatypes:-

DATATYPES




Primitive                                                  Derived                           User-defined
Integer,float,character,Boolean                                                       function,array,pointer,reference                            class,structure,union,enum

INT:- The first bit show the sign of number , first bit also called MSB(most significant bit), if MSB=1 then number is –ve else number is +ve.


•	C++:-


#include<iostream>
int main(){
std::cout<<”hello”;
return 0;
}

In above c++ program there is some basic concept:
•	#include:- Preprocessor Directives used to include files
•	Iostream:- Header file for taking inpt and printing output
•	Main:-  the execution of code begins from main function
•	Cout: used to display ouput in quotation marks
•	Return 0: exit status of a function

•	Operator:

Operator are he symbols that tell the compiler to perform some specific operations.
1.	Arithmetic Operators:
	Binary Operators (+,-,*,/,%)
	Unary Operators(++{Incrementer},--{Decrementer})

Pre Incrementer(++a)
Int a=10;
Int b;
B=++a;
Cout<<a<<””<<b;

Ouput:
A=11
B=11
		Post Incrementer(a++)
Int a=10;
Int b;
B=a++;
Cout<<a<<’’’<<b;

Output:
A=11
B=10

2.	Relational operators:
Return the Boolean values(==,!=,<,>,<=,>=)
3.	Logical operators:
Used to connect multiple conditions together or to reverse logical value.
•	&&: AND gives us true if both operands are true , else false.
•	||: OR gives  us true if at least one of the operands are true.
•	! :  NOT give the opposite logical value of the operand.
4.	Bitwise operator:
Operate on bits and perform bit by bit operations.
AND(&), OR(|), XOR(^), Ones complement(~),Left shift operator(<<), Right shift operator(>>)
5.	Assignment operator
6.	Miscellaneous operators:
	Sizeof(): Returns the size of variables.
	Condition?X:Y  - Returns value of X if condition is true or else value of 
                               Y.
	Cast :  Convert one data type to another.
	Comma(,):  Causes a sequence of operations to be performed.
	& :  Returns the address of a variable.
	* :  Pointer to a variable.


Operator Precedence:
	 
 

 

•	Functions:

Functions is a piece of code that perform a specific task.

Syntax: 
returnType functionName(parameter1, parameter2,…..){
//function body}
NOTE:
1.	Only names of variables are passed and not their type while calling a function.
2.	We pass the values, not variables themselves. Local variables are created in functions which are destroyed on returning from them.
3.	A function can be called from any other function and main function.
