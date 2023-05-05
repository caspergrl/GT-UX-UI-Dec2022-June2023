# 20.2 Lesson Plan: Customizing Bootstrap 4

---

## Overview

Today you'll teach students how to customize Bootstrap, specifically the Bootstrap 4 template they created last class. Additionally, students will expand their CSS techniques for positioning and styling elements with Bootstrap. 

Today is the second of three lessons in Unit 20. In Lesson 20.1, you introduced Bootstrap 4 and how to use its components to create prototypes quickly. Today, in Lesson 20.2, you'll teach how to overwrite Bootstrap 4 components' CSS to customize a Bootstrap 4 template, so students can create custom websites out of a Bootstrap 4 template. This will prepare students for Lesson 20.3, when students will serve in the role of freelance web developer and export web-ready images from a design. Students will then use the assets to create a design file based on a prompt.

## Learning Objectives

By the end of class, students will be able to:

1. Customize the Bootstrap 4 template's UI components, including buttons, navigation, and cards.
2. Analyze user funnels on github.com to better understand how to design sections.
3. Design and code a fully responsive, customized Bootstrap 4 template.

## Class at a Glance

- Welcome to Lesson 20.2.

Today's lesson covers customizing Bootstrap 4 templates and overriding Bootstrap's CSS properties.

The overarching message is that Bootstrap 4 skills are desirable in the workplace. Bootstrap 4 speeds up the development process by enabling designers to create professional templates that are used to generate responsive websites quickly.

You'll remind students that a site "works" when it guides the user through a journey to find information or purchase something. You'll touch on this in the Value Proposition section and connect today's concepts to students' existing UX and UI knowledge.

Students will practice customizing Bootstrap 4 templates and overriding Bootstrap's CSS properties by working through a series of activities to build a site layout for Rock Nation. Specifically, they'll customize the following Bootstrap 4 components:

1. Navbar
2. Hero image
3. Bootstrap 4 cards and rows
4. Footer section

## Instructor Notes

Many of our activities were written for in-person classes, so we've added in-line callouts (usually indicated by this icon: > :globe_with_meridians: **Online Recommendation** to let you know how to adapt an activity for online delivery.

Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.

> :globe_with_meridians: **Online Recommendation**: Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here are some examples of what you can say during common transitions:
- From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”
- From sharing the slideshow to sharing a tab on your browser: “Bear with me as I switch over to my browser for the next demonstration.”

> :globe_with_meridians: **Online Recommendation**: Transitions and activities tend to take longer in virtual classrooms. If you find that you are running short on time, feel free to combine review sections by doing the activity as a class instead of creating breakout groups. 

---


## Preparing for Class

