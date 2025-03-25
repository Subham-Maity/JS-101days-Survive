# Setup Guide – CodeXam
### ✈️ Method 1: (Common)[](#️-method-1-common)

1.  With HTML

To use JavaScript in a web browser, you need to have a web page with an HTML `<script>` tag that includes the JavaScript code. Here is an example:

CodeXam.java

```
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript in the Browser</title>
</head>
<body>
<h1>My Web Page</h1>
<p>This is some text on the page.</p>
<script>
    // This is where you put your JavaScript code
    alert('Hello, world!');
</script>
</body>
</html>
```


You can put the `<script>` tag either in the `<head>` section of the page, or at the end of the `<body>` section. It is generally best to put it at the end of the `<body>` section, so that the page loads and renders before the JavaScript is executed.

Once you have your JavaScript code in a web page, you can open the page in a web browser to run the code.

![example](https://github.com/Subham-Maity/JS-101days-Survive/blob/main/001.Setup%20&%20Installation/picndvid_xam/1.png?raw=true)
![example](https://github.com/Subham-Maity/JS-101days-Survive/blob/main/001.Setup%20%26%20Installation/picndvid_xam/1.png)

2.  Browser Console

The browser console is a tool that is built into most web browsers. It allows you to run JavaScript code and see the results. You can open the browser console in Chrome, Firefox, Safari, and Edge. Here are the steps to open the browser console in Chrome:

1.  Open a web page that includes JavaScript code.
    
2.  Right-click anywhere on the page and select **Inspect**.
    
3.  Click the **Console** tab.
    
4.  Type some JavaScript code into the console and press **Enter** to run it.
    

![example](https://github.com/Subham-Maity/JS-101days-Survive/blob/main/001.Setup%20&%20Installation/picndvid_xam/2.png?raw=true)![example](https://github.com/Subham-Maity/JS-101days-Survive/blob/main/001.Setup%20&%20Installation/picndvid_xam/3.png?raw=true)

### 🛩️ Method 2: (Easy)[](#️-method-2-easy)

With NODE.JS

Basically, Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine. Ryan Dahl created Node.js in 2009 and its popularity has been increasing ever since. Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser. He puts the V8 JavaScript engine in a C++ program. The program is called a Node.js application. It can be run on any platform that supports C++.![example](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Ryan_Dahl.jpg/800px-Ryan_Dahl.jpg)

To run JavaScript using Node.js, follow these steps:

1.  Install Node.js on your computer. You can download the latest version from the official Node.js website ([https://nodejs.org/en/ (opens in a new tab)](https://nodejs.org/en/)).
    
2.  Open a new text editor and create a new file with the .js extension. This file will contain your JavaScript code.
    
3.  In your text editor, type the following code to print "Hello, World!" to the console:
    

```
 console.log("Hello, World!");
```


4.  Save the file.
    
5.  Open a command prompt or terminal window and navigate to the directory where you saved the file.
    
6.  Type the following command to run the JavaScript file:
    

Replace "filename" with the name of your JavaScript file.

7.  If everything was successful, you should see the "Hello, World!" message printed to the console. You can now write and run JavaScript code using Node.js! Keep in mind that Node.js is primarily used for server-side programming, so you may want to learn more about how to create web servers and work with databases to fully utilize its capabilities.

### 🚀 Method 3: (Easiest)[](#-method-3-easiest)

With IDE (Integrated Development Environment)

We prefer if you are student you can use your college email to get free access to this WebStorm IDE. And this is the best IDE for JavaScript. You can also use Visual Studio Code, Atom, Sublime Text, etc. But we recommend you to use WebStorm. You can download it from here: [https://www.jetbrains.com/webstorm/download/#section=windows (opens in a new tab)](https://www.jetbrains.com/webstorm/download/#section=windows)

1.  Install WebStorm on your computer. You can download the latest version from the JetBrains website ([https://www.jetbrains.com/webstorm/download/ (opens in a new tab)](https://www.jetbrains.com/webstorm/download/)).
    
2.  Open WebStorm and create a new project.
    
3.  In the project window, right-click on the project name and select "New" and then "JavaScript File" from the drop-down menu.
    
4.  Type your JavaScript code in the editor window.
    
5.  To run the code, go to the "Run" menu and select "Run 'filename'" (replace "filename" with the name of your JavaScript file).
    
6.  The code will be executed and the results will be displayed in the console window at the bottom of the screen.
    

Alternatively, you can also use the keyboard shortcut Ctrl+Shift+F10 to run the code without going through the menu.

You can now run JavaScript code in WebStorm! You can also use the built-in debugger to set breakpoints, step through your code, and inspect variables and other data. For more information, see the [WebStorm documentation (opens in a new tab)](https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html)

### 🛸 Method 4: (Best and Future)[](#-method-4-best-and-future)

With Online IDE

Advantage

*   Accessibility: Online IDEs can be accessed from anywhere with an internet connection, so you can code from your home, office, or on the go.
    
*   Ease of use: Online IDEs are user-friendly and easy to set up, so you can start coding quickly without having to install any software or configure your development environment.
    
*   Collaboration: Online IDEs make it easy to share your code and collaborate with other developers in real time. This can be especially useful for pair programming or working on group projects.
    
*   Community support: Many online IDEs have active communities of developers who can provide help and support if you run into any problems.
    
*   Built-in tools and features: Many online IDEs include built-in tools and features that can help you write, test, and debug your code more efficiently. For example, some IDEs have integrated debuggers, code linters, and automatic code completion.
    

How to use most of the online IDE ?

Open the StackBlitz online code editor in your web browser. You can find it at [https://stackblitz.com/ (opens in a new tab)](https://stackblitz.com/). you can use other online IDE like CodePen, Repl.it, codeSandbox, etc.

1.  Create a new project by clicking on the "Create New Project" button. This will open a new editor window.
    
2.  In the "New Project" window, select the "Node.js" option from the list of available technologies.
    
3.  This will create a new Node.js project in StackBlitz, and you will see a default "index.js" file in the editor.
    
4.  You can write your JavaScript code in the "index.js" file, and then save it by clicking on the "Save" button.
    
5.  To execute your JavaScript code, click on the "Run" button in the top-right corner of the editor or in CLI type "node index.js".
    
6.  This will open a new window with the Node.js command-line interface (CLI), where you can see the output of your code.
    
7.  Or you can also use javascript console to see the output of your code.
    

To stop the execution of your code, you can press the "CTRL + C" keys on your keyboard.

Look at the console window at the bottom of the screen. You can see the output of your code there.
