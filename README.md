# Assignment: 02-basics-01-variables
This assignment introduces how __variables__ are __declared__ and __initialized__ in C++.

### 0. Get Started
You will always do these two steps:
1. Launch Xcode and clone this repository.
2. Update the comment header with your name/date.

### 1. Initialize the Code
Copy and paste the following code over the existing code:

```
#include <iostream>
using namespace std;

int main(int argc, const char * argv[]) {

  cout << "There once was a man named George." << endl;
  cout << "He was 70 years old." << endl;
  cout << "He liked the name George." << endl;
  cout << "But he did not like being 70." << endl;

  return 0;

}
```

Build and run your code to test that it works properly. When it is working, commit and push it to GitHub.
Be sure to use the section heading as the commit message: _1. Initialize the Code_.

$$\large{{\text{\color{red}In Desmos, respond to Prompt 1 on Screen 2}}}$$

### 2. Declare and Initialize a _string_ Variable
Declare and initialize a `string`:
```
string characterName = "John";
```

Use the string to change:
```
cout << "There once was a man named George." << endl;
```
to
```
cout << "There once was a man named" <<  characterName << "." << endl;
```

Test your code to ensure it runs correctly. Commit and push it to GitHub.
Again, be sure to use the section heading as the commit message: _2. Declare and initialize a string variable_.

### 3. Edit Your Code to Use an _integer_ Variable:
Use:
```
int characterAge;
characterAge = 35;
```
to update your code to use the variable `characterAge` instead of `70`.

Test your code to ensure it runs correctly. Commit and push it to GitHub.
Use the section heading as the commit message.

### 4. Changing a Variable Value
Copy and paste the following code over the existing code:
```
#include <iostream>
using namespace std;

int main(int argc, const char * argv[])  {

  string characterName = "John";
  int characterAge;
  characterAge = 35;

  cout << "There once was a man named " << characterName << "." << endl;
  cout << "He was " << characterAge << " years old." << endl;
  characterName = "Mike";
  cout << "He liked the name " << characterName << "." << endl;
  cout << "But he did not like being " << characterAge << "." << endl;                              

  return 0;

}
```
Build and run your code.
Commit and push it to GitHub. Use the section heading as the commit message.

$$\large{{\text{\color{red}In Desmos, respond to Prompt 1 on Screen 3}}}$$

### 5. Wrap Up
You will always do these two steps:
1. Double-check you have properly committed/pushed all steps (view your change history on GitHub).
2. Read the _Notes.md_ and summarize the main points in your composition book.
