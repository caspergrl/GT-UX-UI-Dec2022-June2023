# 20.1 Lesson Plan: Introduction to Bootstrap 4

---

## Overview

Today you'll teach students about content delivery networks (CDNs), specifically Bootstrap. You'll show how to use Bootstrap's built-in column media queries to control layouts and explain the importance of acquiring these skills.

Unit 20 comprises three lessons that provide the instruction and practice for students to capably work in Bootstrap. In Lesson 20.1, you'll introduce Bootstrap 4 and show students how to use it to create prototypes. In Lesson 20.2, students will learn how to overwrite Bootstrap component's CSS to customize a Bootstrap 4 template so that they can create custom websites. In Lesson 20.3, students will practice the role of freelance web developer by exporting web-ready images from a design. Students will then use the assets to create a design file based on a prompt.

## Learning Objectives

By the end of class, students will be able to:

1. Link Bootstrap 4 to an HTML page through their first CDN.
2. Explain how Bootstrap 4 CDNs save developers time during the web development process.
3. Code an HTML/CSS webpage using Bootstrap 4 components.
4. Create a fluid layout with the Bootstrap 4 built-in col system.
5. Build a desktop layout with three columns in Bootstrap using its built-in 12-column grid and user interface (UI) components.

## Class at a Glance

Welcome to Lesson 20.1.

Today's lesson covers three key topics:

**1. Bootstrap components**

In the first section, you'll introduce students to the basics of Bootstrap. First, you'll teach the class how to use Bootstrap on the students' site by linking to it.

Afterward, you'll introduce students to Bootstrap components and show them how easy it is to start using Bootstrap.

**2. Bootstrap columns and rows**

In the second section, you'll show how to add Bootstrap-specific containers and rows to templates.

**3. Bootstrap col classes**

In the third section, you'll discuss using Bootstrap's responsive classes—the column system. The column system is very powerful and can make a site completely responsive without any CSS.

---

## Instructor Notes

Many of our activities were written for in-person classes, so we've added in-line callouts (usually indicated by this icon: > :globe_with_meridians: **Online Recommendation** to let you know how to adapt an activity for online delivery.

Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.

> :globe_with_meridians: **Online Recommendation**: Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here are some examples of what you can say during common transitions:
- From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”
- From sharing the slideshow to sharing a tab on your browser: “Bear with me as I switch over to my browser for the next demonstration.”

> :globe_with_meridians: **Online Recommendation**: Transitions and activities tend to take longer in virtual classrooms. If you find that you are running short on time, feel free to combine or shorten activity reviews. 

## Prepare for Class

