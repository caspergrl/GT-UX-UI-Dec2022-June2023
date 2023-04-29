# 19.3 Lesson Plan: jQuery Custom Animations

---

## Overview

Today is the final lesson of Unit 19. In the first lesson, you introduced JavaScript and jQuery and the concepts of variables and functions—giving students a foundation for going deeper with these languages. In the second lesson (19.2), students learned and practiced conditionals, enabling them to create logic and interactivity in jQuery functions. Today, they'll learn about building user interface (UI) interactions on a UI to master the fundamental concepts of using jQuery. By the end of this unit, students will design and develop UI interaction using jQuery.

One goal today is to communicate the value of accordions, which are useful for toggling between hiding and showing a large amount of content. You'll also help students learn and practice using accordions through the in-class activities and working session.

### Learning Objectives

By the end of class today, students will be able to:

1. Code an accordion element that toggles classes on sibling elements using jQuery functions.
2. Create an animated drop-down search field element.
3. Create a preloader element by combining keyframe animations and JavaScript functions.
4. Trigger animations with a `setTimeout()` function.

## Class at a Glance

Today's class has three parts:

**Part 1:** Students will learn about accordion elements and build one that opens and closes tabs when clicked.

**Part 2:** Students will learn about drop-down elements, display a search form element, and create a search field that drops down and covers the whole screen to display the navigation menu.

**Part 3:** Students will learn about preloader elements and use keyframe animation to spin a preloader that fades to reveal a website after three seconds. The preloader element loads and hides slow-loading content on the page.

Today's activities culminate in a completed UI that contains several different interactions. 

**Today has a working session at the end: **

Once students complete the three in-class activities, they can use the working session to make progress on their homework or practice their jQuery by redoing activities.

---


## Online Recommendations

Many of our activities were written for in-person classes, so we've added in-line callouts (usually indicated by this icon: > globe_with_meridians: **Online Recommendation:**) to let you know how to adapt an activity for online delivery.

***Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.***

> :globe_with_meridians: **Online Recommendation:** Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here is an example of what you can say during common transitions:
- From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”

> :globe_with_meridians: **Online Recommendation:** Transitions and activities tend to take longer in virtual classrooms. If you find that you are running short on time, feel free to combine review sections. Although we encourage students to work in groups to help them move through activities in class, learn from their peers, and prepare them for teamwork as a designer, if working in groups presents technical challenges or eats up too much time, feel free to have students work independently instead of creating breakout groups. 

## Prepare for Class

**Review the slides beforehand**.

