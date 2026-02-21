1\) find files whose content starts with the word linux in a current directory.

&nbsp;          grep -l -i '^linux' \*

2\) find files whose content starts with the word linux in all directory.	

&nbsp;	               grep -rl -i '^linux' \*

3\) The command used to find the IP address in a Linux machine is:

&nbsp;         ip a    ;   hostname  ;   ifconfig

4\)		   





# &nbsp;            **STRINGS**

**✅ What is String in Python?**



&nbsp;	String is a collection of sequence of characters.

&nbsp;	used to store text data such as names, sentences, symbols, and numbers in text form.



👉 Strings are written inside quotes.



&nbsp;	Example:

&nbsp;	name = "Python"

&nbsp;	print(name)



##### **🔹 How to Create a String in Python**



&nbsp;	You can create strings using three types of quotes:



&nbsp;	1️⃣ Single Quotes ' '

&nbsp;	s = 'Hello'



&nbsp;	2️⃣ Double Quotes " "

&nbsp;	s = "Hello"



&nbsp;	3️⃣ Triple Quotes ''' ''' or """ """



&nbsp;	Used for multi-line strings.



&nbsp;		s = """Welcome

&nbsp;			to

&nbsp;			Python"""



##### **🔹 Characteristics of Python Strings**

	**✅ 1. Strings are Immutable**



&nbsp;		Once we created, we cannot modify the data.



&nbsp;		Example:



&nbsp;		s = "Hello"

&nbsp;		s\[0] = "h"   # Error



✔ You must create a new string instead.



	**✅ 2. Strings are Indexed**



&nbsp;		Each character has a position number.



&nbsp;		Example:



&nbsp;		s = "Python"

&nbsp;		print(s\[0])   # P

&nbsp;		print(s\[2])   # t





&nbsp;		Index positions:



&nbsp;		P  y  t  h  o  n

&nbsp;		0  1  2  3  4  5



	**✅ 3. Supports Negative Indexing**

&nbsp;		print(s\[-1])   # n

&nbsp;		print(s\[-2])   # o



	**✅ 4. String Slicing**



&nbsp;		Used to get part of string.



&nbsp;		Syntax:



&nbsp;		string\[start:end]





&nbsp;		Example:



&nbsp;		s = "Python"

&nbsp;		print(s\[1:4])   # yth



##### **🔹 String Operations**

**✅ Concatenation (Joining Strings)**

&nbsp;	a = "Hello"

&nbsp;	b = "World"

&nbsp;	print(a + b)



&nbsp;	Output:



&nbsp;	HelloWorld



**✅ Repetition**

&nbsp;	print("Hi " \* 3)



&nbsp;	Output:



&nbsp;	Hi Hi Hi



**🔹  Case Conversion Methods**

**✅ upper()**



&nbsp;	Converts string to uppercase.



&nbsp;	s = "hello"

&nbsp;	print(s.upper())   # HELLO



✅ lower()



Converts string to lowercase.



print("HELLO".lower())   # hello



✅ title()



Converts first letter of each word to uppercase.



print("python programming".title())



✅ capitalize()



Capitalizes only the first character.



print("python".capitalize())



✅ swapcase()



Swaps upper case to lower and vice versa.



print("PyThOn".swapcase())