**Review the slides beforehand**.
- [20-Week/01-Slides/20.1-FE-Dev-Bootstrap-4](https://docs.google.com/presentation/d/1CUlPiPxcUA1K5yI2YJnKpN5aCB3Ahm3lx4Rl3F9xDMc/edit?usp=sharing)

- Make any teaching notes you'll need.

- As you lecture, relate your own on-the-job experience whenever possible to bring what students are learning to life and connect it to their future goals.

- Look for the :gem: icon, which prompts you and/or a TA to share professional anecdotes directly related to a particular concept.

**Bootstrap 4**

Bootstrap 4 is widely used in the web world and often listed on job postings. Learning Bootstrap is invaluable, as many companies use it.

- It is a particularly useful tool for user experience (UX) developers who aren't specifically front-end developers.
- Bootstrap is used to build responsive websites quickly without having to write media queries to control what it looks like at different browser widths.

If you need a working knowledge of Bootstrap, please review the following:
- [Bootstrap's Getting Started Guide](https://getbootstrap.com/docs/3.3/getting-started/) provides an overview of how Bootstrap works conceptually.
- [Bootstrap's Grid System](https://getbootstrap.com/docs/3.3/examples/grid/) provides an overview of how Bootstrap's grid system functions.
- [Bootstrap's Prebuilt Components](https://getbootstrap.com/docs/3.3/components/) provides an overview of what components are and how you can use them.

_TAs should review the Bootstrap documentation, too, time permitting_.

**You'll lead five Bootstrap 4 demos.**

There will be a lot of copying and pasting of components to see how they work. To prepare before class, be sure to run through each Bootstrap 4 demo on your own:
- Components Demo (Section 3)
- Navigation Bars Demo (Section 7)
- Containers, Rows Demo (Section 11)
- Bootstrap's Col Class Demo (Section 13)
- Cards Demo (Section 18)

Download the demo files here: [20-Week/05-Instructor Resources/20.1_Demo_Files](https://drive.google.com/drive/u/1/folders/19JqnJPwsDhnIbKXz1BABepHY2zyjKV5p).

If you need a refresher on how to use Bootstrap, review the solved activity folder [01-Day/Activities/Bootstrap_Components/Solved/index.html](01-lesson-plans/20-Week/01-Day/Activities/Bootstrap_Components/Solved/index.html). This solved file reflects what students create after this class is over. 

- If needed, review the Strategies for Class Online in the unit README.

---


## Class Materials

Download the activity zip files before class.

- See the solved folder and files located in the UX/UI repo for each activity see 20-Week/01-Day/Activities/ if you need something to reference for yourself or a student during the activities.

## Time Tracker

- Keep track of the clock. Have TAs consult the [20-Week/04-Time Trackers/20.1 - Time Tracker](https://docs.google.com/spreadsheets/d/1J7cdxwLIcjmx3Fk_4IlFpfvMWEnbyL4BLVHHSQTb0oE/).

- If your class is on a Saturday schedule, use the flex time for extending lectures, activities, or review sessions. 

- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---


### Office Hours: (45 min before class) (Office Hours)

Encourage students to come early and utilize the time provided and not to be afraid to ask questions.

> Instructor Note: Do your part by engaging students who come early and participate in office hours.

---

## 1. Instructor Do: Welcome and Share Today's Objectives (2 min)

Welcome the students to Week 20! 

Open and download today's slides. TAs should share a pdf of them with the students via Slack. 
[20-Week/01-Slides/20.1-FE-Dev-Bootstrap-4](https://docs.google.com/presentation/d/1CUlPiPxcUA1K5yI2YJnKpN5aCB3Ahm3lx4Rl3F9xDMc/edit?usp=sharing)

**Give an overview of the day.**

**Say:** "Today, we'll talk about Bootstrap 4, a CSS framework used to rapidly create responsive prototypes."

Bootstrap 4 is a content delivery network (CDN); otherwise known as a library. Bootstrap 4 components can be imported on your page using link and script tags.

We'll cover the essentials of how to use Bootstrap, a much easier tool to learn than CSS because it is so straightforward.

There will be many in-class activities today and students will put together a complete template using Bootstrap 4 components.

**Review today's learning objectives.**

Walk through the learning objectives slide. Convey excitement that students will be working toward creating websites!

> 💎 **Designer Insight:** Share your personal experience with Bootstrap or your perspective on how Bootstrap 4 affects designers. You could ask the TAs to share their own stories about Bootstrap 4.

Get started by introducing the class to Bootstrap 4.

## 2. Instructor Do: Introducing Bootstrap 4 (5 min)

> 📌 The goal of this section is to introduce students to the concept of CDNs and Bootstrap 4 in particular. This lecture and the demo that follows will prepare students to tackle today's first and second learning objectives, linking Bootstrap 4 to an HTML page through a CDN and being able to explain how the Bootstrap 4 CDN saves developers time during the web development process.



Bootstrap 4 is used to create front-end prototypes rapidly. Bootstrap is a common framework in the professional world of web development. This framework enables students to create designs that use both Bootstrap 4 components and the responsive col class system.

Tie what students have learned about UX/UI in this boot camp to what they're learning today. For example:

- In Unit 3.3, students learned about low-fidelity prototyping. Bootstrap 4 is a quick way to build testable prototypes before you turn a prototype into a full-color webpage. 

- In Unit 10.3, students learned about components and multistate elements, both of which are used in Bootstrap, further speeding the development of front-end prototypes.

## SLIDES 1-11
Review

## SLIDE 12
**Bootstrap** is an open-source front-end UI framework for developing front-end websites with HTML, CSS, and JavaScript. 

## SLIDE 13
With Bootstrap, developers can prototype ideas quickly or build entire apps with Bootstrap’s responsive grid system, prebuilt components, and plugins built on jQuery, creating fully responsive templates.

## SLIDE 14
### What's a Framework?

## SLIDE 15
A **framework** is a codebase written to simplify common problems in a programming language.

We can compare a framework to a collection of tools. If you were a carpenter, you would have a set of specialized tools used to speed your carpentry work. A framework is the same—tools designed to solve a specific problem. For example, with Bootstrap 4, developers can create responsive websites with literally zero CSS (it has already been written; the developer just has to leverage it). The developer's tools would be the components and responsive column system speeding the workflow.

Software frameworks are written so developers can focus on meeting deadlines rather than re-creating common system processes. Why reinvent the wheel when the problem has already been solved multiple times by other devs?

Frameworks are hosted on CDNs, which we'll define in a moment. First, let's discuss the pros and cons of a framework.

## SLIDE 16
### Using Frameworks: Pros and Cons

Pros:

- Include predefined classes and functions that can be used to design web applications
- Streamline the development process

Cons:

- Lock development teams into a codebase
- Harder to customize and refactor code

## SLIDE 17
### Front-End Frameworks

There are many types of front-end frameworks. Bootstrap is the most popular, which is why we teach it in this class.

**TAs:** Slack out some different front-end frameworks for student to review at home:

- [Bootstrap](https://www.getbootstrap.com) - UX/UI focus.
- [Materialize CSS](https://materializecss.com/)
- [Semantic UI](https://semantic-ui.com/)
- [Material UI](https://v0.material-ui.com/#/)
- [ZURB Foundation](https://foundation.zurb.com/)
- [Pure CSS](https://purecss.io/)

## SLIDE 18
**Reason 1:** Bootstrap 4 has been the most popular CSS framework on the web since its inception in 2011. According to builtwith.com, Bootstrap 4 runs on about 20+ million websites. Students can see for themselves (and share with the class): [Twitter Bootstrap 4 Usage Statistics](https://trends.builtwith.com/docinfo/Twitter-Bootstrap). Once Bootstrap 4 is active, you can simply copy snippets from the documentation to save yourself the time it takes to create elements from scratch!

## SLIDE 19
**Reason 2:** Bootstrap 4 is mobile-responsive by default with its custom columns system. This means that your website will automatically look great when viewed on screens ranging from monitors to tablets to phones.

## SLIDE 20
**Reason 3:** Bootstrap 4 has many features and is easy to use. Familiarize yourself with the UI features Bootstrap offers by reading the [Bootstrap 4 documentation](https://getbootstrap.com/docs/4.4/getting-started/introduction/). Also, once Bootstrap is active, you can simply copy snippets from the documentation to save yourself the time it takes to create elements from scratch!

**TAs:** Slack out Bootstrap 4's documentation with the class: [Bootstrap 4 documentation](https://getbootstrap.com/docs/4.4/getting-started/introduction/).

## SLIDE 21
Review

## SLIDE 22
### What is a CDN?

Bootstrap 4 (and frameworks in general) are hosted on a CDN (a.k.a. framework or library). Many of today’s most popular and powerful web technologies are frameworks built for developers by developers to speed their workflows.

## SLIDE 23
CDNs are servers (or data centers) that publicly host files that contain code.

To conceptually understand what a CDN is, use an analogy:

Let's use your TV or Smartphone as an analogy. Your TV comes with standard programs (programming languages installed in your TV), but what if you want to add to the functionality of it? You install other software onto your TV to extend the functionality (e.g., Netflix). The same is true for CDNs—CDNs serve content directly to our website over the internet. You "install" a CDN by linking to it.

These code-containing files can be imported into programs or websites, allowing them to use the JavaScript functions or, in our case, HTML/CSS files.

Why that's helpful to us: As long as your site is connected to the internet, you can import a CDN's code into your webpage without actually installing the framework into your working files. The webpage doesn't have to worry about running slower due to having more stuff to load and you don't have to manually update the code—the developers of the CDN do that for you.

- **TAs:** share this link by Cloudflare: [What is a CDN?](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/)

> :key: **Key Tech Note:** Bootstrap 4's website is a CDN. CDN stylesheets are publicly accessible over the internet and free to use! Take, for example, node.js, Bootstrap 4, or react.js—all are frameworks that save developers time by adding functions that solve common problems on the web.

**Instructors:** Open up the following link in front of the class showcasing a Bootstrap 4 CSS file hosted on Bootstrap 4's CDN: [Bootstrap 4 CDN](https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.css).


## SLIDE 24
Review

## SLIDE 25
## 3. Instructor Do: Bootstrap 4 Components Demo (5 min)
### Demo Instructions

1. Download and open the instructor demo file located at [20-Week/05-Instructor Resources/20.1_Demo_Files/1_Jumbotron](https://drive.google.com/drive/u/1/folders/1nkNMqu7nZvGSYuflnVK1Ix3Me__e7VX2).

1. Open the [Bootstrap Quick Start Guide](https://getbootstrap.com/docs/4.3/getting-started/introduction/) in your browser.

	![Bootstrap Step 1](Images/Bootstrap_1.png)

1. Copy the link to the CSS file and paste it into your code on Line 10.

1. Click on **Components**.

	![Bootstrap Step 2](Images/Bootstrap_2.png)

1. Click on the jumbotron in the list.

	![Bootstrap Step 3](Images/Bootstrap_3.png)

1. Copy the code below and paste it into your HTML to see the jumbotron appear. Paste the code on Line 20.

	![Bootstrap Step 4](Images/Bootstrap_4.png)

1. Open the index.html file in your browser.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen.
>
> Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

We’ve covered the concept of Bootstrap 4 components. Hopefully, students now appreciate how easy and effective this content management tool is. Next, they get to apply it themselves with a hands-on Bootstrap 4 activity.


## SLIDE 26
## 4. Student Do: Getting Started With Bootstrap 4 Activity (5 min)

> :globe_with_meridians: **Online Recommendation:** This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.1/20.1-01-Getting started with Bootstrap 4](https://docs.google.com/document/d/1SKEcLwbDtsEV5thE_Ib15DLLojhmNBC9acdfJhl9Gks/edit?usp=sharing).

### Summary

This activity will be students' introduction to a CDN, which they should find surprisingly easy. In this activity, they'll also use their first Bootstrap 4 component.

### Instructions

First, students will connect to the Bootstrap 4 CDN using a link tag. Next, students will add their first Bootstrap 4 component to a webpage—a jumbotron.

*If students struggle:* First make sure students have correctly linked to Bootstrap 4's CDN with a link tag. Check the placement of the component; this should be an easy copy and paste. Make sure students open the correct file in their web browsers.

*If students complete the activity early:* Start a conversation with these students about their portfolio or conceptually how components are similar to symbols in Adobe XD.

### Instructors and TAs

> :globe_with_meridians: **Online Recommendation**: Be sure to check your #ClassActivities Slack channel for questions while students are working and provide feedback.

With your TAs, offer help where needed. Encourage students to help one another, too.

Students might encounter the following common problems:
1. They might place Bootstrap 4's link tag in the incorrect location.
2. They might open the incorrect index.html file to view their results.

### Deliverable

A webpage with a basic jumbotron component will display on the screen.

## SLIDE 27
## 5. Instructor Do: Getting Started With Bootstrap 4 Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.

**Review Students' Experience**

Call the class back to attention so that you can lead a review of the Bootstrap 4 activity.

Ask the students if they have finished the exercise before asking a volunteer to share their work.

Have two or three students take turns sharing their work by hosting it on GitHub Pages or sharing a zip and discuss the questions that arise.

Offer students actionable feedback that they can apply to their work. For example:
1. Getting started with Bootstrap is easy—you can even find prebuilt Bootstrap templates to get you started if you're in a rush.
2. Just because you use Bootstrap 4 on your site doesn't mean that you can't use the stuff we learned previously. All concepts taught before Bootstrap 4 can be applied to this section.

Next, lead a review of the concepts that students just practiced:

**Ask:**

- "What does CDN stand for? What do CDNs do?"

	_CDN stands for content delivery network. CDNs host files that can be imported into your website._

- "What is a Bootstrap 4 component?"

	_A Bootstrap 4 component is a prewritten piece of code that is copied and pasted and then customized on your website._

- "Why is Bootstrap 4 useful?"

	_Bootstrap 4 greatly speeds development time by giving you prebuilt components and CSS properties to make your website responsive._

Take a moment to give students a sense of some common misconceptions or FAQs about getting started with Bootstrap 4. For example:
1. Bootstrap is used to speed your development process, but without hard work, your design will still look like a template.
2. You can overwrite CSS or JavaScript properties on any Bootstrap components. They're prebuilt to get you started faster, but you can still customize them to your satisfaction.

Let's move on, build on our knowledge, and add another Bootstrap component to a webpage: a navbar.

## SLIDE 28
Review

## SLIDE 29
A **prebuilt navigation component** is a navbar (the layout depends on the navbar you use) that comes with prebuilt functionality. Prebuilt navigation components will be responsive and have drop-down menus already coded. All you need to do is style your navbar to make it your own.

Navbars are essential; they're literally on every webpage in some way, shape, or form. 

## SLIDE 30
For example:

1. On a shopping website, the navbar may have two or three main menus and more depth, with sub-menus, such as those on Ikea's website. Ikea's site has two top-level navbars, one for general customer service topics and a second one for sale items and new offers.

## SLIDE 31
2. On a personal website, the navigation might be a horizontal bar across the top of the page, showing About, Shop, Blog, and Work With Me.

## SLIDE 32
3. On mobile, the navbar is a hamburger menu.

Adding a navbar to a template is necessary for a site to be fully functioning. Without navigation, users will view your website as a landing page.

Building a custom navbar into your website is a time-consuming process. There are so many HTML elements to build and style, and that is not even counting making it responsive. With Bootstrap 4, all you need to do is remove elements you don't need.

## SLIDE 33
Review


## SLIDE 34
## 7. Instructor Do: Navigation Bars Demo (5 min)
In this demo, show students how to add a navbar to a template.

1. Download and Open the instructor demo file located at [20-Week/05-Instructor Resources/20.1_Demo_Files/2_Navigation](https://drive.google.com/drive/u/1/folders/1JTUuVwQ_V-63wXYfru_AWiVFg2J1SHIE).

1. Open Bootstrap's [Getting Started Documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/).

3. Navigate to Bootstrap's [Navbar Component](https://getbootstrap.com/docs/4.3/components/navbar/).
4. Copy the code for the first navbar on the list.
5. Paste it into your code under Line 17.
6. Reload the page to show the component to the class.

Students will explore navbar components in the next activity.

> Instructor Note: Take questions.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen.
>
> Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

Now it is the students' turn to add a navbar to a template in the following activity.

## SLIDES 35-36
## 8. Student Do: Add a Navigation Bar Activity (10 min)

> :globe_with_meridians: **Online Recommendation**: This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.1/20.1-02-Bootstrap-4-Navigation-Bars](https://docs.google.com/document/d/14LWVz6pG9WmI3hTmqp8z_Xsr8pj_Hge0yHaCO1GcjB0/edit?usp=sharing).

### Summary

Students have a jumbotron component on their pages from the previous activity. Now it’s time to add a navbar.

### Instructions

Students will navigate the Bootstrap component documentation page again and then copy and paste the code for the navbar onto their page.

*If students struggle:* First, make sure students have correctly linked to Bootstrap 4's CDN with a link tag. Check the placement of the component; this should be an easy copy and paste. Make sure students open the correct file in their web browsers.

*If students complete the activity early:* Start a conversation with these students about their portfolio or conceptually how components are similar to symbols in Adobe XD.

### Instructors and TAs

> :globe_with_meridians: **Online Recommendation:** Be sure to check your #ClassActivities Slack channel for questions while students are working and provide feedback.

With your TAs, offer help where needed. Encourage students to help one another, too.

Look for students who are struggling to place their code within the `<body>` of the index.html page.

Students might encounter the following common problems:
1. Students might not be properly linked to Bootstrap 4's CDN.
2. Students might place the component in the incorrect area, leading to a weird-looking template.

### Deliverable

A webpage with a basic navigation component will display on the screen.

## SLIDE 37
## 9. Instructor Do: Add a Navigation Bar Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.

**Review Students' Experience.**

Call the class back to attention so that you can lead a review of the navbar activity.

Ask the students if they have finished the exercise before asking a volunteer to share their work.

Have two or three students take turns sharing their work and discuss the questions that arise.

Offer students actionable feedback that they can apply to their work. For example:
1. Navbars can be designed to display on the left side of a page like a column.
2. Bootstrap's navbar can be customized like any other template. Don't feel constrained to using the base layout.

**Review Navbar Concepts.**

Next, have the students turn to their neighbor and ask the following questions:

1. "Did you have any trouble getting your navigation to work?"
2. "Did you customize your navbar in any way? If not, how would you do that in the future?"

Share some common misconceptions or FAQs about working with Bootstrap components. For example:
1. Bootstrap components can be placed anywhere on your page. The order in which your elements are laid out is up to you.
2. As a designer, there are Bootstrap toolkits used to prototype components before you build.

Next, we'll add responsive containers and rows to fill with content.


## SLIDE 38
Review

## SLIDES 39-40
Review

## SLIDE 41
The **responsive column system** (`col` class system) is a series of classes that you can add to any HTML element to make it respond to different viewports based on the classes you write.

The responsive column system has three parts:
1. Containers and container-fluids that serve as the outside wrapper of our responsive content
2. Rows that are used to separate rows of content within containers
3. Columns which are created by using the .col class and are defined within rows

The Bootstrap 4 classes that are applied to our HTML elements define how our layout responds to different viewports (screen widths).


**TAs:** share the following Bootstrap Adobe XD template with students: [Bootstrap XD template](https://drive.google.com/drive/u/1/folders/19JqnJPwsDhnIbKXz1BABepHY2zyjKV5p).

## SLIDE 42
Review

> :key: **Key Tech Note:** Bootstrap classes are CSS, be mindful that all CSS is case-sensitive. 

The foundation of this system is made up of the Bootstrap 4 class container, container-fluid, and rows. Let’s define each element individually:

- `.container`: Containers provide a means to center and horizontally pad your site’s contents. Use .container for a container with a fixed width.

- `.container-fluid`: A fluid container has the same function as a regular container except that you use .container-fluid for width: 100% across all viewport and device sizes. This container will always span the full width of the webpage or parent container.

- `.row`: Rows serve as a way to separate content within containers. Rows can display either horizontally or vertically depending on the layout you are trying to achieve.

## SLIDE 43
Review

## SLIDE 44
### Bootstrap 4 Responsive Screen Sizes

Bootstrap’s grid system works from a series of classes that define breakpoints.

| Size | Class | Screen Type | Pixel Width Range |
|-|-|-|-|
| Extra Small | `col-xs-` | Phone | < 576px |
| Small | `col-sm-` | Small Tablet | >= 576px |
| Medium | `col-md-` | Tablet, Small Laptop | >= 768px |
| Large | `col-lg-` | Laptop | >= 992px |
| Extra Large | `col-xl-` | Desktop | >= 1200px |
| Auto Responsive | `col-` | - | - |


## SLIDE 45
### Bootstrap 4 Column Example

Bootstrap's `col` system must have a `container` or a `container-fluid` and a row in order for our Bootstrap columns to respond correctly. Below is an example of what the proper structure looks like.

Here we have a container-fluid as our outside wrapper, a row to separate content, and three divs. The divs are assigned different classes that control how our layout responds depending on the size of different viewports. Point out this basic structure (containers -> rows -> col classes) for students before we move onto defining how the col class system works in detail.

```html
<div class="container-fluid"><!-- This could also just be a regular container -->
  <div class="row"><!-- Rows are used to separate our columns. If we need multiple rows, we can always add another. -->
    <div class="col-sm-12 col-md-4 col-lg-4">sample column</div>
    <div class="col-sm-12 col-md-4 col-lg-4">sample column</div>
    <div class="col-sm-12 col-md-4 col-lg-4">sample column</div>
  </div>
</div>
```

## SLIDE 46
Review

## SLIDE 47
## 11. Instructor Do: Containers, Rows Demo (5 min)
> - [20-Week/05-Instructor Resources/20.1_Demo_Files/3_Containers_Rows](https://drive.google.com/drive/u/1/folders/10WrL2-Sg77UG9JBNTUJAKa6qKPn6UEm_)

When all the numbers on the classes equal 12, they will display responsively and evenly across your elements.

You will add the number to the end of your classes. Here are two examples of a responsive container with content for understanding:

**Write the code below into your template for your class. Leave this up on a different screen for reference:**

```html
<div class="container-fluid">
  <div class="row">
    <div class="cardContainer col-lg-3 col-md-3 col-sm-12">
      <!-- Paste Card Here -->
    </div>
    <div class="cardContainer col-lg-3 col-md-3 col-sm-12">
      <!-- Paste Card Here -->
    </div>
    <div class="cardContainer col-lg-3 col-md-3 col-sm-12">
      <!-- Paste Card Here -->
    </div>
    <div class="cardContainer col-lg-3 col-md-3 col-sm-12">
      <!-- Paste Card Here -->
    </div>
  </div>
</div>
```

> Instructor Note: The code above is making use of three Bootstrap 4 classes. We'll explain what each piece of code is doing:
>
> - `col-lg-3`: On screens with large breakpoints, we have four children, each with the class col-lg-3. That means that on large screens, we'll see a four-column layout that spans the whole section (3 + 3 + 3 + 3 = 12).
>
> - `col-md-3`: This will work the same way as col-lg-3, except on medium displays.

> - `col-sm-12`: Notice that each child has a value of 12 at the end of the class. This means that on small displays, each child element will take up 100% of the width of its container.

> :key: **Key Tech Note:** When creating responsive layouts with Bootstrap 4, you can use any or all of the responsive classes for your 12-column layout, depending on where you want your website to respond.

In the example above, the content at large and medium resolutions will display a row that is four items across. At small resolutions, each item will display 100% of the width of the container (calculating margins and padding).

> Instructor Note: **Take time for questions:** Since you're moving on to a lecture, take a moment to be sure that students understood what they just saw in your navbar demo.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> - Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen. 
> - Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

Now you'll talk about the key concepts to understand Bootstrap's 12-Column layout.



## SLIDE 47
Review

## SLIDE 48
Review

## SLIDE 49
Bootstrap 4's **12-column grid system** is a series of prewritten CSS classes that define breakpoints for our content.

Bootstrap has developed CSS classes that are used to control the layout of HTML elements. Each class targets a specific width (e.g., `col-lg-4` targets large windows). When our website's width (of the browser windows) reaches each breakpoint, the contents will be rearranged to display differently.

Bootstrap's grid system works off a number system (12) that tells the CSS how to display content on your page in a responsive number. Each element is given a class with a number (1-12) that specifies how much space the element takes up on the screen.

**When Bootstrap’s classes equal to 12 inside a container, the children will be fully responsive and span the full container.**

## SLIDES 50-55
Review

## SLIDE 56
### Bootstrap Grid: `container`

Notable items about the example below:
1. This example uses a regular container. Regular containers have margins on the left and right sides.
2. This example has multiple rows. You can have rows display content differently based on your preference and design. The row will respond based on the classes wrapped inside of it.
3. The first row has two rows that will take up 50% of the width on large layouts; 6 + 6 = 12, so this row will be fully responsive.
4. The second row has three divs with the class of `col-lg-4`. Each div will take up 33% of the space; 4 + 4 + 4 = 12, so this row will also be completely responsive.

```html
<div class="container">
  <div class="row">
    <div class="col-lg-6"></div>
    <div class="col-lg-6"></div>
  </div>
  <div class="row">
    <div class="col-lg-4"></div>
    <div class="col-lg-4"></div>
    <div class="col-lg-4"></div>
  </div>
  <div class="row">
    ...
  </div>
</div>
```

## SLIDE 57
Fluid containers have the same function as regular containers, but use the .container-fluid class and have a width of 100% across all viewports and device sizes, making the width of the container always fill either it's parent container or the page.

## SLIDE 58

### Bootstrap 4 Grid: `container-fluid`

Notable items about the example below:
1. This row uses a container-fluid. Container-fluids don't have margins on the left and the right and will span 100% of the space.
2. You can still use regular tags inside of a Bootstrap 4 container. Notice how we have an h1 containing the text Hello World! You can target and style this h1 the same as any other HTML element.
3. This example has a row containing two div with the class of `col-sm-12`; 12 + 12 = 24, so this example's rows will both span 100% width and stack on top of each other.

```html
<div class="container-fluid">
  <h1>Hello World!</h1>
  <div class="row">
    <div class="col-sm-12" style="background-color:yellow;">
      <p>I love the color yellow</p>
    </div>
    <div class="col-sm-12" style="background-color:violet;">
      <p>Purple is my jam!</p>
    </div>
</div>
```
## SLIDE 59
Rows are wrappers for columns. Each column has horizontal padding (called a gutter) for controlling the space between columns. This padding is then counteracted on the rows with negative margins. This way, all the content in your columns is visually aligned down the left side.

## SLIDE 60
Review

## SLIDE 61
Containers and container-fluid must have a row inside them for you to be able to use Bootstrap classes on your HTML elements.

This step may seem minimal, but using Bootstrap’s columns and rows are fundamental to understanding how to build layouts with Bootstrap 4.

## SLIDE 62
## 13. Instructor Do: Bootstrap's Col Class Demo (5 min)
1. Add one div to your template between the rows on lines 64 and 66.

2. Code that div the following classes: `cardContainer col-lg-3 col-md-3 col-sm-12`. Explain to the class that you are adding your own class, `cardContainer`, in front of Bootstrap's so you can customize it later without changing Bootstrap's col classes.

3. After you're finished adding the classes to your div, copy and paste it three more times under the first so you have four for each row.

	The result should look like this:

	```html
	<div class="row">
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12"></div>
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12"></div>
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12"></div>
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12"></div>
	</div>
	```

Bootstrap's responsive column is the most important thing students can learn from this section.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> - Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen.
>
> - Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

To help students gain competency, let's have them add containers, rows, and columns to their templates. That's next.

## SLIDE 63
Review

## SLIDES 64-65
## 14. Student Do: Add Containers, Rows, and Columns to Your Template Activity (15 min)

> :globe_with_meridians: **Online Recommendation**: This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.1/20.1-03-Bootstrap-4-Containers-Rows-And-Columns](https://docs.google.com/document/d/1BW9FlyqhvIgzANyhUcpp8bB8KP7jn0RjPWYI3PXgGjA/edit?usp=sharing).

### Summary

It's time for students to add the structure for the content on their page by adding rows, containers, and columns.

### Instructions

During this activity, students will follow the activity doc instructions to add containers, rows, and columns to their template. Students will also make their webpage responsive using the col classes.

*If students struggle:* Syntax is important for creating containers, rows, and responsive columns. Make sure students wrap rows in containers and responsive columns inside rows.

*If students complete the activity early:* Engage them in a conversation about how they could use components to speed up their design and development processes.

### Instructors and TAs

> :globe_with_meridians: **Online Recommendation:** Be sure to check your #ClassActivities Slack channel for questions while students are working and provide feedback.

With your TAs, offer help where needed. Encourage students to help one another, too.

Students might encounter the following common problems:
1. It is common for students to improperly wrap their responsive columns resulting in nothing happening.
2. Students may misunderstand how the column system works. Students may be confused that you have to add only the same class together to effect certain breakpoints.

### Deliverable

Students' templates will now show a row that has four div children with responsive col classes medium-large.

## SLIDE 66
## 15. Instructor Do: Add Containers, Rows, and Columns to Your Template Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.

**Review Students' Experience**

Call the class back to attention so that you can lead a review of the activity.

Ask the students if they have finished the exercise before asking a volunteer to share their work.

Have two or three students take turns sharing their work and discuss the questions that arise.

Offer students actionable feedback that they can apply to their work. For example:
1. Designing your layouts first with a column can greatly help you when you go to code your work.
2. All websites are built off a column system. Bootstrap has created the column system for you, but some website code their own completely from scratch!

**Review the Concepts.**

> :globe_with_meridians: **Online Recommendation:** Stop sharing your screen, switch to gallery view, and use the Raise Hands feature in Zoom to gather answers. Share your screen again before continuing.

**Ask:**

- "What is the difference between a container and a container-fluid?"

	_A regular container has a fixed width of 1024px. A container-fluid will span the entire width of the screen._

- "How does the col class system work conceptually?"

	_Each class represents a breakpoint, and the number associated with it (col-lg-4, for example) is added together with the rest of the other sibling elements. When the numbers in each child (three children with col-lg-4) add up to 12, it creates a fully responsive row._

Share some common misconceptions or FAQs about working with Bootstrap components. For example:
1. Bootstrap's column system can be used to create rows and columns.
2. Bootstrap's column system is actually powered by CSS Flex—any CSS Flex properties you learned during Week 18 will work here.

Great! Let's take a break.

## SLIDE 67
## 16. Break 


## SLIDE 68
Review


Containers, rows, and Bootstrap's col system can be used to create content right alongside structure quickly.

"You can use Bootstrap 4's col system first to create structure (containers and rows). You can then use components to add pre-styled content to your template (take cards for example) and make your cards responsive using Bootstrap's col system."

A **card** is a UI design pattern that groups related information in a flexible-size container visually resembling a playing card. 

Cards visually separate and group content that is related. The class has learned about this technique—content chunking—during the UI sections of this boot camp. Content chunking helps users find information that is relevant to their needs.

Cards are rectangles full of inclusive images and text that serve as a teaser to more detailed information. This could be an article, a piece of art, or a project that is being shared.

## SLIDE 70
## 18. Instructor Do: Bootstrap 4 Cards Demo (5 min)

1. Continue working from the same file as the previous demos: [20-Week/05-Instructor Resources/20.1_Demo_Files/4_Cards](https://drive.google.com/drive/u/1/folders/1LPUbXXMWTVo0fE3m3uNUQsPphzZzPsUo).

1. Navigate to the documentation for Bootstrap Cards.

2. Copy the code for the first card on the page. You will have to scroll down slightly.

3. Paste the code in between the rows that you have.

4. Refresh the page and see for yourself! It should look like this:

	```html
	<div class="row"> <!-- This row is going to separate our content -->
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12">
		<div class="card" style="width: 18rem;">
		<img src="..." class="card-img-top" alt="...">
		<div class="card-body">
			<h5 class="card-title">Card title</h5>
			<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
			<a href="#" class="btn btn-primary">Go somewhere</a>
		</div>
		</div>
	</div>
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12">
		<div class="card" style="width: 18rem;">
		<img src="..." class="card-img-top" alt="...">
		<div class="card-body">
			<h5 class="card-title">Card title</h5>
			<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
			<a href="#" class="btn btn-primary">Go somewhere</a>
		</div>
		</div>
	</div>
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12">
		<div class="card" style="width: 18rem;">
		<img src="..." class="card-img-top" alt="...">
		<div class="card-body">
			<h5 class="card-title">Card title</h5>
			<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
			<a href="#" class="btn btn-primary">Go somewhere</a>
		</div>
		</div>
	</div>
	<div class="cardContainer col-lg-3 col-md-3 col-sm-12">
		<div class="card" style="width: 18rem;">
		<img src="..." class="card-img-top" alt="...">
		<div class="card-body">
			<h5 class="card-title">Card title</h5>
			<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
			<a href="#" class="btn btn-primary">Go somewhere</a>
		</div>
		</div>
	</div>
	</div>
	```

Cards are a very versatile feature of Bootstrap 4. It takes very little time and effort for a designer to customize a card, and they look great with minor tweaks.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> - Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen.
>
> - Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

Students will add cards to their layout in the upcoming activity.

## SLIDES 71-72
## 19. Student Do: Add Cards to Your Bootstrap 4 Template Activity (10 min)

> :globe_with_meridians: **Online Recommendation**: This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.1/20.1-04-Add-Bootstrap-4-Cards](https://docs.google.com/document/d/1O4Ygrq3BkJUMvT5pXlX4HV_THzoqe45FPYlSTP-_0vk/edit?usp=sharing).

### Summary

In this activity, students are going to add cards to their page.

### Instructions

Students will follow the Google Doc instructions to copy and paste the code for a card component into their page.

*If students struggle:* First, make sure students have correctly linked to Bootstrap 4's CDN with a link tag. Check the placement of the component; this should be an easy copy and paste. Make sure students open the correct file in their web browsers.

*If students complete the activity early:* Start a conversation about their portfolios or conceptually how components are similar to symbols in Adobe XD or component in Figma.

### Instructors and TAs

> :globe_with_meridians: **Online Recommendation:** Be sure to check your #ClassActivities Slack channel for questions while students are working and provide feedback.
-	Broadcast a two-minute warning to help them wrap up this work session.

With your TAs, address student questions as they arise.

Students might encounter the following common problems:
1. It is common for students to place their card components in the incorrect position. Lean on the solved file to show students where to place their cards.
2. Unlike the other components, cards display next to each other by default. Make sure students place their cards inside a container for the correct layout.

### Deliverable

Students' pages will now show two rows with four cards, each displaying content.

## SLIDE 73
## 20. Instructor Do: Add Cards to Your Bootstrap 4 Template Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.

**Review Students' Experience.**

Call the class back to attention so that you can lead a review of the activity.

Ask the students if they have finished the exercise before asking a volunteer to share their work.

Have two or three students take turns sharing their work and discuss the questions that arise.

Offer students actionable feedback that they can apply to their work. For example:
1. Bootstrap components (like cards) can be made responsive using Bootstrap's grid system. Try making your cards responsive using Bootstrap's col system.
2. When using cards, make sure you save images that are the same dimensions before you code your webpage. Using images with different dimensions will make your cards different heights and widths.

**Review Cards Concepts.**

> :globe_with_meridians: **Online Recommendation**: Stop sharing your screen, switch to gallery view, and use the Raise Hands feature in Zoom to gather answers. Share your screen again before continuing.

**Ask:**

"What is a card? Have you seen cards used on any big websites? Where?"

	_Cards are rectangles full of inclusive images and text that serve as a teaser to more detailed information. Some major examples are Facebook, Twitter, and Pinterest._

Share some common misconceptions or FAQs about working with Bootstrap components. For example:
1. Bootstrap cards will line up next to each other by default. You can alter this behavior using CSS Flex.
2. All of Bootstrap 4's CSS properties utilize CSS Flex and can be modified using CSS.


## SLIDE 74
Review

## SLIDE 75
Review

## SLIDE 76
### Bootstrap 4 Form Components

A **from** on a webpage allows a user to enter data that is sent to a server for processing.

Form elements are common elements found on the web and are the primary mode of transportation of data. They are used to capture user, payment, or contact information. Bootstrap gives us a form that is quick to customize (or connect to a database).

They can have a variety of functions:

- Signing up for a website or app
- Submitting payment information
- Signing up for an email blast


## SLIDE 77
Forms in the past were notoriously difficult to style, requiring additional code called a polyfill to look the same across browsers, such as Chrome, Safari, Firefox, or MS Edge.

This isn't a problem with Bootstrap 4's forms—they are already compatible across all browsers.

> :key: **Key Tech Note:** A polyfill is a piece of code (usually JavaScript on the web) used to provide modern functionality on older browsers that do not natively support it.

Bootstrap 4 also has many custom form elements that can be added to your form to embellish it and make it look nice.

> **TAs:** Slack out the following two links with the class:

- [Bootstrap 4 Form](https://getbootstrap.com/docs/4.3/components/forms/)
- [Bootstrap 4 Custom Form Elements](https://getbootstrap.com/docs/4.3/components/forms/#custom-forms)

> Instructor Note: Students should bookmark these links to reference them during activities or to study them after class.

## SLIDE 78
Review

## SLIDE 79

### Bootstrap 4 Modal Components

A **modal**  is a graphical control element subordinate to an application's main window. It creates a mode that disables the main window but keeps it visible, with the modal window as a child window in front of it.

- Bootstrap 4's modals are components that come prebuilt with animations and transitions that make a fully functional, pleasing UI component.


## SLIDE 80
Modals are built with HTML, CSS, and JavaScript.

They’re positioned over everything else in the document and darken the backdrop so that your user is focused on your content.

Modals should be used sparingly to avoid usability issues.

Modals can hold many different UI elements and are used to focus a user on a specific part of our UI.

> Instructor Note: Never place a modal on a modal—it is a bad UX.

**Examples of modals:**

- Sign-in forms
- Payment forms
- Advertisements
- Information boxes

Modal elements were not common on the web before Bootstrap 4, partially because they require custom JavaScript code to function.

> Instructor Note: Bootstrap 4 also requires jQuery/JavaScript, but this code has already been written for you.

All you need to do is link to the Bootstrap's CSS and JavaScript files.

Bootstrap 4 modals have two requirements:
![Bootstrap Required Attributes](Images/bootstrap_Button.png)

The button has two attributes:

1. ```data-toggle="modal" ``` - This attribute tells our button that it is connected to a Bootstrap 4 modal element. This is required for our button to trigger a Bootstrap 4 modal.

2. ```data-target="#exampleModal"``` - This attribute tells our button which modal element it is targeting.

   ![Bootstrap Modal ID](Images/bootstrap_modal.png)

3. In the image above, the only important element is the ID. Notice how this ID's name is the same as our data-target above? Both target the ID of an example modal. This attribute connects our modal to our button.

> :gem: **Designer Insight**: Share how use of forms and modals has benefitted your workflow to help students grasp the value of these tools.

> Instructor Note: Take questions that students might have about forms or modals before moving on.

Now that we have seen a few more Bootstrap 4 components, it's time for students to take these components for a test run by adding a form and modal components to their page.

## SLIDE 81
## 22. Student Do: Forms and Modals Activity (10 min)

> :globe_with_meridians: **Online Recommendation**: This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.1/20.1-05-Bootstrap-4Forms-and-Modals](https://docs.google.com/document/d/1IrNPaNx4E225ooztDHuyBJ224LUDlPHn_zB8CGtSMNU/edit?usp=sharing).

### Summary

In this activity, students will add a form and a modal component to their template, customizing their Bootstrap elements with HTML and CSS.

### Instructions

Students will add a fluid container and a row to act as containing elements for their form. They will center the form on their page.

*If students struggle:* Make sure students have Bootstrap 4's script tags; modals will not function without this tag. Lean on the solved file if you are not an experienced front-end developer to show students how their code is different.

*If students complete the activity early:* Start a conversation with these students about their portfolios or conceptually how components are similar to symbols in Adobe XD and components in Figma.

**Bonus:** Students will then add a Bootstrap 4 modal to their site and attach their modal to the button in the existing jumbotron so that it toggles. Students will then create a form inside of their modal window.

### Instructors and TAs

> :globe_with_meridians: **Online Recommendation:** Be sure to check your #ClassActivities Slack channel for questions while students are working and provide feedback.

While the activity is in process, make sure students are putting the Bootstrap 4 form in the correct place in their HTML. Students are new to Bootstrap 4 and the HTML may visually overload them.
  - Help students keep their work concise, condensed, and well-formatted.
  - Help students who are having trouble getting their modal running.

Students might encounter the following common problems:

1. Often, students will forget their script tag, preventing their modal from functioning.
2. Modals also require modifications to the `data-target="#exampleModal"` and `id="exampleModal"` if students attempt to trigger a modal on a button and the data-target and css ID (#) are not the same, (remember case sensitive matters) it will not launch the modal. 

### Deliverable

Students' pages should now match with the solved activity file located in the solved folder:

![Solved gif](Images/solved_gif.gif)

- Solved file location: [20-Week/02-Activities/20.1/20.1-Bootstrap 4 - 12 col Grid Template - Phone, Tablet, Desktop](https://drive.google.com/a/2tor.com/file/d/1w8nvB2Puvq-_3x_fGVzCB3naHQxuXzWG/view?usp=sharing)

## SLIDE 82
## 23. Instructor Do: Forms and Modals Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.

**Review Students' Experience.**

Call the class back to attention so that you can lead a review of the activity.

Ask the students if they have finished the exercise before asking a volunteer to share their work.

Have two or three students take turns sharing their work and discuss the questions that arise.

Offer students actionable feedback that they can apply to their work, for example:
1. Modals can contain all sorts of data. Design your modal's function first. What will your modal contain? A sign-up form or advertisement? The possibilities are endless.
2. Forms are the universal way to collect data on the web. You find forms in many places: sign up forms, payment forms, surveys. Design the function of your form first so you can customize your Bootstrap 4 form quicker.

**Review Forms and Modals Concepts.**

> :globe_with_meridians: **Online Recommendation**: Stop sharing your screen, switch to gallery view, and use the Raise Hands feature in Zoom to gather answers. Share your screen again before continuing.

**Ask:**

- "What are forms used for on the web? Why is the Bootstrap 4 form useful?"

	_Forms are the primary method of data transfer on the web! Bootstrap 4 provides an easy way to customize database forms._

- "What is a modal? What kind of UI elements might you find in a modal?"

	_Modals overlay the main window but keep the main window's content visible with opacity, with the modal window as a child window in front of it displaying our content to the user. A UI might use a modal to process information or display visual cards with choices._

Share some common misconceptions or FAQs about working with Bootstrap components. For example:
1. Bootstrap forms without back-end programming knowledge will not function. You can, however, still design the look and the feel of your form and have an engineer connect it to a database or script.
2. Bootstrap modal animations can be customized. You can target the HTML elements with your own stylesheet or script tag.

## SLIDE 84
## 24. Student Do: Bootstrap 4 Components Challenge (45 min)

> :globe_with_meridians: **Online Recommendation**: This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the following activity instructions:

[20-Week/02-Activities/20.1/20.1-06-Extended-Activity-Explore Bootstrap-Components](https://docs.google.com/document/d/1S0Fc6vT2AqyKxR-hSUyAh3yJFookQJ3wuFbHYkKcC00/edit?usp=sharing).

> Instructor Note: Students will follow the links to Bootstrap documentation listed in the Google Doc activity instructions.

In this extended activity, students will choose from the following elements to add to their component-based page—**students must add at least three of these elements to their page**:

- Collapsible element: [Bootstrap collapsible element](https://getbootstrap.com/docs/4.3/components/collapse/)

- Drop-down (for your navigation): [Bootstrap drop-down](https://getbootstrap.com/docs/4.3/components/dropdowns/)

- Carousel with images: [Bootstrap carousel](https://getbootstrap.com/docs/4.3/components/carousel/)

- Popover: [Bootstrap popover](https://getbootstrap.com/docs/4.3/components/popovers/)

> :globe_with_meridians: **Online Recommendation:** Be sure to check your #ClassActivities Slack channel for questions while students are working and provide feedback.

> Instructor Note: This is a long activity, so do your best to keep the energy flowing in the room. Support students as they work by providing feedback and answering questions as they arise.

## 25. Instructor Do: Bootstrap 4 Components Challenge Review and Lesson Recap (10 min)

> :globe_with_meridians: **Online Recommendation**: Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.

Ask the students if they’ve finished the exercise before asking a volunteer to share their work.

**Discuss students' experience of the challenge.**

- Allow *at least five minutes* to process this long activity.
- Encourage students who have lengthy questions to stay after class.

**Review the Lesson's Concepts**

> :globe_with_meridians: Online Recommendation: Stop sharing your screen, switch to gallery view, and use the Raise Hands feature in Zoom to gather answers. Share your screen again before continuing.

Recap today's class and be sure students have absorbed as much learning as possible. You can ask students to sit in small groups and discuss the following questions.

**Ask:**

- "What is a Bootstrap 4 component? How can it speed our development process?"

	_Bootstrap 4 components are prebuilt HTML elements that can be copied and pasted into our code so we don’t have to code it ourselves._

- "What is the Bootstrap 4 col system? How does it make our site responsive?"

	_Bootstrap's col system allows us to add classes directly to our HTML that make our site responsive without having to write our own CSS or media queries._

- "Why is Bootstrap 4 useful?"

	_Bootstrap 4 is useful because it speeds our development process by allowing us to use prebuilt components and classes that make our site responsive._

> Instructor Note: Pause to take any final questions.
>
> **Say:** "If anyone has questions about any of the concepts we learned today or if you just want feedback on your work, please stay for office hours."

Your final step of the day is to introduce this week's challneg.

## 26. Instructor Do: Introduce Challenge and End Class (5 min)

> Instructor Note: Ask a TA to share the challenge document with students via Slack or students can open it in the class Google Drive.
>
> Recommend that students make a copy of the assignment in their personal drive folders as soon as they open the link.
>

Take a moment to make sure everyone is clear on what this week's challenge involves.

- Open the challenge for the class: [20-Week/03-Homework/01-Instructions/Unit 20 Homework](https://docs.google.com/document/d/1eWJqcatyZpOmMyy-HQVySn-3B9h_23pDyyYCH80zQCc/).

- First, explain the assignment’s due date.
  - As a general rule, a challenge assignment is due at the start of class two weeks from the date it was assigned.
- Next, read through the instructions with the class.
  - **Tell students that the Unit 20 Challenge asks them to code a Bootstrap 4 webpage showcasing one of their case studies.**
- Finally, ask the class if there are any questions.

That’s it for today! Remind students to use the office hours to practice and receive feedback on their code. 

Say goodnight and dismiss the class. 

## We Want Your Feedback!

Instructor, how did class go today?

Please submit any issues or comments on the UX/UI curriculum to our Google Form:

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

View the status of your submission and other issues here:
[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing)


---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.	
