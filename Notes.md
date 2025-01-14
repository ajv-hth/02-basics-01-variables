# Class Notes: An Introduction to Variables
(Repository: _02-basics-01-variables_)

An introduction to variables.

## Notes about the Formatting of Class Notes
This section is provided as background. It can be omitted for note-taking purposes.

In C++ _Class Notes_, a few formatting conventions are used to provide clarity:
- the first time a __new term__ is used, it is written in __bold font__:
  - these terms should be in your composition book along with a brief description or definition.
- a _recently new term_ is written in _italic font_
  - eventually, the term is no longer emphasized.
- a `piece of code` is written in a `code block`:
  - code blocks can be `inline` or standalone:
```
a standalone block of code: note the copy button on the right    ---->
```

## Preamble
This section is also provided as background. It can be omitted for note-taking purposes.

A __variable__ is a type of __identifier__. In C++ an _identifier_ is a name used to refer to a program __element__. Other types of indentifiers include:
- Functions (perform actions)
- Classes/Structs (define user-defined types)
- Constants (immutable values)
- Enumerations (named integral constants)
- Namespaces (scope management)

There three types of variables:
1. Primitive (`int`, `float`, `char`, etc.)
2. Derived (__pointers__, __arrays__, __references__)
3. User-defined (`struct`, `class`, `union`)

## Variables
A _variable_ is a named storage location, making it an _identifier_ that references memory for holding data: you can think of variables as 'containers' for holding data values. When a program executes, main memory is allocated to store the data values.

To use variables in a program, two things must be specified:
  1. the __type__ of data to be stored, and
  2. the __name__ of the variable.
 
### Strings
One type of variable in C++ is a `string`, which is short for "a string of characters". A `string` is always placed inside double quotes. An example of a `string` that is already in the program is:

```
"There once was a man named George"
```

An example of __declaring__ a `string` and __initializing__ its value:

```
string characterName = "John";
```

To use variables, we simply use their names:

```
cout << ""There once was a man named " << characterName << "." << endl;
```

### Integers
Another type of variable is the integer type: $$\dots, -2, -1, 0, 1, 2, \dots$$.

In C++, it is abbreviated as `int`:

```
int characterAge;
```
The above line of coding is an example of declaring a variable __without__ initializing it.
It is always good practice to initialize a variable before it is used by __assigning__ it a value:

```
characterAge = 35;
```

### The Greco Connection
In the Greco Assembly Language, variables were implemented using labels. To _declare_ a variable you used:
```
        .data
num1:
```
To _declare_ and _initialize_ you used:
```
        .data
num1:          0A
```
To _assign_ a variable a value you used:
```
        .code
        STORL num1, FF
```

In the Greco, variable types are not used: the type of the variable is __implied__ by the instruction that uses it.
