# basic-interview-questions
##### This repository contains basic questions for freshers and professionals with 2-3 years of experience.


### HTML-CSS
#### 1. Do all HTML tags have an end tag?
	    No. There are some HTML tags that don't need a closing tag. 
       For example: <image> tag, <br> tag.

#### 2. How to insert a copyright symbol on a browser page?
	You can insert a copyright symbol by using &copy; or &#169; in an HTML file.

#### 3. Can you create a multi-colored text on a web page?
	Yes. To create a multicolor text on a web page you can use <font color ="color"> </font>.
   it is helpful for the specific texts you want to color.

#### 4. What is the use of an iframe tag?
	An iframe is used to display a web page within a web page.

#### 5. Which type of video formats are supported by HTML5?
    	HTML 5 supports three types of video format:
    	1. mp4
    	2. WebM
    	3. Ogg

#### 6. How do you add CSS styling in HTML?
      	There are three ways to include the CSS with HTML:
      
      	Inline CSS: It is used when less amount of styling is needed or in cases where only a single element has to be styled.
                To use inline styles add the style attribute in the relevant tag.
         
      	External Style Sheet: This is used when the style is applied to many elements or HTML pages. 
             Each page must link to the style sheet using the <link> tag:
         
      	<head>
        <link rel="stylesheet" type="text/css" href="mystyle.css" />
      	</head>
      
      	Internal Style Sheet: It is used when a single HTML document has a unique style and several elements need to be styled to follow the format.
           Internal styles sheet is added in the head section of an HTML page, by using the <style> tag:
         
      	<head>
        	<style  type="text/css">
        	 h1{
        	 }
      	</head>

#### 7. What are the different types of lists in HTML?
	      There are three lists in HTML: ordered, unordered, and definition. 
           1. Ordered lists are numbered lists.
           2. unordered lists are bulleted lists.
           3. definition lists are lists of terms and their definitions.

#### 8. What is the difference between HTML and HTML5?
      	HTML5 is the latest version of HTML and includes new features and improvements over previous versions.
         Some key differences between HTML and HTML5 include support for multimedia elements (such as video and audio), improved semantics, and better support for mobile devices.

#### 9. What is the difference between an absolute and relative URL?
	      An absolute URL includes the full web address, the protocol (such as http or https) and the domain name (such as www.example.com). 
         A relative URL, on the other hand, specifies the location of a resource relative to the current web page.
         For example, a relative URL might include the file path (such as /images/picture.jpg) or the relative path (such as ../images/picture.jpg).

#### 10. What is the difference between “display: none” and “visibility: hidden” when used as attributes to the HTML element?
	        The main difference between “display: none” and “visibility: hidden” is that the former removes the element from the document flow, while the latter simply hides it. 
          Elements with “display: none” are not visible and do not take up any space on the page, while elements with “visibility: hidden” are not visible but still take up space.

#### 11. What is the use of CSS Opacity?
	        The CSS opacity property is used to specify the transparency of an element. In simple word, you can say that it specifies the clarity of the image. 
         In technical terms, Opacity is defined as the degree to which light is allowed to travel through an object.

#### 12. Name the property for controlling the image scroll in the background.
        	The background-attachment property is used to specify if the background image is fixed or scroll with the rest of the page in the browser window. 
           If you set fixed the background image, then the image not move during scrolling in the browser. 
           Let's take an example with the fixed background image.
            	background: white url('bbb.gif');  
            	background-repeat: no-repeat;  
            	background-attachment: fixed; 

#### 13. What is the CSS Box model and what are its elements?
        	The CSS box model is used to define the design and layout of elements of CSS.
        	The elements are:
            	Margin - It removes the area around the border. It is transparent.
            	Border - It represents the area around the padding
            	Padding - It removes the area around the content. It is transparent.
            	Content - It represents the content like text, images, etc.

#### 14. What is meant by RGB stream?
	        RGB represents colors in CSS. The three streams are namely Red, Green, and Blue. 
         The intensity of colors is represented using numbers 0 to 256. This allows CSS to have a spectrum of visible colors. 

#### 15. How can you target h3 and h2 with the same styling?
	        Multiple elements can be targeted by separating with a comma:
         
	          h2, h3 {color: red;}

