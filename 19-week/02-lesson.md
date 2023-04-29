# 19.2 Lesson Plan: JavaScript/jQuery Event Listeners and Interaction on the Web

------

## Overview

Last class, your students learned the fundamentals of JavaScript (variables and functions) and jQuery (event listeners and jQuery functions). Today you'll show them how to use jQuery and JavaScript to build interactions on the web, using conditional statements. We'll also discuss `if else` statements and the `this` keyword and how they can be used to add interactivity to a website.

This is the second of the three lessons that comprise Unit 19. Lesson 19.1 covered the basic syntax and concepts for using jQuery, a JavaScript framework. Lesson 19.2 teaches students about conditional statements, which add logic and interactivity to our jQuery functions. Lesson 19.3 gives students the opportunity to add interactivity with jQuery to a user interface (UI), teaching them how to write functions to pair with HTML elements. 

Together, the lessons in this unit prepare students by giving them a basic overview of how jQuery works and how it can be used to create interactions on a webpage.

## Learning Objectives

By the end of class today, students will be able to:

1. Write conditional JavaScript statements that will detect if a button is in a particular state.

2. Using jQuery, apply the `this` keyword to create logic in functions.

3. Manipulate the document object model (DOM) to create UI interactions using jQuery functions.

4. Create a working To-do App using all the conditional logic principles learned in class.

## Class at a Glance

Today's class has three parts:

**Part 1:** Provide an exploration of conditionals and how designers apply them to make web apps interactive and engaging for users. You'll use conditional statements to apply and check for different element states.

> **Instructor Note:** **This lesson has two demos. Practice them in advance.**

1. Demo on conditionals plus jQuery Logic (Section 3).
2. Demo on debugging with the Chrome's Web Inspector tool (Section 6).

**Part 2:** Students will practice manipulating the DOM using conditional statements. Also, students will create custom CSS animations that are applied with an event listener using jQuery.

**Part 3:** Students will finish the day by building a working "To-do App" to wrap all of the conditional principles together.

## Online Recommendations

Many of our activities were written for in-person classes, so we've added in-line callouts (usually indicated by this icon: :globe_with_meridians:) to let you know how to adapt an activity for online delivery.

Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.

> :globe_with_meridians: **Online Recommendation:** Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here are some examples of what you can say during common transitions:
- From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”
- From sharing the slideshow to sharing a tab on your browser: “Bear with me as I switch over to my browser for the next demonstration.”

## Prepare for Class

**Review the slides beforehand**.

