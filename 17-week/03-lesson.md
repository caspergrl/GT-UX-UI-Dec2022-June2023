# 17.3 Lesson Plan: Positioning Elements on the Web

---

## Overview

Last class, students learned how to add styling to a webpage using CSS. Today's class will be about positioning elements on a webpage using HTML and CSS. Specifically, students will code a webpage using HTML/CSS and host it on GitHub Pages.

## Learning Objectives

By the end of class today, students will:

1. Position HTML elements using CSS floats and automatic margins.
2. Position inline, block, and inline-block HTML elements to build webpages.
3. Create HTML divs that overlap by positioning elements absolutely with CSS.
4. Code their first webpage and host it via GitHub Pages to become their first website.

## Class at a Glance

Today you will prepare students for positioning elements on the web. We have organized today's lesson into three parts.

**Part 1: Positioning HTML Elements**

During this part of the lesson, students will be practicing HTML elements using floats and margins. Afterward, students will learn about inline, block, and inline-block elements and how you can use them to build HTML elements.

**Part 2: CSS Display Property**

Students will practice using the display property to position HTML elements using relative, absolute, and fixed positioning.

**Part 3: GitHub and GitHub Desktop**

The last part of today's class is a challenge: build a one-page site about yourself.

After you finish, use GitHub Desktop to publish the website on GitHub Pages!

---


## Prepare for Class

**Review the slides beforehand**.

