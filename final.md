
<p align="center">
   <img src="https://miro.medium.com/max/1200/1*PPIp7twJJUknfohZqtL8pQ.png" alt="Python Programming"
        width="500" height="150">
   <br />
   <b> VARIABLES AND DATATYPES IN PYTHON </b>
   <br />
   <b> This mark down file helps understand VARIABLES and DATATYPES in PYTHON. </b>
   <br />
</p>

---

### 📋 Variables in Python

<p align="justify">
   Variables in Python are identifiers just like in any other programming language. They can be treated off like a name given to a memory location. Once a variable is declared, the memory block could be located using only the variable name. Any operations on that particular memory location have to be performed using the variable name. Variables always need to go through two stages, one is declaration and other one is initialization. Variable declaration deals with assigning the user-defined identifier as a name to a memory location, and initialization is assigning a value to that particular memory location. In general, two stages are combined into a single statement but in most of the programming languages explicit definition of a datatype is necessary, which is not the case with Python.
</p>
<p align="justify">
   Python is not a "statically-typed" language, therefore variable declaration doesn't even exist. A variable is created only when a value is assigned to it. As the variable is being provided with the value it is going to hold beforehand, defining the datatypes is not needed. Just like in any other programming language, if the variable name is used and an operation is performed, the operations' result reflects the value held in the memory location.
</p>
</ br>

<b> Rules for naming variables in Python </b>
<p align="justify">
   All programming languages have certain rules that need to be followed when programmer is working with variables. Python is no different. Almost all the programming languages have similar rules for naming variables, but to be specific the rules to be followed in Python are thereby,
</p>

   - The variable name can only have alpha-numeric characters and an underscore (A-Z, a-z, _).
   - The variable name can begin with a alphabet or an underscore i.e., they cannot begin with a numeric character.
   - Just like in most of the programming languages, variables in Python are case-sensitive.
   - Keywords in Python cannot be used as a variable names.

<p align="justify">
   Python doesn't require explicit datatype definition, but it doesn't limit it to only a particular datatype. When a variable in Python is defined, assigning it to a numeric value, impicitly it means that the variable defined holds numeric data and therefore datatype assigned to this variable would be numeric. But the same variable can be used to hold strings as well, and if a string is assigned to the same variable, the variable now is of the string type. The programmer always can change the value of the variable, which in turn could lead to change in type of the variable, which most of the programming languages fail to provide.
</p>

```
a=10 //assigning a numeric value
>>> print a
10
>>> a= “Hello” //reassigning a string value
>>> print a
Hello
b=c=20 //multiple variable assignment
>>> print(b)
20
>>> print(c)
20
```

---

### 📋 Datatypes in Python

<p align="justify">
   The data type of a variable or object determines which operations can be applied to it. Once a variable is assigned a data type, it can be used for computations in the program. The best thing about Python is that the data type doesn’t need to be defined when declaring a variable. Data types exist, but the variables are not bound to any of them. Languages that act in this way are called "dynamically-typed" languages. The datatypes in Python can be categorized into two,
   
   - Primitive Datatypes
   - Non-Primitive Datatypes (Python specific datatypes)
   
</p>

<p align="center">
   <img src="http://hindiwalo.com/wp-content/uploads/2020/06/Untitled-Document-3-1024x656.png" alt="Datatypes in Python"
        width="700" height="500">
</p>
<b> Primitive Datatypes in Python </b>
</br>
<p align="justify">
   Primitive datatypes can be defined as the most basic datatypes of any programming language. They alongside variables form the building blocks of the program. These are the datatypes upon which non-primitive datatypes are built. Primitive datatypes are mutable in nature, meaning the variable declared using these datatypes can have a change in its value. Primitive datatypes in Python can furthur be classified into four.
   
   - Integer
   - Float
   - Complex
   - String
</p>
<p align="justify">
   Integer value is represented by the int class. It contains positive or negative whole numbers (without fraction or decimal). In Python there is no limit to how long an integer value can be.
</p>
<p align="justify"> 
Float value is represented by the float class. It is a real number with floating point representation. It is specified by a decimal point. Optionally, the character e or E followed by a positive or negative integer may be appended to specify scientific notation. 
</p>
<p align="justify">
Complex Numbers is represented by the complex class. It is specified as (real part) + (imaginary part)j. If for example, the complex number is 5+5j, real part is 5 and the imaginary part is 5 again.
</p>
<p align="justify">
Like many other popular programming languages, strings in Python are arrays of bytes representing unicode characters.However, Python does not have a character data type, a single character is simply a string with a length of 1. Square brackets can be used to access elements of the string.
</p>

```
a=10 //assigning a integer value
>>> print a
10
>>> print(type(a)) //print the type of a
>>> <class 'int'> //int type

a=10.3 //assigning a float value
>>> print a
10.3
>>> print(type(a)) //print the type of a
>>> <class 'float'>

a=5+3j //assigning a complex value
>>> print a
5+3j
>>> print(type(a)) //print the type of a
>>> <class 'complex'>

a="HELLO" //assigning a string value
>>> print a
HELLO
>>> print(type(a)) //print the type of a
>>> <class 'str'>
```
<p align="justify">
These are only the basic primitive datatypes in Python. But it is not like Python has only these Primitive datatypes. There are many more which include boolean, long.. etc. but they are out of scope of this markdown file.
</p>
</br>
<b> Non-Primitive Datatypes in Python </b>
</br>
<p align="justify">
   Non-Primitive datatypes can be defined as the derived datatypes. These are the datatypes which are built upon primitive datatypes. In contrast to primitive datatypes, non-primitive data types not only store values, but a collection of values in different formats. Non-Primitive datatypes in Python can furthur be classified into four.
   
   - List
   - Tuple
   - Set
   - Dictionary
</p>
</br>
<b> List </b>
</br>
<p align="justify">
Lists are a very useful variable type in Python. A list can contain a series of values. List variables are declared by using brackets [ ] following the variable name. All lists in Python are zero-based indexed. When referencing a member or the length of a list the number of list elements is always the number shown plus one. Assigning data to a specific element of the list can be done using an index into the list. The list index starts at zero. Lists aren’t limited to a single dimension. Although most people can’t comprehend more than three or four dimensions lists having multiple dimensions can be declared by separating it with commas.
</p>


