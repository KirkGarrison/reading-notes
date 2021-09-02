## JavaScript Functions

[Back page](README.md)

- Javascript has what's called a "control flow," which means it reads and executes code from right to left, top to bottom.

- There are exceptions to this, such as conditions or loops. These parameters can alter the control flow to optimize the desired result of the code's execution.

- One function in JavaScript is what's called an "If, Else" function.
It essentially tells the computer If* the user does/says this, then execute X function.
Else* do/execute Y function.

### Example:

```
if(userName.toLowerCase() == 'steve') {
    document.write('Welcome ' + userName);
}
else {
    document.write('<h2>' + userName + '</h2>')
}
```

- In this example, the computer would prompt the user to enter their name. If their name is "Steven," then they will get a nice "Welcome" message before their name.
Any other name, and it will just display the name given.