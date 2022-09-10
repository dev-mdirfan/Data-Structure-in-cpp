# Introduction to c++

- A general-purpose programming language.
- C++ is designed & implemented by `Bjarne Stroustrup` in  1979 at Bell Labs.
- C++ is actually an extension of c language with more feature and more powerful than c language
- It runs on a variety of platforms, such as Windows, MacOS, and the various versions of UNIX.
- **Fun Fact :** The initial version of C++ was called `C with classes`.

## C++ : An Extension of C

- C++ is :
    - a better C
    - It supports data abstraction
    - It supports object-oriented programming
    - It supports generic programming

- In C Language :
    - Let **i** be an integer variable whose value = 6
    - Now, **i++** will increment the value by 1
    - `++` is an increment operator. So i++ will make i=7
    - Hence the name C++ was chosen to denote it being the "next","successor", or "increment" of C

### Prerequisites :

- Do I need to have prior knowledge of C to learn C++ ?
    - No
- Do I need to know any other programming language before learning C++ ?
    - No

### Syllabus :
- Introduction
- Variables and Basic Types
- Strings, Vectors, and Arrays
- Expressions
- Statements
- Functions
- Classes
- The IO Library
- Overloaded Operations and Conversions
- Object-Oriented Programming

### Writing a Simple C++ Program

- **Function :** Every C++ Program contains one or more functions, one of which must be named `main`.
- The operating system runs a C++ program by calling main.
- Structure of main body :
<pre>
int main()
{
    return 0;
}
</pre>
- A simple version of main that does nothing but return a value to the operating system.


### Elements of a function definition :
- A function definition has 4 elements :
    - A return type.
    - A function name.
    - A (possibly empty) parameter list enclosed in parentheses.
    - A function body

<pre>
int main()
{
    return 0;
}
</pre>

- return type : `int`
- function name : `main`
- parameter list : `()`
- function body : `{ operations(inside curly braces) }`

### An Example :
    #include<iostream>
    using namespace std;

    int main()
    {
        cout<<"Welcome to the C++ world.";
        return 0;
    }
- **Output :** Welcome to the C++ world.

### Types :

- One of the most fundamental concepts in programming.
- A type defines both the contents of a data element and the operations that are possible that are possible on those data.

### Example :
- `int my_variable;`
    - my_variable has type integer.
    - my_variable is an integer.

