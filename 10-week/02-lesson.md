# 10.2 Lesson Plan: UI and Atomic Design

---

## Overview

In today's class, students will learn atomic design principles and practice building wireframes and mockups. This will enable them to think about and design responsive web solutions that are a system of prototyped components.

Lesson 10.1 covered the fundamentals of interaction design (IxD), designing for the interaction between users and systems, including mental models, habit loops, and micro-interactions. In the next class, Lesson 10.3, you'll help students build their UI skills, learn the value of buttons, and design a mobile UI prototype. All together, Unit 10 prepares students for creating high-fidelity responsive web prototypes that can be tested by users.

## Learning Objectives

By the end of class today, students will be able to:

1. Articulate how a UI is a collection of parts broken into atoms, molecules, organisms, templates, and pages, according to the atomic design framework.

2. Annotate the atomic design organisms of an e-commerce website using Figma/Adobe XD.

3. Design and annotate a wireframe in InVision Freehand.

4. Create a website mockup using the material design library in Figma/Adobe XD.

## Class at a Glance

- Welcome to Lesson 10.2 on UI and atomic design. It has three conceptual parts:

  - Part 1 will introduce atomic design.
  - Part 2 will discuss wireframes, type hierarchy, and UI components.
    - Students will build a wireframe using InVision Freehand.
  - Part 3 will cover style guides, the material design library, and mockups.
    - Students will design a unique mockup using a UI library kit and Figma/Adobe XD.

By the end of today's class, students will have confidence in building a UI and all the interactions associated with an interface.

## Instructor Notes

Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.

🌐 **Online Recommendation:** Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here are some examples of what you can say during common transitions:
- From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”
- From sharing the slideshow to sharing a tab on your browser: “Bear with me as I switch over to my browser for the next demonstration.”

Transitions and activities tend to take longer in virtual classrooms. If you find that you are running short on time, feel free to combine the activity and review sections by doing each activity as a class instead of creating breakout groups.  

## Preparing for Class