- [19-Week/01-Slides/19.2-Event Listeners and Interaction on the Web Slides](https://docs.google.com/presentation/d/1MEZvXUUtJ7-lFBxRj_qF-MZoit10JfrCM0sTE69o-yk/edit?usp=sharing)

- Make any teaching notes you'll need.

- As you lecture, relate your own on-the-job experience whenever possible to bring what students are learning to life and connect it to their future goals.

- Look for the :gem: icon, which prompts you and/or a TA to share professional anecdotes directly related to a particular concept.

**Demos**: *Be sure to practice your demos beforehand (see Class at a Glance, above).*

If you're unfamiliar with conditions, read the following resource: [MDN `if else` Statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else).

- Prepare yourself to convey the value of understanding JavaScript and jQuery.
  - It is valuable for students to understand that JavaScript is a common language that has been used in the most popular web frameworks such as Node, Angular, and React. Knowing JavaScript will help them work with all the popular JavaScript frameworks (most JavaScript developer jobs will work in one of the frameworks listed).

**Have fun!**

Lastly, have fun out there! 

Don’t forget, you're making a huge difference in your students' lives. You're guiding them through the creation of some very cool projects—ones that will help them become real-world designers.

- If needed, review the Strategies for Class Online in the unit README.

---

## Class Materials

Today all you need is your laptop and this lesson plan open on a second monitor.

## Time Trackers

- Keep track of the clock. Have the TAs consult the [19-Week/04-Time Trackers/19.2 Time Tracker](https://docs.google.com/spreadsheets/u/1/d/1jGPUNuWC0k7vIEBG7vAeKc6WE4dbFLpdmk_EL3iN6qs/). Empower your TA to help you stay on track.

- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---


## Office Hours: Each class, before class (45 min)

Encourage students to come early and use the time provided and not to be afraid to ask questions.

> Do your part by engaging students who come early and participate in office hours.

---

## 1. Instructor Do: Welcome and Share Today's Objectives (5 min)

Welcome your students to class.

Open and download today's slides. TAs should share a pdf of the slides with the students via Slack:

[19-Week/01-Slides/19.2-UX-UI-Event-Listeners-and-Interaction](https://docs.google.com/presentation/d/1MEZvXUUtJ7-lFBxRj_qF-MZoit10JfrCM0sTE69o-yk/edit?usp=sharing).

Share today's objectives. By the end of class today, students will be able to:

- Write conditional JavaScript statements that will detect if a button is in a particular state.

- Using jQuery, apply the `this` keyword to create logic in functions.

- Manipulate the document object model (DOM) to create UI interactions using jQuery functions.

- Create a working To-do App using all the conditional logic principles learned in class.

Connect today's lesson to students' previous UX/UI learning. As users interact with a UI system, they are making decisions. Conditional logic allows designers to control how a page behaves in response to how users behave.

## 2. Instructor Do: Conditionals and Logic in Functions (15 min)

> :pushpin: **Important Point:** The goals of this section are for students to understand the definition of `if else` statements, be able to recognize them, and get how they work. This ties into the first learning objective of the day, which is for students to write conditional JavaScript statements.

**Conditional logic** determines an output based on one or more inputs. That is, it does something different for each possible condition.

A condition is always either `true` or `false`. This kind of value is known as a **boolean**. It can be helpful to think of booleans in terms of a true/false quiz. The answer is always one or the other, and never anything in-between.

> :key: **Key Tech Note:** Booleans are named for the scientist who invented Boolean Logic. This kind of logic predates computers by a century!

Booleans allow for more complex scripts than those that rely on event listeners alone. Recall that event listeners wait for one specific trigger&mdash;with booleans, entirely different sets of statements and functions can be run based on whether boolean values are `true` or `false`.

> :gem: **Designer Insight:** Briefly describe the logic of a UI or other program you have worked on&mdash;what were the conditions you have to keep track of?

> :briefcase: **Employer Competitive Note:** Boolean logic is present in every programming language, so learning to think in terms of `true` and `false` is essential for all careers involving software.

### `if else` Conditional Statements

`if else` statements help your program "choose" which code to run.

For example, consider Google Maps. First, the software calculates the best route and displays it. It continuously checks to ensure that the best route is being used.

**Ask:**

- "What happens if you stay on the best route?"

- "What happens otherwise?"

> **Instructor Note:** As you proceed through the `if else` Syntax section, pause at every example to ask the class what will be logged to the console. If students get an answer wrong, spend some time clarifying the result before moving on.

An `if` block is made of three parts:

- the `if` keyword

- a condition inside of parentheses

- statements inside of curly braces

The statements inside an `if` block run if the condition is `true`.

The statement inside an `else` block run if the condition from the previous `if` block is `false`. In an `if else` chain, only one of the two blocks will be allowed to run; they are mutually exclusive.

It is rarely useful to actually type `true` or `false` as the condition of an `if` block. Checking a variable is better, because the "truthiness" of the variable can change.

> :key: **Key Tech Note:** In JavaScript, "truthiness" refers to whether a value is considered `true` or `false`. More advanced developers can take advantage of the fact that positive numbers and full strings are "truthy," which zero and empty strings are "not truthy."

### Conditional Operators

**Comparison operators** are used to get boolean values by comparing two values.

For example, 100 is greater than 10, so the comparison `100 > 10` becomes the boolean value `true`.

These allow for more complex logic than the simple on/off states that were achievable with just boolean variables.

The following 5 comparisons are the most common:

| operator | `true` if |
|-|-|
| `A == B` | A is equal to B |
| `A > B` | A is greater than B |
| `A < B` | A is less than B |
| `A >= B` | A is greater than or equal to B |
| `A <= B` | A is less than or equal to B |

> **Instructor Note:** Continue to pause at every example to ask the class what will be logged to the console. If students get an answer wrong, spend some time clarifying the result before moving on.

Instead of using a boolean value, it is possible to substitute a comparison. `myNumber > 10` will resolve to `true` if `myNumber` is greater than 10.

Because comparison operators open up more complex logic, `if else` chains can be more than two blocks long. `else if` blocks can be used between the first `if` block and the final `else` block.

Lastly, it is often more useful to compare two variables, as opposed to one variable and one value.

> :key: **Key Tech Note:** Comparing a variable directly to a value is known as "hard-coding" the value, because the threshold is written directly into the logic statement. "Hard-coding" is generally considered a bad practice, because it is easier to change variables at the top of a script than to find and replace every instance of a number or string.

## 3. Instructor Do: Conditionals and `this` Demo (5 min)

> :pushpin: **Important Point:** Your goal is to demonstrate the use case for conditionals, as well as show how to use the keyword `this` effectively.

1. Open the [CodePen demo](https://codepen.io/2u-uxuxi-bootcamp/pen/MWpbxML).

	> **Instructor Note:** Only the JavaScript panel will be necessary in this demo. Minimize the HTML and CSS panels to make the code easier to read.

1. Show what this simple program does by changing the "Width" field and clicking on one of the red boxes.

	> **Instructor Note:** This is setting the width in pixels, just like students have done in CSS. To ensure that the change is visible, use large differences, like 100 pixels.

1. Walk students through the simple jQuery code. They should be familiar with this pattern from 19.1.

	1. We start with a query: `$('.redBlock')`

	1. An event listener waits for clicks from the user: `.on('click', function() {});`

	1. When a user clicks on one of the red blocks, two statements run.

		- The first statement uses jQuery's `val` function to get the number that the user has typed into the "Width" field; that number is stored in the variable `widthValue`: `var widthValue = $('#widthInput').val();`

		- The second statement uses jQuery's `animate` function to change the width of the red blocks to the variable `widthValue`: `$('.redBlock').animate({width: widthValue});`

		> **Instructor Note:** Students are likely to not understand these statements fully. Reassure students by reminding them that this demo is about conditionals and the `this` keyword, not about `val` and `animate`.

1. **Ask:** "What can we add to set a minimum and maximum width?"

	_`if else` blocks can be used such that the blocks only animate if the inputted width is within a certain range._

1. **Say:** "Let's prevent it from going below 0."

	1. Add the following conditional statement above line 5: `if (widthValue >= 0) {`.

	1. Add a closing curly brace after line 5, such that the `animate` function is within the `if` block.

	> **Instructor Note:** The resulting code should look like this:
	>
	>	```js
	>	$('.redBlock').on('click', function() {
	>	
	>		var widthValue = $('#widthInput').val();
	>		
	>		if (widthValue >= 0) {
	>			$(this).animate({width: widthValue});
	>		}
	>	});
	>	```

1. **Say:** "Let's add a message for when the user tries to enter a value below 0."

	1. Add an `else` block below the `if` block.

	1. Inside the `else` block, add an `alert` function with the message, "Width must be a positive number."

		> **Instructor Note:** If students ask, explain that `alert` is just like `console.log`, except that the user sees it.

	> **Instructor Note:** The resulting code should look like this:
	>
	>	```js
	>	$('.redBlock').on('click', function() {
	>	
	>		var widthValue = $('#widthInput').val();
	>		
	>		if (widthValue >= 0) {
	>			$('.redBlock').animate({width: widthValue});
	>		} else {
	>			alert("Width must be a positive number.");
	>		}
	>	});
	>	```

1. **Ask:** "What can we change to make only one red block animate when we click on it?"

	_`'.redBlock'` on line 5 can be changed to the keyword `this`._

	Inside of `on`, the keyword `this` always refers to the one element that triggered the event. In this case, `this` will be the red block that is clicked on.

1. Edit the second `$` function such that it reads: `$(this).animate({width: widthValue});`

	> **Instructor Note:** The resulting code should look like this:
	>
	>	```js
	>	$('.redBlock').on('click', function() {
	>	
	>		var widthValue = $('#widthInput').val();
	>		
	>		if (widthValue >= 0) {
	>			$(this).animate({width: widthValue});
	>		} else {
	>			alert("Width must be a positive number.");
	>		}
	>	});
	>	```

1. Change the width field and click on one of the red blocks&mdash;only the one you clicked on should animate.

> **Instructor Note:** Take questions. This is a challenging moment for many students, so encourage the class by reminding them that mastering conditionals opens up infinite possibilities&mdash;most intermediate programs can be written using only `if else` blocks!

## 4. Student Do: Writing jQuery Conditionals Activity (25 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.2/19.2_1 - Writing jQuery Conditionals](https://docs.google.com/document/d/1AoEkz0rb6nsO-_PEIhFFpIxzNhK0nN9Pvq3hUSqWNzY/).

### Summary

Students will write conditional statements during this activity by adding and removing a class to alter the CSS and display the correct tab.

Students will also manipulate the DOM to display the correct tab content.

### Instructions

Students will practice creating tabs that hold content. They will write `if else` statements into their code, add conditionals, add interactivity, and run their code.

To check if the tab they click is "Active" or not, they will use jQuery's `hasClass()` function. If the tab has the class, they will do nothing. If it doesn't, they will switch the display of the two tabs.

*If students struggle:* double-check the syntax of their `if else` statement. If you aren't a strong web developer, lean on the solved file to show the student how their code differs.

*If students complete the activity early:* Share the following [resource](https://learn.jquery.com/) with them or engage the student in a conversation about their portfolio. Encourage the student to practice with this tutorial in their spare time.

### Instructors and TAs

Monitor students as they work and help students who appear to be stuck or have questions.

Review the documentation for conditionals and share with students who have questions:

	- [W3Schools `if else` Documentation](https://www.w3schools.com/jsref/jsref_if.asp)

	- [MDN documentation `if else`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

If you see a student who appears to be stuck, ask them what they are stuck on. Check the student's work for syntax errors in their code. Refer students to the documentation provided above after the problem is solved.

Offer to demo writing the statements for students who need to see it once again.

Some common problems students may have:

1. The most common mistakes students will make during this activity will be syntax related. If you see a student has written the shell of their `if else` statement incorrectly, show them where their syntax is incorrect.

2. Sometimes students have difficulty deciding where to place their jQuery functions inside their `if else` statement. Double-check that the student has placed their code in the correct area.

**TAs:** Offer support, too. Remind students that you had to practice writing conditional `if else` statements over and over before you could do it easily.

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## 5. Instructor Do: Writing jQuery Conditionals Activity Review (5 min)

> :globe_with_meridians: **Online Recommendation:** Since students can’t physically come to the front of the class to demonstrate, ask students to share their screen instead. ***Remind the student sharing their screen to mute notifications and close any screens that may contain private information before sharing.***


Call the class back to attention and initiate a review conversation.

**Say:** “Let’s review and discuss your work.”

**Ask:**

- "Can two to four people offer their definitions of an `if else` statement?"

	> Instructor Note: Let a few students provide answers and then comment on the answers as a whole, pointing out aspects of each answer that were helpful and accurate.

- "What kind of properties can be checked with an `if else` statement?"
	
	_Almost any condition that is measurable. "Does a container have a certain class? Is the value of this variable equal to...," etc._
  
- "Is there anything that surprised you about writing `if else` statements?"

	> Instructor Note: Student answers will vary—just listen and provide feedback if necessary.

> :gem: **Designer Insight:** Take part in the conversation by sharing your experience learning to write conditionals.

Offer students actionable feedback that they can apply to their work, for example:
1. Always start programming a conditional statement by testing your `if else` statement with `console.log`. Use `console.log` to test your conditional statements to see if they are evaluating as you designed.
2. Conditional statements can have multiple `else if` statements as well as operators depending on the complexity of the interaction you're programming.

Take a moment to give students a sense of some common misconceptions or FAQs about getting started with writing conditional statements. For example:
1. Conditionals can check for more than just the basics. You can add as many logical operators as you want to extend your `if else` statement.
2. The `this` keyword always refers to the function that evoked it. For us, this means the HTML element that triggers the event listener will always be targeted by "this."

Wrap up the conversation by pointing out a couple of your observations about `if else` statements that you want to be sure students notice.

Next, switch gears and move on to a demo of debugging with Chrome's Web Inspector tool.

## 6. Instructor Do: Debugging With Chrome's Web Inspector Demo (10 min)

> :pushpin: **Important Point:** **Important Point:** The goal of this debugging demo is for students to get accustomed to seeing errors, or bugs, and understand that debugging is a part of coding. This ties into the learning objective on using Chrome's Web Inspector for debugging.

> :globe_with_meridians: **Online Recommendation:**
>
> - Navigate away from the slideshow for this demonstration. If you shared your entire desktop, make sure to open your files on that shared desktop. If you shared a single window, be sure to re-share your screen to capture the appropriate window or desktop.
Remember to narrate what you are doing during transitions and demonstrations. In this instance, you might say: “I’m now going to switch from the slideshow to another tab so I can demonstrate variables.”
>
> - Since you’ll be sharing your screen for this demonstration, ask students to use the raise hands feature on Zoom to ask questions. At a good breaking point, call on a specific student to unmute and ask their question. Alternatively, you can ask students to share their questions in the Zoom chat and have the TA provide answers in the chat.

Before you do the demo, give students a 101 on debugging with Chrome's Web Inspector tool.

> **Say:** "As always, for anyone to become proficient at debugging code, it takes two things---time and practice. Experiencing errors in code is an essential part of learning web development."

Knowing how to use Chrome's Web Inspector tool and debug code puts students at a career advantage. Take a moment to connect this skill to working with design teams in the professional world.

> :briefcase: **Employer Competitive Note:** Debugging with Chrome's Web Inspector will help UI designers communicate with developers. It's much more convincing in giving the developer an idea of what went wrong when you can point out the line the error occurred in the UI you have designed. Students will also be able to double-check the product they designed to make sure everything is working appropriately.

Debugging is an essential skill for UX developers. Why? It means that when they find something that isn’t working with their code, they can look under the hood to see why. If you can’t debug your code, you’re not coding.

For example: Would you submit a book you wrote to be published without sending it first to an editor? The same concept applies---you wouldn't push any code live without first debugging it.

There are six stages to debugging for new front-end developers:

1. That can't happen.
2. That doesn't happen on my machine.
3. That shouldn't happen.
4. Why does this happen?
5. Oh, I see.
6. How did that ever work?

**"Part of learning how to be an effective developer is learning how to debug your own code."**

Why are coding and debugging one and the same?

Debugging code is a normal part of writing code, as you likely won't get it right on the first try. In the context of this lesson, you need to test and debug your code to make sure all your parameters work correctly.

> :gem: **Designer Insight:** If you have a story about debugging with the Web Inspector, whether it's yours or a friend's, please share it with the class.
>
> - Alternatively, you can play this video to the class for a laugh:

- ["What people think programming is vs. how it actually is."](https://www.youtube.com/watch?v=HluANRwPyNo)

Chrome's Web Inspector is very useful for debugging.

- This is because it not only reports messages related to problems with links to files in HTML files but also reports when your JavaScript statements have an error.

### Demo Chrome's Web Inspector

**Walk students through some common errors.**

Here are some common errors you will see in your console menu when building the front end of your website.

![Improper link to files](Images/link_err.png)

![jQuery not linked properly](Images/jquery_undefined.png)

jQuery functions will fail gracefully when a variable is undefined.

- "Fail gracefully" means you won't see an error code in your console window when you test your code. Instead, nothing will happen on your page.

- For example: Let’s say you have an event listener that is listening for a click on a specific button with the class of `.example`. In our jQuery, if we made a mistake and targeted the `id` of `#example`, the statement is technically correct but will not run because there is no element with the `id` of `#example`.
  - In other programming languages, this would throw an undefined variable error. JavaScript, however, assumes you meant the selector you typed correctly and will not throw an error and it will just continue on through your script.

For beginners, undefined variables are usually the result of improperly targeting an HTML element (usually mixing up the syntax for a class or an ID).

- Improperly targeting an HTML element results in our variable being "undefined," which means that no value has been assigned to this variable, causing our function to do nothing when we try to test our conditional statement or function.

![jQuery graceful fail](Images/jquery_fail_graceful.jpg)

We will experience this by debugging a file to make it work correctly.

> **Instructor Note:** Ask the TAs to share their perspectives on debugging and errors. They can share how they thought about debugging when they first started coding vs. now.

**Optional Instructor Do:**

- Open the index.html file located in Activities/Fail_Graceful/index.html.
- Click the button and show students how the `console.log` message clicked prints out to our console window but there is no error, telling us that our jQuery selector does not exist.

> **Instructor Note:** Pause for questions about Chrome's Web Inspector tool.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered. 
-	Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen. 
-	Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

Now it's time for students (and you) to take a brief break.

## 7. Break (10 min)

Take a break. Brain breaks are an important part of the learning process, so take a break! Get up from your screen and relax, have a bite to eat, and drink some water.

> globe_with_meridians: **Online Recommendation:**: Don't stop sharing your screen! Put up a Google or YouTube timer video. A visual timer will help get students back into the main Zoom room on time.

Let students know that after the break, they'll learn about use cases for conditional statements to get an idea of what to use when.

## 8. Instructor Do: Practical Conditionals (10 min)

> :pushpin: **Important Point:** The goal of this section is to discuss how logical operators can be used in combination with conditional operators to create complex conditional statements

Recall that comparison operators are used to get `true` or `false` by comparing two values.

Similarly, **logical operators** are used to get `true` or `false` by combining two booleans.

The following 3 combinations are the most common:

| logic | `true` if |
|-|-|
| `A && B` | A is `true` and B is `true` |
| `A || B` | A is `true` or B is `true` |
| `!A` | A is `false` |

> :key: **Key Tech Note:** The keywords `and`, `or`, and `not` are also valid JavaScript. It is rare to see these in the real world, as most experienced developers are used to reading the symbolic operators. However, there is an argument to be made that using these words makes code easier to read. Ultimately, it is best just to be consistent.

> **Instructor Note:** Continue to pause at every example to ask the class what will be logged to the console. If students get an answer wrong, spend some time clarifying the result before moving on.

Logical operators can be used to check multiple conditions in one statement. Using `&&` is an alternative to using two separate, nested `if` statements.

Logical operators can be used alongside comparison operators.

Logic can be combined and grouped, much like mathematical equations. This should be used somewhat sparingly, as logical expressions can quickly become entangled and difficult to read.

> :key: **Key Tech Note:** As a rule of thumb, many developers recommend cutting a statement into multiple lines if it is longer than 72 characters. This helps to keep logic succinct and prevents readers from having to scroll horizontally.

> :briefcase: **Employer Competitive Note:** When writing conditionals, UX designers will find options for almost any kind of interaction a user can have when working with a website or app. Knowing the limitations of conditional statements allows for students to be code conversational and map out in their flowcharts and wireframes how the developer team should build out the UI the student designs.

> :gem: **Designer Insight:** Share an example of a complex user flow that would require many logical operators.

## 9. Student Do: Conditional Clicks Activity (25 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.2/19.2-0X-Conditional Clicks](https://docs.google.com/document/u/1/d/1-fVmWt1Sw9CBn7wzsNpbs8GY5gRTD6XAjxLjyBU7vCQ/).

### Summary

Students will use conditionals to determine which CSS stylesheet to apply to a webpage. Which stylesheet is applied will be based on user click behavior.

### Instructions

During this activity, students will learn how to use conditionals to check for a specific button and apply a different `href` attribute to a stylesheet.

This activity is meant to help reinforce an understanding of conditionals through application into an actual UI.

*If students struggle:* Students have had trouble with the new syntax of some of the jQuery functions we use. Depending on which function is causing the student problem, help the student search for relevant documentation and show them how their syntax is incorrect.

*If students complete the activity early:* Share the following [resource](https://www.tutorialrepublic.com/jquery-tutorial/jquery-chaining.php) with them. Alternatively, you can engage the student in a conversation about their portfolio.

### Instructors and TAs

_If you're an experienced web developer:_ Assist students with technical questions about their code. Explain how and why what they were trying didn't work. The most common problem students will face when using conditionals is that their `if else` statement's logic doesn't work correctly, and they don't know why or how to check.

_If you're not an experienced web developer:_ Make sure you review the solved file and show students how their code differs from that in the solved file.

**TAs:** Offer support and encouragement, too. Remember, this isn't easy—but with repetition, it's learnable!

Some common problems students may have:

1. Different jQuery functions have different syntax that students might write incorrectly. Double-check the function's syntax and use the console to check for obvious errors.

2. Students might open the wrong stylesheet. Make sure students are working off the files specified in the instructions.

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## 10. Instructor Do: Conditional Clicks Activity Review (5 min)

Call attention back to the class and engage students in a discussion of the conditionals activity they just completed.

> globe_with_meridians: **Online Recommendation:**: Have students share their answers in the Zoom chat or Slack so they can refer to your screen to answer the following questions.

**Ask:**

- "What about this activity posed a struggle?"

- "What seemed fairly straightforward?"

- "Did anyone discover anything surprising (or annoying)?"

**Review concepts.**

**Ask:**

- "What is a conditional statement?"

	_A conditional is a statement that checks for specific conditions or parameters that you define using a logical operator._

- "What are some use cases of conditional statements?"

	- _Check if a number is equal to or greater than a specific number_
	- _Check if an HTML element has a specific class or attribute_
	- _Check if a class or element even exists_

> :gem: **Designer Insight:** Share your own experience working with conditionals and how you've learned to work with them in your own professional life. Invite a TA to share as well.

Offer students actionable feedback that they can apply to their work. For example:
1. Always design your interactions before you program. Create a user flow that pairs with your design that showcases how the interaction is intended to function.
2. When a conditional statement evaluates to true, it executes the code inside the curly braces. You can have different code blocks execute different interactions depending on how your user interacts with your UI.

Take a moment to give students a sense of some common misconceptions or FAQs about getting started with JavaScript. For example:
1. `this` always refers to the function that invoked the function (or event listener). You can use `console.log` on your jQuery statement to double-check that the student is targeting the correct HTML element with their code.
2. jQuery can modify the HTML attribute, inline CSS syntax, or even the content of an HTML element. Try out these different techniques to produce interesting effects.

There's one more activity in today's lesson and you're going to introduce that next.

## 11. Instructor Do: Introduce the To-do App Activity (5 min)

> :pushpin: **Important Point:** **Important Point:** Your goal is to introduce the final activity for the day: building a To-do App using jQuery event listeners and conditional statements. This final activity supports the final learning objective, which is for students to create a working To-do App using the conditional logic principles they've learned today.

Your purpose here is to reassure students that creating UI elements that users interact with is the only way to really understand how jQuery and conditionals work. You must apply the skills by building UI elements, as each UI element will be built differently.

> :gem: **Designer Insight:** Share with the class how gratifying it is to build simple UI elements from the inside-out for users.
>
> - Alternatively, ask a TA who uses JavaScript and jQuery to share their experience with creating simple apps.

Take a moment to make this relevant and connect the value of knowing how to build a To-do App with job competitiveness and careers in UX/UI design.

> :briefcase: **Employer Competitive Note:** Building fully functional features is essential for students to become code conversational. Having the ability to code complete UI elements will increase the student's knowledge of designing realistic UI systems.

**Say:** "The next activity is meant to reinforce all the concepts you learned in class today and from Lesson 19.1. Remember, practice makes perfect!"

Students will be creating a UI element—their very own **To-do App** using the jQuery skills they learned in lessons 19.1 and 19.2.

The To-do App will have three features:

1. The ability to create tasks that need to be done.
    *Students will use an event listener to append tasks to HTML elements when creating tasks.*
2. The ability to check tasks off as done.
    *Students will create an event listener that listens to the document body and removes the element clicked using "this."*
3. The ability to delete tasks.
    *Lastly, students will create an `if else` statement that adds and removes classes based on how a user interacts with their app.*

**Say:** "If you don't fully understand how jQuery works, that's OK! It takes time to master any front-end development language."

## 12. Student Do: Build a To-do App Activity (40 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.2_03 - To Do App](https://docs.google.com/document/d/1BrS7PalsVtJtrQptU4NC5iu7n8aXlq7PAZ_lPmDmBn0/).

### Summary

This activity wraps together all the principles that we learned today and in the previous lesson. The goal of this activity is for students to understand how they can create interactive elements with JavaScript.

### Instructions

Students will be creating a working To-do App during this activity. This activity is a long one (40 minutes), designed to test students' skills and get them out of their comfort zones.

*If students struggle:* This activity is meant to be challenging. Student problems are going to vary. Lean on the solved file to show students how their syntax is different from the solved. The problems that students encounter will vary on their skill level.

*If students complete the activity early:* Share the following [resource](https://www.webfx.com/blog/web-design/40-exceptional-jquery-interface-techniques-and-tutorials/) with them. Remember, practice makes perfect. Alternatively, engage the student in a conversation about their portfolio.

### Instructors and TAs

**Instructors:** While students work on the activity, be sure to monitor students' screens as they work. Answer students' questions on JavaScript. If a student gets stuck, ask them what part of the activity they are stuck on and help them logic their way through it.

Practice makes perfect!

Be sure to stress that students should go home and practice JavaScript and front-end development in their free time if they want to master these concepts truly.

**TAs:** If you are experienced with JavaScript, follow the lead of the instructor and assist students with their JavaScript woes. If you aren't an experienced programmer, either catch up on your challenge (if applicable) or search the internet for useful jQuery guides and tricks to share with students via Slack.

Some common problems students might have:
1. Students will sometimes get stuck on how to target the correct HTML element. Students also commonly get stuck on event listeners that target the [document body](https://api.jquery.com/on/#direct-and-delegated-events).
2. Students may struggle with the different jQuery functions that are used in this activity. Remember that finding the documentation for any particular function is only a Google search away.

### Deliverable

Students should submit a project with an `index.html` file and an `index.js` file.

## 13. Instructor Do: Build a To-do App Activity Review and Recap (15 min)

Call the class back to attention and initiate a review conversation.

> :globe_with_meridians: **Online Recommendation:** Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer these questions.

**Review the activity.**

> **Say:** "That was a LONG activity! How'd you do? Let’s review and discuss your work!"

> **Ask:**
>
> "What part of the activity was most difficult? Why?"
>
> "What seemed fairly "easy" about it?"

See where the discussion leads and then transition to review a few concepts to reinforce learning.

### Review the concepts.**

> **Ask:**

1. "What kind of error messages can the Web Inspector tell you?"

	> Instructor Note: Listen for answers like:
	>
	> 1. Syntax errors with your code
	>
	> 1. Incorrectly linked images and files
	>
	> 1. `console.log` messages logging words to validate if an event listener is functioning, variable contents, or HTML content

1. "What is a conditional? "

	_A conditional is a statement that checks for specific conditions or parameters that you define using a logical operator._

> **Instructor Note:** Ask a few students to give answers to this question so students can learn from the group.

1. "What is a logical operator?"

	_A logical operator is syntax that tells our condition how it is measured._

1. "How can conditionals and logical operators be used together?"

	_Conditionals and logical operators are used to create options that power `if else` statements._

> :gem: **Designer Insight:** Take part in the conversation by sharing your experience learning to write conditionals.

Wrap up the conversation by pointing out a couple of things about `if else` statements that you want to be sure students notice.

**Review today's top concepts.**

Review the high points of today's class to reinforce student takeaways. In particular:

- Ask the class to define conditionals.
- Discuss what practical conditionals are.
- Discuss how conditional logic is defined.

Offer students actionable feedback that they can apply to their work. For example:
1. No two conditional statements are exactly the same. Make sure to test your interactions using `console.log` to test your function even if you're sure the code is correct.
2. Using conditional statements can create any type of interaction. You can create `if else` statements on forms, drop-down menus, various UI elements, or statements that execute when the document loads based on what browser our audience is using.

Take a moment to give students a sense of some common misconceptions or FAQs about getting started with JavaScript. For example:
1. jQuery can both append and remove divs. You can use conditional statements to create functions that apply properties at the correct time.
2. jQuery can create HTML elements with content using `.append()`.

Great work! Ask if there are any final questions.

## 14. Instructor Do: End Class (5 min)

Remind students that you're available after class during office hours.

Say goodnight and end the class!

*Psst! Great work!*

---

## We Want Your Feedback!

Please submit any issues or comments on the UX/UI curriculum to our Google Form.

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

With this form you can now view the status of your submission and other issues here:
[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing)

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.	
