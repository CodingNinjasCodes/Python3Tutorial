# Python 3.x Tutorial

## Python
Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python’s elegant syntax and [dynamic typing](http://c2.com/cgi/wiki?DynamicTyping), together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.
Like Java, Python is also an [interpreted](http://www.codeproject.com/Articles/696764/Differences-between-compiled-and-Interpreted-Langu) programming language.

### Python 3.x

Current tutorial will be focused on Python 3.x . Python 3.x is the present and future of the language.


## Interpreter and Interactive shell
Python is an interpreted language and comes with an interactive shell.The interactive shell is interactive in the way that it stands between the commands or actions and their execution.

To fire up the interactive shell,type :
~~~~
$ python3
~~~~
in the terminal on your machine. If Python 3.x is succesfully installed on your machine, you should get such kind of output.
~~~~
Python 3.5.1+ (default, Mar 30 2016, 22:46:26) 
[GCC 5.3.1 20160330] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
~~~~
type 
~~~~
>>> exit()
~~~~ 
to quit the interactive shell.


## Data types and variables
### **What is a variable ?**


A variable is something which can change. A variable is a way of referring to a memory location used by a   computer program.In many programming languages a variable is a symbolic name for this physical location. This memory location contains values, like numbers, text or more complicated types. We can use this variable to tell the computer to save some data in this location or to retrieve some data from this location. 

### **How to create a variable in Python ?**


You create a varible in Python by the the following syntax.


**variable_name = variable_value**
`my_variable = 90`
Here we have created a variable with identifier name as *my_variable* and has assigned a value of *10* to it.

#### **How to print something in Python ?**
Python comes with a built in command `print` to print something on the interactive shell.
type `print("Hello world!")` in the interactive shell, after this you'll see a message; **Hello world!**.
Similarly to print the variable *my_variable* that we created before, type `print(my_variable)`, you will see a message saying **90**.

If something like a prompt comes up, similar like this :
~~~~
Traceback (most recent call last):
NameError: name 'my_variable' is not defined
~~~~ 
this means that we have not defined the variable *my_variable* in Python.

#### **How are variables stored in memory?** 
This section is especially intended for C, C++ and Java programmers, because the way these programming languages treat basic data types is different from the way Python does it. Those who start learning Python as their first programming language may skip to the next section. 


In Python,a variable can be seen as a container (or some say a pigeonhole) to store certain values. While the program is running, variables are accessed and sometimes changed, i.e. a new value will be assigned to a variable. 
By changing of value of a variable we mean that old value is removed and now the container i.e the variable now contains the new value.
For C++ and Java programmers the above concept of how variables are stored in memory might be different from the way they are stored in C++ and Java.

Putting values into the variables can be realized with assignments. The way you assign values to variables is nearly the same in all programming languages. In most cases the equal "=" sign is used. The value on the right side will be saved in the variable name on the left side. 

