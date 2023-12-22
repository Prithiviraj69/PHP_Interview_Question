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
11. **[How can PHP and HTML interact?](#q11-php-and-html-interaction)**
12. **[What is the purpose of @ in PHP?](#q12-purpose-of-at-in-php)**
13. **[Explain the importance of Parser in PHP?](#q13-importance-of-parser-in-php)**
14. **[Explain the main types of errors.](#q14-main-types-of-errors)**
15. **[What are traits?](#q15-traits)**
16. **[Does JavaScript interact with PHP?](#q16-javascript-interaction-with-php)**
17. **[What is the most used method for hashing passwords in PHP?](#q17-most-used-method-for-hashing-passwords-in-php)**
18. **[What is the difference between the include() and require() functions?](#q18-difference-between-include-and-require-functions)**
19. **[What are cookies? How to create cookies in PHP?](#q19-cookies-and-creating-cookies-in-php)**
20. **[What is the meaning of ‘escaping to PHP’?](#q20-escaping-to-php)**
21. **[Explain Path Traversal](#q21-path-traversal)**
22. **[What is the meaning of a final method and a final class?](#q22-final-method-and-final-class)**
23. **[What are the steps to create a new database using MySQL and PHP?](#q23-create-new-database-using-mysql-and-php)**
24. **[What is the use of session_start() and session_destroy() functions in PHP?](#q24-session-start-and-session-destroy-in-php)**
25. **[How to connect to a URL in PHP?](#q25-connect-to-url-in-php)**
26. **[What is PDO in PHP?](#q26-pdo-in-php)**

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

### Q11. How can PHP and HTML interact?
   - PHP scripts have the ability to generate HTML, and it is possible to pass information from HTML to PHP.
   - PHP is a server-side language whereas HTML is a client-side language. So PHP executes on the server-side and gets its results as strings, objects, arrays, and then we use them to display its values in HTML.
   - This interaction helps bridge the gaps and use the best of both languages.
   - [Back to Top](#php-interview-questions)

### Q12. What is the purpose of @ in PHP?
   - In PHP, @ is used for suppressing error messages. If any runtime error occurs on the line which consists @ symbol at the beginning, then the error will be handled by PHP.
   - [Back to Top](#php-interview-questions)

### Q13. Explain the importance of Parser in PHP?
   - A PHP parser is software that converts source code into the code that computer can understand. This means whatever set of instructions we give in the form of PHP code is converted into a machine-readable format by the parser.
   - You can parse PHP code with PHP using the token_get_all() function.
   - [Back to Top](#php-interview-questions)

### Q14. Explain the main types of errors.
   - The 3 main types of errors in PHP are:
     - Notices: Non-critical errors that can occur during the execution of the script. Example: Accessing an undefined variable.
     - Warnings: More critical than notices. Don’t interrupt the script execution. Example: include() a file that doesn’t exist.
     - Fatal: The most critical error type which, when occurs, immediately terminates the execution of the script. Example: Accessing a property of a non-existent object or require() a non-existent file.
   - [Back to Top](#php-interview-questions)

### Q15. What are traits?
   - Traits are a mechanism that lets you create reusable code in PHP and similar languages where multiple inheritances are not supported. It’s not possible to instantiate it on its own.
   - A trait is intended to reduce the limitations of single inheritance by enabling a developer to reuse sets of methods freely in many independent classes living in different hierarchies of class.
   - [Back to Top](#php-interview-questions)

### Q16. Does JavaScript interact with PHP?
   - JavaScript is a client-side programming language, whereas PHP is a server-side scripting language. PHP has the ability to generate JavaScript variables, and this can be executed easily in the browser. Thereby making it possible to pass variables to PHP using a simple URL.
   - [Back to Top](#php-interview-questions)

### Q17. What is the most used method for hashing passwords in PHP?
   - The crypt() function is used for this functionality as it provides a large number of hashing algorithms that can be used. These algorithms include sha1, sha256, or md5 which are designed to be very fast and efficient.
   - [Back to Top](#php-interview-questions)

### Q18. What is the difference between the include() and require() functions?
   - **include() function:**
     - This function is used to copy all the contents of a file called within the function, text-wise into a file from which it is called.
     - When the file is included cannot be found, it will only produce a warning (E_WARNING) and the script will continue the execution.
   - **require() function:**
     - The require() function performs the same as the include() function. It also takes the file that is required and copies the whole code into the file from where the require() function is called.
     - When the file is included cannot be found, it will produce a fatal error (E_COMPILE_ERROR) and terminates the script.
   - [Back to Top](#php-interview-questions)

### Q19. What are cookies? How to create cookies in PHP?
   - A cookie is a small record that the server installs on the client’s computer. They store data about a user on the browser. It is used to identify a user and is embedded on the user’s computer when they request a particular page. Each time a similar PC asks for a page with a program, it will send the cookie as well.
   - After verifying the user’s identity in encrypted form, cookies maintain the session id generated at the back end. It must reside in the browser of the machine. You can store only string values not object because you cannot access any object across the website or web apps.
   - By default, cookies are URL particular. For example, Gmail cookies are not supported by Yahoo and vice versa. Cookies are temporary and transitory by default. Per site 20 cookies can be created in a single website or web app. 50 bytes is the initial size of the cookie and 4096 bytes is the maximum size of the cookie.
   - In PHP, we can create cookies using the setcookie() function:
     - `setcookie(name, value, expire, path, domain, secure, httponly);`
     - Here name is mandatory and the remaining parameters are optional.
   - Example:
     - `setcookie("instrument_selected", "guitar")`
   - [Back to Top](#php-interview-questions)

### Q20. What is the meaning of ‘escaping to PHP’?
   - The PHP parsing engine needs a way to differentiate PHP code from other page elements. The mechanism to achieve this is known as ‘escaping to PHP’. Escaping a string means reducing ambiguity in quotes used in that string.
   - For example, when you’re defining a string, you surround it in either double quotes or single quotes:
     - `"Hello, InterviewBit."`
   - But what if I include double quotes within the string?
     - `"Hello "InterviewBit.""`
   - Now I have ambiguity - the interpreter doesn’t know where does my string end. If I want to keep my double quotes, I have various options. I could use single quotes around my string:
     - `'Hello "InterviewBit."'`
   - Or I can escape my quotes:
     - `"Hello \"InterviewBit.\""`
   - Any quote that is preceded by a slash is escaped and understood to be part of the value of the string.
   - [Back to Top](#php-interview-questions)

### Q21. Explain Path Traversal
   - Path traversal is a form of attack to read into the files of a web application. '../' (dot-dot-sequences) is a cross-platform symbol to go up in the directory. Path traversal makes use of this symbol to operate the web application file. The attacker can reveal the content of the file attacked using the path traversal outside the root directory of a web server or application. It is usually done to gain access to secret passwords, tokens, and other sensitive information stored in the files.
   - Path Traversal is also called “Directory Traversal”. It allows the attacker to exploit vulnerabilities present in the web file under attack.
   - Let’s take a simple example. Consider we have a “Show File” button that opens up some URL.
     - For a classic directory traversal attack, the attacker may try to access the system file /etc/passwd (assuming a UNIX/LINUX system). If the application receives the value of the file parameter from the URL and passes it to a system call, it would traverse the relative path ../../etc/passwd starting from /var/www and ask the system to load the password file.
     - This technique is also called a dot-dot-slash attack because it usually uses the special characters ../ (or \.. on Windows) to climb to a higher-level directory.
   - [Back to Top](#php-interview-questions)

### Q22. What is the meaning of a final method and a final class?
   - The final keyword in a declaration of the method indicates that the method cannot be overridden by subclasses. A class that is declared as final cannot be subclassed.
   - This is especially useful when we are creating an immutable class like the String class. Only classes and methods may be declared final; properties cannot be declared as final.
   - [Back to Top](#php-interview-questions)

### Q23. What are the steps to create a new database using MySQL and PHP?
   - The 4 main steps used to create a new MySQL database in PHP are given below:
     - A connection establishment is done to the MySQL server using the PHP script.
     - The connection is validated. If the connection is successful, then you can write a sample query to verify.
     - Queries that create the database are input and later stored into a string variable.
     - Then, the created queries will be executed one after the other.
   - [Back to Top](#php-interview-questions)

### Q24. What is the use of session_start() and session_destroy() functions in PHP?
   - The session_start() function is used to start a new session. Also, it can resume an existing session if it is stopped. In this particular case, the return will be the current session if resumed.
   - [Back to Top](#php-interview-questions)

### Q25. How to connect to a URL in PHP?
   - Any URL can be connected to PHP easily by making use of the library called cURL. This comes as a default library with the standard installation of PHP.
   - The term cURL stands for a client-side URL. cURL makes use of libcurl (client-side URL Transfer Library) which supports many protocols like FTP, FTPS, HTTP/1, HTTP POST, HTTP PUT, HTTP proxy, HTTPS, IMAP, Kerberos, etc. It allows you to connect to a URL and retrieve and display information from that page – like the HTML content of the page, HTTP headers, and their associated data, etc.
   - Steps for connecting with URL using PHP cURL POST are given below:
     - Initialize cURL session.
     - Define your URL where you want to post the request. We can directly enter this URL into the URL section inset option parameter or we can assign it to an object.
     - Now, define the cURL options that you want to execute with the post option.
     - After setting all the functions then it’s time to execute our cURL.
     - After this, close the cURL and echo your object to check their response.
   - [Back to Top](#php-interview-questions)

### Q26. What is PDO in PHP?
   - PDO stands for PHP Data Object. PDO is a set of PHP extensions that provide a core PDO class and database-specific drivers. The PDO extension can access any database that is written for the PDO driver. There are several PDO drivers available which are used for FreeTDS, Microsoft SQL Server, IBM DB2, Sybase, Oracle Call Interface, Firebird/Interbase 6 and PostgreSQL databases, etc.
   - It gives a lightweight, vendor-neutral, data-access abstraction layer. Hence, no matter what database we use, the function to issue queries and fetch data will be the same. And, it focuses on data access abstraction instead of database abstraction.
   - [Back to Top](#php-interview-questions)
