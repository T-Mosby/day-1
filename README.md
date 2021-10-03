#day1 
# 1.
As we know in order to declare a variable in javascript we have two options either declare with var or declare with let. Now the question is when to use var and when to use let i.e what are the major difference between both.

In the following text we come to know the major difference between var and let in javascript.

The main difference between let and var is that scope of a variable defined with let is limited to the block in which it is declared while variable declared with var has the global scope. So we can say that var is rather a keyword which defines a variable globally regardless of block scope.

The scope of let not only limited to the block in which it is defined but variable with let also do not get added with global window object even if it get declared outside of any block. But we can access variable with var from window object if it is defined globally.

Due to limited scope let variables are usually used when there is limited use of those variables such as in for loops, while loops or inside the scope of if conditions etc while var variable is used when value of variable need to be less change and used to accessed globally.

Also, one difference between var and let is variable with var can be redeclared to some other value while variable could not be redeclared if it is defined with let.


# 2.
we can create arrays by using new operator and we know that every object is created using new operator. Hence we can say that array is also an object. 
a null is an object. Its type is object . null is a special value meaning "no value. undefined is not an object, its type is undefined