#### 16. What does !important mean in CSS?
	T      The style “!important” in the CSS has the highest precedence. Also, the cascaded property will be overridden with it.

#### 17. The correct way to select only inputs which are "disabled" is?
		      input:disabled

#### 18. To give the effect of using tables without actually using tables in the HTML use:
		      display:table

#### 19. li:nth-child(2n+1) { background-color: rgba(225, 0, 30, 0.8); } This code will:
		      change the background color for each odd numbered li tag

### javascript-Bootstrap
#### 1. What is equality in JavaScript ?
    	JavaScript has both strict and type–converting comparisons:
    	Strict comparison (e.g., ===) checks for value equality without allowing coercion.
     
    	Abstract comparison (e.g. ==) checks for value equality with coercion allowed.
        	eg:  a='42', b=42
        	a == b true;
        	a === b false;

#### 2. Given a string, reverse each word in the sentence
    	var string = "Welcome to this Javascript Guide!";
    
    	// Output becomes '!ediuG tpircsavaJ siht ot emocleW'
    	var reverseEntireSentence = reverseBySeparator(string, "");
    
    	// Output becomes 'emocleW ot siht tpircsavaJ !ediuG'
    	var reverseEachWord = reverseBySeparator(reverseEntireSentence, " ");
    
    	function reverseBySeparator(string, separator) {
    	  return string.split(separator).reverse().join(separator);
    	}
#### 3. What are the features of JavaScript?
    	Following are the features of JavaScript:
    
    	It is a lightweight, interpreted programming language.
    	It is designed for creating network-centric applications.
    	It is complementary to and integrated with Java.
    	It is an open and cross-platform scripting language.

#### 4. In how many ways a JavaScript code can be involved in an HTML file?
    	There are 3 different ways in which a JavaScript code can be involved in an HTML file:
        	1. Inline
        	2. Internal
        	3. External
    
    	An inline function is a JavaScript function, which is assigned to a variable created at runtime. 
       You can differentiate between Inline Functions and Anonymous since an inline function is assigned to a variable and can be easily reused. 
    	  When you need a JavaScript for a function, you can either have the script integrated in the page you are working on, or you can have it placed in a separate file that you call, when needed. 
         This is the difference between an internal script and an external script.
     
#### 5. What are the ways to define a variable in JavaScript?
      	The three possible ways of defining a variable in JavaScript are:
      
      	Var – The JavaScript variables statement is used to declare a variable and, optionally, we can initialize the value of that variable.
             Example: var a =10; Variable declarations are processed before the execution of the code.
             
      	Const – The idea of const functions is not allow them to modify the object on which they are called. 
               When a function is declared as const, it can be called on any type of object.
               
      	Let – It is a signal that the variable may be reassigned, such as a counter in a loop, or a value swap in an algorithm. 
              It also signals that the variable will be used only in the block it’s defined in.

#### 6. What is the difference between null & undefined?
    	Undefined means a variable has been declared but has not yet been assigned a value. On the other hand, null is an assignment value. 
       It can be assigned to a variable as a representation of no value.
       Also, undefined and null are two distinct types: undefined is a type itself (undefined) while null is an object.

#### 7. What would be the result of 2+5+”3″?
	  Since 2 and 5 are integers, they will be added numerically. And since 3 is a string, its concatenation will be done. 
     So the result would be 73. The ” ” makes all the difference here and represents 3 as a string and not a number.

#### 8. What will be the output of the code below?
  	var Y = 1;
  	if (function F(){})
    	{
    	y += Typeof F;</span>
    	}
  	console.log(y);
   
	    The output would be '1undefined'. The if condition statement evaluates using eval, so eval(function f(){}) returns function f(){} (which is true). 
       Therefore, inside the if statement, executing typeof f returns undefined because the if statement code executes at run time, and the statement inside the if condition is evaluated during run time.

#### 9. What is the difference between window & document in JavaScript?
	window :- JavaScript window is a global object which holds variables, functions, history, location.
	document :- The document also comes under the window and can be considered as the property of the window.

#### 10. How you can submit a form using JavaScript?
		To submit a form using JavaScript use
		document.form[0].submit();