- [17-Week/01-Slides/17.3-Positioning Elements on the Web Slides](https://docs.google.com/presentation/d/1w1s9uOz4DdkIpROULSvo-31kl5FpQA1Kcws8xegzJOk/)

- Make any teaching notes you'll need.

- As you lecture, relate your own on-the-job experience whenever possible to bring what students are learning to life and connect it to their future goals.

**Prepare to support students building their first webpages**.

- Today is going to be the students' first time creating and coding a webpage on their own.

- Your learners will have *many* questions. Students are still beginners in the world of web development. You'll encounter questions about common developer workflows as well as the following topics:

    1. Creating a file structure using various operating system tools and text editor functions
    2. Creating a workspace in a text editor
    3. Leaving tags open and "breaking" the HTML
    4. Confusing the class and ID tags
    5. Operating GitHub Desktop

 - Students might become frustrated as they learn how to be front-end web developers. Reassure students that web development is hard at first—after all, the students are learning two new languages, HTML and CSS. Over time, by practicing and researching HTML/CSS problems, students will grow into great front-end developers.

**Brush up on your skills.**
  - Be sure to brush up on your positioning fundamentals, as this is going to account for the vast majority of questions.
  - Review [Positioning at W3Schools](https://www.w3schools.com/Css/css_positioning.asp).

**Prepare to help students learn GitHub**.

  - Navigating GitHub and uploading files to a cloud repository can present a challenge for students. Be sure to brush up on your GitHub skills and practice today's in-class demo before the class starts.
  - Providing a clear and concise explanation of how these technologies work is of the utmost importance. Generally, even if the demo is sound, some students will still experience trouble uploading files to GitHub.
  - Be prepared for Git problems and helping students troubleshoot. Here are some common Git problems that you will likely encounter:
    1. Students having difficulty moving their project files into the folder tracked by Git. If you encounter a student with this issue, check the student's file path in GitHub Desktop. Using GitHub Desktop, open the branch that the students want to update and click the view in the finder button to locate the root folder.
    ![View Git repo in Finder](Images/viewInFinder.jpg)

    2. Students having trouble successfully cloning a repo. It's easy to forget that you can find the initial URL to clone a project off [github.com](https://github.com). Locate the main repository page and show the student the URL that needs to be copied.
    ![GitHub URL location](Images/clone_github.jpg)

    Alternatively, students can clone their project off GitHub Desktop. Click File -> Clone and the  window below will appear. Select the repo the student is attempting to clone.

    ![GitHub Desktop clone](Images/github_desktop_clone.jpg)

    3. Students who are beginners to Git will often be confused by the concept that Git "tracks" changes in a file. To explain this concept to a student, open a file in a student repository, make changes to a file, and then save it. Show the branch in GitHub Desktop that is now tracking the changes to it. Show the students how to save their changes in a commit and push them back up to a cloud repository.

**Run through your demo in advance.**

- There is one demo today. You will give a demo of GitHub Pages, showing students how to create and clone a repository (Section 13).

- If needed, review the Strategies for Class Online in the unit README.

---


## Class Materials

- Please come to class with the activity files downloaded for today. The zip file contains both a solved and unsolved file. Lean on the solved file to show students the differences between the solved code and theirs if you are not a strong front-end developer. The zip file is located [17-Week/02-Activities/17.3/17.3_activities.zip](https://drive.google.com/a/2tor.com/file/d/1g8Tusp2fGTYFFUtIQ04UCUyfv9Bygxxb/view?usp=sharing).

- Bring your laptop for the presentation.

## Time Tracker

- Keep track of the clock. Have the TAs consult the [17-Week/04-Time Trackers/17.3 Time Tracker](https://docs.google.com/spreadsheets/u/1/d/1yWSOVx8wxwOWeXN6CS3KYOLEeg2-2Wna0xYsMn7ww1o/).

- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

---


## Office Hours: Review and Practice (45 min before class)

> **Instructor Note:** Encourage your students to make the most out of class and not to be afraid to ask questions.
>
> - Do your part by engaging students.

---

## 1. Instructor Do: Welcome the Class and Share Learning Objectives (2 min)

Open the [17-Week/01-Slides/17.3-Positioning Elements on the Web Slides](https://docs.google.com/presentation/d/1w1s9uOz4DdkIpROULSvo-31kl5FpQA1Kcws8xegzJOk/).

> :globe_with_meridians: Online Recommendation: Use a Slack poll (https://www.polly.ai/Slack-poll) or Zoom poll (https://support.zoom.us/hc/en-us/articles/213756303-Polling-for-meetings). To quickly engage your students on how they are feeling about code so far. 

Welcome the class and tell students, "Today, we will get more in-depth into HTML and CSS positioning by learning about floats, the display property, and the position property."

***First, define positioning***.

Positioning is a broad term used to describe several CSS properties that are used to move HTML elements on a page.

For this lesson, we'll teach students about the basics of positioning HTML elements. Today students will be introduced to the following CSS properties:
1. Floats
2. Display
3. Position

In the previous lessons, we learned about the basics of creating folder structure and files specific to web files. Students also learned about the basics of building HTML elements. For students to succeed, they must now learn how to position the HTML elements they create in their layout.

> :briefcase: **Connect the concept to design jobs**: Say how understanding the basics of positioning HTML elements has helped you construct layouts. Alternatively, prompt the TAs to share their experiences.

- If students are proficient in the different ways to position elements on the web, the work will be evident in their portfolios with pixel-perfect code.

Positioning sounds like a minor detail, but it is fundamentally the hardest concept to grasp for new front-end developers. There are many nuances to positioning elements and the best way to learn is to try and see for yourself.

- Let students know that today you will discuss how to position elements with floats and the display property as well as using positioning to create unique layouts.

- After you discuss positioning fundamentals, students will be creating their own webpage.

Students will use the positioning properties they learn to then upload the webpage to GitHub for publishing via GitHub Pages.

:gem: **Designer Insight**: A concept like positioning elements is second nature to designers, so take a moment to acknowledge where you do this in your own work. Positioning on the web allows designers to create complex layouts with overlapping elements. Feel free to share examples of complex layouts that you have seen used on the web (think LinkedIn's or Facebook's profile pages, which have two elements that overlap).

Once you've given the class a broad view of what they'll be learning and accomplishing today, dive into a discussion about floats and the display property.

## 2. Instructor Do: CSS Float and Display Properties (5 min)

> :pushpin: **Important Point:** Your goal is threefold: help students understand how to position elements on a webpage, explain the uses for floats, and explain how the display property helps to build content on a webpage. This section supports learning objective No. 1: Position HTML elements using CSS floats and automatic margins.

> :globe_with_meridians: Online Recommendation: Encourage students to use Zoom raise hand or come off mute at any time to ask a question. 

With this first lecture, you'll be explaining two methods that designers use to control the order and style of content on a page (i.e., how a page looks).



## SLIDES 1-5
Review

## SLIDE 6
Review

## SLIDE 7
**CSS Float Property**

- The CSS float property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, which means that it will no longer affect the box model of other divs around it.

## SLIDE 8
- CSS float can also be used to float two items next to each other.

- Using CSS float to build parent containers is not recommended—there are definite drawbacks to using such an approach because a floated element’s height and width will no longer affect its siblings. This can cause an overlap of divs and create a strange effect.

When an element is applied with either float: left or float: right, its height and width will no longer be calculated with its parent containers. This can cause the parent container to collapse because it doesn't contain any content according to our browser!

- Additionally, floated elements will sometimes get stuck on other elements—this can only be fixed by using the CSS property clear. Clear will force our HTML element to flow around any element it is stuck on.

- Because of these issues, we do not recommend using float for layouts. Use floats for their intended purpose, which is *floating text around an image.*

## SLIDE 9
Review

## SLIDE 10
Review

## SLIDE 11
**CSS Display Property**

The display property specifies if and how an element is displayed.

- Display is fundamentally the most important CSS property for controlling layouts.

Every HTML element has a default display value depending on what type of element it is and how it is defined in the browser's inherit stylesheet. The default display value for most elements is block or inline.

There are three CSS display properties that students should know:

- display: inline
- display: block
- display: inline-block

These three display values are the basics. Each HTML element by default will be either inline, block, or inline-block. Having an understanding of these three values will allow students to build UI elements quickly and correctly.


## SLIDE 12
Review

## SLIDES 13-14
**Positioning Block-Level HTML Elements**

Let's define what properties a block element has.

- A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

- Some examples of block-level elements are div tags, p tags, and ul tags.

This means that block elements are normally used as containers for inline elements (we'll define those next). Containers are often used to build elements like forms and then position them appropriately in containers.

## SLIDE 15
Review

## SLIDE 16
**Positioning Inline HTML Elements**

First, let's define what properties an inline element has. An inline HTML element does not start on a new line and only takes up as much width as necessary.

- Some examples of inline HTML elements are span tags and b tags and the actual text that you write into your text editor (the stuff between the tags).

- Inline HTML elements can be positioned by using text-align on its parent container if you need your text to align to a certain side.

This can also be accomplished by setting the display property of an element to inline and then manipulating it by setting text-align on its parent.

## SLIDE 17
Review

## SLIDE 18
Review

## SLIDE 19
Display: inline-block; sets an HTML element to display as an inline-block container through a CSS class or ID. The element itself is formatted as an inline element, but you can apply height and width values.

## SLIDES 20-21
Inline-block HTML elements:

- Allow other elements to sit to their left and right.
- Respect top and bottom margins and padding.
- Respect height and width.

A good example of an inline-block element is the image tag because they will align next to other inline-block elements but can be modified with box model properties.

- Inline block elements can also be used to create layouts by putting two inline-block elements next to each other and setting their width to 30% on one and 69% on the other. An obvious question to ask about this is, Why don't our numbers add up to 100%?

- That is because inline-block elements still display as inline, causing spaces to be recognized around them. This prevents you from creating perfectly responsive layouts using inline-block, but you can get close—and for some layouts, this approach works quite well.

## SLIDE 22
Review

## SLIDE 23
Review

## SLIDE 24
Review

## SLIDE 25
**CSS - Width-Based Percentages**

Setting pixel widths and heights are fine for a warm-up in creating elements. However, the webpages of today are often responsive—they change their structure based on the width of the browser window.

- This can be accomplished by setting the width of an element to 100%—block-level elements do this by default.

- When you set an element to width: 100%, what you're telling your browser is: make this element’s content area exactly equal to the explicit width of its parent.

- Imagine you have a parent container that’s 400px wide. A child element given a width of 100% will also be 400px wide. This container will still be subject to margins, paddings, and borders—which can break your layout if these exceed 100% width.

Margins and paddings can also be given percentage-based widths, and they work in the same way as any other percentage-based layout.

## SLIDES 26-28
Review

## SLIDE 29

**What is an inline HTML element, and how does it display?**

_Answer:_ Inline HTML elements are tags that only take up as much space as necessary and will line up next to other inline-elements.

**What is an inline-block HTML element, and how does it display?**

_Answer:_ An inline-block HTML element will display inline (line up next to inline and other inline block-level elements), but its height/width can be manipulated.

**What is an HTML block-level element, and how does it display?**

_Answer:_ A block-level HTML element always takes up 100% of its parent container and causes other content to start at a new line.


## SLIDE 30
## 4. Student Do: Practice With CSS Positioning Activity (20 min)

**TAs,** Slack out the following instructions to students: [17-Week/02-Activities/17.3/17.3-01-Practive-With-CSS-Positioning](https://docs.google.com/document/u/1/d/1crjj3CrJU-2g0xcbHXPM7K8kDQWgcPIelvp_6L_W9Uw/).

**Summary**

Students will practice positioning by building three basic page layouts.

**Instructions**

Students will open their index.html file.

First, they will add floats by following the steps in the Activity instructions doc. Next, they will add the block and inline elements to their page. Finally, they will position the inline-block elements on their page.

*If students struggle during this activity,* check their syntax. Show the student how to double-check if their syntax is correct by searching on Google for the CSS property that was causing the student problems. Make sure you add w3 at the end of your search to find a basic explanation of the property for beginners.

*If students complete the activity early,* be sure to approach the students and ask them questions about their portfolio.

**Deliverable**

Students will take a screenshot of their work and share it on the Slack channel. They will have created three basic page layouts and practiced positioning elements on those pages, including text, containers, and images.

**Support students while they work.**

Walk the room and help students who lose their place or become stuck with coding. Feel free to encourage them to get help from classmates as well.

## SLIDE 31
## 5. Instructor Do: Practice With CSS Positioning Activity Review (5 min)

Call attention back to the front of the class and lead a review of the positioning activity.

> :globe_with_meridians: Online Recommendation: Pull up the solution file and have students share their screen to discuss their success or failure. 

Begin the review by taking a look at some of the work that was shared on Slack and provide actionable feedback that all students can apply to their work.

- Using floats, margin: 0 auto, and text-align to center and position content on your website is very powerful and a good practice to get into before you start coding responsive websites.

- Many of the tricks you just used in this activity you can apply to all web projects when building a user interface.


## SLIDE 32
Review

## SLIDE 33
In CSS, the position property is used to create complex layouts. For example, the position property enables designers to move page elements to specific positions on a webpage.


## SLIDE 34
There are five properties that you should know:

1. **Static**: We position the element according to the normal flow of the document. Top, right, bottom, left, and z-index does not affect elements that we have not positioned.
- An example of a static element is any element that respects the normal flow of a webpage. Static is the default position property applied.

```css
.myClass {
  position: static;
}
```

## SLIDE 35
2. **Relative**: We position the element as we would normally to the flow of the document, and then it is offset relative to itself based on the values of top, right, bottom, and left. Relative positioning is mainly used to position elements absolutely inside of them.
  - An example of a relative element is the container for any profile picture that overlaps other HTML elements. Think of the container for the profile picture for LinkedIn.
![Relative image example](Images/relative_example.png)
- *Note*: Students need to understand how to use relative and absolute positioning together to create unique layouts. Absolutely positioned elements must be contained inside of a positioned container. The most common position property used is relative.

```css
.myClass {
  position: relative;
}
```

## SLIDE 36
3. **Fixed**: The element is removed from the normal document flow. It is positioned to the viewport of the browser and will always stay where you put it even if the user scrolls down the page.
- An example of a fixed element is a Contact Us button that follows you as you scroll.

```css
.myClass {
  position: fixed;
}
```

## SLIDE 37
4. **Sticky**: This is the newest position property. The element is positioned according to the normal flow of the document, and then offset relative to its nearest scrolling ancestor and containing block.
- An example of a sticky element is a navbar that scrolls with you when you hit a certain height.

```css
.myClass {
  position: sticky;
}
```

## SLIDE 38
5. **Absolute**: This is the hardest position property to master. Absolute elements are removed from the document flow and are in position relative to their nearest-positioned ancestor. If a parent container has any position property applied to it (except static), the absolute will be positioned inside of it. If no element has a stated position, then it will be positioned to the browser viewport or window.
  - An example of an absolutely positioned element is one that breaks out of its bounding box without affecting content around it. *Think of a profile picture for LinkedIn or Facebook.*
![Absolute example](Images/absolute_example.jpg)


```css
.myClass {
  position: absolute;
}
```

🔑**Key Tech Point:** position: relative is often used to contain elements that you are using position: absolute on.

The best way to learn about the different positioning properties is to practice applying them to a page. Let's do that with the student activity that follows.

> **Instructor Note:** Pause and check-in for any questions before moving into an activity to practice.


## SLIDE 39
## 7. Student Do: CSS Positioning With Relative, Absolute, and Fixed Positioning Activity (20 min)

**TAs,** share the following activity instructions with students via Slack: [17-Week/02-Activities/17.3/17.3-02-CSS-Positioning-With-Relative-Absolute-and-Fixed-Positioning](https://docs.google.com/document/d/1J4RYoqbnHaqVHPFDhX9TenI3RULa1YYzmzzsPeJUDiI/).

**Summary**

In this activity, students will be applying three of the positioning properties we just discussed: relative, absolute, and fixed.

**Instructions**

> :globe_with_meridians: Online Recommendation: Keep everyone in the main Zoom room and open 1 or 2 break-out rooms to help students 1 on 1. Recommend having the solution file at hand to share code snipits via Slack. 

Students will start with the index.html and index.css files. Following the instructions and steps in the activity instructions, they will edit relative, absolute, and fixed properties.

*If students struggle*: During this activity students will commonly get tripped up by absolute positioning. Elements positioned absolutely **MUST BE** contained inside another positioned element (commonly relative positioning).

*If students complete the activity early*, have them study and practice with the different types of position/display properties.

**Deliverable**

When students reload their page, they will see the elements they built displayed on the webpage.

## SLIDE 40
## 8. Instructor Do: CSS Positioning With Relative, Absolute, and Fixed Positioning Activity Review (5 min)

Call attention back to the front of the classroom. Discuss with students how to position elements in their design.

A few questions you could ask to get things started:

- ***Which of the CSS positioning properties do you think you will use most often?***
*Answer:* The most commonly used CSS position properties are relative and absolute.
- ***Why would you need to use fixed positioning on an HTML element with CSS?***
*Answer:* Fixed positioning is most commonly used to create a navbar that scrolls with you, or a Contact Us button that scrolls with you.
- ***Which CSS positioning property do you think you would need to test the most?***
*Answer:* The absolute property in tandem with relative positioning to contain it.

> **Instructor Note:** Remind students to stay for office hours if they have any more positioning questions.

Give students some practical, actionable feedback they can apply to their work, for example:

1. It is very common for students to overuse the position property when trying to build user layouts for the first time. Beginners will commonly force their HTML elements into place using absolute or relative positioning, which causes a problem when students attempt to make their website responsive. Students should rely on fully responsive positioning techniques like text-align or automatic margins to make their site responsive and positioned correctly.

2. The hardest to understand position property is absolute positioning. If you're going to use absolute positioning, make sure you study and understand what your HTML element will do when you apply position: absolute to it. Make sure it is contained inside of a positioned container (using relative most commonly).

## SLIDE 41
## 9. Break (10 min)


## SLIDE 42
## 10. Student Do: Build a One-Page Website Challenge (50 min)


**TAs,** Slack out to students the following instructions: [17-Week/02-Activities/17.3/17.3-03-Build-a-One-Page-Website](https://docs.google.com/document/u/1/d/1tMXBI988lmvoDdOnac4GXaYkg9obN7TvwPF8o1ui9Ig/).

**Summary**

Students are going to practice building a basic website. The website will be about their favorite pet.

In the following activity, students will upload their page to GitHub Pages.

> **Instructor Note:** This activity will partially fulfill learning objective No. 4: code a webpage. The other part, to follow later on, is to host the webpage via GitHub Pages.

**Instructions**

> :globe_with_meridians: Online Recommendation: Keep everyone in the main Zoom room and open 1 or 2 break-out rooms to help students 1 on 1. Recommend having the solution file at hand to share code snipits via Slack to keep student moving.

Students will use a wireframe as the basis for their content and apply HTML tags to it following the steps and instructions in the activity doc. Their work is divided into four steps:

1. Navigation

2. Building the body structure of the site

3. Filling in the left column

4. Adding and positioning content

**Deliverable**

Students will take a screenshot of their work and share it on the Slack channel.

**Support students as they work.**

Walk the room with your TAs and offer support where needed as students work through the activity.

## SLIDE 43
## 11. Instructor Do: Build a One-Page Website Challenge Review (5 min)

**Demo** the solution using gray scale colors to represent a wireframe.

- Here is a codepen showcasing the solution file: [code solved one-page webpage scaffolding](https://codepen.io/2u-uxuxi-bootcamp/pen/bGqBEGx).

> :globe_with_meridians:Online Recommendation: Manipulate some of the position elements in the CSS and share the codepen for students to Fork.

Give students some practical, actionable feedback they can apply to their work, for example:
1. All the CSS properties taught today are used interchangeably depending on the layout. Think of the different web skills as tools in your tool belt.
2. Students need to practice; building a single layout is not enough. Encourage students to go home and practice building this layout again or building a different layout

## SLIDE 44
Review

## SLIDES 45-47
**Webpage Vs. Website**

A *webpage* is a domain that is connected to the internet that displays a single HTML document that can be viewed in a web browser. These are often called just "pages." It’s common for portfolio sites to be a webpage.

A *website* is a domain connected to the internet that maintains one or more pages on the World Wide Web. Amazon's website, for example, has thousands of pages. 

> **Instructor Note:** Open up brunoarizio's portfolio page in you browswer and click through a couple webpage. Point out the clean URL structure.

  - a webpage is a unique url. 

    - [https://brunoarizio.com/](https://brunoarizio.com/) > homepage (index.html)

    - [https://brunoarizio.com/about](https://brunoarizio.com/about) > about page (about.html)

    - [https://brunoarizio.com/essays](https://brunoarizio.com/essays) > essays page (essays.html)


> 💎**Designer Insight**: The **difference between a website and a webpage** is that a **website** is a collection of **webpages** with information on a subject. A **webpage** indicates that this site only has one page that a user interacts with.


## SLIDE 48
Review

## SLIDE 49
Review

## SLIDE 50
**Justifying GitHub**

The goal of this section is to justify the use of Git to designers who, up to this point, might not see much value in using developer tools. Git is not easy and will take lots of practice. You will be helping students with Git for the rest of the boot camp. If you're not familiar with Git, it will be key to practice yourself, as you and the TAs will be helping troubleshoot.

- GitHub is software that is used for version control. It is free and open-source.

> 💎**Designer Insight**: The ability to use GitHub will allow you stand out from your UX/UI competition. Although primarily a developer centric platform your ability to navigate these systems will make you more employable on a software team.

- Why Git?

  - It is a version control system that allows team members (developers, UX, UI) to collaborate without overriding each other’s work.

- Git is not easy and has a lot of developer jargon, but we will spend some time getting used to it!

- **TAs,** Slack out resources:

  - [https://www.atlassian.com/git/tutorials/why-git](https://www.atlassian.com/git/tutorials/why-git)

  - [https://medium.com/shyp-design/managing-style-guides-at-shyp-c217116c8126](https://medium.com/shyp-design/managing-style-guides-at-shyp-c217116c8126)

  - [https://www.c-sharpcorner.com/article/what-is-version-control-git-vs-tfs/](https://www.c-sharpcorner.com/article/what-is-version-control-git-vs-tfs/)

  - [https://git-scm.com/book/en/v2/Git-Internals-Git-References](https://git-scm.com/book/en/v2/Git-Internals-Git-References)

## SLIDES 51-58
- Now, let’s understand what version control is.

  - Version control is the management of changes to documents, computer programs, large websites, and other collections of information.

  - Version control saves all the previous changes you make to a file in "commits." Each commit has a unique number that you can use to see how your project has changed over time.

  - This means that projects that are tracked by Git can roll back to previous versions. Having a backup is especially useful if you post incorrect code up to your production server and need to roll it back.

- Different versions are stored locally on your computer in a hidden folder named .git. You won't be able to see this folder unless you have specific permissions set on your computer. We don't recommend you change those settings unless you know what you're doing.

  - So, if the changes are stored locally, how do teams use this tool to collaborate?

  - Enter cloud repositories like GitHub. GitHub is a service that provides a space for developers (and other professionals) to store their projects.

- Using Git, we can push our code up to GitHub's servers, where other people can pull your code to their local machine and work with it.

GitHub is also a valuable skill to have as a UX/UI designer and can be the difference between candidates for open roles. It is common for UX/UI designers to be embedded in dev teams and work on front-end code. Having a base understanding of Git will help you stand out for these roles.

## SLIDE 59
Review

## SLIDES 60-63
**GitHub Desktop Functions**

Using Git, there are four major functions that you will need to be familiar with that will be completed with GitHub Desktop.

_Commit:_ Git commits are used to save the work you have done on your local computer.

_Push:_ Git push is used to push files that you have committed to a cloud repository.

_Pull:_ This will update your local repository with any changes that have been pushed to the remote repository while you were away. This keeps your project synced with your team's work.

![Git pull](Images/gitpull.gif)

**Note:** You should always take a pull before you begin work on a shared repository.

_Merge:_ Merges happen when you have unsaved changes in your local repository and you take a pull. This results in merge conflicts. Merge conflicts occur when your local work and the work in the repository are not the same.

The first thing that happens if you encounter a merge conflict is that GitHub Desktop will kick up an error like so:

![Merge conflict](Images/merge_conflict.gif)

The next step is to open the conflicting file in Visual Studio Code.

- When a merge conflict happens, Git will automatically mark places in your code that are different from the remote repository.

![Visual Studio Code merge conflict](Images/vscode_mergeconflict.png)

Using Visual Studio Code, we can use extensions to help us select which version is the correct and current version. Merge conflicts can be resolved by resolving all these conflicts in our file, then committing the changes and pushing them up to the remote.

![Accept changes](Images/resolveConflict.gif)

After all the conflicting files have been fixed, we can merge our code and push it back to the repo, all in GitHub Desktop.

![Resolve conflict](Images/resolveConflict.png)

**Merge conflicts are the hardest part of learning to use Git. Don't be frustrated if it happens and it takes some time to resolve.**

**Instructors:** Please share the following resources with your class for a Git extension for Visual Studio Code.
[Visual Studio Code Git Package](https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack)

## SLIDE 64
Review

## SLIDES 65-73
**Common GitHub Desktop Workflows**

1. You take a pull from the remote repository to update your code before you start your workday.
2. You make changes to a document and then add it as a commit. You then push the commit up to a repository to update it.
3. You take a pull from a remote repository and encounter a merge conflict. You select the correct version and push the merge to the local repository.

We have spent all this time creating nice layouts. It would be a shame if we didn't show off a little bit.

- The students need a way to host their code, but we don't need to buy server space to accomplish this. GitHub lets you publish your HTML pages to a public URL that anyone can view: GitHub Pages.

- GitHub Pages is a static site-hosting service designed to host your personal, organization, or project pages directly from a GitHub repository.

- You can host as many pages as you want. We will be hosting all of our in-class work and homework here so that employers, friends, and family can view them.

Now that students know what GitHub is, it's time to show them what it looks like in action with a demo.

## SLIDE 74
## 13. Instructor Do: Demo - GitHub Pages (5 min)

> :pushpin: **Important Point:** Your goal for this demo is to instill confidence in students who might be creating their first GitHub repositories and commits.

Remind students that you and the TAs will be able to answer their questions when it's time for them to try this on their own.

:gem: **Designer Insight:** Before jumping into the demo, ask a couple of students who have experience with GitHub to share about their first time using it. This will reassure others new to GitHub and identify classmates who can offer support.

Don't worry about giving the class a comprehensive GitHub tutorial. For now, just provide a general feel for how GitHub works.

**Instructions**

1. Go to [https://www.github.com](https://www.github.com).

   - Create a new repository.

   ![Step 1](Images/1.png)
   ![Step 2](Images/2.png)

2. Make sure you set your repo to "public."
3. Create your repo.

   ![Step 3](Images/3.png)

4. Search for your repo in GitHub Desktop's UI. Do you remember what you named it?
5. Clone your repo to your local machine.

   ![Step 4](Images/4.png)

6. Choose where you want to save the repository in your local directory. Make sure you choose a spot you will remember. Then click "clone."

   ![Step 5](Images/5.png)

7. Drag the files you want to upload to the cloud into the folder you cloned. Make sure your root file is named "index.html" or GitHub won't load your page.

   ![Step 6](Images/6.png)

8. GitHub notices that you have changed the files in the repo and is now tracking it.

9. Enter a description of what is in this commit. Thorough descriptions help you remember what you pushed up each commit and help to backtrack if needed. Only the summary is required. The description is optional.

10. After you have entered your description, click "commit" to master.

Now it's time for students to test this skill out for themselves—that's next!

## SLIDE 75
## 14. Student Do: Upload Your First Webpage to the GitHub Cloud! Challenge (20 min)

**TAs,** Slack out to students the [17-Week/02-Activities/17.3/17.3-04-Upload-Your-First-Webpage-to-the-GitHub-Cloud Instructions](https://docs.google.com/document/d/1nI1a-uNkZiKTtnLZfNpyeTXQx5N-oyG7RHJWbesK20Y/).

**Summary**

Understanding how to push code is important for students—many companies are beginning to use GitHub to manage more than just code projects.

**Instructions**

First, students will create a repository, then clone that repository. From there, they will open the GitHub Desktop tool and follow the instructions in the activity doc. They will add files to their repository, commit their changes and new files, and publish their branch. Finally, they will use GitHub Pages to push their page live to the web.

> **Instructor Note:** Remind students that GitHub can sometimes take up to 15 minutes to make the changes.

**Deliverable**

Once completed, students will see their published webpage appear live on the web.

**Support students as they work.**

Be on hand while students work with GitHub and be willing to demo how to create/clone/commit using GitHub as needed.

Now that students are done uploading their newly created website to github.com, let's review some key concepts.

## SLIDE 76
## 15. Instructor Do: Upload Your First Webpage to the GitHub Cloud! Challenge Review (5 min)

Now that students have gotten their first taste of version control, dig into their work and see where they can reflect and learn.

Some actionable insights and feedback to consider:

1. Keep your Git projects in a single "master" folder. Keeping your projects organized makes it easy to find the folder you cloned your project into and reopen using GitHub Pages.

2. When working on a file that is tracked by Git, any change that you make will appear in your GitHub Desktop UI to be committed to your remote repository.

Next, ask the following questions to test for competency:

**What is GitHub?**

_Answer:_ GitHub is a website that holds cloud repositories.

**Why would you want to publish your work on the web?**

_Answer:_ Publishing your work on the web allows everyone to view your design and coding abilities.

**Ask the class if anyone wants to share their work.**

- Call on two to three students to share their website URL on Slack. Showcase it to the class, and introduce the students.

Afterward, have students:

1. Share their GitHub Pages' URLs in Slack.
2. Open two to three fellow students' work and learn about each other!

That's it! Let's recap the day and end class.

## 16. Instructor Do: Recap and End Class (3 min)

- **Say,** "You did it!""
- Acknowledge the hard work students did today.

**Review concepts.**

Spend a couple of minutes helping students anchor today’s learning. Ask students to raise their hands—or post answers in Slack—and offer definitions for the following concepts, all learned today in class:

1. Ask a few students to explain how floats are used.
2. Ask what margin auto is used for.
3. Ask about positioning elements:

   - What is an inline element?

   - What is a block element?

   - What is an inline-block element?

4. What are the five positioning properties?
5. What are the advantages of GitHub?

Invite final questions and remind students that you are available for office hours—starting *now*!

Say good night, and dismiss the class.

---

## We Want Your Feedback!

Instructor, how did class go?

Please submit any issues or comments on the UX/UI curriculum to our Google Form:

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

View the status of your submission and other issues here:
[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing)


---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved. 	
