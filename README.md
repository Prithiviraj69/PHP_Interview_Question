# PHP_Interview_Question

## PHP Interview Questions
1. **[What is PHP?](#q1-what-is-php)**
2. **[What is the difference between variables and constants?](#q2-what-is-the-difference-between-variables-and-constants)**
3. **[Differentiate between static and dynamic websites.](#q3-differentiate-between-static-and-dynamic-websites)**
4. **[Is PHP a case-sensitive scripting language?](#q4-is-php-a-case-sensitive-scripting-language)**
5. **[What is the meaning of PEAR in PHP?](#q5-meaning-of-pear-in-php)**
6. **[What are the types of variables present in PHP?](#q6-types-of-variables-in-php)**
7. **[Explain the difference between $message and $$message in PHP?](#q7-difference-between-message-and-message-in-php)**
8. **[What are the rules for naming a PHP variable?](#q8-rules-for-naming-a-php-variable)**
9. **[What is the difference between “echo” and “print” in PHP?](#q9-difference-between-echo-and-print-in-php)**
10. **[Tell me some of the disadvantages of PHP?](#q10-disadvantages-of-php)**

# Questions and Answers

### Q1. What is PHP?
   - PHP stands for PHP: Hypertext Preprocessor is a widely used open-source server-side scripting language especially suited for creating dynamic websites and mobile APIs.
   - It is used to manage dynamic content, session tracking, databases, and also to build an entire e-commerce site. 
   - By default, most of the web hosting servers support PHP, and thus it contributes to cost-effectiveness.
   - [Back to Top](#php-interview-questions)

### Q2. What is the difference between variables and constants?
   - **Variables:**
     - Variables are used to store data values.
     - The value of a variable can be changed during the execution of a script.
     - You declare a variable using the $ symbol, for example, $variableName.
     - Variables are handy when you need to work with data that can change or is unknown at the time of writing the code.
   - **Constants:**
     - Constants are used to store fixed values that do not change during the execution of a script.
     - Once a constant is defined, it cannot be changed or redefined.
     - You declare a constant using the define() function or the const keyword, for example, define("CONSTANT_NAME", "constant value"); or const CONSTANT_NAME = "constant value";.
     - Constants are useful when you want to ensure that a value remains constant throughout your code.
   - [Back to Top](#php-interview-questions)

### Q3. Differentiate between static and dynamic websites.
   - **Static Website:**
     - The content cannot be manipulated after the script is executed.
     - No way to change the content as it is predefined.
   - **Dynamic Website:**
     - The content can be changed even at runtime.
     - The content can be changed easily by manipulation and reloading.
   - [Back to Top](#php-interview-questions)

### Q4. Is PHP a case-sensitive scripting language?
   - The answer to this is both yes and no. Variables and their declaration in PHP are completely case-sensitive while function names are not.
   - For example, user-defined functions in PHP can be defined in uppercase but later referred to in lowercase, and it would still function normally.
   - [Back to Top](#php-interview-questions)

### Q5. What is the meaning of PEAR in PHP?
   - PEAR stands for PHP Extension and Application Repository. It is one of the frameworks and acting repositories that host all of the reusable PHP components. Alongside containing some of the PHP libraries, it also provides you with a simple interface in PHP to automatically install packages.
   - [Back to Top](#php-interview-questions)

### Q6. What are the types of variables present in PHP?
   - There are eight primary data types in PHP:
     - **Array:** A named and ordered collection of data
     - **Boolean:** A logical value (True or False)
     - **Double:** Floating point numbers such as 5.1525
     - **Integer:** Whole numbers without a floating point
     - **Object:** An instance of classes, containing data and functions
     - **NULL:** A special data type, supporting only the NULL data
     - **Resource:** Special variables that hold references to external resources
     - **String:** A sequence of characters such as, “Hello learners!”
   - [Back to Top](#php-interview-questions)

### Q7. Explain the difference between $message and $$message in PHP?
   - **$message:**
     - This is a regular variable with a fixed name. For example, if you have $message = "Hello, World!";, you can access the value of $message using that variable name throughout your code.
   - **$$message:**
     - This involves variable variables. It's a bit more dynamic. If $message contains the string "example", then message is like referencing the variable with the name stored in $message. So if $message = "example", then message is equivalent to the variable $example.
   - [Back to Top](#php-interview-questions)

### Q8. What are the rules for naming a PHP variable?
   - The following two rules are needed to be followed while naming a PHP variable:
     - A variable must start with a dollar symbol, followed by the variable name. For example: $price=100; where price is a variable name.
     - Variable names must begin with a letter or underscore.
     - A variable name can consist of letters, numbers, or underscores. But you cannot use characters like + , – , % , & etc.
     - A PHP variable name cannot contain spaces.
     - PHP variables are case-sensitive. So $NAME and $name both are treated as different variables.
   - [Back to Top](#php-interview-questions)

### Q9. What is the difference between “echo” and “print” in PHP?
   - **echo:**
     - echo can output one or more strings.
     - echo is faster than print because it does not return any value.
     - If you want to pass more than one parameter to echo, a parenthesis should be used.
   - **print:**
     - print can only output one string and it always returns 1.
     - print is slower compared to echo.
     - Use of parenthesis is not required with the argument list.
   - [Back to Top](#php-interview-questions)

### Q10. Tell me some of the disadvantages of PHP?
   - The cons of PHP are:
     - PHP is not suitable for giant content-based web applications.
     - Since it is open-source, it is not secure. Because ASCII text files are easily available.
     - Change or modification in the core behavior of online applications is not allowed by PHP.
     - If we use more features of the PHP framework and tools, it will cause poor performance of online applications.
     - PHP features a poor quality of handling errors. PHP lacks debugging tools, which are needed to look for warnings and errors. It has only a few debugging tools in comparison to other programming languages.
   - [Back to Top](#php-interview-questions)
