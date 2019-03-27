# JavaScript assignment

## Some useful resources
* Some [JavaScript tutorials](https://www.htmldog.com/guides/javascript/)
* The complicated [resources in the You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) series, including [your reading last week](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch2.md)
* [A resource for CSS/style/colors](https://htmlcolorcodes.com/)  
* [An excerpt from a specific workshop site](https://witny-summer-guild-2018.github.io/day_4_exercise_2.html) (for a different audience than yourselves) which addresses some common questions about jQuery
* [The simple JSFiddle example from class](https://jsfiddle.net/2of65j8q/)
* A [W3Schools resource on JavaScript output](https://www.w3schools.com/js/js_output.asp)
* Google, Piazza, your classmates, office hours, lab time!

## Included files
* This `README.md`, which you should edit with answers to the questions
* `jsPracticeLab.html`, which you'll need to edit and try out
* `jquerylib_submit_example.html`, which you'll need to edit and try out

## Your goals for this lab

### Broadly
The aim for this lab is to practice adapting to and understanding code in a new-to-you (or not) language and its own libraries/packages -- JavaScript, in this case.

The programming skills you have built up till now are useful for *Python programming*, but, more than that, they extend to fundamentals of many kinds of programming.

This experience is *not in any way* about becoming an expert JavaScript programmer. Instead, it is about using what you *do* have experience with -- and your skills in *learning new things* that relate to programming -- in order to make educated judgments about some brand new-to-you code, even if you haven't learned in detail about it yet. That's part of what being in technology -- or even technology-adjacent -- will often mean.

### Specifically

Below are a bunch of questions and indications of things to do. For each indication of something to do with code, there is also an accompanying question to answer or brief explanation to give.

**To complete and submit this assignment, you should:**

* Fork (and clone) this repository
* Add our instructional team as a collaborator to your fork (see instructions for adding collaborators on Canvas)
* Edit this `README.md` file with answers to the questions/prompts, briefly, using Markdown formatting so that the questions appear in bulletpoints and the answers appear clearly below each respective question, *not* as bulletpoints.
* Add all names of those who worked on this (as indicated below)
* Make the changes that are indicated below to each of the `.html` files with JavaScript programs provided. (You'll probably do this concurrently with answering questions)
* Commit (as you go) and push your changes to all three files to your GitHub forked repository.
* Submit a link to your repository on Canvas. (This HW doesn't have an autograder -- it will be graded by hand/by humans this time.)

### Important notes
* You are *more than* welcome to work together on this, but **you must <u>each</u> submit a repo to be graded on it**, so if you do work together, you should do the following:
	* Make sure each one of you understands all the work -- YOU are responsible for using and knowing this information
	* Write each person's name & uniqname who worked on the assignment together on your submitted `README.md` file (you'll see a space for this below)

* In answering questions, please make sure the formatting is clear to read and that you have updated the names of everyone who worked with you, with your name first (see below).

* In answering questions, assume all of the questions include a *explain briefly* note -- you do NOT have to, and should not, write extended paragraphs. Be as concise as you can and explain in your own words. Don't worry about "whether it's enough" -- just worry about conveying your understanding so you can read it later, or even give it to someone else, and the answers will help/make sense.

* It is not acceptable to copy and paste answers from the internet and submit them as your own. If you cite things, make sure you provide a citation, including to links. If you get information from a resource and rephrase it so you're basically explaining an idea, that's just fine for an explanatory purpose in this assignment, but you *must* cite any quotes or examples that aren't yours.

* **For grading:** we are grading on...
	* Following the instructions
	* Approximate correctness of the code edits
	* Careful & clear answers to the questions
	* Correct answers to the questions
	* Slightly more than half the 1000 points will come from answering the questions. The rest will come from your edits to the code.

### Names of people you have worked with on this assignment
* List everyone's names and uniqnames who have worked on this assignment with you, **including your own name, but make sure YOUR name is first and bold**
* Like this:
* **Meng Wang (mwscott)**
* Jackie Cohen (jczetta)
* Yea-Ree Chang (cyearee)
* Ruchi Ookalkar (ruchido)
* Innocent Obi (innoobi)
* Zhen Wang (alejwang)
* etc.

## Questions & code instructions

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**

The comment in JavaScript looks different from normal code. If we look at the code in Chrome, the comments are green and italic. We have to put two // before a comment.

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**

Basically, we just need to use a web browser to open the ".html" file that contains the JavaScript program. Of course, there are different ways to do that, either open it directly, or like what we did before --- use a Flask application to render the ".html" file as a template and go to the route related to this ".html" file.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**

The first one is alert(), the second one is console.log(). Things in alert() function can be shown in the web page to the user. Things in console.log()  can only be shown in the console. If we want to show something to users, we need to use alert(). If we want to show something in the console (may just for programmers), we just use console.log().

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**

alert("hello") needs to be comment out. We just add code:
```js
alert(new Date())
```
* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**

Just replace 'A name' with my own name in the function displayInformation() where the heading is defined.

* **What does the word `document` represent in this code? Explain briefly.**

'document' represent the 'document object'. When an HTML document is loaded into a web browser, it becomes a document object. The document object is the root node of the HTML document. (cite from: https://www.w3schools.com/jsref/dom_obj_document.asp)

* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**

 Set the HTML content of the first element with id="items' in the document to the length of a list containing the elements  with the specified tag name 'li'.

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**

White.

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**

This is because this part of code is displayed between \<p> tags where \<p> tag defines a paragraph and the style of these paragraphs have been set with borders and different background color in <style> tags. To make them a different color, we just change the  **background-color** attribute in the brace of
```js
<style> p{}
```
to make those boxes some shade of blue, I would use:
```js
background-color: #3399ff
```

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**

I define a new function called copyFunction2() which set the first element with id="Canada" to a text "O Canada". Then I call this function on McGill University and display the text at the bottom. I figure out what to do by referring to the original copyFunction() in the code and the texts shown when copy 'University of Michigan'.

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
The function handleClick() is defined with alert("hello"), where alert() is the function that call the text box to show up. At the bottom, there is a button input that call the handleClick() function. So once users click on the button, the handleClick() function would be called and the alert() function in handleClick() would also be called.

* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**



### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**

Because the code has make this setting between <style> tags:
```js
<style type="text/css">
    .error{
        color: red;      //Errors are in red
    }
    .good {
        color: blue;    //Valid inputs are in blue
    }
</style>
```


* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**

This line defines a regular expression, helping with specifying what kind of result should be accepted as a right 'answer'. If the input is in such format, 'Nice!' will be shown. If the input is not in this format, 'Not valid!' will be shown. /^[a-zA-Z]+$/ approximately means a word with one or more characters from a-z or A-Z.

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**

The general format of if-else conditional statements in Javascript is as the following:
```js
if (condition) {
  //  block of code to be executed if the condition is true
} else {
  //  block of code to be executed if the condition is false
}
```
Generally, the syntax in Javascript and in Python are very similar. One main difference is that in Javascript, the conditions should be included by the parenthesis and the block of code to be executed should be included by the brace; in Python, we do not use parenthesis for conditions and use colon to indicate the code to be executed. Another difference is that in Python, we need to indent the code to be executed and leaving 'if' and 'else' unindented. In Javascript, we just leave 'if' and 'else' out of the brace.


* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**

'10000' refers to the speed of the fading effect in milliseconds.

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

```js
$(document).ready(function(){
    $("form").submit(function(event){
```
The first line involving a ready() method, which makes the function() available after the (document) is loaded. function() specifies the function to run after the document is loaded. The second line involves an Event method which triggers or attaches a function to an event handler for the selected elements. In this case, the submit event has been attached. (cite from: https://www.w3schools.com/jquery/event_ready.asp and https://www.w3schools.com/jquery/jquery_ref_events.asp)

* **Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.
