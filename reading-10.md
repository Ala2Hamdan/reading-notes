# The Call Stack and Debugging

![Image](https://miro.medium.com/max/752/1*7GXoHZiIUhlKuKGT22gHmA.png)

* The call stack  is a mechanism to  how for function invocation (call) where function(s) execution, is done, one at a time, from top to bottom

*  Debugging :its used to check the running code line by line to get where exactly an error happens.


## Error Types:
* Reference errors: for not declared vars, it is happened when you try to use a variable that is not declared yet .
- Syntax errors: this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
- Range errors: Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
- Type errors: when the types (number, string and so on) you are trying to use or access are incompatible.

*  Handling errors
- it is a way to catch error and send it to a error logging to be checked later and send a fallback to the function so that our code continues without problems.
- The commonly used function is (`try....catch`)