# 19.1 Lesson Plan: jQuery Fundamentals

------

## Overview

This week's focus will be on JavaScript. We'll jump into how front-end developers use JavaScript to manipulate HTML elements on the web for added interactivity. Specifically, we'll teach students jQuery, a JavaScript library that greatly simplifies JavaScript code and makes it more legible. jQuery solves common problems on the web that would generally take multiple lines of JavaScript code.

This is the first of the three lessons that comprise Unit 19. Today's lesson (19.1) covers the basic syntax and concepts for using jQuery (a JavaScript framework). In the next lesson (19.2), students will learn about conditional statements, which add logic and interactivity to the jQuery functions. In the last lesson, 19.3, students will add interactivity with jQuery to a user interface (UI) and learn how to write functions to pair with HTML elements. 

Altogether, this unit prepares students for building interactive UIs by giving them a basic overview of how jQuery works and how it can be used to create interactions on a webpage.

## Learning Objectives

By the end of class today, students will be able to:

1. Explore and analyze JavaScript behaviors.
2. Code jQuery functions on HTML elements.
3. Code an event listener that animates when triggered.
4. Create JS variables to store values and to be used in functions.

## Class at a Glance

Welcome to Unit 19. 

Today's lesson focuses on JavaScript and jQuery basics and how designers use them to create good UI design.

- Students have five in-class activities to complete during the lesson.
- This lesson is divided into two parts:
  - Part 1: Introduce students to the **basic building blocks of JavaScript and jQuery** variables, JavaScript Arithmetic Operators, and functions.
  - Part 2: Explain **variables and their importance** and what types of information can be placed in them.

**Demo:** There are two demos today. You will lead a demo of variables in practice and a demo on jQuery toggle. 

---

## Online Recommendations

Many of our activities were written for in-person classes, so we've added in-line callouts (usually indicated by this icon: :globe_with_meridians:) to let you know how to adapt an activity for online delivery.

Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.

> :globe_with_meridians: **Online Recommendation:** Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here are some examples of what you can say during common transitions:
   - From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”
   - From sharing the slideshow to sharing a tab on your browser: “Bear with me as I switch over to my browser for the next demonstration.”

> globe_with_meridians: **Online Recommendation:**: Transitions and activities tend to take longer in virtual classrooms. If you find that you are running short on time, feel free to combine activity sections and keep the class in the main room instead of creating breakout groups. You also have the option of shortening review time to maximize coding activity time.

## Preparing for Class

**Review the slides beforehand**.

