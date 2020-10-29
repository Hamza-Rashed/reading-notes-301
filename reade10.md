# Call Stack 
A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

   * When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
    Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
    When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
    If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.
    ![](https://youshaohua.com/assets/img/post/simply-and-easily-understanding-function-call-stack-by-a-vision/thum.jpg)
    
# Types of error messages
    there is many type of message like : 
  1. Reference errors:
  2. Syntax errors
  3. Range errors
  4. Type errors
  
and you can console it to know what is the error .

# Debugging
To debug your JS code, the easiest and maybe the most common way its to simply console.log() the variables you want to check or, by using chrome developer tools, open your page with your JS code (press cmd+o in macOS or Ctrl+o in Windows) and choose your file to debug, click the line you wanna debug and refresh your page again (F5).

If the line you selected was run you will be able to see what has happened before that point and you can try and evaluate the next lines to check if everything is outputting what you are expecting.

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.
  
  ![](https://resources.jetbrains.com/help/img/idea/2020.2/ws_node_multiprocess_dark.png)
