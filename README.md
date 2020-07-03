# 100 Days of Machine Learning
![](/images/ml.png)

# Day 1 

### Basic of Python 

![](/images/Py.png)

Python is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991, Python's design philosophy emphasizes code readability with its notable use of significant whitespace. Its language constructs and object-oriented approach aim to help programmers write clear, logical code for small and large-scale projects.

Python is dynamically typed and garbage-collected. It supports multiple programming paradigms, including structured (particularly, procedural), object-oriented, and functional programming. Python is often described as a "batteries included" language due to its comprehensive standard library.

Python was conceived in the late 1980s as a successor to the ABC language. Python 2.0, released in 2000, introduced features like list comprehensions and a garbage collection system with reference counting.

Python 3.0, released in 2008, was a major revision of the language that is not completely backward-compatible, and much Python 2 code does not run unmodified on Python 3.

The Python 2 language was officially discontinued in 2020 (first planned for 2015), and "Python 2.7.18 is the last Python 2.7 release and therefore the last Python 2 release."[30] No more security patches or other improvements will be released for it.With Python 2's end-of-life, only Python 3.5. and later are supported.

Python interpreters are available for many operating systems. A global community of programmers develops and maintains CPython, an open source reference implementation. A non-profit organization, the Python Software Foundation, manages and directs resources for Python and CPython development.
#### Learning Resources for Python:
##### Video Lectures:
 1.[Learn Python - Full Course for Beginners [Tutorial]](https://www.youtube.com/watch?v=rfscVS0vtbw)
 2.[Python Tutorial for Beginners by Telusko](https://www.youtube.com/playlist?list=PLsyeobzWxl7poL9JTVyndKe62ieoN-MZ3)
3.[Complete Python tutorial in Hindi (2020) by 
  Harshit vashisth](https://www.youtube.com/playlist?list=PLwgFb6VsUj_lQTpQKDtLXKXElQychT_2j)
# Day 2

### Working on List , Loops.
#### About List

A list is a data structure in Python that is a mutable, or changeable, ordered sequence of elements. Each element or value that is inside of a list is called an item. Just as strings are defined as characters between quotes, lists are defined by having values between square brackets [ ].

Lists are great to use when you want to work with many related values. They enable you to keep data together that belongs together, condense your code, and perform the same methods and operations on multiple values at once.

When thinking about Python lists and other data structures that are types of collections, it is useful to consider all the different collections you have on your computer: your assortment of files, your song playlists, your browser bookmarks, your emails, the collection of videos you can access on a streaming service, and more.

#### About Loops
In general, statements are executed sequentially: The first statement in a function is executed first, followed by the second, and so on. There may be a situation when you need to execute a block of code several number of times.

Programming languages provide various control structures that allow for more complicated execution paths.

A loop statement allows us to execute a statement or group of statements multiple times. The following diagram illustrates a loop statement −

![](/images/Loop1.png)

#### Types Of loop in python:
#### 1. While Loop
A while loop statement in Python programming language repeatedly executes a target statement as long as a given condition is true.

          Syntax
          The syntax of a while loop in Python programming language is −
          while expression:
          statement(s)
                 
          Here, statement(s) may be a single statement or a block of statements. The condition may be any expression, and true is any non-zero value. 
          The loop iterates while the condition is true.
          When the condition becomes false, program control passes to the line immediately following the loop.
          In Python, all the statements indented by the same number of character spaces after a programming construct are considered to be part of 
          a single block of code. Python uses indentation as its method of grouping statements.

#### 2. For Loop
It has the ability to iterate over the items of any sequence, such as a list or a string.

            Syntax
           for iterating_var in sequence:
           statements(s)
           If a sequence contains an expression list, it is evaluated first. Then, the first item in the sequence is assigned to the iterating variable iterating_var. 
           Next, the statements block is executed. Each item in the list is assigned to iterating_var, and the statement(s) block is executed until the entire
           sequence is exhausted.
#### 3.Decision Making 

Decision making is anticipation of conditions occurring while execution of the program and specifying actions taken according to the conditions.

Decision structures evaluate multiple expressions which produce TRUE or FALSE as outcome. You need to determine which action to take and which statements to execute 
if outcome is TRUE or FALSE otherwise.

Example: If Else statement       
                         
           
# Day 3
### Working on Function ,Object Oriented Programming ,Exception Handling.

#### About Function 

A function is a set of statements that take inputs, do some specific computation and produces output. The idea is to put some commonly or repeatedly done task together and make a function, so that instead of writing the same code again and again for different inputs, we can call the function.
Python provides built-in functions like print(), etc. but we can also create your own functions. These functions are called user-defined functions.

#### About Object Oriented Programming 

Object-oriented Programming, or OOP for short, is a programming paradigm which provides a means of structuring programs so that properties and behaviors are bundled into individual objects.
For instance, an object could represent a person with a name property, age, address, etc., with behaviors like walking, talking, breathing, and running. Or an email with properties like recipient list, subject, body, etc., and behaviors like adding attachments and sending.
Put another way, object-oriented programming is an approach for modeling concrete, real-world things like cars as well as relations between things like companies and employees, students and teachers, etc. OOP models real-world entities as software objects, which have some data associated with them and can perform certain functions.
Another common programming paradigm is procedural programming which structures a program like a recipe in that it provides a set of steps, in the form of functions and code blocks, which flow sequentially in order to complete a task.
The key takeaway is that objects are at the center of the object-oriented programming paradigm, not only representing the data, as in procedural programming, but in the overall structure of the program as well.

#### About Exception Handling

Error in Python can be of two types i.e. Syntax errors and Exceptions. Errors are the problems in a program due to which the program will stop the execution. On the other hand, exceptions are raised when some internal events occur which changes the normal flow of the program.
# Day 4 
### Working Started With Numpy Library. 
![](/images/np.png)

NumPy is a general-purpose array-processing package. It provides a high-performance multidimensional array object, and tools for working with these arrays.

It is the fundamental package for scientific computing with Python. It contains various features including these important ones:
<ul>
          <li>A powerful N-dimensional array object</li>
<li>Sophisticated (broadcasting) functions</li>
<li>Tools for integrating C/C++ and Fortran code</li>
<li>Useful linear algebra, Fourier transform, and random number capabilities</li>
<li>Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data.</li>
<li>Arbitrary data-types can be defined using Numpy which allows NumPy to seamlessly and speedily integrate with a wide variety of databases.</li>
          </ul>

# Day 5
### Working Started with Pandas Library.
![](/images/pd.png)
Pandas is an open-source Python Library providing high-performance data manipulation and analysis tool using its powerful data structures. The name Pandas is derived from the word Panel Data – an Econometrics from Multidimensional data.

In 2008, developer Wes McKinney started developing pandas when in need of high performance, flexible tool for analysis of data.

Prior to Pandas, Python was majorly used for data munging and preparation. It had very little contribution towards data analysis. Pandas solved this problem. Using Pandas, we can accomplish five typical steps in the processing and analysis of data, regardless of the origin of data — load, prepare, manipulate, model, and analyze.

Python with Pandas is used in a wide range of fields including academic and commercial domains including finance, economics, Statistics, analytics, etc.

#### Key Features of Pandas
<ul>
          <li>Fast and efficient DataFrame object with default and customized indexing.</li>
<li>Tools for loading data into in-memory data objects from different file formats.</li>
<li>Data alignment and integrated handling of missing data.</li>
<li>Reshaping and pivoting of date sets.</li>
<li>Label-based slicing, indexing and subsetting of large data sets.</li>
<li>Columns from a data structure can be deleted or inserted.</li>
<li>Group by data for aggregation and transformations.</li>
<li>High performance merging and joining of data.</li>
<li>Time Series functionality.</li>
          </ul>

# Day 6 
### Working With Data Analysis:
![](/images/da2.png)

Data analysis is a process of inspecting, cleansing, transforming and modeling data with the goal of discovering useful information, informing conclusions and supporting decision-making. Data analysis has multiple facets and approaches, encompassing diverse techniques under a variety of names, and is used in different business, science, and social science domains. In today's business world, data analysis plays a role in making decisions more scientific and helping businesses operate more effectively.

Data mining is a particular data analysis technique that focuses on statistical modeling and knowledge discovery for predictive rather than purely descriptive purposes, while business intelligence covers data analysis that relies heavily on aggregation, focusing mainly on business information. In statistical applications, data analysis can be divided into descriptive statistics, exploratory data analysis (EDA), and confirmatory data analysis (CDA). EDA focuses on discovering new features in the data while CDA focuses on confirming or falsifying existing hypotheses. Predictive analytics focuses on application of statistical models for predictive forecasting or classification, while text analytics applies statistical, linguistic, and structural techniques to extract and classify information from textual sources, a species of unstructured data. All of the above are varieties of data analysis.

### What are examples of data analysis?

#### Data analysis is a somewhat abstract concept to understand without the help of examples. So to better illustrate how and why data analysis is important for businesses, here are the 4 types of data analysis and examples of each.
<ol>
<li>Descriptive Analysis: Descriptive data analysis looks at past data and tells what happened. This is often used when tracking Key Performance Indicators (KPIs), revenue, sales leads, and more.</li>
          
<li>Diagnostic Analysis: Diagnostic data analysis aims to determine why something happened. Once your descriptive analysis shows that something negative or positive happened, diagnostic analysis can be done to figure out the reason. A business may see that leads increased in the month of October and use diagnostic analysis to determine which marketing efforts contributed the most.</li>

<li>Predictive Analysis: Predictive data analysis predicts what is likely to happen in the future. In this type of research, trends are derived from past data which are then used to form predictions about the future. For example, to predict next year’s revenue, data from previous years will be analyzed. If revenue has gone up 20% every year for many years, we would predict that revenue next year will be 20% higher than this year. This is a simple example, but predictive analysis can be applied to much more complicated issues such as risk assessment, sales forecasting, or qualifying leads.</li>

<li>Prescriptive Analysis: Prescriptive data analysis combines the information found from the previous 3 types of data analysis and forms a plan of action for the organization to face the issue or decision. This is where the data-driven choices are made.</li>
</ol>          

