# Debugging

## Execution Context And Scope

- Global Context: any code that not in a block of code it will be global
- function Context: any code that in a block of code it will be in its scope and have its context

## Error object

- `Error.name` : type of the error
- Error.message: description
- Error.fileNumber: name of the file that has the error
- Error.lineNumber: number of the line that occurs the error

good link abut using chrome debug tool: [Debugging JavaScript - Are you doing it wrong?](www.youtube.com/watch?v=ABlaMXkUwzY)

## try-catch

```
try {
// Try to execute this code
catch (exception) {
// If there is an exception, run this code
finally {
// This always gets executed
```

try block test your code if there is an error then the catch block will execute. finally, block will always run.

`throw new Error('message') ;`

using this statement in the try box you can create your new custom Error.
