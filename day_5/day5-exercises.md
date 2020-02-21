1. Variables are declared using the keyword 'var' followed by a name for the variable. Once the variable has been declared, it can be assigned a value, this is done using the 'equals sign' ( = ) symbol, which in Javascript is referred to as an assignment operator. The assignment operator is used to assign an initial value to a variable, and can also be used to change the value of the variable as needed. In Javascript an 'equals sign' doesn't really mean equal to, it means that for now, the computer should remember the specified information under that name.
2. Data Types
> - Numbers are used for counting, calculating sums and indicating measurements. Numbers can be whole numbers, decimals and/or negative numbers. When indicating large number values, do not place commas within the number.
> - Strings are used for any type of text and can include numbers (that are not being used for calculations), letters, punctuation (with some care) and inline html markup. Strings are enclosed in quotation marks
> - Booleans represent data in terms of it being either 'true' or 'false'. This is useful for determining what behavior will follow the action. We can instruct code to perform one function if the data returns as 'true', and a different function if the data returns as 'false'

3. Rules for Naming Variables
 > 1. Variable names can start with a letter, underscore or dollar sign; they must not start with a letter
 > 2. Variable names may not contain a dash ( - ) or a period ( . ); they can contain letters, numbers , underscores  ( _ )or dollar signs.
 > 3. Certain words (or letter combinations) have assigned meanings that tell the computer to do things,  and there are words that have been set aside, or 'reserved' for future use as keywords. These words may not be used as names for variables.
	**reserved words include** 'enum', 'try', 'default', 'super', 'switch', and several others, which can be found in various places online.
 > 4. Variable names are case sensitive, so the same case must be used each time you reference that variable. It is poor form to use the same name with different cases for different variables within the same work.
 > 5. Variable names should be descriptive. Assigning a random or esoteric name to a variable will make it difficult for others to figure out what the purpose of the variable is. If you are creating an array of tools, 'tools' would be a better name for the variable than 'thingys' would.
 > 6. Camel Case or underscores are used in to give variables names that are longer than one word. In camel case the first word is not capitalized, but all subsequent words are. Dashes my not be used in a name for a variable.

4. Arrays useful for creating lists or sets of related data. Arrays can contain items from different data types, but they should relate to each other in some way. Arrays are particularly useful because the number of objects in an array can easily be changed as needed. Objects in an array are automatically indexed with numerical values, with the first object having the number zero, and each additional object being assigned numbers increasing in value. To access an object in an array, you would call the object by specifying the index number for that object. You can change the value of the object by using the assignment indicator ( = ) to assign a new value to the index number of the object, just like you would any variable.
5. A statement is an individual step in a series of instructions. A series of statements tells the computer what the designer wants. An expression is used to create a value. Expressions can be used to assign a value to a variable, to perform calculations or to concatenate strings.
6. Operator types include:
	* assignment operator: the equal symbol ( = ) which is used to assign values to variables, including when that value is being changed
	* arithmetic operators are used to perform basic math such as addition, subtraction, etc. It is important to understand the order in which those operations will be carried out when using arithmetic operators
	* string operator: the only string operator is the plus symbol ( + ). This is used to combine or concatenate strings so that they flow together.
	* comparison operators are used to provide a boolean (true/false) response. These include symbols such " == " to determine if two values are the same,  " != " to indicate that two values are not the same, " < , > " to indicate that values are greater or less than one another and so on. Boolean values can apply to various forms of data, not only to numerical values.
	* logical operators also return values of true or false, but can be used for comparing the results of more than one comparison operator. So if you have two or more values that must all return as true to elicit a particular behavior, a logical operator can tell you if all of the values are true rather than having to run each comparison individually with a comparison operator.