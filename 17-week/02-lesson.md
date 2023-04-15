# 17.2 Lesson Plan: The HTML/CSS Box Model

---

## Overview

In today's class, students will expand their knowledge of HTML and CSS basics by learning about the box model and how we use it with HTML and CSS.

## Learning Objectives

By the end of class today, students will:

1. Apply CSS to target HTML tags with IDs and classes.

2. Employ Chrome's Web Inspector to experiment with CSS in the browser.

3. Code the CSS box model by manipulating the height, width, margin, and padding to create containers for a style guide.

4. Build a style guide for the U.S. Postal Service.

5. Demonstrate competency with Google Fonts by adding it to our USPS style guide.

## Class at a Glance

Today you'll discuss the box model and how we use it to display content on the web. The lesson has three learning arcs:

**Part 1: Classes, IDs, Divs, and Section Tags**

You'll cover HTML tags used to build the structure of the web. We'll focus on growing our HTML skills by learning about tags that we use as containers—divs and section tags.

**Part 2: The CSS Box Model**

Students will apply the box model by coding margins and other CSS properties to their HTML containers on their USPS style guide.

**Part 3: Classes and IDs**

Students will practice their CSS by learning how to target IDs and classes with CSS. You'll also discuss margins and padding and how they are used to create a structure that is aesthetically pleasing for the user. Students will practice these skills with style guides and font families.

---


## Prepare for Class