Review slides for today: [10-week/01-Slides/10.2-UX-UI-Atomic-Design Slides](https://drive.google.com/open?id=1LmNUkvvLLLiaGB1F7etzzPbXLnqWvVSyJq9_vr_HdIw).

In advance of class:
  - Remind students on Slack to review InVision Freehand before class.
  - Share your favorite UI resources, videos, and articles on Slack to prime students' minds for today's topics.

Students might not finish their work (wireframes specifically) during class. Remind them that office hours are an appropriate time for completing that work—while the lesson is fresh.

If needed, review the Strategies for Class Online in the unit README.

---

## Class Video

- [Class Video:](https://codingbootcamp.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ef9f033a-c983-4cf6-a030-aa9301730557) Watch a sample video of this class being taught by Holly Reynolds.

## Time Tracker

- Keep track of the clock. Have TAs consult the [10-Week/04-Time Trackers/10.2-Timetracker](https://docs.google.com/spreadsheets/d/1Y3-kDMin_Spbp5uXQT3tPvvGer93ggzFI1SaiIyNTG4/edit#gid=746489284).


- Use an online timer to manage activities, whether you start it up at the beginning of activities or you ask a TA to do so. There's a Chrome extension you can download: [Chrome Timer Extension](https://chrome.google.com/webstore/detail/timer/edebbhkhcaafmolanelponjjanocpacd?hl=en).

---

## Office Hours: Reviews and Practice (45 min before class)

Encourage your students to use office hours. By the same token, encourage them to make the most out of class by asking questions, which has benefits for their classmates.

---

## 1. Instructor Do: Welcome and Share Today's Objectives (3 min)

- Open up the slides for today's lecture: [10-week/01-Slides/10.2-UX-UI-Atomic-Design Slides](https://drive.google.com/open?id=1LmNUkvvLLLiaGB1F7etzzPbXLnqWvVSyJq9_vr_HdIw).

  - **TAs:** Make a PDF copy and share in Google drive for class. Share slides in Slack.

  - UI design will continue to get harder, so students should practice often at home.

- Get students in the right mind frame to begin learning about the concept of atomic design. Without getting into atomic design itself specifically, talk about concepts in the world that are similar. For example:

  - **Say"** "A house can be thought of as one thing, a house, or it can be thought of as composed of many components: boards, nails, windows, and a concrete foundation. Today's concept will require you to understand the parts as well as the whole."


**Share today's learning objectives.**

- Connect today's atomic design lesson to what students studied in the early UX weeks of the boot camp. For example:

  - During the UX units, we practiced solving problems by considering users' needs. Today we address how to solve our users' needs across multiple devices through considering the web system.

  - Solving the right problem requires iterate > prototype > test. Today we will dive deeper into UI prototypes through applying atomic-level design.

  - In UX, we designed at a lower fidelity to learn from our users early and often. Today we will explore working on prototypes at a higher fidelity through executing our responsive prototypes with UI kits of material design.


## 2. Instructor Do: Atomic Design and UI Systems (15 min)

> :pushpin: **Important Point:** Your goal is to get students to think about UI design through a conceptual mental model, where a website is made of parts that build a whole. This section supports today's first two learning objectives: (1) to identify and name the atomic design components of a webpage, and (2) to use Adobe XD to annotate those components of a webpage.

In this section, you're going to encourage students to see webpages as UI systems. We want them to understand the pieces that comprise the whole.


## SLIDES 1-4
Review

## SLIDE 5
- > **Ask:** "Has anyone seen the Milky Way?"... "Tell us briefly where you were when you saw it and how that made you feel."
    
- What does the Milky Way have to do with UX design? Well, it requires us to think conceptually, especially since we can only see an exceedingly small part of it. The cosmos is large and complex, yet it has order. Just like UX/UI design.

## SLIDE 6
  - **Read the quote of** Clement Mok, a graphic designer and author.

- The cosmos is helpful to keep in mind as a way to think about atomic design. This is because what might seem vast and hard to approach, like space, has order and structure, and we will break it down into its individual parts.


## SLIDE 7
Atomic design is a methodology for designing within dynamic systems as a way to create systems that consider the parts that build the whole.


## SLIDE 8
**What**
Atomic design is a methodology comprised of 5 levels which we use to evaluate and organize complex UI systems, typically in preparation for building design systems.
The levels are:
- Atoms
- Molecules
- Organisms
- Templates
- Pages

**When**
- In preparation for designing and developing a design system
- working to establish rules about visual design surrounding consistency, maintenance and organization


**Why**
- Design systems are often large, complex systems that can be difficult to maintain just due to size. Atomic design can help add clarity both when dealing with maintenance as well as when preparing to create new systems though giving teams a shared understanding and langauge for the components.


## SLIDE 9
Review

## SLIDE 10
_Read quote from Brad_
- Developer Brad Frost authored *Atomic Design*, which provides a methodology for crafting design systems.

"Atomic design is a process that considers the parts of a web or app system to help us build the whole experience through code."

- Atomic design employs a scientific lexicon for building interfaces: Atoms > Molecules > Organisms > Templates > Pages.

- **TAs:** Slack out in the #resource channel [Brad Frost's *Atomic Design*](http://atomicdesign.bradfrost.com/) for students to read at home.


## SLIDE 11
1. **Atoms:**

   - Atoms are the basic building blocks of matter. When applied to web interfaces, atoms are our HTML tags, such as a form label, an input, or a button.
   - Using our earlier "house" metaphor, think of atoms as nails, tile, or lumber.
   - Discuss atoms as the smallest pieces of your system.

## SLIDE 12
2. **Molecules:**

   - Molecules are groups of atoms bonded together and are the fundamental units of a compound. These molecules take on their own properties and serve as the backbone of our design systems.
   - Using the "house" metaphor, think of molecules as windows (glass and lumber) or a door (lumber and doorknob and hinges).
   - Building up from atoms to molecules encourages “doing one thing and doing it well.”

## SLIDES 13-14
3. **Organisms:**

   - Organisms are groups of molecules joined together to form a relatively complex, distinct section of an interface.
   - Using the "house" metaphor, think of organisms as windows and doors, which together could create a sunporch or solarium.
   - Building up from molecules to organisms encourages creating standalone, portable, reusable components.
   - > **Say:** "We discussed content chunking. An organism is a chunk."

## SLIDE 15
4. **Templates:**

   - Templates consist mostly of groups of organisms stitched together to form pages.
   - Templates begin their lives as wireframes, HTML/low-fidelity prototypes. Over time, templates increase fidelity to become the final deliverable.
   - Using the "house" metaphor, think of a template as a closet and room paired with windows and doors to create a bedroom. This "template" could be used in several house designs in a development.
   - Templates are reusable and can be filled with different types of content.

## SLIDE 16
5. **Pages:**
Pages are specific instances of templates. Here, placeholder content is replaced with real representative content to give an accurate depiction of what a user will see.
- Pages apply content and have the highest level of fidelity because they’re the most tangible.
- Pages are most applicable to websites due to the fact they are designed as paged experiences. Still, app screens can also be designed into similar pages of the experience. For example, in Slack, all channels use the same page layout.
- Using our "house" metaphor, think of pages as adding actual home furnishings to bare rooms, bringing the space to life.

## SLIDE 17
Pages are the place to test variations in templates... 

## SLIDE 18
"We’re not designing pages; we’re designing systems of components."

## SLIDE 19
Atoms make up molecules. Molecules make up organisms. Organisms make up templates and templates can be used to build pages.

## SLIDE 20
Questions??

## SLIDES 21-28
Review 

## SLIDE 29
Questions?

## SLIDES 30-31
## 3. Student Do: Atomic Design e-Commerce Analysis Activity (20 min)

**TAs:** Slack out to students the following Google Doc activity in the #_in_class_chat:
[10-Week/02-Activities/10.2/10.2-01-Atomic-Organism-Redesign-Activity Google Doc](https://drive.google.com/open?id=1JGbyZvjYzyiKWiyl4afw3kawNClWknE3QbDOgm-ruQM)

**Instructor and TAs:** Monitor students during this short activity to make sure they're making progress.

> :globe_with_meridians: **Online Recommendation:** Get students into Zoom breakout rooms of two to six people, with TAs assigned to assist. TAs can reference the agency selection template to establish these student groupings. If students need more time, you can reduce the review time. Encourage the use of Slack for getting help.

**Summary**

Here, students will get hands-on practice identifying and then creating atomic elements for their government agency sites.

*Tips for students who struggle*: Have students start top-down on a webpage and tell them not to jump around the page.

*For students who finish early*: This should not be a problem, but if they finish early, have them jump-start on their challenge by reviewing an additional webpage.

**Instructions**

1. Students should pair up with a classmate who is working on the same government agency (2 min).

2. Together, they'll decide which page to analyze for this activity. Working separately, they'll explain the atomic organisms on the webpage (13 min).

3. Finally, they should identify an organism to redesign and sketch out a new organism for the page (5 min).

**Deliverable**

Students will share a photo of their sketched organism via Slack.


## SLIDE 32
## 4. Instructor Do: Atomic Design e-Commerce Analysis Activity Review (10 min)

Call the class back to attention, and lead a review of the atomic organism samples.

> :globe_with_meridians: **Online Recommendation:** Move students out of breakout rooms and back into the main Zoom room.

- First, scroll through all the shared redesigns on Slack.
- Aim to review two to three samples.

- **Select the first design and ask the student:**

  - "Were all the atoms necessary?"
    - "What were you trying to make important?"
  - "Did your partner help with the iterations?"
    - "What do you like, and what would you have done differently?"

- Invite the class to share their feedback.

- Discuss a few others.

- Provide students with a few pieces of actionable feedback that they can apply directly to their work the next time they apply high-fidelity mockups, for example:

  - Don't be sloppy with analysis—all elements should be accounted for.

  - Look for consistent labels and naming of organisms. For example, "UI component card" is not as informative as "image card," "video card," "type card," etc.

- Finally, discuss any **common misconceptions and FAQs** about atomic analysis. For example:

  - "Atomic analysis is not useful when designing something new." *False.* No software solution is done in a vacuum, and if it is, you are doing it wrong. Evaluating what works and how UI is designed will help you solve interface problems.

  - "Not all teams use atomic design" *True but false.* Atomic design is a mental model for considering all the parts of a UI. If a design team chooses not to "call it" atomic design, that is fine, but they are using the same concepts when producing UI.

> **Instructor Note:** Share a personal story of having to defend UI decisions to your team or clients.

Now that students know how to see the system components and not just the whole, they have a foundation for appreciating wireframes, which we build from components, which are covered in the next section.


## SLIDE 33
Review

## SLIDE 34
Review

## SLIDE 35
- A wireframe is made up of three essential parts:

1. Content layout and grid use
2. Type hierarchy
3. UI components

- The wireframe will show the arrangement of the content on your site. Wireframes typically include navigation, interface elements, copy, and so on. Wireframing is just a part of the design process. It should focus on your user's needs when interacting with content, which requires considering the context (mobile, tablet, desktop, etc.).

- The context includes the interface modality and the content, which is something you can only hope to put together if you understand the user's goal, the product or service, the value proposition, and the actual message.


## SLIDE 36
Review elements of a wireframe

- **TAs:** Slack out in the #resources channel [The Hipper Element](https://thehipperelement.com/post/53283081651/protip-tuesday-8-what-isnt-a-wireframe) for students to read at home.

## SLIDES 37-41
Review

## SLIDE 42
### Six Issues to Address in a Wireframe

1. **Clarity:** Right at the top of your page, you need to have your value proposition answering basic questions for the visitor.

2. **Focus:** Keeping your user focused on the task of the page (read: conversion) is the primary goal.

3. **User confidence:** Can the user feel confident that yours is a trustworthy business?


## SLIDE 43
4. **Social proof:** No one wants to be the first one to buy your product or service. It’s too risky.

5. **Reduce friction:** Some friction-reducing elements include shorter sentences and paragraph structures that can be scanned and that consider how people read on the web.

6. **Microcopy:** Refers to the tiny tidbits of copy found on websites, applications, and products. These short sentences tell a user what to do. Microcopy addresses user concerns, provides context to a situation, and helps determine the greater story about your brand/product and how you do business.


## SLIDE 44
Questions?

## SLIDE 45
Review

## SLIDE 46
Type hierarchy is a system for organizing type that establishes an order of importance, allowing the reader to quickly navigate content and find what they want.

## SLIDE 47
### Type Size
Type size is the first place to start with hierarchy. In HTML, typography tags establish a default set of sizes. H1-H6 HTML elements: We'll explore more of this in front-end development, but start thinking about how type is an essential piece of UI systems and website code systems.

## SLIDE 48
### Type Weight and Proportion
Along with size, type weight can help clarify what is essential or not. Use the two-thirds rule: two typefaces with three weights each. Type proportion refers to the proportion of the width of a character to its height.

- **TAs:** Slack out in the #resources channel the following to help students improve their typography skills at home:

  - [https://www.fonts.com/content/learning/fontology/level-1/type-anatomy/weight-and-proportion](https://www.fonts.com/content/learning/fontology/level-1/type-anatomy/weight-and-proportion)

  - [https://www.fonts.com/content/learning/fontology/level-2](https://www.fonts.com/content/learning/fontology/level-2)

## SLIDE 49
### Type Positioning 
Where sections of information are positioned in relationship to each other can establish a hierarchy.


## SLIDE 50
Review

## SLIDE 51
Buttons, toggles, dropdowns, checkboxes, these are typically in a more generic way as "components" or "elements" - thought you'll find out that both words are also used to describe not just Atoms but also Molecules and Organisms.

## SLIDE 52
Input patterns include elements such as checkboxes, radio buttons, many of the items we just talked about. 

## SLIDE 53
These patterns include things like breadcrumbs, sliders, searches, pagination and scrolling, etc.

## SLIDE 54
Information patterns include tooltips, icons, progress bars, notifications, cards and modals.


## SLIDE 55
Questions?

## SLIDE 56
Review

## SLIDE 57
Cards are a common UI component. They became almost a default option when balancing UI aesthetics with excellent usability. Cards are a big trend in UI design.

## SLIDES 58-60
Review

## SLIDE 61
Questions??

## SLIDES 62-63
## 6. Student Do: InVision Freehand Wireframe Activity (15 min)

**TAs:** Slack out to students the instructions: [10-Week/02-Activities/10.2/10.2-02-InVision-Freehand-Wireframe-Activity Google Doc](https://drive.google.com/open?id=1emIDU-aVbQa4laSL0dudRXe253tYdZm3teUopoza1sc).

**Instructor and TAs:** Monitor students during this short activity to make sure they're collaborating.

> :globe_with_meridians: **Online Recommendation:** Allow groups to use either InVision Freehand or Figma. Get students into Zoom breakout rooms of two to four people with TAs assigned to assist in the rooms. TAs can reference the agency selection template to establish these student groupings. Assign a student leader who shares their workspace and screen in the breakout room. If students need more time, you can reduce the review time.

**Summary**

This activity allows students to apply their knowledge of wireframing in Figma/Adobe XD to wireframing in InVision with the Freehand tool. Point out that sketching with the Freehand tool can be faster (with practice), allowing for quicker iteration, feedback, and collaboration with design teams.

- Assign a group leader who sets up the InVision Freehand space and invites their fellow group members.

*Tips for students who struggle*: Make sure they are starting with simple sketching tools. Lines first.

*For students who finish early*: This should not be a problem but have groups keep iterating and annotating their wireframe sketch.

**Instructions**

1. Working in groups, students will first choose an interior page of their government agency website to work on (5 min). 

2. Using Freehand, they will work together to create a wireframe of the page (10 min).

**Deliverable**

Students will submit via Slack a screenshot of the wireframe they created with the Freehand tool.

## SLIDE 64
## 7. Instructor Do: InVision Freehand Wireframe Activity Review (10 min)

Call the class back to attention and lead a critique of students' InVision Freehand work.

> :globe_with_meridians: **Online Recommendation:** Get students out of breakout rooms and back into the main Zoom room.

- Aim to review the work of two to three students.

- Choose a file from Slack and ask the student:
  - Can you walk me through your process?
  - What worked well?
  - What would you do differently?

- Ask a student from a different group to offer feedback:
  - What is one thing you like about this wireframe?
  - What is one thing you would do differently?

- Ask a TA:
  - What is one thing you like about this wireframe?
  - What is one thing you would do differently?

- Provide your own feedback, too:
  - What is one thing you like about this wireframe?
  - What is one thing you would do differently?

Repeat this critique process for one to two more designs.

- Provide students with a couple of pieces of actionable feedback that they can apply directly to their work the next time they apply high-fidelity mockups, for example:

  - Even if your wireframe doesn't look like a "normal" wireframe, as long as it solves a problem, you're on the right track.  

  - Perhaps your wireframe sketch does not have a clear grid or layout logic. However, it’s important to create one to support the design—12 columns can make: 2 column (6x6), 3 column (4x4x4), and 4 column (3x3x3x3) layouts quickly.

- Finally, discuss any **common misconceptions and FAQs** about collaborative design. For example:

  - "No one will wireframe as a team." *False.* Collaboration tools like Figma are becoming the standard, not the exception.

  - "Teamwork and collaborative tools have their limits" *True.* Every tool and, for that matter, every team member, has their limits. However, solving problems as a team can mitigate risk and raise the quality bar faster.

> **Instructor Note:** Be sure to encourage students to stay for office hours to complete their wireframes.

Hopefully, students feel more competent at building a wireframe and appreciate how a wireframe is the sum of its parts (layout plus type plus UI components).

## SLIDE 65
## 8. Break (15 min)

## SLIDE 66
Review

## SLIDE 67
### Style Guides

Whether you’re overseeing the marketing efforts in a large B2B organization or running a startup, a style guide should be an integral component of your marketing strategy. A style guide or manual of style is a set of standards for the writing, formatting, and design of documents.

- A style guide is a document that provides guidelines for the way your brand should be presented from both a visual and a language perspective. The purpose of a style guide is to make sure that multiple people contribute to a design and that they do so clearly and cohesively in a way that reflects the corporate style and ensures brand consistency with everything from design to writing.

- Style guides are maintained by a design and development team.

#### Typography

Typography is one of the most common interface design elements, so it’s not enough to merely list the names of typefaces used in a product. Clear instructions should be given in your style guides for titles, subtitles, headings (H1, H2, H3), body text, and captions.

- For example, the "Typography" section of Firefox's UI Style Guide gives detailed instructions for creating readable text with a clear design hierarchy.

  - Additionally, font sizes should be provided, weights indicated, and styles defined. Line height and kerning (the space between letters) are also needed, and it’s a good idea to single out a go-to font to be used when exceptional circumstances arise.

## SLIDE 68
#### Color Palette

One of the quickest ways to wreck an interface is inconsistent color use, so color combinations need to be clearly defined.

- Listing colors and their values (hex, UIColor) is a good start. Still, specific pairings and use examples should also be given.

- For example, in addition to a broad color palette that includes a range of lighter secondary colors, IBM's UI Style Guide demonstrates how to apply specific schemes (like this triadic example) to its products.

## SLIDE 69
#### Buttons 

Nearly every interface includes buttons, so take time to document their sizes, styles, colors, placement, spacing, and typographic elements.

- A style guide should define all the various buttons that are used in different contexts as well as their interaction states to make that clear as well.

#### Other UI Components

Components may be necessary depending on the content, website, or application intent, and the data being used or collected.

- For example, components include iconography, tooltips and popovers, modals, form elements, data tables, navigation menus, charts and data visualizations, tabs, dialogs, toolbars, date, and time pickers, loading indicators, checkboxes, alerts, and dropdown menus.

In addition to must-have UI components, several practical features make UI style guides easier for businesses and design teams to reference, navigate, and implement, such as:

## SLIDE 70
#### Table of Contents

A well-organized and marked table of contents is a simple way to help everyone quickly find what’s inside the document.

#### Dos and Don'ts

Frequently, it can be helpful to outline design dos and don’ts clearly.

- For example, “*Do use the white wordmark version of our company logo in the interface footer.*”

- “*Don’t use alternate color versions of our company wordmark on black backgrounds.*”

- **TAs:** Slack out in the #resource channel: [https://www.frontify.com/](https://www.frontify.com/) for students to explore at home.


## SLIDE 71
Questions??

## SLIDE 72
Review

## SLIDES 73-74

Mockups are a visual representation of an app, product, or website. While a wireframe mostly represents a product’s structure, a mockup shows what a product is going to look like. However, a mockup is not clickable (just like the wireframe). A mockup is either a mid- or high-fidelity display of design.

- A mockup helps you make final decisions regarding a product’s color scheme, visual style, and typography. With a mockup, you can allow yourself to experiment with the visual side of the product to see what looks best. 

- Here again, you can ask your potential users for feedback and make the necessary changes right away. Getting feedback throughout the design process can save you a lot of time, as you can avoid making adjustments to the UI after you have launched the product.

- You can't sketch a mockup. Mockups are made using design tools.


- **TAs:** Slack out these links in the #resources channel for students to nerd out at home:
  - [https://material.io/design/](https://material.io/design/)
  - [https://www.youtube.com/watch?v=tfSiXRy1vEw](https://www.youtube.com/watch?v=tfSiXRy1vEw)

## SLIDE 76
Questions??

## SLIDE 77-78
## 10. Student Do: Material Design Mockup Activity (40 min)

It's time to practice creating a mockup using the material design library.

**TAs:** Slack students the following Google Doc activity file:
[10-Week/02-Activities/10.2/10.2-03-Material-Design-Mockup-Activity Google Doc](https://drive.google.com/open?id=1zhr1CjlFl9hJLFcqDj7HkIweic8F3BcJt20SX-Xv2J8)

**Instructor and TAs:** Monitor students and offer support if they need help assembling material design elements.

> **Instructor Note:** Encourage students to have fun with this activity. Remind them they have longer than usual for this activity.

> :globe_with_meridians: **Online Recommendation:** Students will be working individually, so keep them in the main Zoom room and have them all share their screens. During review, take volunteers to highlight.

**Summary**

This activity allows students to apply their knowledge of wireframes and mockups while designing in Figma/Adobe XD.

*Tips for students who struggle*: Help students start top-down and start them out with creating a grid to apply UI components.

*For students who finish early*: This should not be a problem, but have students improve their mockups with interactive elements or work on other pages for their challenge.

**Instructions**

1. Working independently, students will first download the Figma/Adobe XD files and the material design GUI shared via Slack (5 min).

2. Next, students will resketch the Figma/Adobe XD wireframe they downloaded. Then they’ll design a mockup based on the sketch and apply material design elements (35 min).

**Deliverable**

Students will take a screenshot of their wireframe and share it via Slack.

## SLIDE 79
## 11. Instructor Do: Material Design Mockup Activity Review (15 min)

Call the class back to attention and lead a review of the mockups.

> :globe_with_meridians: **Online Recommendation:** Students will be working individually, so keep all students in the main Zoom room and have them all share their screens. During review, take volunteers to highlight.

- Aim to review the work of two to four students.

**Discuss the following with the class:**

- What works here?
- What would you do differently?
- Where do you see the material design library at work in this mockup? 
  - Could the library have been used more effectively?
- Discuss the page layout logic (two columns or three columns, etc.). 
  - Why have they chosen this layout strategy?

**Ask:**
- "Did anyone find the UI library limiting? Why?"
- "What did you gain from using the UI library?"

- Provide students with a few pieces of actionable feedback that they can apply directly to their work the next time they apply high-fidelity mockups. For example:

  - *Usable* is more valuable to your user than *pretty*. So focus on solving your user's problems rather than on using material design UI elements.
  - Call out if material design elements have been modified beyond recognition.

- Finally, discuss any **common misconceptions and FAQs** about webpage mockups. For example:
  - "Designers get hours to design webpages." *False (sometimes true).* Your ability to produce solutions quickly is essential and many times on the job you will need to solve problems efficiently. Good thing we are practicing in this boot camp!
  - "Using UI kits is cheating" *False.* You have the opportunity to stand on the shoulders of giants. Take it and show how you can elevate the solutions from the platform you have been given.

:gem: **Designer Insight:** Share a personal story about developing mockups and applying the material design library in your own design work.

Students should now be fully steeped in how to evolve a wireframe into a mockup, while still remembering to regard a website as a system of components.

## 12. Instructor Do: Recap and End Class (2 min)

You did it!

**Review today's concepts: atomic design, wireframing, typography, and UI style guides.**

Spend a couple of minutes helping students anchor today’s learning by asking students to raise their hands—or post answers in Slack—and offer definitions for the following concepts, all learned today in class:

1. Ask students to recall the components that comprise atomic design—see what students can remember.
   - Feel free to go back to the beginning of your slides to find the atomic design section.
   - *Answer: atoms, molecules, organisms, templates, and pages.*

2. What are the three parts that comprise a wireframe?
   - *Answer: layout, type hierarchy, and components.*

3. What is the value of a style guide when designing a mockup?
   - *Answer: Defines the rules of your visual execution.*

4. How do high-fidelity mockups differ from wireframes?
   - *Answer: They apply all the visual design and content needed to make a screen design closer to the finished product.*

### Challenge

Students will need to use these skills we just practiced for challenge not procrastinate!

- Everyone should be adding to and iterating their InVision prototypes and making progress on their challenge!

### Office Hours

Remind students that you're holding office hours after class to help them. 

Take questions and wish everyone a good night.

---

## We Want Your Feedback!

Instructor, how was class tonight?

Please submit any issues or comments on the UX/UI curriculum to our Google Form. [Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform).

With this form, you can now view the status of your submission and other issues here: [Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing).

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
