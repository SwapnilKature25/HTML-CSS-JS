# 1. Working with Varables  =>  

    => var is a reference name of a memory block.
    => Var are created or stored in RAM(stack Area).     
       (stack,heap, method, register) area
       RAM  =>  JS Runtime Area   =>  Stack, Heap , Class/Method, Register areas used by the programming lang.
            1. stack area => Local variables, parameters, current execution code.
            2. heap area  =>  array,object.
            3. class/method area  =>  class, constructors, static items.
            4. register area  =>  it contains the algorithm / program schedule/ contains order of execution of program


    => hard disk not hold variables.
    => Var are used to store/hold a value for reuse purpose and automatically substitute values in steps.
       automatically substitute -  it reduces the lines.

    

# 2. Delcare var ?

    => 3 ways to define variables :  var , let, const








# 3. Datatype : 
    Primitive Datatype  :  String , number, boolean, undefined, null(obj)
    Non-Primitive Datatype  :  Array, class & object , funnctions.


    typeOf : 
    typeOf is one of reversed word, it's used to identify datattype of a variable or value.
    Syn : typeOf var_name
          typeOf value    


    Js does not allow Char value it use only String.


    # non-primitive datatype :
     every class first letter of class should be capital




# Diff b/w var & let

        var                                 let
supports re-defination/redeclaration     not support
supports hoisting                                   not
for changable use var                   for const,fixed, global use let



var allowed to use var first and declare later but let doesn't





# Js Dialogs       

1. alert :
displaying message
alert("text")
don't add html tag in alert functions.


2. confirm :
taking  confirmation from user (cross checking)
confirm("text")

3. prompt : 
taking input from user (runtime values)
prompt("text")
-> if user didn't enter the data and tap cancel then it will return null if tap ok blank space.

all the above 3 fun accessible through window object.






# Js Operators :

-> Operator is a Symbol(special char) and it is used to perform certain operations(task).
-> Every Operator is a Symbol, but every symbol is not an operator.
-> Every operator requires some values, those are called operands.
-> ex. a+b

# Expression  :  
It's Combination of one operator and some operands.




# Operators Categories :

1. Unary   -> It requires one operand  -> incr/ decr

2. Binary   -> It requires two operand 
                -> Arithmetic
                -> relational
                -> logical
                -> Logical
                -> Assignment
                -> Concatenation

3. Ternary   -> It requires three operand   -> Conditional