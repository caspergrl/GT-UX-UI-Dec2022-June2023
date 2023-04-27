# 18.3 Lesson Plan: CSS Transitions and Animations

---

## Overview

Today's lesson is focused on web animation. In units 9 and 12, you covered animation in Adobe XD. Now you'll show students how to animate with code in HTML/CSS.

For context, remember that Unit 18 is about the CSS Flexible Box Model. Once students complete all three Unit 18 lessons, they'll be proficient in building responsive websites using the CSS Flexible Box Model. 

The first of these three lessons covered CSS Flex, where students learned how to create one-dimensional layouts using CSS Flex. The second lesson covered CSS Grids, giving students the ability to create two-dimensional layouts. 

This final lesson covers web animation, which gives students the power to add basic interactivity to a website. Altogether, these lessons enable students to build flexible layouts that respond to our users.

---

## Learning Objectives

By the end of class today, students will:

1. Construct a CSS transform animation that rotates, transforms, and moves an element.
2. Create a CSS transition using pseudo-classes to make buttons interactive.
3. Construct a custom CSS keyframe animation that has multiple steps.

## Class at a Glance

Today's class can be broken into three parts:

Part 1: CSS transforms
Part 2: CSS transitions
Part 3: CSS keyframe animation

Understanding how these three pieces of code work together will be a great asset to students choosing to practice their CSS.

---

## Preparing for Class

**Review the slides beforehand**.

- [18-Week/01-Slides/18.3-CSS-Transitions-and-Animations](https://docs.google.com/presentation/d/1Na9VwLoavTBpycyjHH--skR9_FueDfJ4v9FMv3zLREk/edit?usp=sharing).

- Make any teaching notes you'll need.

- As you review this lesson plan, make note of opportunities for ***relating professional anecdotes to bring concepts to life***. Be sure to connect the concepts to work that real-life designers do. Look for the :gem: (gem) and > :briefcase: (briefcase) icons in the lesson plan as prompts for you and TAs to share your insights.

- Today is all about CSS animations. Students will create an animation that rotates a div, scales an element's size, and translates an element's position. If you're unfamiliar with CSS transform, animations, and keyframes, be sure to review the following documentation:
  - [Mozilla Transforms Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)
  - [Mozilla Transitions Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)
  - [Mozilla Keyframe Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)

- You will give two demos today:

1. CSS transitions demo where you showcase a hover state (Section 6)
2. CSS keyframe demo where you show students the basic keyframe syntax (Section 11)

Be sure to run through each of the demos on your own *at least once* before class.

If you don't have a [www.codepen.io](https://codepen.io/) account created, create one and fork (CodePen's copy function) the demo files to your new account in preparation for class.

- If needed, review the Strategies for Class Online in the unit README.

---


## Class Materials

- Make sure you have all the class activities downloaded and ready to go at the start of class.

---

## Time Trackers