#### 11. What is called Variable typing in Javascript?
		Variable typing is used to assign a number to a variable. The same variable can be assigned to a string.
		    eg: - i = 10;
				i = "string";	

#### 12. What is the difference between an alert box and a confirmation box?
		An alert box displays only one button, which is the OK button.
		But a Confirmation box displays two buttons, namely OK and cancel.

#### 13. What is break and continue statements?
	      Break statement exits from the current loop.

	      Continue statement continues with next statement of the loop.

#### 14. shift() and unshift() in javascript
		  The shift() method removes the first element from an array and returns that removed element. This method changes the length of the array.

          	const array1 = [1, 2, 3];
          	const firstElement = array1.shift();
          	console.log(array1);
          	// Expected output: Array [2, 3]
          	console.log(firstElement);
          	// Expected output: 1

	    The unshift() method adds the specified elements to the beginning of an array and returns the new length of the array.
          	const array1 = [1, 2, 3];
          	console.log(array1.unshift(4, 5));
          	// Expected output: 5
          
          	console.log(array1);
          	// Expected output: Array [4, 5, 1, 2, 3]

#### 15. What is the difference between the scope of the variables in JavaScript?
		    JavaScript variables have different scopes. The scope of the variable is nothing but the functionality of the variable.

		  Global variables- Global variables consist of global scope whereas these variables can be utilized in the whole program repeatedly.
      
		  Local Variables- Local variables have no scope and are used only once in the whole program.

#### 16. How do you make images responsive?
	      Bootstrap allows to make the images responsive by adding a class .img-responsive to the <img> tag. This class applies max-width: 100%; and height: auto; to the image so that it scales nicely to the parent element.

#### 17. What do you mean by column ordering in Bootstrap?
	        Column ordering is one of the most interesting features found in bootstrap. By using appropriate functions, the columns can be written easily and also in a defined order. 
         You can also show them in another column. In order to change or alter the order of the column easily, the functions .col-md-push-* and .col-md-pull-* can be used.

#### 18.  What is the Bootstrap Grid System?
	      The Bootstrap Grid System is a responsive, mobile-first system that scales up to 12 columns as per the increase in the device or viewport size. 
       The system features predefined classes for easy layout options and powerful mix-ins for generating effectively semantic layouts.

#### 19. Why do we need to use Bootstrap? 
		It is a free and open-source Web Designing Framework.
    	Bootstrap has the support of all the web browsers like Internet Explorer, Google Chrome, Firefox, Opera, Safari, etc.
    	It is a very powerful mobile first front-end framework.
    	Also, it is very easy to start as one needs to have an idea of HTML and CSS only to work with it.
    	We can design a responsive website through it which adjust to desktop, tablet, and mobile.
    	It comprises functional built-in components which are easy to customize.

#### 20. How can you make an image round in Bootstrap 4?
	       You can use the .rounded class to make an image round.

#### 21. What is the purpose of the grid system?
	        By using the grid system, we can make up to 12 columns across a page. Different classes have been defined for this purpose.

### DBMS-RDBMS
#### 1. What are the advantages of DBMS over traditional file-based systems? 
      	Some of the most important advantage of DBMS over traditional file-based systems are:
          	.Data redundancy can be controlled
          	.No unauthorized access of data
          	.Multiple user interfaces
          	.Easy accessibility and processing of data
          	.Provides backup and data recovery

#### 2. What is the difference between an entity and an attribute?
	      An entity refers to a real-world object in a database. For example, in an employee database, the different entities can be employee, designation, department, and so on. 

	      An attribute is a characteristic that describes an entity. For example, the entity “employee” can have name, ID and age as its attributes. 

#### 3. What is the main difference between DELETE and TRUNCATE command?
	      DELETE command is used to remove the rows in a table based on the condition set by the WHERE clause. The rows deleted can be rolled back.

	      TRUNCATE command is used to remove all the rows in a table without any conditions. The rows cannot be rolled back.

#### 4. What are the differences between Hash join and Merge join?
	      Hash join - A hash join is used to join large tables.

	      Merge join - A merge join is used to join two input streams of the joined tables into a single output stream.