**Review the slides beforehand**.
- [17-Week/01-Slides/17.2 HTML and CSS Box Model Slides](https://docs.google.com/presentation/d/1blcIGbK39lUuYEzLoVLX0OynGNZOy9yWJp0U7pGN4zQ/)

**Prepare for today's demos.**

- You have two five-minute demos today, so run through them in advance:
  - Section 4 demonstrates using Chrome's Web Inspector.
  - Section 14 demonstrates adding Google Fonts.

**HTML—Div and Section Tags**

Many of the student questions at the beginning of today's lesson will be about positioning containers. Make sure you're up to date on the different positioning properties.

- If you need to brush up on your CSS layout skills, please go through the following tutorial:

[Learn CSS Layout](http://learnlayout.com/)

- If needed, review the Strategies for Class Online in the unit README.

---
## Time Tracker

- Be sure to open and follow the [17-Week/03-Time Trackers/17.2 Time Tracker](https://docs.google.com/spreadsheets/d/1-gVnuSumgNMdyBlZnwlqKWdFNfcW6j2jOo--MDnAS64/edit?usp=sharing).

- Use an online timer, which you or your teaching assistant (TA) can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---


## Office Hours: Review and Practice (45 min before class)

> Note: Encourage your students to make the most out of class and not to be afraid to ask questions.
>
> - Do your part by engaging students.

---

## 1. Instructor Do: Welcome and Objectives (5 min)

> :pushpin: **Important Point:** Your goal is to introduce students to the HTML/CSS box model and to help bring organization and structure to their HTML and CSS.

Welcome the class and introduce today's topic: the HTML/CSS box model. 

Open up the [17-Week/01-Slides/17.2 HTML and CSS Box Model Slides](https://docs.google.com/presentation/d/1blcIGbK39lUuYEzLoVLX0OynGNZOy9yWJp0U7pGN4zQ/) for the day.

Put today's lesson in context for students.

**Say,** "Today, you'll build a style guide for the U.S. Postal Service (USPS)."

We'll apply the concepts discussed in class today to create a basic webpage for a USPS style guide. While it might seem simple, there is plenty of work to be done!


Review today's learning objectives.

**Review concepts from the last class.**

> **Instructor Note:** Students who are new to programming will benefit from frequent reviews of what we have covered. Take the time to go over concepts as part of the post-activity recap.
>
> Before you move on to the first lecture of the day, review a couple of concepts from last class and take questions to be sure that the fundamentals of HTML and CSS are sinking in for students.



## SLIDES 1-7
Review


## SLIDE 8
  **What does HTML stand for? How is it used?**

  _Answer:_ Hypertext Markup Language. It is used to create tags that provide the structure for the web.

  **What does CSS stand for? How is it used?**

  _Answer:_ Cascading Style Sheets. CSS is used to style HTML tags.

  **How do HTML and CSS work together?**

  _Answer:_ HTML provides the structure of the web. CSS makes it look and feel good by making it visually appealing as opposed to barebones HTML elements.

## SLIDE 9
Review

**TAs,** share the following resources with students via Slack:
- [W3Schools - CSS Box Model Tutorial](https://www.youtube.com/watch?v=lPm8lK4C7nc)
- [CSS Tricks - The Difference Between IDs and Classes](https://css-tricks.com/the-difference-between-id-and-class/)
- [Stack Exchange - What Is the Difference Between Section and Div?](https://stackoverflow.com/questions/6939864/what-is-the-difference-between-section-and-div)
- [W3Schools - HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

Take any questions students may have about HTML and CSS basics, then move on to the first lecture.

## SLIDE 10
## 2. Instructor Do: VS Code Demo (10 min)

1. Open the [Semantic Sandbox solution pen](https://codepen.io/2u-uxuxi-bootcamp/pen/gOmLENx) in Chrome.

	> **Instructor Note:** Students can open their own saved pens or the solution file.

1. Create a directory structure.

	1. Start with a folder on your desktop that will contain all projects for the bootcamp. Title this folder: `Code`.

	1. Add a folder inside `Code` for this demonstration's project. Title this folder: `VSCodeDemo`. 

1. Set up the project in VS Code.

	1. Open VS Code.

	1. Select <kbd>File</kbd>><kbd>Open Folder</kbd>, then select `Desktop/Code/VSCodeDemo`.

	1. Right-click in VS Code's Explorer pane and select <kbd>New File</kbd>. Name the file `index.html`.

	> :key: **Tech Point:** The main HTML file in a project is always called `index`, because the browser knows to look for a file with that name.

	1. Create a second new file. Name the second file `style.css`.

1. Add HTML elements.

	1. Copy everything from CodePen's HTML panel into `index.html`'s body.

	1. > **Say:** "When working in a real HTML file, we need one extra element to tell the browser which version of HTML we're using."

		Add the doctype for HTML5: `<!DOCTYPE html>`.

		> **Instructor Note:** Students with prior experience in HTML may expect to see other "boilerplate" elements, like `html`, `head`, and `body`. Contrary to popular belief, these are not required. The [official HTML5 spec](https://html.spec.whatwg.org/multipage/syntax.html#optional-tags) lists these as optional, and many code style guides (such as [Google's](https://google.github.io/styleguide/htmlcssguide.html#Optional_Tags)) recommend omitting them.

	1. Open `index.html` in Chrome, showing that it is exactly the same as on CodePen.

1. Add CSS rules.

	1. Add a CSS rule to `style.css`: `p { color: red; }`.

	1. Refresh Chrome to show that nothing has changed. Explain that the CSS needs to be **linked** to the HTML, which is something CodePen was doing automatically.

1. Link the CSS.

	1. Add a CSS link to `index.html`: `<link rel="stylesheet" href="style.css">`.

	1. Refresh Chrome again to show that the CSS is now linked.


## SLIDE 11
Review

## SLIDE 12
Review

## SLIDE 13
To style containers that we create in our HTML, we use two different CSS attributes, the class and ID attributes. Attributes are used to target unique HTML elements, while classes make our CSS reusable and target multiple HTML elements that need the same style.

### CSS Classes

**Class attribute:** A class is an HTML attribute that is used to target multiple elements across the same page using CSS. You specify a class on an HTML element by typing "class" followed by the equals sign with the name of your class between the quotation marks.


## SLIDE 14
Classes are targeted using a dot (.) in a CSS file. After the dot, type out the name of your class to style an HTML element.

:key: **Key tech point:** In the examples above and below, you might have noticed the caps at the start of each word. This is known as camel casing, which makes code more legible. It is a common naming convention in web development.

Think of classes like components in Figma. You create a component once and then reuse it throughout the design. The same concept applies to CSS with UI elements.

For example, consider the button component in the screenshot (Slide 14).

## SLIDES 15-16
**Question:** How many times is it reused on the page (also Slide 14)?
_Answer:_ This component was used four separate times on the page.

Imagine you are coding this page. Would you code each button individually or just once by using a class?


## SLIDE 17
Classes are used to target multiple elements across the same page.

This means that you can reuse a class to apply the same style to all particular elements of a page.

In the picture above, we have the CSS selector of .cities styling two HTML elements with a background-color, font-size, and spacing with margin and padding.

## SLIDE 18
Review

## SLIDE 19
HTML elements can have multiple classes. You can add two classes to an HTML element by simply adding another name for your class after your first.


## SLIDE 20
**Key takeaways for classes:**
- Classes are not unique. Classes are designed to be reused just like components in Figma/Adobe XD.
- You can use the same class on multiple elements.
- You can use multiple classes on the same element.

## SLIDE 21
Review

## SLIDE 22
**ID attribute:** ID stands for an identifier. An ID is an HTML attribute used to create unique instances of a CSS selector. IDs are *unique* to a page, so you can only have one ID per page.

You should not have two IDs that are named the same. Identifiers are very useful when writing jQuery code. IDs will be the primary way that we target HTML elements in jQuery.

## SLIDE 23
IDs are HTML attributes that can be added to any HTML element by typing "id" followed by the equals sign and quotations containing the name of your ID.

## SLIDE 24
With CSS, you target IDs with a hash (#) before the name of the selector.

## SLIDE 25
**Key takeaways for IDs:**
- An ID is a unique instance of an HTML element.
- Each element can have only one ID.
- Each page can have only one element with that ID.

## SLIDE 26
Review

## SLIDE 27
Review

## SLIDE 28
- The section tag needs no explanation, as the name says it all. This tag is used to build specific sections of a webpage.
  - Generally, these containers define the boundaries of your website, and divs are positioned inside them to create content that users interact with.
  - Section tags can be used to define sections in a document, such as footers, hero images, or sections that showcase features or products specifically.
- Div stands for division. Divs are used to create content meant to be positioned inside a container. The div tag is used to group block and inline elements to be formatted with CSS.
- Think of a sign-in form. The form's container is probably a div positioned inside a section.
- Knowing when to use a div or section tag helps students write semantic code—HTML that introduces meaning to the web page rather than just presentation. For example, a p tag indicates that the content within is a paragraph.

This makes your code easier to understand for yourself and your fellow developers by labeling HTML elements with tags that fit what they are.

- For example, an aside element is a sidebar.  

## SLIDES 29-35

## SLIDE 36
## 5. Instructor Do: Demo - Chrome's Web Inspector (5 min)

> :pushpin: **Important Point:** Your goal for this demo is to help students feel empowered to tackle building containers and structure for their USPS style guides. This demo supports learning objective 2: employ Chrome's Web Inspector to experiment with CSS in the browser.

> **Instructor Note:** A common frustration among CSS beginners is that they want to see how it looks immediately after they have made changes, so the "additional step" of refreshing their browser can feel time-consuming.

***Say,*** "It's a drag to reload, but it's the only way—and all developers have to."

Before you begin, put this demo into context by explaining how front-end developers use the Web Inspector to build UIs visually. Earlier in the lesson, we discussed section and div tags. During this demo we'll show students how to use the Web Inspector to apply box model properties to our HTML elements—visually.

- Enter Chrome's Web Inspector tools. The Web Inspector can be used to view CSS visually, and it lets you play with your design.

- The Web Inspector is a game-changer. It allows you to see what you are doing when you apply specific CSS properties.

:gem: **Designer Insight:** Reinforce the importance of this demo by telling students that designers in the real world use Google Chrome's Web Inspector. For example, a professional front-end developer will use the Web Inspector to visually build out a website's CSS, then copy-paste it into their CSS (you're about to demo this concept). Professional back-end developers will use the Web Inspector to check their page for errors with data transfers.

In Chrome, to view the Web Inspector, you can do a couple of things:

- Right-click on an element and click inspector.
- Use the hotkey (Mac: CMD + Option + i; Windows: Shift + ctrl + i).

Once you have the Inspector open, you will see the following interface:

![Web Inspector interface](Images/webInspecter_annotated.jpg)

**Walk through the following annotated Web Inspector image:**

- Open webInspecter_annotated.jpg in front of the class.

![webInspecter_annotated.jpg Location](Images/webInspecter_annotated.jpg)

**Instructions:**
  1. This is the elements panel. It is used to go through all the HTML structure of a page.
  2. This is the console panel. It is used to check for errors on your page. It will be used more when we talk about JavaScript. However, it can display errors related to improperly linked images and CSS files.
  3. This is the styles panel. It displays what styles are being inherited by your HTML elements.
  4. This is the box model panel. You can see margin and padding that is applied to your elements in a visual manner. It also shows how these properties interact with your object.
  5. This is the element style panel. You can use it to apply inline styles to your elements. When you reload the page, however, your styles will reload back to what's in your CSS file.
  6. Add styles by clicking between the brackets { }.
  7. You can also add styles directly to the selectors you write in the CSS file. Click in the brackets to modify CSS rules and you will see the effects applied to the site as if they were written in your CSS file.

**Demo Chrome's Web Inspector tool for the class.**

> **Instructor Note:** During this demo, the goal is for students to see how you can use Chrome's Web Inspector to test CSS and to build out front-end websites visually.

**Instructions:**

1. Open the index.html file located in [17-Week/02-Day/Demos/Web_Inspector_Demo/index.html](https://github.com/coding-boot-camp/ux-ui-curriculum-version2/tree/master/01-lesson-plans/17-Week/02-Day).  
2. Open the style.css file located in [17-Week/02-Day/Demos/Web_Inspector_Demo/css/index.html](https://github.com/coding-boot-camp/ux-ui-curriculum-version2/tree/master/01-lesson-plans/17-Week/02-Day).   
> **Say:** "When writing front-end code, you should split your HTML and CSS files so you can code them in plain view of each other."
3. Right-click on the style.css tab and click split right from the drop-down menu.

  ![Visual Studio Code split files](Images/splitRight.png)

  Your workspace should now look like the following:

  ![Visual Studio Code after split](Images/workspace_split.png)

  **Say,** "Now, we can view both our HTML and our CSS while we work. Generally, you want to pre-write your CSS selectors (classes & IDs) before you start styling."

  ![CSS selectors](Images/css_nostyles.png)

  4. Open the index.html file in Google Chrome.
  5. Right-click on the picture of the person and click inspect. The Inspector window will pop up to the right (default).
  6. Click on the div with the class of ```.styleMe```.

  ![Style Me HTML element](Images/styleMe.png)

  **Say,** "Notice how the Web Inspector can see that we have written a selector without any styles."

  7. Type out the following CSS properties into the ```.styleMe``` selector.

  ```css
    .styleMe { 
      outline: 1px solid red;
      width: 500px;
    }
  ```

  **Say,** "Notice how the changes we make happen in real time right before our eyes."

  8. Highlight the CSS you wrote in ```.styleMe``` and copy it. Paste it into your CSS file. Save your file and reload your page.

  9. Hover over the ```.styleMe``` HTML element with your mouse and show the class that you can visually see the box model.

  ![Web Inspector box model example](Images/webInspector_boxmodel.png)

  - Alternatively, you can click the arrow on the top left of the Web Inspector panel and hover over elements on your screen.

> **Instructor Note:** the elements panel can be used to locate elements in your HTML. You always have the option of right-clicking and hitting inspect again to view the CSS of whatever you are inspecting.

  10. Tell the class that the web is literally made up of boxes. Even shapes that don't appear to be boxes are, in fact, boxes.

  **Say,** "You can use the Web Inspector to style and experiment with CSS code."

> **Instructor Note:** Students need to play with CSS in the Web Inspector. It helps their understanding of how CSS works by letting them see the results of their code visually in front of their eyes.

Now that students have seen how they can use the Web Inspector to build front-end webpages, it's time for them to test their skills by building HTML content for their USPS style guide.


## SLIDE 37
Review

## SLIDE 38
## 6. Student Do: Containers and Structure Activity (40 min)

**TAs,** share a copy of the activity with the class: [17-Week/02-Activities/17.2/17.2-01 Containers and Structure](https://docs.google.com/document/d/1APsBg734B73WG3vo7kMRT6hHRqOFBfCGYj427TnNxSk/).

**Summary**

Students put their HTML skills to the test by adding structure to a style guide.

**Instructions**

First, students will open their index.html file and their style guide .xd file. Next, they will add section tags to their style guides.

*If students struggle with this activity*: First, double-check student tags for syntax errors. Second, check if a student has constructed their HTML as described in the activity document. As an instructor, you can lean on the solved file to showcase to students how their HTML was supposed to be constructed. Alternatively, encourage students to Google anything they are ensure of. Internet research is a normal part of developers' workflow. For example, if a student doesn't know what a break tag is, they can search for “break tag w3schools.” W3School is an excellent resource for complete beginners to HTML / CSS. 

*If students finish the activity early*: If students finish early, have them research CSS selectors, as they will be applying them in later activities during this lesson.

**Be available to students.**

Monitor students and offer help where needed, but also encourage them to look up tags or documentation during this activity.

**Deliverable**

When all tags in the activity file have been added, students’ work is done.

## SLIDE 39
## 7. Instructor Do: Containers and Structure Activity Review (5 min)

Call attention back to your screen and lead a review of the container and structure activity.

Provide actionable feedback that students can use, for example:

- Knowing when to correctly use section and div tags will help even long HTML files be more digestible for yourself and colleagues.

- Always double-check your HTML structure for closing tags. Getting in the habit of closing a div (or section) tag whenever you create one will save you time debugging your HTML.

- Learning how to construct HTML tags will help you build designs you create yourself later on down the road.

To test the students for competency, ask them the following questions about div and section tags:

- What is a div tag used for? When should you use this tag?

  - Answer: A ```<div>``` tag is used to create UI elements on a page. A ```<div>``` could be anything you want it to be.

- What is a section tag used for? When should you use this tag?

  - Answer: Sections are used to create whole sections of webpages. Sections contain ```<div>``` that all relate to the overarching theme of the section.

- How can you use div and section tags together?

  - Answer: Sections are used to create themes for groups of content on a page. ```<div>``` are then created inside the section to create content for our section.

Students now understand how div and section tags are used to bring structure to the content on a webpage. They're ready to add an additional structural element to their work with containers—that's next, after the break.

## SLIDE 40
## 8. Break (15 min)


## SLIDE 41
Review

TAs, share the following resources with your class:
- [MDN - CSS Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
- [internetingishard - CSS Box Model](https://internetingishard.com/html-and-css/css-box-model/)
- [CSS Tricks - CSS Box Model](https://css-tricks.com/the-css-box-model/)
- [W3Schools - CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)

The web is made up of boxes. We saw this concept earlier during the Web Inspector tutorial.

## SLIDE 42
CSS Box Model: Each HTML element you create in your HTML file is represented as a rectangular box, with the box’s content, padding, border, and margin built up around one another like the layers of an onion. 

CSS calculates all the boxes on the page to display the content.

## SLIDE 43
Each HTML element you create in your HTML file is represented as a rectangular box. The box's content, padding, border, and margin are built up around one another like the layers of an onion. All the box's CSS calculates on the page to display the way content lays out on a page.

- Go to any webpage and use the Chrome Inspect tool.

  - Point out the box model.

- The web is made of a bunch of boxes.

  - CSS treats each element in your HTML document as a box with a bunch of different properties that determine where it appears on the page.

    - Understanding this idea will help you become a much better CSS developer and a better UI designer.


## SLIDES 44-45
Review


## SLIDE 46
Let's walk through the properties that affect the box model:

1. **Content inside your containers:** Text and images will both cause your box to expand to contain the content inside. The height and width can also be explicitly defined by setting a height and width for a container.
2. **Height/width:** Adding height and width to any of your elements will cause it to expand depending on what properties you set.
3. **Padding:** Padding properties are used to expand space *inside* the box model. This is fundamentally the opposite of margin, which creates space outside the element.
4. **Margin:** Margin properties are used to create space *outside* elements. Margin will move your box away from other elements that surround it.

- The box model is the building block of CSS. Everything you see on the web is a rectangle.


## SLIDE 47
Review

## SLIDE 48
## 10. Student Do: Apply the CSS Box Model Activity (25 min)

**TAs,** share a copy of the activity with the class: [17-Week/02-Activities/17.2/17.2-02 Apply the Box Model Google Doc](https://docs.google.com/document/d/10oOl6ISjokvHhXa52HcVqdT4YvYXDx2vnE5wk_yx0Pg/).

**Summary**

Students will create a box model of their USPS style guide, giving structure to their content.

**Instructions**

Students will start by opening their style.css file. From there, they will add various elements to create their box: header, primary colors, typography, and UI elements.

*For students who struggle*: Double-check students' CSS to make sure they are using the correct CSS selector. Students may target a class using a dot (.) instead of a hashtag (#) or vice versa. If students are having trouble building out their layout, lean on the solved file to show the student what CSS properties are used to build out the HTML element the student is tripped up on.

*For students who complete the activity early*, encourage them to study the box model and the differences among inline, block, and inline block level elements, as they are directly related to one another

**Be available to students.**

With TAs, keep an eye on students as they work through the activity. Point them to the links to documentation resources in the activity file as needed.

**Deliverable**

Once students have added all the elements listed in the activity document, they’re done.

## SLIDE 49
## 11. Instructor Do: Apply the CSS Box Model Activity Review (5 min)

Call attention back to your screen and lead a review of the box model activity.

Provide actionable feedback that students can use, for example:

- The box model is a fundamental concept for building HTML elements.
- Content inside containers can have their height and width defined by the content inside of them. Setting height and width to a fixed pixel width can cause content to break outside of its container.

> **Ask:**

- **What CSS properties affect the CSS box model?**
  _Answer:_ Height, width, border, margin, and padding.

- **What is the difference between margin and padding?**
  _Answer:_ Margin affects the space around the element; padding affects the inside of our element.

> **Instructor Note:** Take questions: Be sure that all students have had an opportunity to ask questions before moving on to the next activity.

## SLIDES 50-51
## 12. Student Do: Style Our Style Guide Activity (10 min)

**TAs,** Slack out the following instructions to students: [17-Week/02-Activities/17.2/17.2-03-Style Our Styleguide Google Doc](https://docs.google.com/document/u/1/d/10ZDF6o2hg9Mwhl7uvmahfgPTPLDeycRUmKma_IKhp-E/).

**Summary.**

At this point, the students’ style guide is structurally sound, but it lacks color. Now they will use CSS to add color to their HTML elements.

**Instructions**.

First, students will open their style.css file. Next, they will add selectors for a variety of colors according to the activity file.

*For students who struggle with this activity*: It is common for students to write incorrect selectors during this activity, so keep an eye out for IDs that should be classes (and vice versa). Sometimes students will also type out CSS properties incorrectly. For example, a student might type out font-color as opposed to just color. If you encounter students incorrectly writing CSS properties, tell them to Google their problem—use Google to search for "CSS font color property."

*If students complete the activity early*, ask them if there is anything different in terms of the design of the site. Tell the students to practice their UI or front-end skills by redesigning the Adobe XD file located here: [17-Week/02-Activities/17.2/17.2-USPS-Style-Guide.xd](https://drive.google.com/open?id=1fHOaNCrTEWmZy6orEvnO1xRQD0iX-P5B) or by practicing their front-end skills by continuing to style and alter the USPS style guide.

**Be available to students.**

Monitor students' progress throughout the activity. Demo the code on your own machine if that will help students.

**Deliverable.**

Students will share a screenshot of their work via Slack.

Before we move onto the next topic, let's take a moment to review what we just learned.

## SLIDE 52
## 13. Instructor Do: Style Our Style Guide Activity Review (5 min)

Call attention back to your screen and lead a review of the style guide activity.

*Place this activity in the context of something designers do every day on the job*: At the completion of this activity, students will have gone through a very realistic experience of work a junior front-end developer might do. Students have:
1. Created HTML from a design file (it's also realistic for students to have created the design themselves, then built it).
2. Styled their HTML to match the design file.

Review the work of two to three students, and consider the following questions as the basis for discussion.

> **Ask:**

- What do we like about this style guide?
- What could be done differently in an iteration of this style guide?

Be sure to provide feedback that is actionable, for example:

1. Building the HTML first makes styling UIs easier later on.
2. Always make sure students use the appropriate selector when targeting HTML elements. Students will often mistake classes for IDs when writing CSS selectors (and vice versa).

Invite the TAs to comment as well.

> :gem: **Designer Insight:** This is a great moment to share your professional experience with style guides or a story from your first attempt at a style guide.

Next, you're going to move on to adding font families with Google Fonts to our webpage.


## SLIDE 53
Review

## SLIDE 54
Fonts have a powerful effect on users. An effective font can completely alter the "personality" of a design or webpage and even be what subconsciously keeps a user on a site for a longer period of time.

Websites look better with custom typography—think of a design file. Designs are always better when designed with custom typefaces and color. Imagine trying to create beautiful UI work if your only choices are Arial and Helvetica, 16-point font, and black as your only color.

Arial and Helvetica are the default fonts on the web. In the past, you were forced into choosing between 15 "web-safe" fonts depending on your browser. Web-safe fonts are fonts that come installed into the browser by default.

Google realized this and created [Google fonts](https://fonts.google.com/).

Google Fonts allows you to host any font that is hosted on their servers on your webpage. They also have literally a thousand fonts for you to pick from that allow you to customize your webpage.


## SLIDE 55
## 15. Instructor Do: Demo - Adding Google Fonts to Your Webpage (5 min)

Give students a quick demo of how easy it is to add Google Fonts to a webpage.

**Say,** "What I'm about to show you will be very easy for you to execute on your own."

Google Fonts are so easy to use, students can add them to their website in three easy steps!

![Google Fonts visual walkthrough](Images/google_fonts_annotated.jpg)

**Instructions**

1. Open the solved ID and classes activity: [02-Day/Activities/04_Add-A-Custom-Font/solved/index.html](..//02-Day/Activities/04_Add-A-Custom-Font/solved/index.html).  

2. Open [https://fonts.google.com](https://fonts.google.com).
3. Pick a font you like by pressing the + button.
4. On the bottom right, you will see the font you selected and a link tag.
5. Copy the link tag.
6. Paste it over the custom style sheet.
7. Open index.css located in the CSS folder.
8. Create a CSS selector that targets the body tag:

```css
body {

}
```

9. Add the font-family for the custom font to the body tag. Here is an example:

```css
body {
  font-family: 'Open Sans', sans-serif;
}
```

10. Be sure to tell the students that they can add as many fonts as they want, but too many will slow down the website.

Easy, right?

Google Fonts allow you to host any font that is hosted on their servers on your webpage. There are nearly a thousand fonts for you to pick from, allowing you to customize your webpage like a pro!

## SLIDE 56
Review

## SLIDE 57

## 16. Student Do: Custom Fonts on Your Webpage Activity (15 min)

**TAs,** Slack out the following instructions to students: [17-Week/02-Activities/17.2/17.2-04-Custom Fonts On Your Webpage](https://docs.google.com/document/d/1USDlv3FePscFqtPjs2-bL2BfBCDB-DzfVVUbisOI1do/).

**Summary**

Students will add a font from Google Fonts to their webpage, then style it with CSS, using the activity instruction doc as their reference.

**Instructions**

In Part 1, students will add a Google Font to their index.html file.

In Part 2, students will add CSS to their page.

*If students finish early,* you should recommend that they start or continue to work on their homework. Students now have the basic skills needed to create the base HTML/CSS of their portfolio page.

**Deliverable**

Students will have added a font to their webpage (no need to share anything in Slack).

**Support students as they work.**

With TAs, monitor students' progress and pause to help students who seem to get stuck. Remind them to use Google or a classmate as resources, too.

## SLIDE 58
## 17. Instructor Do: Custom Fonts on Your Webpage Activity Review (5 min)

Call everyone's attention back to your screen and lead a discussion of the custom fonts activity.

> **Instructor Note:** Encourage students to explore Google Fonts further at home. 

- **TAs,** Slack out 20 Best Web Fonts From Google for students to read a home: [https://www.awwwards.com/20-best-web-fonts-from-google-web-fonts-and-font-face.html](https://www.awwwards.com/20-best-web-fonts-from-google-web-fonts-and-font-face.html).

Some questions you could ask to stimulate reflection and conversation:

- "What is the CSS box model? Why is it important to understand it?"
  - _answer:_ The box model is how the browser renders elements of HTML and CSS. Developers can control each parameter of the box.
- "Why would you want to reset your browser-specific styles?"
  - _answer:_ Unfortunately, not every web browser renders your CSS the same way. Just try viewing a webpage in explorer 10 vs Safari vs Chrome. 
- "What is the Web Inspector? How do front-end developers use it?" 

  - _answer:_ Web development tools allow a web developer to use the DOM to quickly render a webpage element and test front-end styles quickly. 

- "What is the difference between a ```<section>``` tag and a ```<div>``` tag ?"

  - _answer: The ```<section>``` tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document, whereas the ```<div>``` tag defines a division in an HTML document. The ```<div>``` tag is used to group block-elements to format them with CSS. Think of it like parent-child. ```<section>``` is the parent and ```<div>``` is the child. 

> **Instructor Note:** Pause for questions.
>
> This is the final section of the class, so be sure to invite students who want feedback on their work to stay online for office hours.

Thank students for their hard work and move on to review the concepts learned today.

## 18. Instructor Do: Recap and End Class (5 min)

We covered a lot of concepts today, so let's do a quick recap.

**Review the concepts students learned today.**

Spend a couple of minutes helping students anchor today’s learning. Ask students to raise their hands—or post answers in Slack—and offer definitions for the following concepts, all learned today in class:

- "What is the box model? Why is it important to understand the box model?"

  - Answer: The box model is four CSS properties that create the containers of HTML. It is important to understand because everything you build revolves around the box model.

- "What is the Web Inspector? How do front-end developers use it?"

  - Answer: The Web Inspector is a tool used to inspect HTML in your web browser. Front-end developers use it to test out CSS properties and JavaScript on their website before making it live.

- "What is the difference between a div tag and a section tag? When should you use a div tag? When should you use a section tag?"

  - Answer: Sections are used to create themes for groups of content on a page. Divs are then created inside the section to create content for our section.

Well done!

Let the class know that they'll be learning more about CSS and HTML next class.

Say good night and dismiss the class.

---

## We Want Your Feedback!

Instructor, how did class go?

Please submit any issues or comments on the UX/UI curriculum to our Google Form:

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

View the status of your submission and other issues here:

[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing)

---

## Copyright

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