Keep track of the clock. Have TAs consult the [18-Week/04-Time Trackers/18.3 - Timetracker](https://docs.google.com/spreadsheets/d/1cErYGnMdwnyGzkaT2iS0FBBFx3admiDBs6wJGZQwpwg/).

- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---


## Office Hours: Each class, before class (45 min)

Encourage students to come early and use the time provided and not to be afraid to ask questions.

> Do your part by engaging students who come early and participate in office hours.

---

## 1. Instructor Do: Welcome the Class and Share Today's Objectives (2 min)

> 📌 The goal of this lesson is to teach the basics of web animation. A few students may feel impatient with the basics and be eager to create dynamic animations. Acknowledge that feeling as valid. Let students know that they can and will get there with *practice*! For example:

Welcome students to class.

- Open the slides for today: [18-Week/01-Slides/18.3_Transitions_and_Animations](https://docs.google.com/presentation/d/1NM-PJ06Mwm9jkkfkzIp17vlyyjWuUy-4WDNoj5uBa1Y/).

**Say:** "Today we'll learn the basics of web animation. We'll discuss transforms, transitions, and keyframes, which is all you need to build complex animations."

> :gem: **Designer Insight:** Open the discussion by telling the class a bit about your own experience applying animation and its benefits to your work as a designer.

> 💼 **Employer Competitive Note:** During the UX/UI Boot Camp, students are required to prototype interactions. Interactivity is essential to modern UX designers who use animation to direct user attention to important content and calls to action (CTAs). Today, we're teaching the basic CSS properties used in animation, giving students working knowledge of the code behind the interactions they prototype.

Creating meaningful animations and indicators can really direct users to convert on our CTAs. For example, let's use a big-name company like Google:
![Google Animation](Images/google_webAnimation.gif)
Do you think it's a coincidence that Google adds its animations right above their main call to action (CTA)?

The web has come a long way since the days of tables and dull, flat layouts.

Let's take a look at the old Apple website built using tables without transforms, transitions, and keyframes.

![Old Apple website](Images/Old-Apple-Website.jpg)

Pretty boring, right? The web today is very much alive thanks to the integration of transforms, transitions, and keyframe animations.

Let's see how far Apple has come.

![New Apple website](Images/apple_gif.gif)

Wow! Looks way better with the new technology. On the new site, notice how the animation is subtle. Your attention is automatically pulled to the rotating products. When you click one of the rotation items, you are taken to the product page.

Now, jump into the first property for creating animations like the ones on apple.com: CSS transforms.

## 2. Instructor Do: CSS Transformations (15 min)

> :pushpin: **Important Point:** Your goal in this section is to teach the basics of CSS transforms and how they help animate HTML elements. This supports the first learning objective of the day, which is for students to construct a CSS transform animation that rotates, transforms, and moves an element.

Students will learn how to add animation to their web development work, which will, in turn, make their pages more exciting for users. You'll start with the CSS transform property, which students will try out for themselves after the lecture.

> **Instructor Note:** It is important to repeatedly tell the students that all three of the CSS animation properties we discuss today are used hand-in-hand to create complex animations. By practicing, students can master creating CSS animations that create a delightful user experience.


## SLIDES 1-3
Review

## SLIDES 4-5
Review

## SLIDE 6
Review

## SLIDE 7
Web animation and CSS animations are two terms that describe the same thing. Animations on the web are powered by CSS3 animation techniques.

CSS transforms, transitions, and keyframe animations offer a lightweight, easy way to create animations on websites.

Animations can also be created using JavaScript, but even JavaScript animations simply leverage CSS3 transforms, transitions, and keyframe animations in the background.


## SLIDE 8
### CSS `transform` Property

Simply put, the CSS transform property allows you to visually manipulate an element by skewing, rotating, translating, or scaling through CSS.

There are two types of CSS transforms: 2D and 3D.

## SLIDE 9
### 2D Transforms

2D transforms are exactly as they sound—2D transforms modify an element by its shape, size, and position. It changes the element along the x-axis and y-axis.

2D transforms have many properties that you can leverage. We'll introduce these CSS properties to students now.

## SLIDE 10
The CSS transform property specifies HOW an element is animated. CSS transitions (another CSS animation technique) makes animations smooth and visually pleasing.

## SLIDE 11
Review

## SLIDE 12
- `rotate` rotates the element in a circular motion. The attributes are specified in degrees (clockwise) or negative degrees (counter-clockwise) depending on which way you want the element to rotate.

## SLIDE 13
- `scale` increases or decreases the size of an element (according to the parameters given for the width and height). Width is specified first and height is specified second.

## SLIDE 14
- `translate` moves the element along the x- and y-axis according to the properties you enter.

## SLIDE 15
Review examples

## SLIDE 16

CSS transforms specify how an HTML element animates and works hand-in-hand with transitions to make that animation smooth. The two properties are used together to create simple animations. These animations can also be designed and developed with JavaScript. Keyframe animations combine these two techniques, but they also allow you to specify multiple CSS properties for creating a complex animation. Transforms, transitions, and keyframes are all tools in a toolkit for creating UI interaction on websites.

_Review list_

## SLIDE 17
## 3. Student Do: CSS Transform: Rotations and Scaling Activity (20 min)

**TAs:** Slack out the activity file: [18-Week/02-Activities/18.3/18.3_01_Rotations And Scaling](https://docs.google.com/document/d/1Lkgl3jrtwmVHwBRMJpusCO3WyCTSmPgV5aNUVp7paoo/).

### Summary

In this activity, students will practice rotating and scaling prebuilt elements on a page.

### Instructions

Students will practice with the following transforms:

```css
transform: rotate();
transform: scale();
transform: translate();
```

*If students struggle:* Double-check the students' syntax for errors depending on the different properties they are trying to apply. Each property for transforms has slightly different syntax, so you may need to Google the various CSS properties with your students. Alternatively, feel free to lean on the solved file to show students how their code differs.

*If students complete the activity early:* Share the following [resource](https://css-tricks.com/almanac/properties/t/transition/) with them.

### Instructors and TAs

> :globe_with_meridians: Online Recommendation: With your TAs, monitor students and offer help where needed. Encourage students to help one another as well.

**If you are an experienced developer:** Assist students with questions. If a student gets stuck, help them understand what they did wrong.

:globe_with_meridians: Online Recommendation: If many students are struggling with the same problem, ask a TA to help them in a breakout room, or jump into a breakout room yourself. 

**If you are not an experienced web developer:** Make sure you review the solved/activity file beforehand. If a student has a question, show them how their code is different from the solved file.

### Deliverable

During this activity, students practice the basic syntax for CSS transforms. Students will create:

1. A dog flipped upside down with 

```css
transform: rotate();
```
2. A red square scaled using 
```css
transform: scale();
```
3. A blue square that has been moved around inside of its container using 
```css
transform: translate();
```
## SLIDE 18
## 4. Instructor Do: CSS Transform: Rotations and Scaling Activity Review (5 min)

Call the class back to attention and lead a review of the rotations and scaling activity.

**Say:** "What you just did may have seemed like simple bits of code, but when paired with the other concepts we teach in this class, you can create complex animations."

For example, maybe you need a preloader on your webpage that simply spins (loading circle). Preloaders can be created on any image by using a transform paired with a transition.

Invite students to share what they learned, were surprised by, had an easy time with, or were frustrated by during the activity.

Students will need actionable feedback that they can apply to their work. Make some suggestions that will make their work easier the next time they rotate, scale, or translate an object. For example:

1. All the CSS properties of CSS transforms have different effects. Students need to experiment with applying the properties to create smooth animations.
2. CSS transforms on their own don't produce cool effects. CSS transforms need to be paired with transitions to create beautiful animations on your UIs.

Invite TAs to share their observations as part of the activity review.

## SLIDE 19
Review

**TAs:** Slack out the following resources to your class: [W3Schools 2D Transforms](https://www.w3schools.com/css/css3_2dtransforms.asp).


## SLIDE 20
CSS transitions allow a user experience to have behaviors and can reinforce navigation and interaction models.

## SLIDE 21
CSS transitions revolutionized the world of web development by adding the ability to animate the CSS attributes of elements.

## SLIDE 22
Transitions allow you to define the transition between two states of an element while controlling the animation speed when changing CSS properties.

Before transitions were introduced on the web, creating animations on the web was limited to using Gifs. Gifs can't be controlled and the only option you have is whether they loop or not. Transitions allow developers and designers to create basic ways to let a user know when they can interact with an HTML element.

## SLIDES 23-24
Review

## SLIDE 25
CSS transitions measure the two intermediate states between the transition you program and the beginning state of the element, assuming the animation you want is similar to Figma or Adobe XD's auto-animate function.

> :key: **Key Tech Note:** It is important to note that you can create animations using any of the animatable CSS properties listed in the above article.

One of the more powerful and useful features of CSS transitions is the ability to transition all CSS properties you modify with your hover state or if you trigger the animation with JavaScript. Developers can use transitions that modify all CSS properties to create a transition between multiple CSS properties between states.

Take a look at the following code:

```css 
/* property | duration | timing */
transition: all 0.5s ease-out;
```

- **property:** represents the property you are going to be transitioning. All will create a transition for ALL animatable CSS transitions.

- **duration:** specifies how long it will take the transition to occur.

- **timing:** specifies what kind of effect the transition will have. Is it ease? Easy-out? There are many options.


- **TAs,** Slack out the [List of all animatable css properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties).


## SLIDE 26
A pseudo-class is a keyword that is added to any CSS selector that defines a special state of the element.

A pseudo-class is so named because this HTML selector extends a class function, but isn't quite a real class. It's pseudo because you didn't make it; the browser "created" it and allows you to set it to change the look of the link when it's in that state.


For an example of a pseudo-class, note the ```:hover``` pseudo-class. It specifies what happens when you hover over a certain div.

## SLIDE 27
As we mentioned earlier, pseudo-classes are added to prewritten CSS selectors. Pseudo-classes extend the functionality of any HTML element by allowing us to program different "states" our HTML element is in. For example, the pseudo-class hover allows us to add a hover state to an element and apply an animation to the HTML element when a user's mouse hovers over the element.

> :key: **Key Tech Note:** There are many different types of pseudo-classes but `:hover` is most often used in web animation. For a list of all pseudo-classes, please view the following link: [All pseudo classes W3Schools](https://www.w3schools.com/css/css_pseudo_classes.asp).

```css
.button {
  background-color: red;
  color: white;
  font-size:16px;
  transition: background-color 0.5s ease;
  width: 100px;
  text-align: center;
  padding: 15px;
}
.button:hover {
  background-color: blue;
}
```

## SLIDE 28
All pseudo-classes are added onto the end of CSS selectors with a colon (`:hover`, for example).

The example below will cause our `background-color` to change blue when we hover over it with our cursor.

Notice how this hover effect also has a transition, which will cause our `background-color` to transition over .5s.

## SLIDE 29
1. Open and share the [CSS hover CodePen](https://codepen.io/2u-uxuxi-bootcamp/pen/abJBXzy) with your class.

1. Hover your mouse over the button to show students our hover state animation. Tell the class that this transition is changing the `background-color` of our element.

	That being said, what else can we do to this button?

1. On line 12, change:

	```css
	transition: background-color 0.5s ease;
	```

	to 

	```css
	transition: all 0.5s ease;
	```

1. Tell the class that now our transition is animating any property we change in our hover state. Properties must be declared in both our main class and our pseudo-class for transitions to be able to animate the property.

1. On Line 17, add the property:

	```css
	width: 200px;
	``` 

	Notice that this element already has a declared width on Line 7.

1. Hover over your animation again and watch the new effect!

> **Instructor Note:** Pause for questions.

There are many pseudo-classes. Slack out to students the following link: [All Pseudo-Classes](https://www.w3schools.com/css/css_pseudo_classes.asp).

- Ask students to open the above link and scroll down to All CSS Pseudo-Classes so that they can see how many pseudo-classes there are.

Now it's time to move onto the CSS transition basics activity.

## SLIDE 30
## 7. Student Do: CSS Transition Basics Activity (35 min)

**TAs:** Slack out the activity file: [18-Week/02-Activities/18.3/18.3-02-CSS Transition Basics](https://docs.google.com/document/u/1/d/1eSJTlLmU5cjEwIemgpmlwdxnf1JDPJaor2xhEkWl9jU/).

### Summary

Students will practice the basic syntax of CSS transitions and create a transition in a hover state.

### Instructions

During this activity, students will add a transition to a button and a hover state.

*If students struggle:* Double-check that students have applied the same CSS properties between the different states of their buttons. Feel free to lean on the solved file to show students how their code is different.

*If students complete the activity early:* Share the following [resource](https://css-tricks.com/almanac/properties/t/transform/) with them. Alternatively, engage the student in a conversation about how they can add interactivity to their portfolio using CSS transitions.

### Instructors and TAs

> :globe_with_meridians: **Online Recommendation:** With your TAs, monitor students and offer help where needed. Encourage students to help one another as well.

**_If you are an experienced developer:_** Assist students with questions. If a student gets stuck, help them understand what they did wrong.

**_If you are not an experienced web developer:_** Make sure you review the solved/activity file beforehand. If a student has a question, show them how their code is different from the solved file.

### Deliverable

Upon completion of this activity, students will have practiced creating a working transition on a button, complete with a hover that creates an effect.

## SLIDE 31
## 8. Instructor Do: CSS Transition Basics Activity Review (5 min)

Call the class back to attention and lead a review of the transition basics activity.

Invite students to share what they learned, were surprised by, had an easy time with, or were frustrated by during the activity.

Students will need actionable feedback that they can apply to their work. Make some suggestions that will make their work easier the next time they work with transitions. For example:

1. Be careful when creating transitions that apply to all CSS properties. If you define two separate CSS properties in a transition, it can have unexpected effects (if you specify two separate widths, for example, your element will shrink or grow).

2. Don't use too many animations on a website. The best-designed UI interactions are simple and subtle. If you use too many animations, your website will feel busy and you will have a hard time directing your user's attention to your CTA.

Invite TAs to share their observations as part of the activity review.

> 💎 **Designer Insight:** Take a moment to share your own perspective on working with transition basics.

**Review the concepts.**

Now, transition into a brief review of the CSS concepts students just practiced.

> globe_with_meridians: **Online Recommendation:** Have students engage by raising their hands to speak or addressing the following questions via Slack to test students' retention.

To test for competency, ask the class the following questions.

**Ask:**

- "What is a CSS transition?"

	_A CSS transition is a CSS property that allows you to animate HTML elements between different states smoothly._

- "What is a pseudo-class?"

	_A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s)._

- "How do you target an element with a pseudo-class?"

	_You target pseudo-classes by adding the pseudo-class to the end of your CSS selector with a colon._

Before the break, talk about common misconceptions, errors or FAQs about web animation in general or transitions in particular. For example:

- When creating a CSS transition, you must specify the same CSS property between element states in a pseudo class. If you do not, your transition will not animate.

## SLIDE 32
## 9. Break (15 min) 

## SLIDE 33
Review

## SLIDE 34
### Keyframes are the Root of Animation

"Transitions are great for making simple animations, but what if we need to create a complex animation where we need to control each step of the animation?"

Transforms and transitions allow you to create basic animations between only two states, but some animations require more than two. Complex animations require multiple states that your element goes through before the animation is complete. Think of logo animation—generally, these types of interactions have more than two states that the HTML is in.


## SLIDE 35
Review

## SLIDE 36
### Simple vs. Complex CSS Animations

- The characteristics of simple animations are short, simple, and used to showcase the interactivity of a website.
  - Example: A micro-interaction on Facebook's like icon. When you click the icon, it grows in size, turns, and stays red until you unlike it.


## SLIDE 37
- Complex animations modify multiple CSS properties, are used to draw attention to HTML elements, and sometimes loop depending on the use case.
  - Example: An animation on a logo or image (e.g., Google Doodles).

## SLIDE 38
Enter the CSS keyframe animation. CSS keyframe animations control the CSS animation sequence by defining how the animation looks in keyframes in the animation sequence.

## SLIDE 39
In animation and filmmaking, a *keyframe* is a drawing that defines the start and end points of any smooth transition. The drawings are called "frames" because their position in time is measured in frames on a strip of film. The keyframe keyword allows you to define when each specific part of our CSS animation happens.

## SLIDES 40-41
Review

**TAs:** Slack out the following resource for students to get some inspiration for their animations: [Animation Inspiration](https://uimovement.com/).

> Instructor Note: Pause for questions. Use the 30-second trick by pausing and letting silence fill the room until a question is asked.


## SLIDE 42
Open and have TAs Slack out the [Keyframe Animation CodePen Sample](https://codepen.io/2u-uxuxi-bootcamp/pen/qBYpBMY) to the class.

> globe_with_meridians: **Online Recommendation:** Ask a TA to set a timer for 10 minutes to track your time. They can give you a 2-minute warning.

Walk your class through the CSS used to set up the CSS keyframe animation.

```css
body {
  /* These properties will simply center our box in our screen and make the body take up 100% the height of the screen */
  display:flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
.animation {
  height: 50px;
  width: 50px;
  background-color: red;
  /* The CSS property animation has three properties you can pass to it. The animation name (slide in this case), the timeframe that the animation takes place (7s), and the timing (this runs infinitely) */
  animation: slide 7s infinite;
}
```

- Uncomment line 12 in the CodePen to let the animation play across the screen.

![Uncomment Example](Images/uncomment_keyframe.jpg)

**Say,** "Let's take a look at the syntax of a CSS keyframe."

The CSS keyframe animation below will slide the box across the screen on the x-axis (first value) and y-axis (second value). You can specify negative values to move this element also, which you will see in the code.

> :key: **Key Tech Note:** Make sure you point out that the **name** of the animation must match in both the CSS in .animation and your keyframe name.

```css
@keyframes slide /* this is the name yet set for your animation */ {
  25% {
    transform: translate(200px , 15px);
  }
  50% {
    transform: translate(-200px, 50px);
  }
  75% {
    transform: translate(-100px, 100px);
  }
  100% {
    transform: translate(0,0);
  }
}
```

> :key: **Key Tech Note:** It's important to note in the following example that you can specify any number of "frames" in your animation. These are represented by percentages (1%, 2%, 3%, etc.). For any "frames" that you don't specify, the code will assume the differences between the two states (for example, 1% to 25%).

**Ask:**

- "If each percentage defines a frame for the animation, how can we specify a CSS keyframe animation that has only three frames? How about 10 frames?"

	_You can define each frame as a percentage in our CSS keyframe syntax. You can literally do 1% to 100% for each frame of your animation._

- "Is there a limit on the number of keyframes you can have in an animation?"

	_Yes, 1% to 100%. Each frame (or percentage in our syntax) can be specified separately._

**TAs:** share the following CSS keyframe animation resources in Slack with the class:

- [Animista.net](https://animista.net/play/basic/swing)
- [Webdesign Tuts - 15 CSS animations](https://webdesign.tutsplus.com/articles/15-inspiring-examples-of-css-animation-on-codepen--cms-23937)
- [W3School CSS animations](https://www.w3schools.com/css/css3_animations.asp)



## SLIDE 43
## 12. Student Do: Creating CSS Keyframe Animations Activity (35 min)

**TAs:** Slack out the activity file: [18-Week/02-Activities/18.3/18.3-03-Creating CSS Keyframe Animations](https://docs.google.com/document/u/1/d/1jikiGrclkKZVoLG7V3hGdD4c9QPOSg8HiT8BdENWWPc/).

### Summary

This activity will give students practice with some common animations that they’ve probably seen across the internet.

### Instructions

Students will create four separate CSS keyframe animations to practice their skills:

- Bouncing arrow
- Preloader wheel that spins (loading circle)
- Loading bar
- Moving box

*If students struggle:* Double-check their syntax and make sure they defined states using percentages between the curly braces of our `@keyframe` keyword. Feel free to lean on the solved file to show students how their code is different from the solved file.

*If students complete the activity early,* share the following [resource](https://www.awwwards.com/websites/animation/) with them that showcases animations built using CSS transforms, transitions, and keyframes. Alternatively, feel free to engage the student in a conversation about how they think they can add web animation to their portfolios.

### Instructors and TAs

> :globe_with_meridians: Online Recommendation: With your TAs, monitor students and offer help where needed. Encourage students to help one another as well.

_If you are an experienced developer:_ Assist students with questions. If a student gets stuck, help them understand what they did wrong.

_If you are not an experienced web developer:_ Make sure you review the solved/activity file beforehand. If a student has a question, show them how their code is different from the solved file.

### Deliverable

The deliverables for this activity are as follows:

- A working bouncing arrow
- A working preloader wheel that spins (loading circle)
- A working loading bar
- A box that animates across the screen

## SLIDE 44
## 13. Instructor Do: Creating CSS Keyframe Animations Activity Review (5 min)

Call the class back to attention and lead a review of the CSS keyframe animations activity.

Invite students to share what they learned, were surprised by, had an easy time with, or were frustrated by during the activity.

Students will need actionable feedback that they can apply to their work. Make some suggestions that will make their work easier the next time they create a CSS keyframe animation. For example:

1. CSS keyframe animations require you to build out each step of your interaction using percentages to define states between HTML elements. Experiment with different CSS properties when working with CSS keyframe animations to see the effects.
2. CSS keyframe animations are often wrapped within classes and triggered with JavaScript. During the next unit, remember that you can use classes to create web animation that is triggered on and off by user interaction with event listeners.

Invite TAs to share their observations as part of the activity review.

> 💎 **Designer Insight:** Take a moment to share your own perspective on working with CSS keyframe animations.

**Review the concepts.**

> globe_with_meridians: **Online Recommendation:** Have students engage by raising their hands to speak or addressing the following questions via Slack to test students' retention.

Now, test the class for competency by asking the students the following questions.

**Ask:**

- "What is a CSS keyframe animation?"

	_A CSS keyframe animation is a CSS property that allows you to control each frame of an animation._

- "How is a CSS keyframe animation different from a CSS transition?"

	_CSS transition assumes states between states, while CSS keyframe animations allow you to control each part of your animation._

Take a moment to give students a sense of some common misconceptions or FAQs about CSS keyframe animations, for example:

1. CSS keyframe animations require you to build out each step of your interaction using percentages to define states between HTML elements. If one step has a specific CSS property, you need to also have that CSS property in other states if you wish for it to animate.
2. It is common for students to not write their states between the `@media`'s curly braces. If a student does this, you will not see an error message—the animation will simply not run.

## 14. Instructor Do: Recap and End Class (2 min)

**Review today's key concepts.**

Spend a couple of minutes helping students anchor today’s learning by asking students to raise their hands—or post answers in Slack—and offer definitions for the following concepts, all learned today in class:

**Ask:**

- "Why is adding web animation useful?"

	_Web animations are used to let a user know if they can or have interacted with an HTML element. Web animations can also direct user attention to a CTA or to an important piece of information._

- "What is a CSS transform?"

	_Transform is a CSS property that allows you to rotate, scale, or translate your element's position._

- "What is a CSS transition?"

	_A CSS transition is a CSS property that allows you to animate HTML elements between different states smoothly._

- "What is a keyframe animation?"

	_A keyframe animation is a CSS property that allows you to control each frame of an animation._

> **Instructor Note:** Remind students that you are available for office hours after class to address questions about today's activities, the challenge, or to provide students with feedback on their work.

Take any final questions that students may have, then dismiss class.

## We Want Your Feedback!

Instructor, how did today's class go?

Please submit any issues or comments on the UX/UI curriculum to our Google Form:

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

View the status of your submission and other issues here:
[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing)


---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.	