#### 5. What is the main difference between two and three-tier architectures?
           In two-tier clients directly communicate with the database at the server-side, but in three-tier clients communicate with an application(GUI) on the server-side, that makes the system more secure and accessible. 
           This application thereafter communicates with the database system.

           client-application-database(2-tier)
           client-GUI(Graphical user interface)-application-database(3-tier)

#### 6. Do we consider NULL values the same as that of blank space or zero? 
	      A NULL value is not at all same as that of zero or a blank space. The NULL value represents a value which is unavailable, unknown, assigned or not applicable whereas zero is a number and blank space is a character.

#### 7. What are the differences between an Unique constraint and a Primary Key?
	      The difference between a UNIQUE constraint and a Primary Key is that per table you may only have one Primary Key but you may define more than one UNIQUE constraints. 
         Primary Key constraints are not nullable. UNIQUE constraints may be nullable.

#### 8. How do you communicate with an RDBMS? 
	      SQL (Structured Query Language) is used in order to communicate with the RDBMS. 

#### 9. How do you know which database model to choose while creating a database?
	      This depends entirely on the purpose of the database, as each model has its own strengths.
         For example, if you want to use atomic data, a relational model works best.
         If you want to use text or semi-structured data, the document model works best. 

#### 10. What is Buffer Manager?
	      Buffer Manager is a program module responsible for fetching data from disk storage into main memory and determining what data to cache in memory.

#### 11.  Explain what is a deadlock and mention how it can be resolved?
	      Deadlock is a situation which occurs when two transactions wait on a resource which is locked or other transaction holds.
         Deadlocks can be prevented by making all the transactions acquire all the locks at the same instance of time. So, once deadlock occurs, the only way to cure is to abort one of the transactions and remove the partially completed work.

#### 12. How can you perform pattern matching in SQL?
	      You can perform pattern matching in SQL by using the LIKE operator.  With the LIKE operator, you can use the following symbols:

        	%(Percentage sign) – To match zero or more characters.
        
        	_ (Underscore) –To match exactly one character.
        
        	Example:
        
        	SELECT * FROM Customers WHERE CustomerName LIKE ‘s%’
        
        	SELECT * FROM Customers WHERE CustomerName like ‘xyz_’

#### 13. What is a different type of index?
    	   Clustered index: It is the index at which data is physically stored on the disk. Therefore, only one clustered index can 	be created in a database table.
        
    	   Non-clustered index: It does not define physical data but represents a logical ordering. Typically, B-Tree or B+Tree data structures are created for this purpose.

#### 14. What is a view in SQL? How to create a view?
     	A view is a virtual table based on the result-set of an SQL statement. We can create it using create view syntax. 
     
    	CREATE VIEW view_name AS
    	SELECT column_name(s)
    	FROM table_name
    	WHERE condition...

### FIREBASE
#### 1. Is firebase frontend or backend?
	        Since Firebase is a backend solution, users can do anything on backend with the Firebase admin sdk.

#### 2. Which method is used to update the firebase data?
	      We can utilize setValue() on the relevant child reference to update a single node in our JSON database.

#### 3. which sort order supports Firebase?
	    According to the documentation, there is no descending order in Firebase, it support ascending order:
	    orderByChild() : The children with a numeric value come next, in increasing order. If more than one child has the same numerical value for the same child node, the children are sorted by key.
	    We can use Collection.reverse(datalist) to perform descending sort order.

#### 4. What are the main features of Firebase?
    	.Authentication
    	.Real-time Database
    	.Hosting

#### 5. How can we create a unique key and use it to send data in Firebase?
	    We can use push() to establish a unique key in the Firebase database, and then add child nodes to that key. When you return to that activity in the future, check to see if the parent node is still present. 
     Save the parent node key and use it to save new child nodes if the node already exists.

#### 6. How Can we retrive data from firebase ?
	      on() method is used to retrieve data.

### SOFTWARE ENGINEERING
#### 1. What different software development life cycle (SDLC) models are available?
      	Like there are different leadership styles, there are different approaches to the SDLC.
      	SDLC models include:
      	a.Waterfall
      	b.Continuous integration
      	c.Incremental development
      	d.Rapid application development
      	e.Agile

#### 2. What is agile software development?
	     Agile software development, also known as agile, is an incremental, collaborative approach. Agile is a method focused on continuously delivering work rather than waiting to deliver one big product. 

