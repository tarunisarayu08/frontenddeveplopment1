# frontenddeveplopment1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"
    <meta name="viewport" content="width=device-width,">
   <title>My Notes</title>
</head>
<body>
    <h1 style="color: blue">My Notes</h1>
	<nav id="sidebar">
		<li>
			<a class="nav item" href="#Introduction">Introduction</a>
		</li>
		<li>
			<a class="nav item" href="#chapter-1">Chapter-1</a>
		</li>
		<li>
			<a class="nav item" href="#chapter-2">Chapter-2</a>
		</li>
		<li>
			<a class="nav item" href="#chapter-3">Chapter-3</a>
		</li><li>
			<a class="nav item" href="#chapter-4">Chapter-4</a>
		</li>
		<li>
			<a class="nav item" href="#chapter-5">Chapter-5</a>
		</li>
	</nav>
    <section id="Introduction">
<h1>Introduction To PYTHON</h1>
    <p>Python is a widely used general-purpose, high level programming language. It was created by Guido van Rossum in 1991 and further developed by the Python Software Foundation. It was designed with an emphasis on code readability, and its syntax allows programmers to express their concepts in fewer lines of code.

        Python is a programming language that lets you work quickly and integrate systems more efficiently.
        
        There are two major Python versions: Python 2 and Python 3. Both are quite different</p>
        <h2>Beginning with Python programming:</h2>
        <ol type="1">
        <li><h3>Finding an Interpreter:</h3></li>
        <p>Before we start Python programming, we need to have an interpreter to interpret and run our programs. There are certain online interpreters like<a href="page.html"> https://ide.geeksforgeeks.org/ </a>that can be used to run Python programs without installing an interpreter.</p>
        <h3>Windows:</h3>
        <p>There are many interpreters available freely to run Python scripts like IDLE (Integrated Development Environment) that comes bundled with the Python software downloaded from <a href="page.html"> http://python.org/.</a></p>
        <h3>Linux:</h3>
        <p> Python comes preinstalled with popular Linux distros such as Ubuntu and Fedora. To check which version of Python you’re running, type “python” in the terminal emulator. The interpreter should start and print the version number.</p>
        <h3>macOs</h3>
        <p> Generally, Python 2.7 comes bundled with macOS. You’ll have to manually install Python 3 from <a href="page.html">http://python.org/.</a></p>
        <li><h3>Writing our first program:</h3></li>
        <p>Just type in the following code after you start the interpreter</p><br>
        <p># Script Begins
            <br>
            print("GeeksQuiz")
            <br> 
            # Scripts Ends</p>
            <p>Output:GeeksQuiz</p><br>Let’s analyze the script line by line.

            <h4>Line 1: [# Script Begins]</h4> In Python, comments begin with a #. This statement is ignored by the interpreter and serves as documentation for our code.
            <h4>Line 2: [print(“GeeksQuiz”)]</h4>To print something on the console, print() function is used. This function also adds a newline after our message is printed(unlike in C). Note that in Python 2, “print” is not a function but a keyword and therefore can be used without parentheses. However, in Python 3, it is a function and must be invoked with parentheses.
            <h4>Line 3: [# Script Ends]</h4>This is just another comment like in Line 1.
            Python designed by Guido van Rossum at CWI has become a widely used general-purpose, high-level programming language.
            <h3>Prerequisites:</h3>
            Knowledge of any programming language can be a plus.
        </ol>
    </section>
        <section id="chapter-1">
        <h1>Input/Output</h1>
        <p><b>input ():</b> This function first takes the input from the user and converts it into a string. The type of the returned object always will be <class ‘str’>. It does not evaluate the expression it just returns the complete statement as String. For example, Python provides a built-in function called input which takes the input from the user. When the input function is called it stops the program and waits for the user’s input. When the user presses enter, the program resumes and returns what the user typed. 
    
            <b>Syntax:</b> inp = input('STATEMENT')
        </p>
        <b><h3>How the input function works in Python :</h3> </b>
     
    
    <p>When input() function executes program flow will be stopped until the user has given input.The text or message displayed on the output screen to ask a user to enter an input value is optional i.e. the prompt, which will be printed on the screen is optional.Whatever you enter as input, the input function converts it into a string. if you enter an integer value still input() function converts it into a string. You need to explicitly convert it into an integer in your code using typecasting. </p>
    <p>
       <b> raw_input():</b> This function works in older version (like Python 2.x). This function takes exactly what is typed from the keyboard, converts it to string, and then returns it to the variable in which we want to store it.</p>
      <b> Accepting Input from Console</b> User enters the values in the Console and that value is then used in the program as it was required. To take input from the user we make use of a built-in function input(). 
      <b>ex:</b># input
      input1 = input()
       
      # output
      print(input1)
     <p><b> 1. Typecasting the input to Integer: </b>There might be conditions when you might require integer input from the user/Console, the following code takes two input(integer/float) from the console and typecasts them to an integer then prints the sum. </p>
     <b>ex:</b>
    # input
    num1 = int(input())
    num2 = int(input())
     
    # printing the sum in integer
    print(num1 + num2)
    <p><b><h4>2. Typecasting the input to Float</h4></b> To convert the input to float the following code will work out. </p>
    
    
    <b>ex:</b># input
    num1 = float(input())
    num2 = float(input())
     
    # printing the sum in float
    print(num1 + num2)
    <p><b><h4>3. Typecasting the input to String:</h4></b> All kinds of input can be converted to string type whether they are float or integer. We make use of keyword str for typecasting. 
    
     we can also take input string by just writing input() function by default it makes the input string</p>
    
    
    <b>ex:</b><p># input
    string = str(input())
     
    # output
    print(string)
     
    # Or by default
    string_default = input()
     
    # output
    print(string_default)</p>
    </section>
    <section id="chapter-2">
           <h1>Python Operators</h1>
            <p>In Python programming, Operators in general are used to perform operations on values and variables. These are standard symbols used for the purpose of logical and arithmetic operations. In this article, we will look into different types of Python operators. 
        
               <b> OPERATORS:</b> These are the special symbols. Eg- + , * , /, etc.
               <b> OPERAND:</b> It is the value on which the operator is applied.</p>
                <p><br><h3>Types of Operators in Python</h3></p>
                  <p>1.Arithmetic Operators<br>
                   2.Comparison Operators</br>
                   3.Logical Operators</br>
                   4.Bitwise Operators</br>
                   5.Assignment Operators</br>
                   6.Identity Operators and Membership Operators</p>
                 <p><h3>Arithmetic Operators in Python:</h3></p>
                   <p>Python Arithmetic operators are used to perform basic mathematical operations like addition, subtraction, multiplication, and division.
        
                    In Python 3.x the result of division is a floating-point while in Python 2.x division of 2 integers was an integer. To obtain an integer result in Python 3.x floored (// integer) is used.</p>
                    <p><h3>Division Operators:</h3>
                        Division Operators allow you to divide two numbers and return a quotient, i.e., the first number or number at the left is divided by the second number or number at the right and returns the quotient. </p>
                        <p>There are two types of division operators: 
        
                            Float division
                            Floor division
                           <h3>Float division:</h3>
                            <p>The quotient returned by this operator is always a float number, no matter if two numbers are integers. For example:</p>
                            
                            # python program to demonstrate the use of "/"
                            print(5/5)
                            print(10/2)
                            print(-10/2)
                            print(20.0/2)
                        </p>
                            <p><h3>Integer division( Floor division):</h3>
                                The quotient returned by this operator is dependent on the argument being passed. If any of the numbers is float, it returns output in float. It is also known as Floor division because, if any number is negative, then the output will be floored. For example:
                                
                                # python program to demonstrate the use of "//"
                                print(10//3)
                                print (-5//2)
                                print (5.0//2)
                                print (-5.0//2)</p>
                                <p>Precedence of Arithmetic Operators in Python
                                    The precedence of Arithmetic Operators in python is as follows:
                                    
                                    <b><br>P - Parentheses<br>
                                    E - Exponentiation<br>
                                    M - Multiplication (Multiplication and division have the same precedence)<br>
                                    D - Division<br>
                                    A -Addition (Addition and subtraction have the same precedence)<br>
                                    S -Subtraction</b></p>
                                    The modulus operator helps us extract the last digit/s of a number. For example:<br>
                                    
                                   <p> x % 10 -> yields the last digit
                                    x % 100 -> yield last two digits</p>
                                    </section>
                                    <section id="chapter-3">
                                        <h1>Data Types in PYTHON</h1>
                                        <p>Data types are the classification or categorization of data items. It represents the kind of value that tells what operations can be performed on a particular data. Since everything is an object in Python programming, data types are actually classes and variables are instances (object) of these classes. The following are the standard or built-in data types in Python:</p>
                                        <ul type="disc">
                                        <li>Numeric</li>
                                        <li>Sequence Type</li>
                                        <li>Boolean</li>
                                        <li>Set</li>
                                        <li>Dictionary</li>
                                        <li>Binary Types( memoryview, bytearray, bytes)</li>
                                        <h3>What is Python type()  Function?</h3>
                                        <p> To define the values ​​of various data types and check their data types we use the type() function. Consider the following examples.</p>
                                        </ul>
                                        <img src="D:\.JPG"></section>
                                        <section id="chapter-4">
                                            <p><h2>Python Strings</h2><br>
                                                A string is a data structure in Python that represents a sequence of characters. It is an immutable data type, meaning that once you have created a string, you cannot change it. Strings are used widely in many different applications, such as storing and manipulating text data, representing names, addresses, and other types of data that can be represented as text.<br><br>
                                      
                                      <b>Example:</b>
                                      
                                      "Geeksforgeeks" or 'Geeksforgeeks'
                                      Python does not have a character data type, a single character is simply a string with a length of 1. Square brackets can be used to access elements of the string.<br>
                                      
                                      <b>Syntax:</b> print("A Computer Science portal for geeks")<br>
                                      <b>Output:</b> A Computer Science portal for geeks<br><br>
                                      <h4>Creating a String in Python</h4>
                                      Strings in Python can be created using single quotes or double quotes or even triple quotes.<br>
                                      <b>Syntax:</b><br>
                                      # Creating a String<br>
                                      # with single Quotes<br>
                                      String1 = 'Welcome to the Geeks World'<br>
                                      print("String with the use of Single Quotes: ")<br>
                                      print(String1)<br><br>
                                       
                                      # Creating a String<br>
                                      # with double Quotes<br>
                                      String1 = "I'm a Geek"<br>
                                      print("\nString with the use of Double Quotes: ")<br>
                                      print(String1)<br><br>
                                       
                                      # Creating a String<br>
                                      # with triple Quotes<br>
                                      String1 = '''I'm a Geek and I live in a world of "Geeks"'''<br>
                                      print("\nString with the use of Triple Quotes: ")<br>
                                      print(String1)<br><br>
                                       
                                      # Creating String with triple<br>
                                      # Quotes allows multiple lines<br><br>
                                      
                                      
                                      String1 = '''Geeks<br>
                                      
                                                  For<br>
                                      
                                                  Life'''<br>
                                      
                                      print("\nCreating a multiline String: ")<br>
                                      
                                      print(String1<br>
                                      <br>
                                      
                                      <b>Output:</B><br>
                                      String with the use of Single Quotes:<br> 
                                      Welcome to the Geeks World<br><br>
                                      
                                      String with the use of Double Quotes: <br>
                                      I'm a Geek<br><br>
                                      
                                      String with the use of Triple Quotes:<br>
                                      I'm a Geek and I live in a world of "Geeks"<br><br>
                                      
                                      Creating a multiline String:<br>
                                      Geeks<br>
                                                  For<br>
                                                  Life<br>
                                             </p>
                                        </section>
                                        <section id="chapter-5">
                                            <p><h2>Basic RegEx</h2><br><br>
                                        Let’s understand some of the basic regular expressions. They are as follows:<br>
                                        <ul>
                                        
                                        <li>Character Classes</li>
                                        <li>Rangers</li>
                                        <li>Negation</li>
                                        <li>Shortcuts</li>
                                        <li>Beginning and End of String</li>
                                        <li>Any Character</li>
                                        </ul><br>
                                        <h3>Character Classes:</h3>
                                        Character classes allow you to match a single set of characters with a possible set of characters. You can mention a character class within the square brackets. Let’s consider an example of case sensitive words.<br>
                                        <b>Example:</b><br>
                                        import re<br>
                                          
                                          
                                        print(re.findall(r'[Gg]eeks', 'GeeksforGeeks: \<br>
                                                         A computer science portal for geeks'))<br>
                                        <b>Output</b><br>
                                        ['Geeks', 'Geeks', 'geeks']<br><br>
                                        <h3>Ranges:</h3>
                                        The range provides the flexibility to match a text with the help of a range pattern such as a range of numbers(0 to 9), a range of characters (A to Z), and so on. The hyphen character within the character class represents a range.<br>
                                        
                                        <b>Example:</b><br>
                                        import re<br>
                                          
                                          
                                        print('Range',re.search(r'[a-zA-Z]', 'x'))<br>
                                        <b>Output</b><br>
                                        Range <_sre.SRE_Match object; span=(0, 1), match='x'><br><br>
                                        <h3>Negation:</h3>
                                        Negation inverts a character class. It will look for a match except for the inverted character or range of inverted characters mentioned in the character class.<br>
                                        
                                        <b>Example:</b><br>
                                        import re<br>
                                          
                                        print(re.search(r'[^a-z]', 'c'))<br>
                                        <b>Output:</b><br>
                                        None<br><br>
                                        <h3>Shortcuts:</h3>
                                        <ul>
                                        <li>\w – matches a word character</li>
                                        <li>\d – matches digit character</li>
                                        <li>\s – matches whitespace character (space, tab, newline, etc.)</li>
                                        <li>\b – matches a zero-length character</li>
                                        </ul>
                                        <b>Example:</b><br>
                                        import re<br>
                                          
                                          
                                        print('Geeks:', re.search(r'\bGeeks\b', 'Geeks'))<br>
                                        print('GeeksforGeeks:', re.search(r'\bGeeks\b', 'GeeksforGeeks'))<br>
                                        <b>Output:</b><br>
                                        Geeks: <_sre.SRE_Match object; span=(0, 5), match='Geeks'><br>
                                        GeeksforGeeks: None<br><br>
                                         </p>
</section>                                        
    
        </body>   
</html>