**Review the slides beforehand**.
- [20-Week/01-Slides/20.2-UX-UI-Customizing-Bootstrap-4](https://docs.google.com/presentation/d/1F-9Bzth39XzO9CikEOakTKAxQstAaBe1JqRRsHo6cjQ/edit?usp=sharing)

- Make any teaching notes you'll need.

- As you lecture, relate your own on-the-job experience whenever possible to bring what students are learning to life and connect it to their future goals.

- Look for the :gem: icon, which prompts you and/or a TA to share professional anecdotes directly related to a particular concept.

**You'll lead three demos.**

- Today, you'll show students how to overwrite and customize the template we created last class. You'll model these concepts, then your students will apply them in their activities.

- Before class, review and practice each demo for a smooth experience:

- Customize a Search Bar (Section 6)
- Customize Our Jumbotron (Section 9)
- Customize Bootstrap 4 Cards (Section 14)

- Download the demo files here: [20-Week/05-Instructor Resources/20.2_Demo_Files/Bootstrap_Customize/unsolved](https://drive.google.com/drive/u/1/folders/1GRvCinzF89TVuW6tgJWeTcmv4CxwHbl6)

- Consider the student questions that might arise during the demos or class. Make notes so that you can address them.

- If needed, review the Strategies for Class Online in the unit README.

---


## Time Trackers

- Keep track of the clock. Have TAs consult the [20-Week/04-Time Trackers/20.2 Time Tracker](https://docs.google.com/spreadsheets/d/1b-QoFzuZUg8Q1YMg-xH1WEt4N_u0yx1sEb2nAs_PjMg/edit?usp=sharing).

- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---


## Preparing to Teach Weeks 17-21

**Help students program.**

- Many students will be nervous about getting into programming. Some might even have impostor syndrome. Reassure students that these feelings are normal and will pass. After all, they're learning a new language.

  - Be sure to mention that the best way to feel more comfortable working with code is to *code*! Every coder working today had to begin somewhere. Your students are no different today than coders were when they started. Practice makes perfect; the best way to get rid of impostor syndrome is to practice.

**Share anecdotes about your journey.**

- Don't be afraid to talk about the difficulties you experienced when you first started learning how to program. Knowing that you also struggled will help students feel better about not completely understanding the material yet.

**Encourage pair coding.**

While the in-class activities indicate that students should work independently, encourage students to work together on problems.

- As pair programming is a common agile software development technique, it is relevant for them to at least try it out for themselves.

- If you decide to pair students to program together in your class, try to pair weaker students with stronger ones.

**Download key tools.**

- If you don't already have them, be sure you have the following tools on your computer:
    - [Visual Studio Code](https://code.visualstudio.com/)
    - [GitHub Desktop](https://desktop.github.com/)

**Set up your computer.**

- **Design a setup for teaching that works for you:**
  - During the coding portion of the lecture, some instructors choose to mirror their laptop screen for the projector so that students can watch them code.

  - Other instructors have used different methods to help them facilitate coding, such as an additional laptop, iPad, or iPhone to review the materials during the lecture.

- **Adjust your Visual Studio Code settings:**

- Students need to be able to see the code you display. Make sure that you enlarge the text on your text editor so that the students can see it clearly.

- **Enlarge the text on your screen:**
  - In Visual Studio Code, the best way to accomplish this is with **command and +** for Mac, and **shift and +** for Windows. For reducing the size, the hotkeys are **command and -** (iOS) or **Shift and -** (Windows).
  - Set your font size to 24 pixels:
    - This setting is under **Code > Preferences > Settings > Commonly Used > Editor**. For Font Size, choose 24.
  ![Font Size VS Code](Images/font_size.png)

- **Change to a white-colored theme:**

  - You can find these settings under **Code > Preferences > Settings > Search for Theme > WorkBench.** For Color Theme, choose Default Light+.
  ![VS Code Themes](Images/VsCode_Themes.png)

**BEFORE EACH CLASS: Students must now download a .zip file before each class.**

During this front-end development portion of the boot camp, students will use HTML and other file types during their in-class activities. For this reason, students need to download the .zip file in the Activities folder **before each class**.

> **TAs:** Please upload only the **unsolved.zip** file to your students' Google Drive and pass out the solved files at your discretion. However, if you think it will benefit your class, you may share solved files with the unsolved files.

> Instructor Note: Here is a screenshot of your class files located in your class's Google Drive. Notice both the solved and unsolved files.

![Google Drive Activity Files](Images/solved_unsolved.png)

**Have students create a folder to contain their activity files**:

![Create an Activity folder](Images/createActivity.gif)

**Have students add their unsolved files into the folder structure, so that they don't get lost**:

![Move files](Images/moveFiles.jpg)

---


## Office Hours: Reviews and Practice (45 min before class)

> **Instructor Note:** Encourage your students to make the most out of class and not to be afraid to ask questions.
>
> - Do your part by engaging students.

---

## 1. Instructor Do: Welcome and Share Today's Objectives (3 min)

Welcome the students!

Open and download today's slides. TAs should share them with the students via Slack: [20-Week/01-Slides/20.2-UX-UI-Customizing-Bootstrap-4](https://docs.google.com/presentation/d/1F-9Bzth39XzO9CikEOakTKAxQstAaBe1JqRRsHo6cjQ/edit?usp=sharing)

**Review today's objectives.**

**Say:** "Today, we'll take our Bootstrap template (from the last class) and customize it to suit our needs."

> Instructor Note: Encourage students to take creative liberties during the lecture and while working through the activities.
>
> - For example: Do students disagree with the color scheme of the site we're building? Awesome! Encourage them to make it their own. Students who are comfortable with their CSS should practice tailoring their template's CSS style.

Draw connections between today's lesson and what students learned about UX/UI in this boot camp. Take Lesson 11.1, for example:

- We discussed responsive web design and UI testing. 
- We covered how the most important elements on a design are on top---usually this is your company's most important call to action (CTA). When viewing websites, the content you see first says a lot about the company.
- We discussed different design patterns encountered on the web. 

**Ask,** "How might you leverage the different design patterns to improve a webpage's value proposition and attract users?"

- **Answer:** This is just a prompt for you to ask students. You can use different design patterns (cards, jumbotrons, etc.) to draw users' attention to your CTAs.

> :gem: **Designer insight**: If possible, share how you've used Bootstrap, specifically to customize. Reassure students that this lesson is relevant to their future work.
>
> - Alternatively, invite a TA to share.

Customization is part of our everyday experience in many areas of our lives. For example, have you ever used a ceramic bowl to amplify your iPhone's sound? That's a simple trick. Or used an IKEA "hack" to transform a standalone bookcase into a built-in? Or modified a car's sound system or window tinting? Customization makes our lives better—that goes for our users, too.

Let students know that they'll practice customizing Bootstrap 4 templates and overriding Bootstrap's CSS properties in a series of activities to build a site layout for Rock Nation. In the process, they'll develop skills for customizing quickly and effectively:

- Constructing a Bootstrap 4 prototype quickly and then customizing it to fit a design
- Customizing Bootstrap 4 templates, greatly reducing development time for personal and professional projects
- Working quickly to construct prototypes that convey the functionality of the UI (design teams typically use agile to design features)

Next, take a moment to refresh the students' memory from the last class and be sure they can recall the high points about Bootstrap 4 components.

## 2. Instructor Do: Bootstrap 4 Components Review (10 min)

Today will be a deeper dive into Bootstrap 4, so make sure students are on steady footing and feel sufficiently comfortable with the basics of the tool.

Take questions that students might have from last class as you review the following concepts.

> :globe_with_meridians: **Online Recommendation:** Instead of switching to Zoom gallery view, have students share their answers in the Zoom chat or Slack so they can refer to your shared screen to answer the questions.

**Ask:**

- "What is a Bootstrap 4 component?"

	_A Bootstrap 4 component is a pre-written piece of HTML code that can be pasted into your file._

- "Why would front-end developers use Bootstrap's components?"

	_Developers use Bootstrap 4 components to add elements like modals or cards without having to write the codebase themselves._

- "How does Bootstrap's grid system work? Why is the number 12 relevant to col classes?"

	_Bootstrap’s grid system works off its col classes. A col-number of 12 makes a responsive row._

Take any final questions, then transition into today's first lecture: How to overwrite Bootstrap 4 styles.

## 3. Instructor Do: Overwriting Bootstrap 4 (5 min)

> :pushpin: **Important Point:** The goal of this section is to prepare students to be able to overwrite Bootstrap 4's CSS file with their own styles and load a custom stylesheet. You will also touch on how content delivery networks (CDNs) are loaded into HTML documents. This lecture supports today's first learning objective, which is for students to customize the Bootstrap 4 template's UI components, including buttons, navigation, and cards.

In this section, you'll introduce how to begin customizing Bootstrap 4 components.

> :briefcase: **Employer Competitive Note:** Overwriting Bootstrap 4 styles will improve students' design work when creating Bootstrap 4 design files. Professionally, Bootstrap 4 is used to prototype a UI quickly with components customized to fit your design file. Having a working knowledge of how to overwrite Bootstrap 4 styles will help students design better because they know the limitations of working with Bootstrap 4 components.

"Overwriting Bootstrap" literally refers to overwriting Bootstrap 4's CSS file to customize components. When overwriting a Bootstrap 4 component, you'll need to have your own stylesheet linked below Bootstrap 4's link tag so that your file loads second and overwrites Bootstrap's.

Bootstrap 4 on its own is useful, but being able to create fully responsive components simply by overriding default styles is Bootstrap 4's real power. Bootstrap was designed to create fully responsive, customized websites quickly—you can do this by overwriting Bootstrap's custom CSS styles to match your design. For example, by overriding styles, you can do the following:

- Change the background-color or image of a component
- Modify any style to visually fit your design file

> :gem: **Designer Insight:** Ask a TA to share about customizations made with Bootstrap and why they're useful.
>
> - Alternatively, invite a student with Bootstrap experience to share.

Bootstrap 4 classes are usually overwritten using your own custom classes that you then style to make components your own.

> Instructor Note: Remind students that much of what we learned in units 16 and 17 still applies here and will be used to align and customize our existing template.

Bootstrap 4 comes with all the CSS and HTML you’ll need to create a template efficiently. Its real power is in creating a responsive, clean template quickly—a real time-saver. We can then customize our template to look however we want. 

- Consider the prior template's look. In Lesson 20.1, we developed a Bootstrap 4 template using components and the Bootstrap col system. You might have noticed that it doesn't look the best. Bootstrap components are meant to be overridden to create a full-color design.

Below is what we developed during Lesson 20.1:

![Bootstrap template](Images/bootstrap_template.png)

Fairly "Bootstrap looking," right?

Below is a peek at what it'll look like after today:

![Rock Nation](Images/rock_nation.png)

Much better! Transforming a template from just components to a full design is how Bootstrap's components are meant to be used.

If you don't customize components, your design will still look and feel "Bootstrappy," and clients and business stakeholders will be able to tell. The whole goal for a UX designer is to create an experience!

**How does overwriting happen?**

First, students need to understand that internet browsers load files top-down, meaning that Line 1 loads first, followed by Line 2, and so on, until the entire page loads. So stylesheets that load second will overwrite those stylesheets that loaded first.

Load stylesheets like so:

```html
<!-- Bootstrap 4 CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
<!-- Load our custom stylesheet 2nd to overwrite bootstrap with our custom styles-->
<link rel="stylesheet" href="css/index.css">
```

> :key: **Key Tech Note:** Remember, the browser reads HTML top-down. By loading our custom stylesheet second, we overwrite Bootstrap 4 with our own custom styles.

Any CSS file (or JavaScript) loaded second will overwrite CSS styles loaded previously. This is how to write a custom CSS on a Bootstrap 4 component. In your custom stylesheet, you can target the Bootstrap 4 elements and write your custom CSS to overwrite Bootstrap 4's component styles.

> Instructor Note: Pause to take questions about the concept of overwriting Bootstrap and its benefits.

Next, transition to a wider view about value propositions on the web. This will provide context for work that follows and will remind students to keep the user top-of-mind.

## 4. Instructor Do: User Funnels and Value Propositions on the Web (10 min)

> 📌 Your goal is to take a step back into a UX/UI mindset to analyze value propositions on the web. This lecture prepares students for today's second learning objective, which is for students to analyze user funnels on github.com to better understand how to design sections.

> 💼 **Employer Competitive Note:** Professional designers make sure that each section of a webpage or website supports a single CTA. CTAs are the way that businesses make money. Creating designs that allow users to convert at multiple points in your UI will make your boss and business stakeholders happy because the business will make money.

A **user funnel**, also known as a sales or marketing funnel, describes the process you create to attract potential buyers to your website and guide them to take some desired action. Websites are built with a section that advertises features and services the business provides. The order of the content always defines the most important features and services as well as the most important CTAs.

A **CTA** is a statement designed to prompt an immediate action associated with interacting with a UI. An example of a CTA is a "Shop Now" button with text and images enticing the user to perform the desired action.

A **value proposition** is essentially advertising a feature of your business. Value propositions are an innovation, service, or feature intended to make a company or product attractive to customers.

### User Funnels on the Web

Value propositions on the web are laid out purposefully in user funnels. This understanding will help students appreciate that designers indeed think about how they use content to engage users at every turn.

Modern websites have a very defined "flow" to how their webpage is built—this is known as a user funnel. Sections are designed to advertise one important CTA. They're designed to catch users' attention as they scroll down through the page. Sections will be ordered from the most important CTA to the least important.

> :gem: **Designer Insight**: Share a story about how user funnel priorities have influenced your work on clients' websites.

Businesses have many different types of users. It's important to tailor CTAs on your homepage to generate the most interest in your user base.

Let's analyze [GitHub's homepage](https://www.github.com) as an example of how businesses build their sections to promote products.

**TAs:** Slack out the [GitHub homepage](https://www.github.com) so that students can follow along on their own if they wish.

Each section targets the type of users the website wants to capture. These sections follow a series of steps that essentially promote a product or service. 

### GitHub User Funnel Step 1: Signup

![Step 1](Images/step1.png)

The first section on most websites (besides news or ecommerce) encourages users to sign up or create a free account for more information on the product or service the site offers. 

In GitHub's case, the initial CTA is to create a free account for the service. The account would be for GitHub's average user---your run-of-the-mill developer.

### GitHub User Funnel Step 2: Introduce the Product and Service

![Step 2](Images/step2.png)

The next few sections are value propositions on how or why you might use the product or service.

Here, GitHub advertises contacting the sales team and signing up for the enterprise service.

This section grabs the attention of project managers or bosses of software teams.

### GitHub User Funnel Step 3: Play as a Team

![Step 3](Images/step3.png)

> Instructor Note: **Ask,** "What do we see here? Any CTAs?"

This specific section advertises how you can use GitHub's products or services to work as a team!

Notice the CTA: Sign up your team.

### GitHub User Funnel Step 4: New Feature/New Section

![Step 4](Images/step4.png)

This is an informative section, specifically for one of GitHub's products—GitHub Enterprise.

> Instructor Note: **Ask,** "Does anyone see a CTA?"

Instead of signing up, however, this just wants the user to learn more about how GitHub Enterprise works, which will lead to a CTA to convert.

### GitHub User Funnel Step 5: More Features

![Step 5](Images/step5.png)

This section is another GitHub feature—GitHub Integrations.

> Instructor Note: **Ask,** "As the user, what do you think you're supposed to do here?"

It is merely advertising for you to learn about how Integrations work on GitHub, which will also lead to a CTA of some sort.

### GitHub User Funnel Step 6: Appeal to the Masses

![Step 6](Images/step6.png)

This section is specific to the community and aims to empathize with the people they want to sign up for their service—developers.

> Instructor Note: **Ask,** "For what purpose is this section?"

A section like this one is meant to catch the interest of the average user base if they're exploring the website but have not yet converted.

### GitHub User Funnel Step 7: One Last Chance!

![Step 7](Images/step7.png)

We come to the bottom of our page.

> Instructor Note: **Ask,** "What do we think GitHub wants the user to do here?"

If a user made it this far down the page, GitHub tried one last time to get the user to sign up for the service.

This CTA is the same as the first—sign up for GitHub. The reason: At this point, the user is probably looking for something or considering signing up for the product or service, so GitHub prompts them one more time.

### GitHub User Funnel Step 8: Maybe They Are Just Lost?

![Step 8](Images/step8.png)

Lastly, we have our classic footer, which serves as a directory to keep users engaged in the website. Maybe they're having trouble finding what they're looking for? Most websites follow this convention, and a well-designed footer converts users and keeps them engaged as an added bonus.

**Ask:** "What do we think GitHub wants the user to do here?"

Each section has a purpose. Help your class to keep this in mind when you move onto developing your templates.

> Instructor Note: Pause for questions.

Next, review what students just learned about clear and defined user funnels from the GitHub site:
1. Businesses will attempt to convert users on each section of a website.
2. Each section has a different feature they're highlighting, complete with a CTA.
3. You'll see the same CTA in multiple locations in an attempt to catch a user if they reach a decision at any point when exploring the UI.
4. Sections of websites will cater to different demographics. For example, one section might cater to the standard user while another is catering to people who run teams and are looking for different tech that they can leverage.

## 5. Instructor Do: Customize a Search Bar Demo (5 min)

> :globe_with_meridians: **Online Recommendation:** Navigate away from the slideshow for this demonstration. If you shared your entire desktop, make sure to open your files on that shared desktop. If you shared a single window, be sure to re-share your screen to capture the appropriate window or desktop. Remember to narrate what you are doing during transitions and demonstrations. In this instance, you might say:

“I’m now going to switch from the slideshow to another tab so I can demonstrate jQuery and JavaScript toggles.”

This demo will cover:

- Show the basic steps involved in redesigning a search bar into something more professional.
- Help students understand that cutting some content out of Bootstrap 4 is OK, even expected.
- How to use the `!important` tag to overwrite stubborn Bootstrap 4 styles.
- Demo the automatic margins for aligning items/content inside a container.

Begin by showing students how to customize the navbar's elements and add our own logo to our navigation component.

**Say:** "It’s time to apply the HTML and CSS skills we learned in the first two weeks!"

> :globe_with_meridians: Online Recommendation: Since you’ll be sharing your screen for this demonstration, ask students to use the raise hands feature on Zoom to ask questions. At a good breaking point, call on a specific student to unmute and ask their question. Alternatively, you can ask students to share their questions in the Zoom chat and have the TA provide answers in the chat.

1. Open the index.html file in the folder Bootstrap_Customize: [index.html location](Activities/Bootstrap_Customize/Unsolved/index.html). 

1. On Line 19, add a logo that you like in place of the text `Navbar`. Add an image tag that targets one of the logos in the images folders: [Logos folder location](Activities/Bootstrap_Customize/Unsolved/images/Logos). 

	```html
	<a class="navbar-brand" href="#">Navbar</a>
	```

	The end result should look like the following:

	```html
	<a class="navbar-brand" href="#"><img src="images/Logos/logo1.png"></a>
	```

1. Great! Now let's delete the search bar so we can simplify our header. A search bar is a form located on lines 44-47. Delete those lines of code.

	```html
	<form class="form-inline my-2 my-lg-0">
	<input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
	<button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
	</form>
	```

1. Now, let's align our navbar to the right. Write a class that targets the class of `navbar-nav` (this is Bootstrap 4's default nav class). It should look like this:

	```css
	.navbar-nav {

	}
	```

1. Add the CSS properties `margin-left: auto;` and `margin-right: 0 !important;`.

	Explain that `margin-left: auto;` or `margin-right:auto;` will position block-level elements to the far left or far right side of their containers, respectively.

	It should look like the following:

	```css
	.navbar-nav {
		margin-left: auto;
		margin-right: 0 !important;
	}
	```

> :key: **Key Tech Note:** With Bootstrap 4 CSS, you'll encounter the `!important` tag often. Bootstrap 4 does this to ensure that Bootstrap's look and feel remains consistent across all browsers. If you can't get a style to work, double-check in Chrome Web Inspector for CSS properties with `!important`.

> Instructor Note: Pause here to take questions.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> - Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen.
>
> - Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

To help students remember what we just learned, it's time for students to customize their own navigation.

## 6. Student Do: Webpage Funnel Customization: Part 1 - Navbar Activity (15 min)

> :globe_with_meridians: **Online Recommendation:** This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.2/20.2-01-Webpage Funnel Customization: Part 1 - Navbar](https://docs.google.com/document/d/1dtHb8SrXG0mhRkIszYmJ7mXM4Anbo9zf6-VmT2YnVGc/edit?usp=sharing).

### Summary

Students will customize their site’s navbar to reflect the site’s layout and overall brand identity better.

### Instructions

Students will follow the instructions in the activity document:

Part 1: Students will update the HTML in their index.html file.

Part 2: Students will update the CSS in their index.css file.

> Instructor Note: Students are provided an activity starter file in their activities folder.

*If students struggle:* Double-check the placement of the student's stylesheet; it must be second to the Bootstrap 4's CDN link tag. If that doesn't work, play with the student's code in the Web Inspector and use the `!important` tag to override difficult CSS properties.

*If students complete the activity early:* Share the following [resource](https://uxplanet.org/how-to-customize-bootstrap-b8078a011203) with them.

### Instructors and TAs

_If you're a skilled front-end developer:_ Support students who have problems with Bootstrap 4. Answer their questions and help them understand why they ran into their problem.

_If you aren't a skilled front-end developer:_ If students ask you for help and you don't know how to solve the problem, direct them toward the solved file.

Students might encounter the following common problems:
1. A student's link tag for their own custom stylesheet might not be placed below Bootstrap 4's stylesheet.
2. Students might need to use the `!important` tag and not realize it.

### Deliverable

Students will have customized navigation that looks like the following:
![Finished Nav Bar](Images/RN_nav.png)

Now that students have customized their navigation, let's do a quick peer review of each other's work.

## 7. Instructor Do: Webpage Funnel Customization: Part 1 - Navbar Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: If you’ve made one of the TAs a co-host of the webinar, they should create breakout rooms for the groups of students to review the activity. Follow [these instructions](https://docs.google.com/document/d/1LxiakaFMQ7FlnhcbgnZvW7bCqGBeDx1SJgZ8qMWVLAg/edit?usp=sharing) to pre-assign breakout rooms for this review. 

**Review Heights and Widths.**

**Say:** "In the previous activity, you might have noticed that we used ```height: calc(100vh - 25px);```. We'll discuss this in the following section."

> :key: **Key Tech Note:** **Heights and widths** can both be calculated using math and the `calc()` CSS property. It will take a measurement of the browser window (height or width) and calculate the remaining space based on parameters you enter. This technique is commonly employed using -100px (as an example). The code used in the activity will fill 100% of the viewer height minus 25px.

**Review Activity.**

To ensure students get the most from what they just learned, invite them to review each other's work. Have students pair up in groups of two to three and ask each other the following questions:

1. "Did you have any trouble overwriting Bootstrap 4? See if they can fix the problem together."
2. "Are there any design choices that you would do differently for this navigation?"

- Offer students actionable feedback that they can apply to their work. For example:
1. Any CSS property in Bootstrap can be overridden to match your design file. Try overriding CSS properties with `!important` if you can't get it to work correctly.
2. Navbars can display as a sidebar or on the top of your website. How your navigation displays is up to you as a designer.

Share a common misconception or FAQ about customizing Bootstrap 4 components. For example:

	- Bootstrap components are designed to be overridden. Components are used to speed your workflow.

Next, you'll demo how to customize the jumbotron component.

## 8. Instructor Do: UI Elements: Jumbotrons (5 min)

A **jumbotron **indicates a big box for calling extra attention to some special content or information.

Students will also learn how to responsively set heights of elements that calculate based on the height of the viewport window.

As you give the demo, encourage students to think about how these components can be altered in a more professional-looking, user-centered fashion.

Inside a jumbotron, you can put nearly any valid HTML—including other Bootstrap elements/classes.

> :key: **Key Tech Note:** Jumbotrons are highly customizable and are used to focus users on a specific CTA (the most important one). Being able to use ANY markdown in a jumbotron makes customizing the message you send very open!

**Say:** Let's make our jumbotron more appealing and teach our students some more CSS tricks along the way.

## 9. Instructor Do:  Customize Our Jumbotron! Demo (10 min)

> :globe_with_meridians: Online Recommendation: Navigate away from the slideshow for this demonstration. If you shared your entire desktop, make sure to open your files on that shared desktop. If you shared a single window, be sure to re-share your screen to capture the appropriate window or desktop.
Remember to narrate what you are doing during transitions and demonstrations. In this instance, you might say:
“I’m now going to switch from the slideshow to another tab so I can demonstrate jQuery and JavaScript toggles.”

In this demo, you'll show how to customize a jumbotron component to look like a real hero section, complete with a CTA. The key takeaway is that students will be able to take a basic component and turn it into professional-looking work *fast*.

> :globe_with_meridians: **Online Recommendation:** Since you’ll be sharing your screen for this demonstration, ask students to use the raise hands feature on Zoom to ask questions. At a good breaking point, call on a specific student to unmute and ask their question. Alternatively, you can ask students to share their questions in the Zoom chat and have the TA provide answers in the chat.

1. Target the class "jumbotron" for our element with the class jumbotron.

	The result should look like the following:

	```css
	.jumbotron {

	}
	```

2. Let's give this jumbotron a height. Add the CSS property 

	```css
	height: calc(100vh - 25px);
	```

	Tell the class that you can use `calc()` in either height or width to calculate the remaining space.

3. Add the CSS property.

	```css
	background-image: url(../images/rockOn_dark.jpg);
	```

	This property adds a background-image on the element you added it on.

4. Add the CSS property.

	```css
	background-size: cover;
	```

	This property will stretch a background image to fill the entire background of its container.

5. Add the CSS property.

	```css
	background-repeat: no-repeat;
	```

	By default, background images will tile in the background of our image. No-repeat prevents that from happening.

6. Let's turn our jumbotron into a Flex container to easily control our content inside of it. 

	Give display flex to the jumbotron.

	```css
	.jumbotron {
		display: flex;
	}
	```

- Bootstrap 4 is written using Flex. Any of the Flexible Box Modal properties we have discussed in Unit 17 apply here in Bootstrap 4.

7. Lastly, let's center our content using align-items and justify-content. What we learned in Unit 17 is still applicable here.

	```css
	.jumbotron {
		display: flex;
		align-items: center;
		justify-content: center;
	} 
	```

	The result should look like this:

	```css
	.jumbotron {
		height: calc(100vh - 25px);
		background-image: url(../images/rockOn_dark.jpg);
		background-size: cover;
		background-repeat: no-repeat;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	```

> Instructor Note: Pause here to take questions.

> :globe_with_meridians: Online Recommendation: Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> - Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen.
>
> - Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

Students have learned some interesting tricks and should start feeling capable of using CSS to overwrite templates. Next, they'll practice customizing a jumbotron on their own.

## 10. Student Do: Webpage Funnel Customization: Part 2 - Jumbotron Activity (15 min)

> :globe_with_meridians: **Online Recommendation:** This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.2/20.2-02-Webpage Funnel Customization: Part 2 - Jumbotron](https://docs.google.com/document/d/1B5FJCLNvi6sY3yHQiYEA6SY-T2duL2HglzhNd0pOAzA/edit?usp=sharing).

### Summary

Students will customize a jumbotron themselves. During the process, students will learn about overriding Bootstrap 4 styles and learn some new tricks using view height to calculate the height of an element.

### Instructions

Students will follow the instructions in the activity document:

Part 1: Update the HTML of the jumbotron element.

Part 2: Update the CSS of the jumbotron element.

*If students struggle:* Double-check the placement of the student's stylesheet; it must be second to the Bootstrap 4's CDN link tag. If that doesn't work, play with the student's code in the Web Inspector and use the `!important` tag to override difficult CSS properties.

*If students complete the activity early:* Share the following [resource](https://hackerthemes.com/kit/) with them.

### Instructors and TAs

_If you're a skilled front-end developer:_ Support students who have problems with Bootstrap 4. Answer their questions and help them understand why they ran into their problem.

_If you aren't a skilled front-end developer:_ If a student asks you for help and you don't know how to solve the problem, direct them toward the solved file.

Students might encounter the following common problems:
1. The student's link tag for their own custom stylesheet might not be placed below Bootstrap 4's stylesheet.
2. Students may need to use the `!important` tag and not realize it.

### Deliverable

Students will have customized hero images that resemble the following:
![Finished Hero Image](Images/RN_hero.png)

Before we move onto the next section, let's review each other's work and talk as a group.

## 11. Instructor Do: Webpage Funnel Customization: Part 2 - Jumbotron Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: If you’ve made one of the TAs a co-host of the webinar, they should create breakout rooms for the groups of students to review the activity. Follow [these instructions](https://docs.google.com/document/d/1LxiakaFMQ7FlnhcbgnZvW7bCqGBeDx1SJgZ8qMWVLAg/edit?usp=sharing) to pre-assign breakout rooms for this review.

To recap what students just learned, have them review each other's work.

**Ask the class to take a screenshot of their work and share via Slack.**

Students should discuss in their groups:

1. "Did you have any trouble centering the content inside the jumbotron?"
2. "Are there any design choices that you would do differently for this jumbotron?"

Offer students actionable feedback that they can apply to their work. For example:
1. There are multiple jumbotron components you can use in your work. Pick the one that best fits your design.
2. Don't just customize the layout of your jumbotron—try building new content inside of it.

Share some common misconceptions or FAQs about customizing Bootstrap 4 components. For example:
1. Jumbotrons can be given background images or colors depending on your preference.
2. Jumbotrons can be turned into full-screen images or just a section on a website. What CSS you use to customize your jumbotron is up to you.

> Instructor Note: Pause and take any remaining questions.

After the break, you'll give another demo.

## 12. Break (15 min)

Break time! Encourage students to stretch, get some fresh air, and/or grab a snack.

When they return, you'll giving a demo on customizing template cards.

## 13. Instructor Do: UI Elements: Cards (5 min)

> 📌 Your goal in this section is to introduce students to the UI card element and give students some best practices when it comes to designing cards for the web. This lecture and the demo that follows prepare students for the third (and last) learning objective of the day, which is to design and code a fully responsive, customized Bootstrap 4 template.

> :briefcase: **Employer Competitive Note:** Cards are a common UI component on the web and can be designed in many different ways. As a UX designer, by customizing Bootstrap cards, you can create designs and prototypes that use cards in unique and eye-catching ways.

Begin by introducing the problem that cards solve.

**Ask:**

1. "Can anyone think of a container that holds a few related things?" 

	_All responses are welcome and don't have to be UX/UI-specific; e.g., jewelry box, a Ziplock bag, or a silverware drawer._

2. "What about a container that holds related things *connecting* to a container with more related things?" 

	_This one's harder. Responses might include a post office box, a window display at a department store, or a car sales lot.)_

**Cards** are UI elements used to separate similar content visually with a literal box. The purpose of cards is to make your content more digestible by grouping elements together that have related content.

**Connect cards to UX/UI.**

Cards are a design pattern we discussed during the UI section of the UX/UI Boot Camp. You'll see cards in both Google's material design toolkit and on popular websites like Facebook or Twitter.

> :gem: **Designer Insight**: Take a moment to share how you've used cards in your design work.

Students have seen cards if you use the internet. Websites like Facebook, Twitter, and Pinterest are places where cards as a design trend became popular.

![Card example](Images/cards_annotated.png)

Point out how each card contains only information that relates to everything else on the card? Cards take your content and break it into bitesize chunks for our users.

### Card Design Best Practices

1. **Keep it simple.** Cards are used to focus our users on specific information. Everything in the card should be relevant.
2. **Direct your user to the desired action.** Users will automatically want to click on cards when they see them. Give them clear CTAs and ways to convert on your content.
3. **Use images strategically.** Use eye-catching imagery that relates to the topic of the card. If the images and headline don’t match, there will be confusion.
4. **Support micro-interactions.** Even simple interactions add life to your cards (like, share, favorite button, etc.).

## 14. Instructor Do: Customize Bootstrap 4 Cards Demo (5 min)

> :pushpin: Your goal is to reintroduce students to Bootstrap's grid system and show them how to add Bootstrap 4's col classes to the layout to make it respond correctly. Reinforce how Bootstrap's col system works by customizing how our cards respond to our template.

> :globe_with_meridians: **Online Recommendation**: Navigate away from the slideshow for this demonstration. If you shared your entire desktop, make sure to open your files on that shared desktop. If you shared a single window, be sure to re-share your screen to capture the appropriate window or desktop.

Remember to narrate what you are doing during transitions and demonstrations. In this instance, you might say:
“I’m now going to switch from the slideshow to another tab so I can demonstrate jQuery and JavaScript toggles.”

In this demo, you'll demonstrate how to alter card components using Bootstrap 4's col system to respond based on your layout's needs. First, we'll cover some basic information on cards.

> :globe_with_meridians: **Online Recommendation:** Since you’ll be sharing your screen for this demonstration, ask students to use the raise hands feature on Zoom to ask questions. At a good breaking point, call on a specific student to unmute and ask their question. Alternatively, you can ask students to share their questions in the Zoom chat and have the TA provide answers in the chat.

We need to update our containers to fit a three-column layout.

In your cards, update the col classes to look like this:

```html
<div class="cardContainer col-lg-4 col-md-4 col-sm-12">
```

- Do this to the cards on lines 66, 79, and 92.
- Explain to the class the math behind the col classes.
  - col-lg-4 will create a 3-column responsive layout for screen sizes greater than or equal to 992px.
  - col-md-4 will create a 3-column responsive layout for screen sizes greater than or equal to 720px.
  - col-sm-12 will create a 1-column layout for screen sizes up to 576px.

> Instructor Note: Pause here to take questions.

> :globe_with_meridians: **Online Recommendation:** Take a moment to check in with the class and see how comfortable they feel about the material covered.
>
> - Stop sharing your screen for a moment and switch to gallery view in Zoom to see your class on one screen.
>
> - Ask the class to use the Zoom meeting reactions found in the Meeting Controls panel at the bottom of the Zoom window to use the thumbs up 👍 or clap 👏 emojis if they're feeling comfortable and confident with the material you've covered so far.

Next, students will customize the card elements in their template.

## 15. Student Do: Webpage Funnel Customization: Part 3 - Cards Activity (15 min)

> :globe_with_meridians: **Online Recommendation**: This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.2/20.2-03-Webpage Funnel Customization: Part 3 - Cards](https://docs.google.com/document/d/1JSYEZt2cUCgUgNvRfwPryoSKZDsikVTmGRqzlt1M3v8/edit?usp=sharing).

### Summary

Students will customize the cards on their template site.

### Instructions

Students will follow the instructions in the activity document:

Part 1: Update the HTML of the cards.

Part 2: Update the CSS of the cards.

*If students struggle:* Double-check the placement of the student's stylesheet; it must be second to the Bootstrap 4's CDN link tag. If that doesn't work, play with the student's code in the Web Inspector and use the `!important` tag to override difficult CSS properties.

*If students complete the activity early:* Share the following [resource](https://www.smashingmagazine.com/2016/10/designing-card-based-user-interfaces/) with them.

### Instructors and TAs

_If you're a skilled front-end developer:_ Support students who have problems with Bootstrap 4. Answer their questions and help them understand why they ran into their problem.

_If you aren't a skilled front-end developer:_ If a student asks you for help and you don't know how to solve the problem, direct them toward the solved file.

Students might encounter the following common problems:
1. A student's link tag for their own custom stylesheet might not be placed below Bootstrap 4's stylesheet.
2. Students might need to use the `!important` tag and not realize it.

With the instructional staff, help students who are stuck and give design tips for how to make the copy visually pleasing.

### Deliverable

Students will have customized cards that resemble the following:
![Finished Cards](Images/RN_cards.png)

Let's review each other's work before moving onto the next activity.

## 16. Instructor Do: Webpage Funnel Customization: Part 3 - Cards Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: If you’ve made one of the TAs a co-host of the webinar, they should create breakout rooms for the groups of students to review the activity. Follow [these instructions](https://docs.google.com/document/d/1LxiakaFMQ7FlnhcbgnZvW7bCqGBeDx1SJgZ8qMWVLAg/edit?usp=sharing) to pre-assign breakout rooms for this review.

To recap what students just learned, have them review each other's work.

**Ask the class to take a screenshot of their work and share via Slack.**

Students should discuss in their groups:
1. "Do you like the images used here?"
2. "How would you tweak this design?"
3. "Did you have any trouble getting your cards to respond correctly?"

Offer students actionable feedback that they can apply to their work. For example:
1. Bootstrap 4 is built using CSS Flex. When customizing components, keep in mind that any CSS Flex property will work on any Bootstrap 4 components.
2. Bootstrap 4 components' responsiveness can be altered by using different column classes. Try to alter the responsiveness of your template by using the different classes.

> Instructor Note: Pause to take questions before moving on to the next student activity.

Share some common misconceptions or FAQs about customizing Bootstrap 4 components. For example:
1. Cards can be filled with text, a CTA, or just an image. The way your card displays is up to you as a designer.
2. Bootstrap components can be hidden and shown depending on what device your user views your website on. Use `display: none;` and `display: block;` to control what content displays on mobile versus desktop.

Next, students are going to continue using CSS and HTML to customize their content by jumping right into the next activity.

## 17. Student Do: Webpage Funnel Customization: Part 4 - Content Activity (15 min)

> :globe_with_meridians: **Online Recommendation**: This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

-	Broadcast a two-minute warning to help them wrap up this work session.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.2/20.2-04-Webpage Funnel Customization: Part 4 - Content](https://docs.google.com/document/d/1UvdQrop4ffTjWWhuu4i7Xe3FteocsFmli7kzsQR8hS4/edit?usp=sharing).

### Summary

Students will practice their HTML and CSS skills by continuing to customize their templates.

### Instructions

Students will follow the instructions in the activity document:

Part 1: Update the HTML to customize their content.

Part 2: Update the CSS to customize their content.

*If students struggle:* Double-check the placement of the student's stylesheet---it must be second to the Bootstrap 4's CDN link tag. If that doesn't work, play with the student's code in the Web Inspector and use the `!important` tag to override difficult CSS properties.

*If students complete the activity early:* Share the following [resource](https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/bootstrap-grid-system.php) with them.

### Instructors and TAs

_If you're a skilled front-end developer:_ Support students who have problems with Bootstrap 4. Answer their questions and help them understand why they ran into their problem.

_If you aren't a skilled front-end developer:_ If students ask you for help and you don't know how to solve the problem, direct them toward the solved file.

Students might encounter the following common problems:
1. A student's link tag for their own custom stylesheet might not be placed below Bootstrap 4's stylesheet.
2. Students might need to use the `!important` tag and not realize it.

### Deliverable

Students will have customized containers that look like the following:
![Finished Cards](Images/RN_rows.png)

## 18. Instructor Do: Webpage Funnel Customization: Part 4 - Content Activity Review (3 min)

> :globe_with_meridians: **Online Recommendation**: If you’ve made one of the TAs a co-host of the webinar, they should create breakout rooms for the groups of students to review the prior activity. Follow [these instructions](https://docs.google.com/document/d/1LxiakaFMQ7FlnhcbgnZvW7bCqGBeDx1SJgZ8qMWVLAg/edit?usp=sharing) to pre-assign breakout rooms for this review.

Call attention back to the class and encourage students to get into groups to reflect on the activity.

Students should discuss in their groups:
1. "Do you like how the content is laid out here? What would do you differently?"
2. "Did you have any trouble getting your containers to work properly?"

Offer students actionable feedback that they can apply to their work. For example:
1. You can have your layout display as either columns or rows—just apply flex direction to alter the behavior of your columns.
2. Use multiple rows in your layout. Rows are used to separate content and can also be customized to suit your design.

> Instructor Note: Pause to take questions before moving on to the next student activity.

Share a common misconception or FAQ about customizing Bootstrap 4 components. For example:

- Bootstrap might not seem flexible at first, but with CSS Flex knowledge you can achieve any layout you can design.

## 19. Student Do: Webpage Funnel Customization: Part 5 - Footer Activity (15 min)

> :globe_with_meridians: **Online Recommendation:** This activity should be done individually, so you don’t need to create breakout rooms. Instead, make sure the whole class is muted and switch to Zoom gallery view so you can monitor students as they work. Tell them that if they have a question, they should share it on the #ClassActivities Slack channel and a member of the instructional staff will respond. If a student has a question that is relevant to the whole class, you or one of the TAs should unmute and share your answer with everyone.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.2/20.2-05-Webpage Funnel Customization: Part 5 - Footer](https://docs.google.com/document/d/1pqHowqD6MDxCxIrK9EpT-dL9wfzNOEg_dGiE2oBWUZs/edit?usp=sharing).

### Summary

Students will customize their footer content to create a CTA.

### Instructions

Students will follow the instructions in the activity document:

Part 1: Update the HTML to customize the footer.
Part 2: Update the CSS to customize the footer.

*If students struggle:* Double-check the placement of the student's stylesheet; it must be second to the Bootstrap 4's CDN link tag. If that doesn't work, play with the student's code in the Web Inspector and use the `!important` tag to override difficult CSS properties.

*If students complete the activity early:* Share the following [resource](https://www.orbitmedia.com/blog/website-footer-design-best-practices/) with them.

### Instructors and TAs

_If you're a skilled front-end developer:_ Support students who have problems with Bootstrap 4. Answer their questions and help them understand why they ran into their problem.

_If you aren't a skilled front-end developer:_ If students ask you for help and you don't know how to solve the problem, direct them toward the solved file.

Students might encounter the following common problem:
- Students might place the footer in the incorrect location---double-check the placement of the student's HTML.

### Deliverable

Students will have customized containers that look like the following:
![Finished Cards](Images/RN_rows.png)

## 20. Instructor Do: Webpage Funnel Customization: Part 5 - Footer Review (3 min)

Call attention back to the class and encourage students to get into groups to reflect on the activity.

Students should discuss in their groups:
1. "Do you think our footer did an effective job of catching our users who made it to the bottom?"
2. "Why or why not?"
3. "How might you better catch your users' attention?"

Offer students actionable feedback that they can apply to their work. For example:
1. Footers serve as a catchall. If users don't find what they're looking for, make sure you have ways to keep your user engaged when they reach your footer (search forms, links to other pages on the site, etc.).
2. Build your own columns inside your footer using Bootstrap 4's col system.

> Instructor Note: Pause to take questions before moving on to the next student activity.

Share some common misconceptions or FAQs about Bootstrap 4 footer components. For example:
1. For professional websites, footers often contain legal information on the use of the particular site. Make sure you have all the relevant information in your footer for users exploring your site.
2. You can custom-build elements in a Bootstrap template. Just because you installed Bootstrap doesn't mean you have to adhere strictly to using it.

Next, students will dive into another activity aimed at customizing their webpage funnel.

## 21. Student Do: Iterate Your Webpage Funnel Activity (40 min)

> :globe_with_meridians: **Online Recommendation**: This activity begins individually, then switches to pair work. While the students are working solo, make sure the whole class is muted and switch to Zoom gallery view to monitor students. While this is taking place, have your TAs create breakout rooms for the upcoming pair work. Follow [these instructions](https://docs.google.com/document/d/1LxiakaFMQ7FlnhcbgnZvW7bCqGBeDx1SJgZ8qMWVLAg/edit?usp=sharing) to pre-assign breakout rooms for this and future activities. 

-	Broadcast a two-minute warning to help them wrap up this work session.

**TAs:** Slack out the activity file: [20-Week/02-Activities/20.2/20.2-06-Iterate On Your Funnel](https://docs.google.com/document/d/1GF1ewdOFSZleU7IcKV5Y5-gylqDttC8GUOi5Cqiy4RU/edit?usp=sharing).

### Summary

Now that students have completed their templates, it's time to iterate on their work.

### Instructions

> Instructor Note: Students will work alone and then in pairs for this activity.

**Part 1:** Students will independently iterate their work by further customizing the sections of their template and applying what they've learned about website funnels.

**Part 2:** Students will host their pages on GitHub Pages by creating and cloning a new repo, then uploading and publishing their site.

**Part 3:** Students will review each other's work and provide feedback on the website funnel in particular.

*If students struggle:* Students might not 100% know how they want to rearrange their content. If this happens, discuss user funnels with the student and show examples of how other sites make value propositions on their sites to spark creativity.

*If students complete the activity early:* Review their work and have them explain the reasoning behind their user funnel redesign. What is the most important CTA? How are they advertising features of the site?

### Instructors and TAs

> Instructor Note: This is a long activity and the review that follows is short, so be sure to address student questions **as they arise** during this activity period.

_If you're a skilled front-end developer:_ Support students who have problems with Bootstrap 4. Answer their questions and help them understand why they ran into their problem.

_If you aren't a skilled front-end developer:_ Monitor students and discuss webpage funnels and how students can focus on theirs.

Students might encounter the following common problems:
1. Students might get creatively blocked on how to redesign the funnel.
2. Students might have difficulty rearranging the elements on the site.

### Deliverable

The deliverable is a customized webpage funnel based off the template we created in class.

## 22. Instructor Do: Iterate Your Webpage Funnel Activity Review (5 min)

> :globe_with_meridians: **Online Recommendation**: Since students can’t physically come to the front of the class to demonstrate, stop sharing your screen and ask a student to share their screen instead. Once they are finished, ask them to stop sharing so you can reshare your screen.

Now that we have finished iterating on our work, take a screenshot or host your webpage on GitHub Pages.

- Have your class share their URL or screenshot in Slack.
- Pick one or two sites and ask the student:
  - Why did you redesign your user funnel this way?
  - In your opinion, what is the most important CTA you were trying to highlight?

- Have students leave feedback on at least two other students' sites about what they did or didn't like, using the design thinking critique script: 
  - "I liked x, y, and z."
  - "What I think could be different/better/improved is x, y, and z."

Offer students actionable feedback that they can apply to their work. For example:
1. Always put your most important CTA first. The most important CTA should also appear multiple times in your user funnel.
2. Sections should always have a specific purpose in mind; when designing, decide what purpose each section has and how together they create an experience for your user.

> Instructor Note: Pause for questions.
>
> - If there are any time-consuming questions, invite students to stay for office hours.

Share some common misconceptions or FAQs about user funnels. For example:
1. "User funnel" is actually a marketing term that applies to design and web work.
2. Keep your user flow simple---cluttered UIs will cause your users to bounce off your page. Less is more in most instances!

Now it's time to recap and end the class.

## 23. Instructor Do: Recap and End Class (5 min)

**Review Concepts**

**Ask:**
- "What is a webpage funnel and why is it important?"
- "How is it related to a CTA?"
- "Which components did we customize today?"
- "Did anyone have trouble customizing any components? What problems did you encounter?"

Great job!

Thank the class for their work today.

Let them know that in the next lesson, we'll wear the hat of a freelance web developer, create a Bootstrap 4 template based on a design prompt, and cover how to be a successful freelancer.

**Office Hours**

Remind students that you're holding office hours and are available to help your class with whatever questions or problems they may have.

Say goodnight and dismiss the class.

---

## We Want Your Feedback!

Instructor, how did tonight's class go?

Please submit any issues or comments on the UX/UI curriculum to our Google Form:

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

View the status of your submission and other issues here:

[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing)


---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.	
