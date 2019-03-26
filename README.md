# JavaScript assignment

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**

"//" should be included before the line of comment code.

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**

In order to 'run' a JavaScript program it must be implemented within an html file so that running the html file runs the JavaScript code.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**

The 'displayInformation' function and 'alert' function seem to be similar to the 'print' function in Python because both are used to show the user some information. Alert is preferred to use in pop-ups to immediately get the user's attention.

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**

The 'alert' line would have to be commented out.

* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**

Replace the contents of the respective line in the displayInformation function.

* **What does the word `document` represent in this code? Explain briefly.**

Document represents the DOM in which all the tags exist.

* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**

Every element with the 'li' tag is being counted in order to output the length.

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**

White

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**

The colors of these boxes, the 'p' tag, were set through the CSS code in <style>. This can edited by changing the 'background-color' hex code in the 'p' tag.

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**

I changed the output string in the copyFunction from "Go Blue!" to "0 Canada". I also added an oncopy="copyFunction()" to McGill University so it calls copyFunction when the line is copied. I knew to do this because a similar thing was done on the University of Michigan line.

* **In the original code, when you click the button that says `Wow`, you see a text box! Wow. Explain briefly in your own words why the following code causes that to happen:**


```js
function handleClick(){
	alert("hello");
}
```
**and**

```js
<button onclick=handleClick() id="wow-button">Wow</button>
```

The first part of the code creates a function to do something when something is clicked, hence "handleClick". That something that happens in this case is a pop-up that says "hello".

The second part of the code creates a button with the "handleClick" function (defined above) integrated so that when the button is clicked, something happens aka a pop-up appears saying "hello"

* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**



### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**

The error is red and the valid input is blue because that is what was defined for each state in the CSS code.

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**

I googled "regex a-zA-Z" and learned that this helps define the type of input we consider valid.

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**

There is no return statement in JavaScript whereas in Python, a return statement is required for conditional statements.

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**

I think it's the speed at which the text will fade out.

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

A page can only be manipulated when the document is "ready." The code shown detects when the document is ready then runs. The jquery code can only run when Document Object Model (DOM) is ready for JavaScript execution.