[19-Week/01-Slides/19.3 jQuery Custom Animations Slides](https://docs.google.com/presentation/d/1-lkpqMcU7sFtshOSj7B3PsQJclp7zVmWwGiJDWxc5Sc/edit?usp=sharing)

- Make any teaching notes you'll need.

- As you lecture, relate your own on-the-job experience whenever possible to bring what students are learning to life and connect it to their future goals.

- Look for the :gem: icon, which prompts you and/or a TA to share professional anecdotes directly related to a particular concept.

**Mini-Project**

Today is a workday for the class. During today's lecture, we'll introduce a mini-project (a "challenge") for our class to work on. 

Why are mini-projects important?

Mini-projects are an important part of the front-end development section of this course. Why? Because they give beginning designers time to explore and experiment, forcing them to become problem solvers.

The mini-project today is adding user experience (UX) interactions to a website for a company that is selling tickets for shows to help users convert and buy tickets. The mini-project entails three activities over the course of the day.

> **Instructor Note:** If a student runs into a question or problem, instruct them to first try to Google their problem or idea. Researching and testing code is an essential part of the learning process and will make students better developers.

Common mistakes you'll encounter today:

1. Syntax errors: Rely on the console to check the student's code for these.
2. Improperly targeted HTML elements: Be sure to check the jQuery selectors.
3. Misunderstanding documentation on jQuery functions: The documentation provides answers but can be confusing for first-time readers. Help students understand the examples in the documentation.

Mini-projects also help you, the instructor, interact with students, taking an active role in helping them understand front-end development.

Mini-projects can result in big wins for student understanding. There is nothing more satisfying to a beginner than to get an aha moment when their code works correctly.

> **Instructor Note:** Encourage students to take creative liberties when working through the activities. If students finish early, prompt them to attempt to alter the design or animations we build today. Workdays throughout our curriculum exist so students can explore and "play" with code.

This mini-project has helped countless boot camp students understand how to connect the dots on targeting and adding animations to HTML elements using simple jQuery functions.

The hardest leap for students to make is connecting how to use jQuery on real UI elements. Today, we'll give students an opportunity to modify a UI in a series of activities.

**Scenarios**

Today, you'll share scenarios describing why we'll add certain interactions onto our site. The scenarios should engage the students and help them get excited about writing code and creating UI interactions.

- The class will use three functions: `setInterval`, `.find`, and `.siblings`. The following resources should help you get up to speed:

  - [setInterval Documentation](https://www.w3schools.com/jsref/met_win_setinterval.asp)

  - [jQuery .find Documentation](https://api.jquery.com/find/)

  - [jQuery .siblings documentation](https://api.jquery.com/siblings/)

- If needed, review the Strategies for Class Online in the unit README.

---
## Time Tracker

- Keep track of the clock. Have the TAs consult the [19-Week/03-Time Trackers/19.3 Time Tracker](https://docs.google.com/spreadsheets/d/1wiXEBQqe23JY8GLazIhnjQwWiyQifIPSmxqWWj16ooc/).

- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---


## Office Hours: Each class, before class (45 min)

Encourage students to come early and use the time provided and not to be afraid to ask questions.

> Do your part by engaging students who come early and participate in office hours.

---

## 1. Instructor Do: Welcome and Share Today's Objectives (5 min)

> :pushpin: **Important Point:** Your goal is to introduce today's objectives and prepare students for a more hands-on class.

Welcome your students to class.

Open and download today's slides. TAs should share a pdf of the slides with the students via Slack:

- [19-Week/01-Slides/19.3 jQuery Custom Animations Slides](https://docs.google.com/presentation/d/1-lkpqMcU7sFtshOSj7B3PsQJclp7zVmWwGiJDWxc5Sc/edit?usp=sharing).

Share today's objectives. By the end of class today, students will be able to:

- Code an accordion element that toggles classes on sibling elements using jQuery functions.

- Create an animated drop-down search field element.

- Create a preloader element by combining keyframe animations and JavaScript functions.

- Trigger animations with a `setTimeout()` function.

Today's class will focus on three in-class activities that build upon each other. These activities will relate to the following scenario:

**Scenario:** You work as a UX/UI designer for a website that sells tickets to upcoming events.

**Problem:** Your website's users aren't staying on the site very long.

**Issue:** You found that users leave the webpage because it isn't visually interactive and it has a lengthy load time.

In each of the three activities, students will add interactivity to a a prebuilt HTML template with jQuery-driven animations. Students will build the following exciting animations:

- A smart accordion that opens and closes tabs when clicked.

- A search button that expands to display a search page.

- A preloader that hides slow-loading content.

After these activities, there will be extra time to work on homework or continue adding animations.



## SLIDE 1-3
Review

## SLIDES 4-6
Review

## SLIDE 7
Review

## SLIDE 8
Accordions are common UI elements that are used to chunk content. Accordions feel more reactive to our users and create a better UX by showing them the contents of only the tab they clicked. Users will no longer have to scroll through tons of content if they opened each tab.

"We use accordions to chunk content and make it easier for users to find the content they're looking for. *What other uses might an accordion have?*"

To trigger complex animations in JavaScript, you'll need to know how to target other HTML elements that are part of the same organism.

## SLIDE 9
Review

## SLIDE 10
Review

## SLIDE 11
Accordions can have several use cases. Depending on the UI element we are creating the accordion on, the look and feel of the accordion can vary. Let's show a few examples to the class.

**Navbars:** Accordions are sometimes seen in navigation to condense complex navigation to be more digestible. This technique can also be applied to group elements in a drop-down menu or sidebar with content that relates to each other.

![Accordion Example 1](Images/accordion_example1.gif)


## SLIDE 12
**Search forms:** For complex search forms with multiple parameters, an accordion could be implemented to condense our form and allow our users to add specifics based on types. Take a look at the following example of a search form used for finding different styles of clothes.


## SLIDE 13
## 3. Student Do: jQuery Smart Accordion Activity (30 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.3/19.3-01-jQuery-smart-accordion](https://docs.google.com/document/d/1Vt0SYu9AVgbPfLrT6aIEzq5Pp8sRYm2-KK484EyJ2uM/).

> **Instructor Note:** Set a timer for 30 minutes.

### Summary

This is the first of three mini-project activities.

In this activity, students will learn how to target sibling elements nested inside the same div as the element that was clicked using jQuery.

Being able to control all elements in a particular UI element is very powerful and useful. It can bring a UI element to life if everything reacts to the user input, giving the UI element a "smart" feel.

### Instructions

To test their jQuery knowledge, students will build a working accordion from scratch.

*If students struggle with this activity:* Lean on the solved file; show the students how their code is different. If you're an experienced developer, you can simply help the student debug their code.

*If students complete the activity early:* Share the following [resource](https://www.youtube.com/watch?v=6LfMsU1LfM8) with the students to give them additional ways to build this UI element.

### Instructors and TAs

**Instructors:** During this activity, assist students who are stuck or who need help debugging their code. If you encounter a problem that you don't know how to solve, reference the solved file and show students how their code is different.

**TAs:** If you're an experienced programmer, follow the instructor's lead and help students solve problems. If you aren't, talk to the students who are finished. Ask them about their experience with the activity and share ideas on how they could customize other elements using the same techniques taught.

Some common problems students might have:

1. Double-check the syntax of the student's work. Students often make mistakes when chaining jQuery functions together.

2. Test the student's event listeners. Use `console.log` to check the student's variables to make sure they're targeting the correct HTML element. Remember, syntax matters!

### Deliverable

When students are finished, they should have a working accordion on their site.

![Accordion Gif](Images/accordian_gif.gif)

Before we move on, let's take a moment and discuss the smart accordion activity that we just completed.

## SLIDE 14
## 4. Instructor Do: jQuery Smart Accordion Activity Review (5 min)

Call attention back to your screen and lead a review of the activity.

**Ask:**

- "Does anyone have any questions about how your smart accordion works?"

- "Are there any questions about how to chain jQuery functions together to create dynamic elements?"

Offer students actionable feedback that they can apply to their work. For example:
1. Next time you design an accordion element, try to build your tabs vertically for a different look and feel.
2. jQuery can be used to find HTML elements. Try using this jQuery function to manipulate any individual element inside of your UI element.

Share some common misconceptions or FAQs about building accordions. For example:
1. There are many ways to develop an accordion—this is only one way you can build one. Encourage students to be creative with their code.
2. Accordions can be used in forms, navigation items, or to separate content. This is just one example of how you can use an accordion element.

Next, move on to introducing animated drop-downs menus in your next lecture.


## SLIDE 15
Review

## SLIDE 16
### Complex Animations Scenario

Our users stated that our navigation bar was too cluttered. In response to this feedback, we trimmed down our navigation by condensing our search bar.

But users still need to use it!

The solution is to create an animation from our navbar that displays our search form.


## SLIDE 17
Navigation menus that animate are extremely common in the UX world because they add a real level of excitement to our UIs. They also allow companies to have a large complex website but still have users able to navigate it. They're often created to condense our UI to make navigation elements more obvious. For example, take a look at a major website like [amazon.com](https://www.amazon.com).

- Animated navigation bars allow designers to create more specific or complex navigation menus that have the bonus of feeling interactive.

- Elements that users interact with are becoming the norm because websites are being designed and developed to be more fluid and interactive, like phone apps. Take a look at [pandora.com](https://www.pandora.com) as an example of a modern web app.


## SLIDES 18-20
Review

## SLIDE 21
## 6. Student Do: Create a jQuery Drop-Down Menu Activity (30 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.3/19.3-02-jQuery-Drop-Down-Search](https://docs.google.com/document/u/1/d/1ulsMzr76XwPvmdbEcNeeT0b0odz8SRnsU8klutxa4Gw/).

> **Instructor Note:** Set a timer for 30 minutes.

### Summary

During this activity, students will create a drop-down menu that contains a search form.

### Instructions

Students will follow the activity instructions and create a working drop-down menu by using jQuery selectors that target the class of searchBar.

*If students struggle with this activity:* Lean on the solved file; show the student how their code is different. If you are an experienced dev, feel free to simply help the student debug their code.

*If students complete the activity early:* Share the following [resource](http://smashinghub.com/simple-jquery-drop-down-menu-tutorial.htm) with the student to give them extra practice.

### Instructors and TAs

**Instructors:** 
During this activity, assist students who are stuck or those or who need help debugging their code. If you encounter a problem that you don't know how to solve, reference the solved file and show students how their code is different.

**TAs:** If you're an experienced programmer, follow the instructor's lead and help students solve problems. If you aren't, talk to the students who are finished. Ask them about their experience with the activity and share ideas on how they could customize other elements using the same techniques taught.

Some common problems students might have:

1. Double-check students' selectors. It is common for students to target IDs instead of classes (and vice versa).

2. Also, double-check student syntax for if-else statements. It is common for students to make mistakes when creating one inside an event listener.

### Deliverable

The deliverable is a working drop-down menu that toggles from the search button.

![drop-down](Images/dropDown.gif)

Creating a drop-down menu is easier than it looks. Let's discuss as a class their experience building a drop-down menu.

## SLIDE 22
## 7. Instructor Do: Create a jQuery Drop-Down Menu Activity Review (5 min)

Call the class back to attention and lead a review of the activity.

Ask the class if they have any questions about the interactions they've created.

> globe_with_meridians: **Online Recommendation:**: Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer these questions.

**Ask:**

1. Did you find this solution to hide an overly complex menu effective? How might you have implemented this differently?

2. Did you have any difficulty creating the code to create our drop-down menu? What were the challenges?

Offer students actionable feedback that they can apply to their work. For example:
1. Drop-down menus can either be full-screen effects or just on the navigation. The choice is yours. 
2. Any CSS property can be modified to create an effect. How might you animate a drop-down menu if it isn't full screen?

> **Instructor Note:** Use the ask-and-wait method: Ask a question, then pause; count the length of three long breaths before continuing. Usually, your silence will provoke a student's question!

Share some common misconceptions or FAQs about drop-downs. For example:
1. Drop-downs can be full screen, animated from the left or right side, or from a navbar.
2. "Drop-downs are what your users expect."" *False.* A dropdown is one of many solutions and will require user testing to validate its usability.

Next, it's time for everyone to take a break. 

## SLIDE 23
## 8. Break (15 min)

## SLIDE 24
Review

## SLIDE 25

Understanding jQuery tools like preloaders are part of the students' conversation skills. Take a moment to connect this skill to working with design teams in the professional world:

A preloader is a simple UI element that has multiple use cases. When students build their own preloaders, they'll understand how and why they would use one in their design work.

As a UX/UI designer, you can include code experiments like preloaders as ways to improve a user experience to moments in your portfolios.

## SLIDE 26
Review

## SLIDE 27
**Preloaders** are UI elements that serve as a visual to hide slow-loading content or that let the users know there is data transfer happening before displaying the result.


- **TAs:** Slack out this link of complex sites that need preloaders: [Loading Page Animations](https://www.awwwards.com/awwwards/collections/loading-page/).
  - *Ask students to* bookmark or check out some of the different loading pages.


## SLIDE 28
Review

## SLIDES 29-30
Review

## SLIDE 31
## 10. Student Do: jQuery Preloader Activity (30 min)

**TAs:** Slack out the activity file: [19-Week/02-Activities/19.3/19.3-03-jQuery-Preloader](https://docs.google.com/document/d/1_OXWpZ28rOEmEmFUExtx0DPPhf5tkckzH-yrZamGJ9E/).

> **Instructor Note:** Set a timer for 30 minutes.

### Summary

In this activity, students will create a preloader on their template. They'll also create work that they can relate to as users of websites—connecting their real-world experience with in-class activities.

Additionally, students will practice the basics of web animation by transitioning between elements with opacity.

### Instructions

Students will follow the activity instructions to complete a working preloader on their site.

*If students struggle with this activity:* Lean on the solved file. Show the students how their code differs. If you're experienced, feel free to help the student debug their code.

*If students complete the activity early:* Share the following [resource](https://ihatetomatoes.net/create-custom-preloading-screen/) with the student to give them extra practice on creating preloaders.

### Instructors and TAs

**Instructors:** During this activity, assist students who are stuck or who need help debugging their code. If you encounter a problem that you don't know how to solve, reference the solved file and show students how their code is different.

**TAs:** If you're an experienced programmer, follow the instructor's lead and help students solve problems. If you aren't, talk to students who are finished. Ask them about their experience with the activity and share ideas on how they could customize other elements using the same techniques taught.

Some common problems students might have:

1. Students might not understand that they'll work on all three files for this activity. Double-check that students are writing code in the correct place.

2. The [setTimeout()](https://www.w3schools.com/jsref/met_win_settimeout.asp) function is new to the class. Help them understand this function if they have problems with the syntax.

### Deliverable

![preloader gif](Images/preloader_gif.gif)

## SLIDE 32
## 11. Instructor Do: jQuery Preloader Activity Review (5 min)

Call the class back to attention and lead a discussion and review of the preloader activity.

**TAs:** Be sure to take part in the discussion and activity review.

> globe_with_meridians: **Online Recommendation:**: Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer these questions.

**Ask:**

- "What uses does a preloader have?"
- "Where else do you see preloaders besides a loading animation?"
- "What did you struggle with?"
- "What did you learn during this activity?"

Offer students actionable feedback that they can apply to their work. For example:
- A preloader can be created using any image or gif. Don't feel constricted to using the image we provide.
- Students can use this simple function for a variety of reasons. What if they design an app that needs to refresh data?

> **Instructor Note:** Remind students: As UX designers, they must be conscious of how design choices affect site performance and the balance between client and user priorities, which sometimes appear to conflict with one another.

Share some common misconceptions or FAQs about preloaders. For example:
- Preloaders can be coded to load when either the page loads or all the website assets load. The choice is up to the programmer.
- Preloaders are a design trend. You'll see them in more than just loading animations.

Next, you'll give students time to work on their challenge assignment. 

## SLIDE 33
## 12. Student Do: Working Session (35 min)

> **Instructor Note:** The rest of class is a working session for students to make progress on their challenge or redo the in-class activities for practice.
> 
> Encourage students to apply what they just practiced to their challenge. They should also seek out inspiration for simple UI interfaces that could benefit from adding animations to bring them to life.

Speak with students about their projects and help answer questions as they work on their challenge and animations.

**TAs and instructor:**

_If you're an experienced front-end dev:_ Help students work on their code and solve jQuery woes. Give them some useful pointers along the way.

_If you aren't an experienced front-end dev:_ Direct students to the solved files and show them how their code is different from the solved files.

**How students should use this time:**

- Invite students to work on their challenge.

- If students have other ideas on how to improve their web templates, they can make those changes.

This time is set aside so that students can focus. They can work on whatever deepens their learning or moves their challenge forward.

> globe_with_meridians: **Online Recommendation:**: Don't just dismiss the class. This time is set aside so that students can have the benefit of the instructional staff's expertise as they practice.

## 13. Instructor Do: Recap and End Class (3 min)

Great day!

Tell students they've had valuable practice using jQuery and creating custom animations.

**Lead a review of today's concepts.**

Spend a few minutes helping students anchor today’s learning through mental recall.

> :globe_with_meridians: **Online Recommendation:** Ask students to raise their hands—or post answers in Slack—and respond to the following concepts, all learned today in class.

> **Ask:**
>
> - "What do you remember about jQuery smart accordions?"
> 
> - "What's important to remember about drop-down menus in jQuery?"
>
> - "What 2-3 things can you recall about jQuery preloaders?"


Thank students for their hard work today.

Remind students that you're staying online and available after class for office hours.

*Psst! Great work!*

---

## We Want Your Feedback!

Please submit any issues or comments on the UX/UI curriculum to our Google Form: [Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform).


With this form, you can now view the status of your submission and other issues here: [Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing).

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.	
