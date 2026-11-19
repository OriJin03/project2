print("="*50)
print("Programming Lessons")
print("="*50)

while True:
    print("Pick A Curriculum:")
    print("="*50)
    print("1.Prelim term lessons:")
    print("a.introduction to programming")
    print("b.python basic syntax")
    print("c.Printing Output")
    print("d. Python Comments")
    print("e.Variables, Constants,and Data Types in Python")
    print("f.basic Data Types in Python")
    print("g.ARITHMETIC OPERATORS and EXPRESSIONS\n,\n")
    print("2.Midterm Lessons:")
    print("a.Basic Input and Output in Python")
    print("b.Conditional Statements in Python ")
    print("c.LOGICAL OPERATOR\n,\n")
    print("3.Final term Lessons:")
    print("a.Introduction to Iteration and Loops")
    print("="*50)
    term=input("Enter A Curriculum To Learn:")
    if term=="1":
        lesson=input("Enter A Lesson:").upper()
        if lesson=="A":
            print("="*50)
            print("Lesson A:Introduction to programming")
            print("="*50)
            print("What is PROGRAMMING LANGUAGE\n")
            print("A programming language is a special language that computers understand and use to perform tasks.")
            print("WHAT IS PYHTON PROGRAMMING")
            print("Python is a high-level, interpreted, and general-purpose programming language designed to be simple, readable, and easy to learn.\n\nPython is a widely-used programming language that was created by Guido van Rossum in 1991")
            print("Guido van Rossum is a dutch software engineer best known for creating the Python programming language in 1991")
            print("He designed Python with the goal of making programming simple, readable, and easy to\nlearn while remaining powerful enough for professional software development.")
            print("Why Learn Python?")
            print("1.Simple And Easy To Learn-Great For Begginers")
            print("2.Readable Syntax-Code Looks almost like enlish")
            print("3.Versatile– Used in many fields (AI, web, automation, games, etc.)")
            print("4.Huge community– Lots of support, tutorials, and libraries")
            print("End of lesson A...\n\n")
            print(":(Quiz)")
            answer1=input("What is a programming Language?").lower()
            if "language"in answer1 or"computer"in answer1 or"task"in answer1 or"instruction" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer2=input("who created python?").lower()
            if "rossum"in answer2 or"guido"in answer2:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer3=input("why is python recommended for Begginers?").lower()
            if "easy"in answer3 or"readable"in answer3 or"simple"in answer3:
                print("Correct...")
            else:
                print("incorrect...")
            
            
            print("="*50)
            choice=input("Would you Like Another Lesson? Press Y for Yes And N For No (Y/N)").upper()
            if choice=="N":
                    break
                
        elif lesson=="B":
            print("="*50)
            print("Lesson B:Python Basic Synthax")
            print("="*50)
            print("What is Python Syntax")
            print("Syntax refers to the set of rules that tells us how to correctly write a program in Python.\n")
            print("1.Python is Case-Sensitive Python treats uppercase and lowercase letters differently.")
            print("Example:(✅)") 
            print('name="john"➡️ create variable name.\n print(name)➡️ print the value fof the name')
            print("Example:(❌)")
            print("print(name)➡️error!Name.not the same variable\n print(Name) ⚠ Python is  case sensitive\n")
            print("2. Indentation Unlike other programming languages, Python uses indentation\n(spaces) to define blocks of code.")
            print("Example:(✅)") 
            print("age=18)➡️ Assign value to varialble\n ️\n if >=18:)➡️ check condition\n")
            print("print(Adult))➡️ Internded (inside the Block)")
            print("End of Lesson B...\n\n")
            print(":(Quiz)")
            answer1=input("What is Syntax in programming?").lower()
            if "rules"in answer1 or"rule"in answer1 or"grammar"in answer1 or"structure" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer2=input("explain what case sensitivity in python?").lower()
            if "uppercase"in answer2 or"lowercase"in answer2 or"different"in answer2:
                print("Correct...")
            else:
                print("incorrect...")    
                
            answer3=input("How does Python organize blocks of code instead of curly braces?").lower()
            if "indentation"in answer3 or"indent"in answer3 or"space"in answer3 or"spaces" in answer3:
                print("Correct...")
            else:
                print("incorrect...")
                
                
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
                
        elif lesson=="C":
            print("="*50)
            print("Lesson C:Printing Output")
            print("="*50)
            print("print statement\nThe print() function displays information on the screen.")
            print("Syntax:\nprint(value)")
            print("print – the function that displays output.\n")
            print("() – parentheses that contain the information to be displayed.\n")
            print("value – the text, number,variable, or expression you want to show.")
            print("Printing Text\nText (also called a string) must be enclosed in quotation marks.\n")
            print("Example:(✅ )")
            print('print("Hello,World!")➡️ Correct syntax usses Double Quotes in the parentheses.')
            print("Example:(❌) ")
            print("print(Hello,World!)➡️ incorrect syntax,missing quote around the text\n")
            print("Printing Numbers")
            print("You can print numbers directly without quotation marks.")
            print("Example:(✅ )")
            print('print("100")\nprint("25.5")➡️ Numbers int,float numbers are used without quotes')
            print("Outout:\n100\n25.5")
            print("2nd Example:(✅ )")
            print('print("100")')
            print('print("25.5")➡️ value inside quotes Are Text (Strings)')
            print("End Of lesson C...\n\n")
            print("Quiz")
            answer1=input("What is the purpose of printing function?").lower()
            if "display"in answer1 or"output"in answer1 or"screen"in answer1 or"show" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
            
            answer2=input("Why must text be in quotation marks inside print()?").lower()
            if "quote"in answer2 or"quotes"in answer2 or"string"in answer2 or"text" in answer2:
                print("Correct...")
            else:
                print("incorrect...")    
            
            answer3=input('explain the difference between print("100") and print(100)').lower()
            if "number"in answer3 or"integer"in answer3 or"string"in answer3 or"text" in answer3 or"quote"in answer3:
                print("Correct...")
            else:
                print("incorrect...")
                
                
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
        elif lesson=="D":
            print("="*50)
            print("Lesson D:PYTHON COMMENTS")
            print("="*50)
            print("Comments are ignored by Python.\nThey are used to explain the code.")
            print("Example: (Single Comment)")
            print("#this is a Comment\n")
            print("2nd Example:(MultiComment)")
            print("'''")
            print("This IS\n a Multi\nComment")
            print("End of Lesson D...\n\n")
            print("Quiz")
            answer1=input("What does Python do when it encounters a comment?").lower()
            if "ignore"in answer1 or"skip"in answer1 or"not run"in answer1 or"nothing" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
                
                
            answer2=input("how do you type a comment?").lower()
            if "#"in answer2 or"'"in answer2 or"hastag"in answer2 or"quotes" in answer2 or"quote"in answer2:
                print("Correct...")
            else:
                print("incorrect...") 
                
                
            answer3=input("Why do programmers write comments in their code?").lower()
            if "explain"in answer3 or"read"in answer3 or"understand"in answer3 or"note" in answer3 or"organized"in answer3:
                print("Correct...")
            else:
                print("incorrect...")    
                
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
        
        elif lesson=="E":
            print("="*50)
            print("Lesson:Variables, Constants,and Data Types in Python")
            print("="*50)
            print("What is Variable?")
            print("A variable is a named storage location used to keep data in a program.\nThe value of a variable can change while the program is running.\nExample:\n a, b, c, age, name\n")
            print("Variable meaning Rules")
            print("A variable can have a short name (like x and y)or a more descriptive name (age, carname,total_volume).\n")
            print("Variable Naming Rules")
            print("A variable name must start with a letter or the under score character.\n")
            print("A variable name cannot start with a number.\n")
            print("Variable Names are Case\n(age and AGE are two different variables)\n")
            print("assigned Value to Variable\nIn programming, we store data in variables. We assign a value to a variable using the \n= (assignment operator).")
            print("Example:")
            print('first name= "John"')
            print('first name (variable) & "John""as Variable\n')
            print("Output Variables")
            print("The Python print() function is often used to output variables.")
            print("Example:")
            print('school= "Clark College"\nprint(school)\n')
            print("In the print() function, you output multiple variables, separated by a comma:")
            print("Example:")
            print("a=""I")
            print("b=""LOVE")
            print("c=""CCST")
            print("print(a,b,c)➡️ print() displays the value of a,b and c seperated by spaces\n")
            print("Output:\n I LOVE CCST\n")
            print("In the print() function, you output multiple variables, separated by a +:")
            print("Example:")
            print("x=""I")
            print("y=""LOVE")
            print("z=""CCST")
            print("print(x,y,z)➡️ add the values of x,y and z and display the result.") 
            print("Output:\n I LOVE CCST\n")
            print("End of Lesson E...\n\n")
            print("Quiz")
            answer1=input("What is a variable in Python, and what does the = operator do?").lower()
            if "store"in answer1 or"memory"in answer1 or"data"in answer1 or"value" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer2=input("List three rules for naming variables in Python:").lower()
            if "case"in answer2 or"space"in answer2 or"number"in answer2 or"underscore" in answer2:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer3=input("what is variable?").lower()
            if "hold"in answer3 or"store"in answer3 or"data"in answer3 or"value" in answer3:
                print("Correct...")
            else:
                print("incorrect...")    
                
            
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
                
        elif lesson == "F":
            print("="*50)
            print("Lesson F:Basic Data Type In Python")
            print("="*50)
            print("Data Type")
            print("Data types are categories that tell Python what kind of data a variable stores.\nThey determine the type of value a variable\ncan hold and what operations can be performed on that value.")
            print("int/integer numbers,Whole Numbers(No decimal Part)")
            print("float/decimal numbers,Numebrs with Decimal Part")
            print("str/string or text,Text or Characters inside Quotes.")
            print("bool/boolean values,represents one of two values:true or false.")
            print("End of Lesson F...\n\n")
            print("Quiz")
            answer1=input("Explain the four basic Python data types (int, float, str, bool)").lower()
            if "whole"in answer1 or"decimal"in answer1 or"text"in answer1 or"true" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer2=input("what is a data type?").lower()
            if "variable"in answer2 or"stores"in answer2 or"store"in answer2 or"data" in answer2:
                print("Correct...")
            else:
                print("incorrect...")    
            
            answer3=input("what does float data type do?").lower()
            if "decimal"in answer3 or"number"in answer3 or"accurate"in answer3:
                print("Correct...")
            else:
                print("incorrect...")
                
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
            
        elif lesson == "G":
            print("="*50)
            print("Lesson G:ARITHMETIC OPERATORS and EXPRESSIONS")
            print("="*50)
            print("What are Arithmetic Operators?")
            print("Arithmetic operators are symbols used to perform mathematical calculations on numbers.\nThey work the same way as the operators used in everyday mathematics.")
            print("operators & description:\n+ Addition,Adds two values.\n- Substraction,substracts the values from the first.\n*Multiplication,Multiplies 2 values\n/Division(Float),\n//\n%\n**\n")
            print("Expressions in Python")
            print("Python follows the order of operations (PEMDAS):\n")
            print("End Of Lesson G...\n\n")
            print("Quiz")
            answer1=input("Explain the difference between / (division) and // (floor division)").lower()
            if "whole"in answer1 or"decimal"in answer1 or"whole"in answer1 or"remainder" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
            
            answer2=input("What does the modulus operator % do?").lower()
            if "dividing"in answer2 or"modulus"in answer2 or"over"in answer2 or"remainder" in answer2:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer3=input("what does ** do?").lower()
            if "multiply"in answer3 or"exponent"in answer3 or"power"in answer3 or"square" in answer3:
                print("Correct...")
            else:
                print("incorrect...")
                
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):")
            print("="*50)
            if choice=="N":
                    break
        else:
            print("Choice Not Found")
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
                
    elif term=="2":
        lesson=input("Enter A Lesson:").upper()
        if lesson=="A":
            print("="*50)
            print("Basic Input and Output in Python")
            print("="*50)
            print("Accepting User Input")
            print("Purpose of input in programming\nReal-life analogies (e.g., asking for a user's name and responding)\n")
            print("Example:")
            print("name=input(""Enter Your Name:)")
            print("age=input(""Enter your Age)\n")
            print('Using input() function\nSyntax: variable = input("Prompt message:")"\nAll input is string type by default\n')
            print("Formating output:")
            print("Using comma , in print():")
            print('print("Name:",name")')
            print('print("Age:",age\n')    
            print("Converting Input to Other Data Types")   
            print("Float Input (for decimal numbers)")
            print("Example:")
            print('grade=float(input("enter your grade:"))')
            print('print(f"Your Grade Is:{grade}")\n')    
            print("Converting Input to Other Data Types")    
            print("Boolean Input (True or False using conditions)")
            print("Example:")
            print('answer=input(Are you Student?(Y/N):")')
            print('is_student=answer.lower()==="yes"')
            print('print("Student Status:",is_student)\n')
            print("Converting Input to Other Data Types")
            print('name=input("Enter Your Name:")')
            print('age=int(input("Enter Your Age:")')
            print('grade=float(input("Enter Your Final Grade:"))\n')
            print("End Of Lesson A...\n\n")
            print("Quiz")
            answer1=input("what data type that used this input() the most?").lower()
            if "string"in answer1 or"str"in answer1 or"text"in answer1 or"quote" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer2=input('How do f-strings (f"...") make printing variables easier?').lower()
            if "clean"in answer2 or"organized"in answer2 or"format"in answer2:
                print("Correct...")
            else:
                print("incorrect...")
            
            answer3=input("how do you convert an input number into a whole number?").lower()
            if "int"in answer3 or"integer"in answer3 or"convert"in answer3 or"cast" in answer3:
                print("Correct...")
            else:
                print("incorrect...")    
                
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
        
        elif lesson=="B":
            print("="*50)
            print("Conditional Statements in Python ")
            print("="*50)
            print("1.Introduction To Conditional Statements:")
            print("A Conditional statement Allows a program to make\ndecisions based on whether a condition is True or False\n")
            print("2.Relational Operators")
            print("relational operators also called comparison operators,are used to compare two values.\nThe result is always either true or false.\n")
            print("operator and its meaning:")
            print("(==)Equal to\n(!=)Not Equal To\n(>)Greater than\n(<)Less Than\n(>=)Greater Than or Equal To\n(<=)Less than or Equal to\n")
            print("The if statement")
            print("the if Statement executes a block of code only  when a ci=ondition is true.\n")
            print("Example:")
            print("if condition:")
            print("    statement(s)")
            print("\nThe if-else statement")
            print("The else statement provides an alternative when the if condition is false.")
            print("Example:")
            print("if codition:\n   statement")
            print("else:\n   statement")
            print("The if-elif-else statement")
            print("The elif statement is used when there are multiple condition to evaluate.\npython checks each condition from top to bottom and executes the first condition that is true.\n")
            print("Example:")
            print("if codition1:\n   statement")
            print("elif codition2:\n   statement")
            print("else:\n   statement")
            print("Nested If condition")
            print("The nested condition is a condition inside a condition.")
            print("Example:")
            print("if codition1:\n  if codition1:\n   statement\nelse:\n   statement\nelse:\n   statement")
            print("End of Lesson B...\n\n")
            print("Quiz")
            answer1=input("what data type that used this input() the most?").lower()
            if "string"in answer1 or"str"in answer1 or"text"in answer1 or"quote" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
            
            answer2=input('How does if, elif, and else work?').lower()
            if "decision"in answer2 or"condition"in answer2 or"true"in answer2:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer3=input("Explain the difference between = and == in Python.").lower()
            if "equal"in answer3 or"compare"in answer3 or"store"in answer3:
                print("Correct...")
            else:
                print("incorrect...")    
                
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
            
        elif lesson=="C":
            print("="*50)
            print("Logical Operator")
            print("="*50)
            print("What Are Logical Operators?")
            print("Logical Operators Are used to Combine  or reverse conditions in a python program.\n(Commonly used in if,elif and else)")
            print("operator and meaning:")
            print("(and)Both Condition must be true.\n(or)Atleast One condition mustbe true.\n(not)reverses The result.\n")
            print("End of Lesson C...\n\n")
            print("Quiz")
            answer1=input("Explain the difference between and and or in Python.").lower()
            if "either"in answer1 or"both"in answer1 or"all"in answer1 or"at least" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer2=input('What does the not operator do?').lower()
            if "reverse"in answer2 or"opposite"in answer2 or"invert"in answer2:
                print("Correct...")
            else:
                print("incorrect...")
                
            answer3=input('Give an example mostly used a "and" or "or" in an if statement').lower()
            if "name"in answer3 or"number"in answer3 or"age"in answer3 or"username"in answer3:
                print("Correct...")
            else:
                print("incorrect...")
                
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
        else:
            print("Choice Not Found")
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                    break
            
    elif term=="3":
        lesson=input("Enter A Lesson:").upper()
        if lesson=="A":
            print("="*50)
            print("Introduction to Iteration and Loops")
            print("="*50)
            print("Introduction to iteration")
            print("Iteration means repeating a process.\nin programming it means repeatedly executing set of instructions.Each Repition is called an iteration.\n")
            print("iteration allows the program to perform the same task multiple times.\n without loop,instruction must be repeatedly\n")
            print('Without loop:\nprint("Study Python")\nprint("Study Python")\nprint("Study Python")\nprint("Study Python")\n')
            print('With loop:\nfor number in range(4)\n   print("Study Python)\n')
            print("Both Program Produce the same output,But the loop makes the program shorter \nand easier to modify.to repeat the message 100 times change 4 to 100.")
            print("Types of Loops in pyhton")
            print("Python Has 2 main types of loops:for and while.")
            print("for loop:\nrepeats instruction for each item in sequence.\nuseful when the numbers of repitition is known\n")
            print("WHile Loop:\nRepeats Instruction while The Codition Is true.\nuseful when a repition depends on a condition.\n")
            print("example: (for Loop)")
            print('for number in range(3):\n   print("Hello!")\n')
            print("example: (While Loop)")
            print('count=1\nwhile count<=3:\n   print("Hello!")\n  count+=1\n\n')
            print("End Of Lesson A...\n\n")
            print("Quiz")
            answer1=input("Explain the difference between a for loop and a while loop:").lower()
            if "sequence"in answer1 or"condition"in answer1 or"repeat"in answer1 or"count" in answer1:
                print("Correct...")
            else:
                print("incorrect...")
            
            answer2=input('What is an infinite loop?').lower()
            if "repeat"in answer2 or"endless"in answer2 or"never"in answer2:
                print("Correct...")
            else:
                print("incorrect...")
            
            answer3=input('what does break do for loops?').lower()
            if "stop"in answer3 or"exit"in answer3 or"skip"in answer3 or"next"in answer3:
                print("Correct...")
            else:
                print("incorrect...")
                
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                break
            
        else:
            print("Choice Not Found")
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                break    
            
            
            
            
    else:
            print("Choice Not Found")
            print("="*50)
            choice=input("Would You like Another Lesson? Press Y for Yes And N for No(Y/N):").upper()
            if choice=="N":
                break        
            
            