- [19-Week/01-Slides/19.1-jQuery Fundamentals Slides](https://docs.google.com/presentation/d/1U-jW80y5MLq6PeEJ4x4QIyPACJJ2O984DExkoTNcZHA/edit?usp=sharing)

- Make any teaching notes you'll need.

- As you lecture, relate your own on-the-job experience whenever possible to bring what students are learning to life and connect it to their future goals.

  - Look for the :gem: icon, which prompts you and/or a TA to share professional anecdotes directly related to a particular concept.

**Run through your demo.**

You'll be giving a demo of variables in practice in Section 7 of this lesson, so be sure to run through it once or twice before class.

**jQuery Refresher**.

Since you'll cover the basics of JavaScript and its use with event listeners, refresh your memory by reviewing jQuery's documentation: [https://api.jquery.com/on/](https://api.jquery.com/on/).

**Read activity instructions out loud.**

Students will be able to dive into their activities if you provide verbal guidance readily.

- Use the activity summaries in this lesson plan to give students a quick overview.
- From there, students should use the student-facing activity document to read more detailed instructions and do their work.

**Have fun!**

Lastly, have fun out there!

Don’t forget; you're making a huge difference in your students' lives. You're guiding them through the creation of some very cool projects—ones that will help them become real-world designers.

- Also, see the solved files located in the UX/UI repo at 19-Week/01-Day/Activities if you need something to reference for yourself or a student during the activities.

- If needed, review the Strategies for Class Online in the unit README.

---

## Class Materials

Today, all you need is your laptop, and the lesson plan open on a second monitor.

## Time Tracker

- Keep track of the clock. Have the TAs consult the [19-Week/03-Time Trackers/19.1 Time Tracker](https://docs.google.com/spreadsheets/d/1DHgr0bmxiUTA64WncPhr57jU4c3Y1GAxV-Hvtuw2C-s/edit).

- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---

## Office Hours: Each class, before class (45 min)

Encourage students to come early and use the time provided, and not to be afraid to ask questions.

> Do your part by engaging students who come early and participate in office hours.

---

## 1. Instructor Do: Welcome and Share Today's Objectives (5 min)

Welcome your students to Week 19. Today's topic is jQuery and JavaScript.

Open and today's slides. **TAs:** share them with the students via Slack:

- [19-Week/01-Slides/19.1-jQuery Fundamentals Slides](https://docs.google.com/presentation/d/1U-jW80y5MLq6PeEJ4x4QIyPACJJ2O984DExkoTNcZHA/edit?usp=sharing)

Take a moment to connect today's lesson to what students learned in the previous units. Specifically, students learned the fundamentals of web animation in Unit 10. jQuery will helps students apply those lessons to create UI interactions and animations.

Share today's objectives. By the end of class today, students will be able to:

- Explore and analyze JavaScript behaviors

- Code jQuery functions on HTML elements

- Code an event listener that animates when triggered

- Create JS Variables to store values and to be used in functions.


## SLIDES 1-7
Review

## SLIDE 8
**JavaScript** is one of the three major programming languages of the modern web.

JavaScript enables interactivity in webpages and is an essential part of web applications. The vast majority of websites use JavaScript in one way or another.

**Say:** Recall the body analogy from Unit 17.

- HTML is the skeleton. It provides structure and organization but typically remains unseen.

- CSS is skin, hair, even clothes. It determines how the body looks but can't change the underlying organization or functionality.

- JS is the nervous system. It receives signals, makes decisions, and tells the rest of the body how to move.

JavaScript was created in 1995 to animate HTML elements. It is now used to power almost everything interactive on the web.


## SLIDE 9
JavaScript was written to manipulate the Document Object Model (DOM) dynamically on websites as users interact with content. Recall that the DOM represents an HTML document as a hierarchical list of nodes&mdash;JavaScript can target and modify these nodes. For our use case, the DOM is literally the HTML elements we create.

In the simplest terms: JavaScript allows us to modify HTML elements.

As a UX/UI Designer, knowledge of the potential of JavaScript can have huge implications in building user experiences that have the behaviors you want. The expectation is not to be a JavaScript developer but rather understand what is and is not possible through your tech stack. A little knowledge goes a long way in communicating with developers.

## SLIDE 10
The DOM is the representation of the objects making up the structure and content of a document on the web. In our case, the DOM is literally the HTML elements.


## SLIDE 11
Review

## SLIDE 12
### JavaScript Variables

The fundamental building block in JavaScript is a variable.

JavaScript **variables** are containers for storing data values. These allow the code to "remember" information for later. Variables can store numbers, text, and even HTML elements. It can be useful to think of variables as the nouns of a programming language.

## SLIDE 13
Creating a variable follows a simple syntax with the same five parts every time:

1. A **declaration** keyword. `var` (short for "variable") is the simplest.

1. A **name**. This is the word used to recall the stored data.

1. An **equals sign**, otherwise known as the "assignment operator."

1. A **value**. This is the data associated with the variable's name.

1. A **semicolon** to terminate the statement.

> :key: **Key Tech Note:** JavaScript is a "weakly typed" language, which means that a variable is a variable, no matter what kind of data it contains. In a "strongly typed" language, we would have to specify what kind of data is contained in each variable.


## SLIDE 14
Although a JavaScript variable can contain any kind of data, it is useful to categorize the three most common types of data:

- **Strings** store text as a series of characters. String values must be surrounded by quotes.
- Ex: When you enter your name into a form, that's a string.

## SLIDE 15
- **Numbers** store numerical data. We call whole numbers **integers**, and decimal numbers **floats**.
- Ex: When you enter your phone # into a form, that's a number.

## SLIDE 16
- **Booleans** store a state: either `true` or `false`. These are useful for controlling UI states.
- - Ex: Password correct or no?
- 
## SLIDE 17
Review

## SLIDE 18
### JavaScript Statements
JavaScript statements are the individual instructions that make up a script. These instructions are executed in order from top to bottom to accomplish a task.


## SLIDE 19
JavaScript **statements** are the individual instructions that make up a script. These instructions are executed in order from top to bottom to accomplish a task.

Statements are used to do everything in a program. They use an **operator** to relate two or more **values**. They can:

- create a new variable

- change the value of a variable

- include multiple operators

- include multiple operators

- copy one variable to another

- modify the value of a variable

## SLIDE 20
Review

## SLIDE 21
### JavaScript Functions

A **function** is a bundle of statements designed to perform a particular task. Breaking scripts into functions allows us to organize and reuse our code.

## SLIDE 22
The code in a function runs when its name is called, followed by `();`.

`console.log` is a commonly used function that shows a value in the developer console, which can be very useful while debugging! To provide a value, we can add text inside the parentheses.

## SLIDE 23
We can also write our own functions by using a function declaration. The `function` keyword is like the `var` keyword. Inside the parentheses, we can ask for arguments (like the text that `console.log` needs). Inside the curly braces, we can add as many statements as we need.


## SLIDE 24
## 3. Student Do: Hello, World...Again! Activity (15 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.1/19.1-01-Hello World ... Again!](https://docs.google.com/document/d/1Z9g2hkH45KCBI_r5KAaeI4g7eb07Nsw09qy-vthr3OE/)

### Summary

Students will practice creating a variable and a function to execute code on a page.

### Instructions

This is a version of the classic "Hello, World!" exercise. Students will start by opening their HTML file. Then they will create a variable, a function, and then invoke that function.

*If students struggle:* double-check the syntax of the script tag. It is a common error for students to link to the JavaScript file incorrectly. If this is not the problem, check the students' code for syntax errors. If you are not an experienced web developer, lean on the solved file and show the student where their code differs from the solved file's.

*If students complete the activity early:* Ask them if they have questions about the basics of JavaScript. If they don't, feel free to share the following [resource](https://www.w3schools.com/jquery/jquery_intro.asp) with the student.

### Instructors and TAs

As your students work on this activity, monitor students' work with the TAs.

- Be on the lookout for any frustration or confusion coming from students.

- Remind students to pay attention to the syntax! It's important to remember how to declare functions and variables.

_Some common problems students may have:_

1. Trouble connecting the script tag to their document. Remember to check if their files are in the correct location and that they have closed their script tag.

2. Students may not understand where the console tab is. If students have questions about what their script is doing, please lend a hand!

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## SLIDE 25
## 4. Instructor Do: Hello, World...Again! Activity Review (5 min)

> :globe_with_meridians: **Online Recommendation:**
>
> - Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.
>
> - Remind the volunteer to mute notifications and close any screens that may contain private information before sharing their screen.

Call students' attention back to your screen to engage them in a discussion of the concepts they just put into practice.

**Lead a post-activity discussion.**

Ask students to volunteer to share their work via Slack, say three to five students.

**Ask:**

- "Did everyone see the message print out to the console window?"

- "Who can share what didn't go so well?"

- "Does anyone have questions about the `console.log()` function?"

Offer students actionable feedback that they can apply to their work, for example:

1. When learning a new programming language, if you encounter an error, always double-check the syntax for your code. Double-checking the documentation will help you understand what this function does and how it is used.

2. You can use the console window in Chrome's dev tools to check for errors in your JavaScript. The console window will tell what line or function the error originated from.

**Invite students to recall concepts.**

**Ask:**

- "What is a variable?"

	_A variable is used to contain data in JavaScript. Variables can contain integers, elements, or strings of text._

- "What is a function?"

	_A function is simply a block of code that performs an action when you run it._

- "Is console.log a function?"

	_Yes! It is a JavaScript function._

Take a moment to give students a sense of some common misconceptions or FAQs about getting started with JavaScript, for example:

1. Script tags can be used to pull down publicly hosted JavaScript files or JavaScript files on your local machine.

2. Unlike link tags, script tags must be closed. You need to close script tags because developers can write JavaScript code inline between them.

Now that students are up to speed on JavaScript basics, it's time to learn more about variables and how to use them with functions.


## SLIDE 26
## 5. Instructor Do: JavaScript Variables in Practice Demo (10 min)

**Give a demo of a variety of variables.**

- Open the demo files located in [19-Week/01-Day/Demos/Variables_In_Practice](Demos/Variables_In_Practice/).
- Open the index.html file in your web browser [19-Week/01-Day/Demos/Variables_In_Practice/index.html](Demos/Variables_In_Practice/index.html).
  - You'll use the [console](https://developers.google.com/web/tools/chrome-devtools/console) window to showcase to students the outputs of our code.
- Open the index.js file so you can walk through the syntax for variables. [19-Week/01-Day/Demos/Variables_In_Practice/js/index.js](Demos/Variables_In_Practice/js/index.js).

We can use variables to calculate numbers or merge strings to form a sentence.

In JavaScript, there are many ways to work with variables using arithmetic operators:

| code | operator |
|-|-|
| `+` | addition |
| `-` | subtraction |
| `*` | multiplication |
| `**` | exponentiation |
| `/` | division |
| `%` | modulus |
| `++` | incrementation |
| `--` | decrementation |

Let's practice some arithmetic operators with variables storing integers.

> :globe_with_meridians: **Online Recommendation:** Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer these questions.

In this example, we have three variables: x, y, and sum. The x and y hold integers that we'll add together in the variable sum.

The sum is being logged to our console using the `console.log()` function.
**Ask,** "What do you think the output of sum will be?"
*Answer:* 30 will be output to the console window.

```js
var x = 20;
var y = 10;
var sum = x + y;
console.log(sum);
```

We can also use variables to store text.

In this example, we only have one variable, `a`, that holds the text "Big Kahuna Burger."

We are logging `a` to the console.

**Ask:** "What do you think the output of `a` will be?"
*Answer:* Big Kahuna Burger.

```js
var a = "Big Kahuna Burger";
console.log(a);
```

We can also use variables to string text together text like this:
- In the example below, we have three variables. The variables `adj` and `noun` hold strings that we will be combining together to create a Mad Lib sentence.
- The `var madlib` concatenates our variables together to form a sentence.
- Lastly, we are logging our sentence to the console.
**Ask,** "What do you think the output of the `var madlib` will be?"
*Answer:* The fat dog jumps in the river.

```js
var adj = "fat";
var noun = "dog";
var madlib = "The " + adj + " " + noun + " " + "jumps in the river";
console.log(madlib);
```

**TAs:** Slack out the class this link for all JavaScript arithmetic operators: [JavaScript Arithmetic Operators](https://www.w3schools.com/js/js_operators.asp).

> globe_with_meridians: **Online Recommendation:**: Take a moment to check in with the class and see how comfortable they feel about using variables. 
-	Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen. 
-	Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

Next, it's time for students to test out what variables can do for them in the upcoming activity.


## SLIDE 27
## 6. Student Do: Understanding JavaScript Variables Activity (10 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.1/19.1-02-Understanding Variables](https://docs.google.com/document/d/1EssG8IrPRJSM7MljRIMWBDc4EUMrc7qCDQoAUynLZrw/).

### Summary

Students will add integers and then they will add strings together.

### Instructions

Students will perform two actions during this activity: adding integers and adding strings together. Their result will be shown on the console.

*If students struggle:* Sometimes, the concept of using the name of your variable in another can be confusing. Check the names of variables if students are having trouble getting their code to concatenate. Alternatively, check the syntax for the student's variables to make sure their syntax is correct. If you are not an experienced web developer, use the solved file to show the students how their code differs.

*If students complete the activity early:* Share the following [resource](https://www.w3schools.com/jquery/) with them. Alternatively, ask the students questions about their portfolio.

### Instructors and TAs

As your students work on this activity, monitor their work with the TAs. Be on the lookout for any frustration or any students being stuck.

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## SLIDE 28
## 7. Instructor Do: Understanding JavaScript Variables Activity Review (5 min)

Review how the activity went.

**Ask:**

- "What went well for you using variables?"

- "What didn't go so well?"

Offer students actionable feedback that they can apply to their work, for example:
1. Try using variables to contain another function. Variables can be used to chain two functions together.
2. jQuery can do more than simple mathematic calculations. Suggest to your class to search Google for the different types of calculations that JavaScript can run.

**Invite students to recall concepts.**

To reinforce learning, ask the following questions.

> globe_with_meridians: **Online Recommendation:**: Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer these questions.

**Ask:**

- "What is concatenation?"

	_Concatenation is the joining of two strings together to form a new sentence. For example, if we had two variables that contain the words "Hello" and "World," we could add them along with JavaScript to create the message "Hello, World." This is a practical example of concatenation in action!_

- "How can we use concatenation in our functions?"

	_In front-end development, concatenation is used to do math or add strings together to create a custom message._

Take a moment to give students a sense of some common misconceptions or FAQs about working with variables, for example:

1. Variables are mainly used to store HTML elements or to build different parts of a function.

2. Variables can have functions run on them to produce an effect.

This wraps up the JavaScript refresher portion of today's class. It's now time for a break.

## SLIDE 29
## 8. Break (10 min)


## SLIDE 30
Review

## SLIDE 31
Review

## SLIDE 32
### What is jQuery?

**jQuery is simplified JavaScript.**

Recall how JavaScript functions automate specific tasks by bundling statements.

jQuery is a whole library of functions designed specifically to simplify common front-end development tasks.

## SLIDE 33
**Ask:** Why did we learn about JavaScript is jQuery is easier?

_We learned about JavaScript first because the fundamentals (**variables**, **statements**, and **functions**) are still in play._

**jQuery** is a JavaScript **library** (bundle of functions) that makes front end development easier by providing solutions for common problems.

## SLIDE 34
In short, jQuery is a **"write less, do more"** JavaScript library.

## SLIDE 35
Review

## SLIDE 36
### Using jQuery

To start using jQuery, we must import it from the jQuery website in a `script` tag.

```html
<script src="https://code.jquery.com/jquery-3.5.1.js"></script>
```

> :key: **Key Tech Note:** This type of import uses a Content Delivery Network (CDN). Another option is to download the library and import it like any other JavaScript. Using a CDN comes with several benefits, including lower latency and simpler updates. However, using a CDN also means relying on the jQuery servers&mdash;if they go down, your site stops working.

## SLIDE 37
Most tasks in jQuery follow three steps:

1. First, the `$` function is used to find an HTML element. This function is the "query" is jQuery&mdash;it scans the DOM for an element that matches that CSS selector.

## SLIDE 38
2. Next, an the `on` function is used to specify when the rest of the code should execute. This is called an **event listener**, because it listens for an event.

	The `on` function takes two arguments. The first is the name of an event, and the second is a JavaScript function that will run when the event occurs.

	**Ask:** What event is this code listening for?

	_This event is waiting for a user to click on `#button`._

	> **Instructor Note:** Demonstrate how this line can be read in reverse by pointing to `function`, `click`, `on`, and `#button` in that order.
	
	**Say:** The function executes when a user clicks on the button.

## SLIDE 39
3. Finally, any number of jQuery functions can be used inside the function to make things happen. In this example, we use the `toggle` function, which toggles the visibility of an element.

	**Ask:** What happens when a user clicks on the button?

	_`#light` has its visibility toggled._

	Recall that any number of statements can be used inside of a function. They can be either plain JavaScript or jQuery.
	
## SLIDE 40
Review


## SLIDE 41
## 10. Instructor Do: jQuery Toggle Demo (10 min)

### Part 1: jQuery Toggle

> **Say:** "Let's take a look at something familiar—how about an accordion?"

1. Open the following CodePen: [jQuery Toggle](https://codepen.io/2u-uxuxi-bootcamp/pen/RwpoWpR).

1. Point out the JavaScript panel.

> **Instructor Note:** This function was created with only three lines of code.

1. Click the button on the bottom left panel.

> **Ask:** But what about if we want it to be animated and slide?

1. Comment out `$(".toggleMe").toggle();` (line 2) by adding `//` in front of it

1. Uncomment `$(".toggleMe").slideToggle();` (line 3) by removing `//` from the front of the function.

1. Click the button again so students can see the new effect you just applied to the accordion element with jQuery.

### Part 2: JavaScript Toggle

**Say:** Let's see what this would look like in pure JavaScript.

1. Illustrate how using jQuery significantly simplified our code by opening the following in CodePen: [Pure JavaScript Toggle](https://codepen.io/2u-uxuxi-bootcamp/pen/gOmLEVG).

1. Point out how much more complex it is.

	In JavaScript, it has 11 lines of code and is not nearly as interactive.

1. Click the button to show the toggle animation.

**To sum up**, reemphasize that jQuery is a JavaScript library that takes common tasks for front-end developers and simplifies them into easy-to-use functions. Again, jQuery is like the fast lane for writing JavaScript.

**TAs:** share the following two links with the class via Slack. These links are very useful and should be referenced often:

- [Links to jQuery's CDNs](https://code.jquery.com/)
- [Link to jQuery Documentation](https://api.jquery.com/)

> :globe_with_meridians: **Online Recommendation:**
>
> - Take a moment to check in with the class and see how comfortable they feel about using variables. 
>
> - Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen. 
>
> - Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

## SLIDE 42
## 11. Student Do: Using jQuery Activity (15 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.1/19.1-03-Using jQuery](https://docs.google.com/document/u/1/d/15h3ADntTm6dfxj2KBrNT2sZFvdTKT0qVCHSK16cVlRw/).

### Summary

During this activity, students will test out two different jQuery functions: `.html` and `.css`. Students will target HTML elements and run these two functions on the elements selected to see how these jQuery functions work for themselves!

### Instructions

Students will:

1. Use jQuery to target the `h1` tag and make it red.

2. Use jQuery to target the `.blue` class and make it blue.

3. Use jQuery to target the `#addMe` ID and change its HTML to Hello.

*If students struggle:* This is the students' first experience using functions on HTML elements. There may be confusion on how each function can be used. If you get questions of this nature, search for the function in question and show the student documentation on how their use case was different from the documentation.

*If students complete the activity early:* Engage the student in a conversation about their portfolio. Offer advice and guidance on how they can become job-ready at the UX/UI Boot Camp conclusion.

### Instructors and TAs

Monitor students with your TAs and offer help where needed. Encourage students to help one another as well.

**Say:** Remember to check the console window in your web inspector for JavaScript errors!

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## SLIDE 43
## 12. Instructor Do: Using jQuery Activity Review (5 min)

Call students' attention back to your screen to engage them in a discussion of the concepts they just put into practice.

**Review how the activity went.**

**Ask:**

- "What went well in working with jQuery?"

- "What didn't go so well?"

Offer students actionable feedback that they can apply to their work, for example:
1. A function's uses depend on context: if students have a problem, they can usually find suggestions as to what functions they need to use to achieve the correct effect. Researching different ways to use jQuery will make your class stronger developers.
2. Some functions can be chained together to form complex effects. For example, you can use `.find` in combination with `.sibling` to find the sibling of an HTML container.

**Invite students to recall concepts.**

To support long-term memory of these concepts, ask the class the following questions.

> :globe_with_meridians: **Online Recommendation:** Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer these questions.

> **Ask:**
> - "How does jQuery speed our development time?"
>
>	_Query speeds our development time by giving us access to prebuilt functions that can be used on our webpage._
>
> - "How does that help us?"
>
>	_Query solves common problems and adds functionality to a webpage. Prebuilt functions save you time in developing and testing new code._

Take a moment to give students a sense of some common misconceptions or FAQs about using jQuery, for example:
1. jQuery functions won't produce errors unless there is a problem with the structure. The functions themselves just won't produce a result. If this happens, double-check the documentation for the function you are using.
2. jQuery can be used interchangeably with JavaScript syntax. It is not best practice to do so, but sometimes you will see JavaScript and jQuery code intermingle.

Now that you have reviewed the fundamentals of jQuery, move on to introduce event listeners to the class.


## SLIDE 44
Review

## SLIDE 45
Review

## SLIDE 46
An event listener is a function. It is a block of code that performs tasks that it was programmed to perform. Its job is to wait, then react.

What makes this type of function special is that it waits for specific user events to occur before it runs the code. It "listens" for its moment of action. For example, say a user clicks a button—you would use an event listener to listen for a “click” event on a specific button.

Ever seen a coin-operated machine, like a kiddie ride at a fair, a player piano, or even a car wash? Those are much like event listeners, ready to do their thing—follow specific instructions they're programmed to follow—but just waiting to be triggered to do so.

## SLIDE 47
You are using JavaScript building blocks to understand the basics of creating event listeners that run jQuery functions on elements that you specify. Why? You need to use variables inside of our event listener to build interaction. Event listeners are also a type of function. Understanding how functions work helps you to understand what happens when you trigger an event listener.

Event listeners must be triggered. Examples of event listener triggers: the user clicks a button, scrolls to a certain point on the page, or progresses to the next part of a form.

Let's take a look at modern syntax for a jQuery event listener.

```html
<div class="button">Click me!</div>
```
This div has the class of button. This comes into play when writing event listeners.

## SLIDE 48
And now for the JavaScript portion.

This is the first jQuery code that we'll encounter.

Everything before this was JavaScript fundamentals that are needed to understand how to write jQuery code.

```js
$( ".button" ).on( "click", function() {
  console.log("Hey a click occurred!");
});
```

## SLIDE 49
Let's break this down, piece by piece.

`$`

	- (the dollar sign) is an alias or shorthand for the jQuery function. Without one of the two before your statement, you can't use jQuery functions in your code.

## SLIDE 50
	- You could also write out "jQuery" in place of the `$`, and it will work the same.

## SLIDE 51
`( ".button" )

	- is jQuery's way of selecting which element you are targeting. Notice anything familiar about the syntax? Any way you target elements in CSS, you can target in jQuery with the same syntax. For example, if this element had an ID of button, we could target it with `(".button")`.

## SLIDE 52
`.on( "click", function() {}`

	- This piece of code is saying that when you click an element with the class of button (we specified this earlier), then run the code between the two curly braces {}.

> **Instructor Note:** There are many different types of event listeners: _Ask your TAs to Slack out this link for students to use as a reference for the different types of event listeners that students can program_: [Event Listeners List](https://api.jquery.com/category/events/).

## SLIDE 53
`console.log("Hey a click occurred!")`


	- This is the code that is executed when we click something with the name of `.button`.

## SLIDE 54

`});`

	- These are the closing brackets from the function we wrote earlier. In our text editor, if you click behind the } or ), the opening tag will be underlined.

**TAs:** Slack out this link for students to use as a reference for the different types of event listeners that students can use: [Event Listeners List](https://api.jquery.com/category/events/).


## SLIDE 55
## 14. Student Do: .on Function Activity (20 min)

> :globe_with_meridians: **Online Recommendation:**
>
> - This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.
>
> - Be sure to check your class Slack channel for questions while students are working and provide feedback.
>
> - Broadcast a two-minute warning to help them wrap up this work session.

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.1/19.1-04-on Function](https://docs.google.com/document/d/1FLwpFxbaMcjTI4qTJ3L8aR_H7KbH0FgE6KGlDHZVFS0/).

### Summary

Students are going to practice creating an event listener using the `.click` method.

### Instructions

Step 1: Students will create an HTML structure needed for our drop-down.

Step 2: Students will then style the HTML elements they created using CSS.

Step 3: Students will create an event listener, write a jQuery selector, add another jQuery function to it, and load the result to test their function.

*If students struggle:* Event listener syntax can be tricky at first. Always double-check the student's event listener syntax for errors. Lean on the solved file if you are not a strong web developer and show students how their code is different.

*If students complete the activity early:* Share with them the following [resource](https://www.w3schools.com/jquery/event_on.asp).

### Instructors and TAs

Monitor students with your TAs and offer help where needed. 

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## SLIDE 56
## 15. Instructor Do: .on Function Activity Review (5 min)

Call students' attention back to your screen to engage them in a discussion of the concepts they just put into practice.

**Review how the activity went.**

> :globe_with_meridians: **Online Recommendation:** Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer these questions.

Some conversation-stimulating questions to consider:

**Ask:**

- "What went well for you with this `.on` function activity?"

- "What didn't go so well?"

Offer students actionable feedback that they can apply to their work, for example:
1. Use the `console.log()` function to check if you have written your event listener syntax correctly. Use a simple message like "my click event worked" when testing.

**Invite students to recall concepts.**

Let's review some key concepts about event listeners before we introduce prebuilt functions to the class.

**Ask:**

- "What is an event listener?"

	_An event listener is a piece of code that "listens" for an event on our page (like a click). There are many different types of event listeners on the web._

- "How does that help us?"

	_Event listeners allow us to add interactivity to our webpage by watching for actions from our user that our UI reacts to._

Take a moment to give students a sense of some common misconceptions or FAQs about using event listeners, for example:
1. `.on` is shorthand for jQuery's event listeners. You can specify what type of event it is. Check jQuery's documentation for samples of how to use the different event listeners.
2. Event listeners need to be checked using` console.log` to make sure your event is correctly connected to your HTML element. Add `console.log` between the curly braces with a message like "Click event connected correctly."

Now that students have had some time to review event listeners, move on to a lecture about jQuery's prebuilt functions, and how to use them.


## SLIDE 57
Review

## SLIDE 58
Prebuilt functions have value to front-end web developers on the job because they're reliable, robust, and quick to implement.

- Reliable because they have been thoroughly tested and documented, with examples of how they work online.
- Robust because they are flexible. Some functions have multiple use cases depending on how you use them.
- Quick to implement because all you have to do is apply them to an HTML element, and the effect will run when you load your page.


## SLIDE 59
Web developers appreciate jQuery because it reduces their coding time and debugging time, too.

Prebuilt functions in jQuery solve common problems on the web (drop-downs, hiding, and unhiding elements, for example). In the past, you would have to build these interactions yourself, and they often required in-depth knowledge of JavaScript to pull off. However, with jQuery, they are as easy to implement as adding a prebuilt function to the end of a jQuery selector.

jQuery comes with many prebuilt functions, some of which you just tested out. jQuery solves common JavaScript uses with their functions. The most popular functions solve problems that many developers have already faced, such as toggling classes, creating HTML elements, or updating the content of an HTML element.

A few examples of popular and useful jQuery prebuilt functions are:

jQuery functions: 

1. for animating a drop-down
```js
.slideToggle
```
2. for altering the CSS properties of an element
```js
.css
```

3. for dropping elements of your choosing into a container
```js
.append
```

4. for adding and removing classes from an element; often used to trigger CSS animations
```js
.toggleClass
```

5.to apply simple CSS transitions to an element 
```js
.animation
```

6. gets or sets the HTML contents of an HTML element
```js
.html
```

One of the most useful functions of jQuery is that it takes things that are difficult to create in pure JavaScript and makes it as easy as targeting specific selectors and running the function.



## SLIDE 60
## 17. Student Do: Build a Toggle Activity (35 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.1/19.01-05-Build a Toggle](https://docs.google.com/document/u/1/d/1QjIHPGCxu1BNk-5gKVSHE_mgefJqsZgBlyzyb9WbRWg/).

### Summary

During this activity, students will use all the concepts discussed in class today to create a toggle that listens for user clicks and reacts to those clicks. Specifically, they will build a drop-down menu using jQuery to handle the animation.

### Instructions

This activity has three steps:

1. Create an event listener that targets the HTML element with the ID of `toggle`.

2. Write code that targets the HTML element with the ID of `dropDown` and run the jQuery function `.slidetoggle()` on it.

3. Test our functions and debug, if applicable.

*If students struggle:* The problems students experience during this activity can vary. If you aren't experienced at debugging jQuery functions, lean on the solved file and show the student how their code is different.

*If students complete the activity early:* Share with them the following [resource](https://www.w3schools.com/js/js_if_else.asp) to prime them for the next lesson.

### Instructors and TAs

Monitor students with your TAs and offer help where needed. Encourage students to help one another as well.

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## SLIDE 61
## 18. Instructor Do: Build a Toggle Activity Review (5 min)

> :globe_with_meridians: **Online Recommendation:**
>
> - Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.
>
> - Remind the volunteer to mute notifications and close any screens that may contain private information before sharing their screen.

Call students' attention back to your screen to engage them in a discussion of the concepts they just put into practice.

**Review how the activity went.**

First, ask a few students to share their work in Slack. Play their work on-screen for the class to see.

- Ask the students who shared their work and the rest of the class to comment on what's working and what could be improved.

- Invite everyone to think about their work and discuss their experience with the activity—what challenged them and what they found worked easily.

Offer students actionable feedback that they can apply to their work, for example:
1. How you build different UI elements varies from design to design. Students need to practice building interactive elements to become experienced web developers.

Your final step of the day is to introduce Unit 19 Challenge.

## 19. Instructor Do: Introduce Challenge (4 min)

> **Instructor Note:** Ask a TA to share the challenge document with students via Slack or students can open it in the class Google Drive.
>
> Recommend that students make a copy of the assignment in their personal drive folders as soon as they open the link.

Take a moment to make sure everyone is clear on what this week's challenge involves.

Open the challenge for the class: [19-Week/04-Howework/01-Instructions/19 Unit Homework File](https://docs.google.com/document/d/177QCHxeBkdwm_aXa-NqQWO4Zq-zfrDIroDUnDJRo9ek/).

1. First, explain the assignment’s due date.
	- As a general rule, challenge assignments are due at the start of class two weeks from the date it was assigned.
2. Next, read through the instructions with the class.
	- **Make it clear that students will be designing and adding interactivity to their portfolio site using jQuery.**
3. Finally, ask the class if there are any questions.

## 20. Instructor Do: Recap and End Class (1 min)

**Office hours start ... now!**

Remind students that you are staying online and are available after class for office hours.

Thank everyone for doing their best work.

_Psst! Great work!_

---

## We Want Your Feedback!

Instructor, how did class go today?

Please submit any issues or comments on the UX/UI curriculum to our Google Form: [Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform).

View the status of your submission and other issues here: [Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing).

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.	