#### 3. What is software scope?
	      Software scope is the project’s boundaries, meaning everything software will be able to do (and limitations on what it won’t be able to do). Software scope can help determine the needed resources, budget, and development timeline.

#### 4. What is the main difference between a computer program and computer software?
	      a. The key difference between software is a collection of several programs used to complete tasks, whereas a program is a set of instructions expressed in a programming language. 
           A program can be software, but software the vice versa is not true.
	      b.  A computer program is a piece of programming code. It performs a well-defined task. On the other hand, the software includes programming code, documentation and user guide.

### NETWORKING
#### 1. What are 127.0.0.1 and localhost?
	      Localhost is the standard hostname given to the machine, and it is represented by the IP address 127.0.0.1. Therefore, we can say that 127.0.0.1 and localhost are the same thing.

#### 2. What is a Gateway?
	      A gateway is a hardware device that is connected to two or more networks. It may be a router, firewall, server, or any other similar device, and is capable of regulating traffic in the network.

#### 3.  Is there a difference between a gateway and a router?
	      A gateway sends the data between two dissimilar networks, while a router sends the data between two similar networks.

#### 4. What are ‘firewalls’?
	      A firewall is a network security system, responsible for managing network traffic. It uses a set of security rules to prevent remote access and content filtering. 
         Firewalls protect the systems or networks from viruses, worms, malware, etc. Firewalls are usually of two types –

	        Physical – A physical firewall or hardware firewall is a physical device that sits between the external network and the server. 
           They analyze incoming traffic and filter out any threats to the device. Widely used in institutions and large companies. 

      	  Logical – A logical or software firewall can exist anywhere on the subnet and protects hosts anywhere without rewiring. 
            They only protect the computer on which they are installed, and in many cases, they are integrated into the operating system.

#### 5. What are the HTTP and the HTTPS protocol?
	      HTTP is the HyperText Transfer Protocol which defines the set of rules and standards on how the information can be transmitted on the World Wide Web (WWW).
         It helps the web browsers and web servers for communication. It is a ‘stateless protocol’ where each command is independent with respect to the previous command.
         HTTP is an application layer protocol built upon the TCP. It uses port 80 by default.

	    HTTPS is the HyperText Transfer Protocol Secure or Secure HTTP. It is an advanced and secured version of HTTP. On top of HTTP, SSL/TLS protocol is used to provide security. 
       It enables secure transactions by encrypting the communication and also helps identify network servers securely. It uses port 443 by default.

### COMPUTING
#### 1. What is an API Gateway?
	    An API gateway allows multiple APIs to act together as a single gateway to provide a uniform experience to the user. In this, each API call is processed reliably. 
       The API gateway manages the APIs centrally and provides enterprise-grade security. Common tasks of the API services can be handled by the API gateway. 
       These tasks include services like statistics, rate limiting, and user authentication.

#### 2. What are the different data types used in cloud computing?
	        There are different data types in cloud computing like emails, contracts, images , blogs etc. As we know that data is increasing day by day so it is needed to new data types to store these new data.
         For an example, if you want to store video then you need a new data type(.avi, .mts, .wmv).

#### 3. Which platforms are used for large scale cloud computing?
	      The following platforms are used for large scale cloud computing:

        	 Apache Hadoop
        	 MapReduce

#### 4. What are the different models for deployment in cloud computing?
        	These are the different deployment model in cloud computing:
        	a.Private cloud
        	b.Public cloud
        	c.Hybrid cloud
        	d.Community cloud(optional if candidate don't mention it)

#### 5. What are Hybrid clouds?
	        Hybrid clouds are the combination of public clouds and private clouds. It is preferred over both the clouds because it applies most robust approach to implement cloud architecture. 
           It includes the functionalities and features of both the worlds. It allows organizations to create their own cloud and allow them to give the control over to someone else as well.

#### 6. What are the advantages of cloud services?
    	Following are the main advantages of cloud services:
    	  Cost saving: It helps in the utilization of investment in the corporate sector. So, it is cost saving.
    	  Scalable and Robust: It helps in the developing scalable and robust applications. Previously, the scaling took months,	but now, scaling takes less time.
    	  Time saving: It helps in saving time in terms of deployment and maintenance.
