# 18.1 Lesson Plan: CSS Flexbox and the Flexible Box Model

---

## Overview

Today’s focus is on positioning elements in HTML documents. Students will learn how to use and apply CSS Flexbox to create rows, columns, and automatically responsive child elements in HTML documents.

For context, Unit 18 is about the CSS Flexible Box Model. Once students complete all three Unit 18 lessons, students will have proficiency in building responsive websites using the CSS Flexible Box Model. Today's lesson covers CSS flex. Students learn how to build responsive containers that display as a row or a column, creating one-dimensional layouts. In 18.2, students learn about CSS Grids, giving students the ability to code two-dimensional layouts. And the final lesson covers web animation, which provides students with the power to create basic web animations. Altogether, these lessons enable students to create flexible layouts that have basic web animation.

## Learning Objectives

By the end of class today, students will be able to:

1. **Create** CSS Flexbox containers and set them to display as a row or a column.

2. **Position** CSS Flexbox items inside containers to create clean and fluid layouts.

3. **Nest** CSS Flexbox containers to control the elements contained inside them.

4. **Apply** CSS Flexbox skills in a coding activity called Jake's Eatery.

## Class at a Glance

1. Part 1: CSS Flexbox basics and concepts like containers, flex1.direction, and an explanation of CSS Flexbox syntax.

1. Part 2: Alignment and nesting with CSS Flexbox.

1. Part 3: A CSS Flexbox activity that uses Jake's Eatery, for which students will build a complete layout using CSS Flexbox.

## Preparing for Class

**Review the slides beforehand**.

- [18-Week/01-Slides/18.1_CSS_FlexAdvanced_Layouts](https://docs.google.com/presentation/d/1jrbItKuXqvHeeF3UwmDtlfkjS027PnudMzO6JUkZk88/edit?usp=sharing)

- Make any teaching notes you'll need.

- As you lecture, relate your own on-the-job experience whenever possible to bring what students are learning to life and connect it to their future goals.

- If you need a refresher on how to use CSS Flexbox for positioning elements, we recommend reading the [Mozilla developer network tutorial](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox). This tutorial describes the CSS Flexbox basics, including how to use the CSS Flexbox layout system to create web layouts.

- If you are unfamiliar with Flexbox, test out the HTML5 [Flexbox Froggy](https://flexboxfroggy.com/) game to review how to use CSS Flexbox to position elements on a webpage.
  - Note: Students will play the Flexbox Froggy game during today's lesson.
- You will give two very brief demos with CodePen—***be sure to run through the demos in advance of the class***. Both demos are part of your Section 2 lecture in which you introduce CSS Flexbox:
  - Demo 1 (Section 3): Showing how to use CSS Flexbox on a parent element.
  - Demo 2 (Section 4): Showing how to use CSS Flexbox to create a column or a row using CSS Flexbox.

- If needed, review the Strategies for Class Online in the unit README.

## Class Materials

See the solved files located in the UX/UI repo at 18-Week/01-Day/Activities if you need something to reference for yourself or a student during the activities.

## Time Trackers

- Keep track of the clock. Have the TAs consult the [18-Week/03-Time Trackers/18.1-Timetracker](https://docs.google.com/spreadsheets/d/1auWRmR3M5xBr3ePiR1yx3kzryZpr7PolN2bUwGPO84A/).


- Use an online timer, which you or your TA can set at the start. You can add a timer to your Chrome browser, found here: [Chrome Timer](https://chrome.google.com/webstore/detail/timer/hepmlgghomccjinhcnkkikjpgkjibglj?hl=en).

## Strategies for Class Online

- The original class materials were not designed for an online class, so there might be some gaps in the instructional materials and the student experience. We know this transition is an inconvenience and that it requires significant preparation and learning from you.

  - The curriculum team will be updating activities and engagement strategies over time.
  
  - Look for the > globe_with_meridians: **Online Recommendation:** icon throughout this lesson plan for tips on how to adapt the activities and reviews for teaching online.

Online teaching strategies:

1. Prebuild and assign Zoom breakout rooms to your TAs to speed up getting into and out of activities.

2. Shorten or combine review times to allow more time for the students on the activities.

3. During reviews, have everyone share their screen. As the instructor, you can then move between students at random, quickly holding everyone accountable and focused during reviews.

   - [https://support.zoom.us/hc/en-us/articles/115000424286-Sharing-Multiple-Screens-Simultaneously](https://support.zoom.us/hc/en-us/articles/115000424286-Sharing-Multiple-Screens-Simultaneously)

4. Assign an activity "Student Lead" for each student breakout group.

   - This means that one student should create, share, and invite fellow activity members to their collaboration document, whether it be a Google Doc, Miro Board, InVision Freehand, Figma Artboard, etc. based on the activity needs.

5. Disable the Zoom chat and focus all communications through Slack.

   - [https://support.zoom.us/hc/en-us/articles/207442843-Disable-Notifications-From-Group-Chat-Mobile-](https://support.zoom.us/hc/en-us/articles/207442843-Disable-Notifications-From-Group-Chat-Mobile-)

6. Shorten lecture times as much as possible to maximize activity interaction and production time.

7. Get creative with office hours.

   - To maximize your time, schedule 10- to 15-minute review blocks for you and the TAs to check in with each student.
   - Use a Slack poll to query your students for topic reviews, tool demos, etc.
     - [https://Slack.com/help/articles/229002507-Create-a-poll-](https://Slack.com/help/articles/229002507-Create-a-poll-)

- Online presentations have their challenges. Know that we appreciate your hard work. The curriculum team is very interested in how things go in your classrooms, both wins and failures. Please post your feedback in the "05-UX-UI-Course channel" or direct message (DM) @jmesias or @mfoley with anything you want to share.

---

## 1. Instructor Do: Welcome the Class and Share Class Objectives (2 min)

Welcome the class to Week 18!

Open and download today's slides, found here: [18-Week/01-Slides/18.1_CSS_FlexAdvanced_Layouts](https://docs.google.com/presentation/d/1jrbItKuXqvHeeF3UwmDtlfkjS027PnudMzO6JUkZk88/edit?usp=sharing).

Today we're covering the Flexible Box Model, which makes our lives easier by simplifying the CSS required for layout and positioning.

Share today's objectives:

1. **Create** CSS Flexbox containers and set them to display as a row or a column.

2. **Position** CSS Flexbox items inside containers to create clean and fluid layouts.

3. **Nest** CSS Flexbox containers to control the elements contained inside them.

4. **Apply** CSS Flexbox skills in a coding activity called Jake's Eatery.

> 💼 **Employer Competitive Note:** When you have a working knowledge of the Flexible Box Model, you can design layouts with Flexbox in mind. As a designer, this allows you to communicate your layout ideas more effectively to developers.

## 2. Instructor Do: Introducing CSS Flexbox (10 min)

> :pushpin: **Important Point:** Your goal in this lecture is to introduce students to key concepts of the Flexbox model, specifically `display: flex;`. Students should understand how Flexbox helps designers create strong layouts.

## SLIDES 1-3
Review

## SLIDE 4
Review

## SLIDE 5
Git/GitHub is a distributed version control system for tracking changes in source code during software development. 

It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.

## SLIDE 6

- Why Git?

  - It is a version control system that allows team members (developers, UX, UI) to collaborate without overriding each other’s work.

- Git is not easy and has a lot of developer jargon, but we will spend some time getting used to it!

- **TAs,** Slack out resources:

  - [https://www.atlassian.com/git/tutorials/why-git](https://www.atlassian.com/git/tutorials/why-git)

  - [https://medium.com/shyp-design/managing-style-guides-at-shyp-c217116c8126](https://medium.com/shyp-design/managing-style-guides-at-shyp-c217116c8126)

  - [https://www.c-sharpcorner.com/article/what-is-version-control-git-vs-tfs/](https://www.c-sharpcorner.com/article/what-is-version-control-git-vs-tfs/)

  - [https://git-scm.com/book/en/v2/Git-Internals-Git-References](https://git-scm.com/book/en/v2/Git-Internals-Git-References)

## SLIDE 7
  - Version control is the management of changes to documents, computer programs, large websites, and other collections of information.

## SLIDE 8
  - Version control saves all the previous changes you make to a file in "commits." Each commit has a unique number that you can use to see how your project has changed over time.

  - This means that projects that are tracked by Git can roll back to previous versions. Having a backup is especially useful if you post incorrect code up to your production server and need to roll it back.

- Different versions are stored locally on your computer in a hidden folder named .git. You won't be able to see this folder unless you have specific permissions set on your computer. We don't recommend you change those settings unless you know what you're doing.


## SLIDE 9
  - So, if the changes are stored locally, how do teams use this tool to collaborate?

  - Enter cloud repositories like GitHub. GitHub is a service that provides a space for developers (and other professionals) to store their projects.

- Using Git, we can push our code up to GitHub's servers, where other people can pull your code to their local machine and work with it.

GitHub is also a valuable skill to have as a UX/UI designer and can be the difference between candidates for open roles. It is common for UX/UI designers to be embedded in dev teams and work on front-end code. Having a base understanding of Git will help you stand out for these roles.

## SLIDE 10
Review

## SLIDE 11
Review

## SLIDE 12
Review

## SLIDE 13
**GitHub Desktop Functions**

_Pull:_ This will update your local repository with any changes that have been pushed to the remote repository while you were away. This keeps your project synced with your team's work.

## SLIDE 14
Review branches

## SLIDE 15
_Push:_ Git push is used to push files that you have committed to a cloud repository.

_Commit:_ Git commits are used to save the work you have done on your local computer.

**Note:** You should always take a pull before you begin work on a shared repository.

_Merge:_ Merges happen when you have unsaved changes in your local repository and you take a pull. This results in merge conflicts. Merge conflicts occur when your local work and the work in the repository are not the same.


## SLIDE 16
Review

## SLIDES 17-25

The first thing that happens if you encounter a merge conflict is that GitHub Desktop will kick up an error like so:
The next step is to open the conflicting file in Visual Studio Code.

- When a merge conflict happens, Git will automatically mark places in your code that are different from the remote repository.


Using Visual Studio Code, we can use extensions to help us select which version is the correct and current version. Merge conflicts can be resolved by resolving all these conflicts in our file, then committing the changes and pushing them up to the remote.


After all the conflicting files have been fixed, we can merge our code and push it back to the repo, all in GitHub Desktop.


**Merge conflicts are the hardest part of learning to use Git. Don't be frustrated if it happens and it takes some time to resolve.**

**Instructors:** Please share the following resources with your class for a Git extension for Visual Studio Code.
[Visual Studio Code Git Package](https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack)

**Common GitHub Desktop Workflows**

1. You take a pull from the remote repository to update your code before you start your workday.
2. You make changes to a document and then add it as a commit. You then push the commit up to a repository to update it.
3. You take a pull from a remote repository and encounter a merge conflict. You select the correct version and push the merge to the local repository.

## SLIDE 27
Review

## SLIDE 28
### What Is CSS Flexbox?

**Ask:** "What are some methods we know for creating layouts?"

- _`block` elements have specified dimensions and occupy whole lines._

- _`inline` elements are automatically sized and share their lines with other elements._

- _`inline-block` elements are a mix of the other two; they have specified dimensions, but also share their lines with other elements._

## SLIDE 29
**CSS Flexbox** is a separate layout model for creating responsive rows or columns.

**Flexbox elements are flexible**; they automatically grow, shrink, squish together, or spread out to fill the available space.


## SLIDE 30
### Why Learn CSS Flexbox?

**Ask:** "If we already know one layout model, why should we learn another?"

Each layout model is best in a different circumstance. Flexbox excels in responsiveness; that is, it allows us to easily create layouts that reposition and scale to fit any display.

In most circumstances, one layout model is not the best solution for all parts of page. Knowing which tool is most suited for each job will save time and make for cleaner CSS.


## SLIDE 31
The following simple layout requirements are challenging to achieve with only the CSS we covered in Unit 17:

- Vertically centering elements. (`margin: auto` only works for horizontal centering.)

## SLIDE 32
- Spacing and sizing elements equally according to the available space (especially in responsive layouts).

## SLIDE 33
- Maintaining consistent container sizes with inconsistent content sizes.

> :gem: **Designer Insight:** Share an experience you had with one of these challenging layouts or a time you simplified CSS code by switching to Flexbox.

> :key: **Key Tech Note:** The difficult layouts shown in this section are technically possible without Flexbox, but those solutions are so unintuitive that they are often considered hacks, workarounds, or exploits.

## SLIDE 34
Review

## SLIDE 35
### How Can We Use CSS Flexbox?

To start using Flexbox, we can use the rule `display: flex` to transform any element into a flex container.

Any elements inside of a flex container are considered **flex items**. These will automatically align themselves in a responsive row.

## SLIDE 36
If we want a column instead of a row, we can add the `flex-direction` property. Note that `row` is the default value, so this is only necessary for flex columns.

## SLIDE 37
1. Open the [demo in CodePen](https://codepen.io/2u-uxuxi-bootcamp/pen/bGqBZPv).

	**Say:** "In this example, we have three child `div`s in one parent `div`. Let's see what happens when we add Flexbox."

1. Add `display: flex;` to the `#parent` CSS rule.

	`#parent` is now a **flex container**, and the other divs are **flex items**. The flex items display in a row, because that is the default flex direction.

	This is the same result we would have gotten from using `display: inline-block;` on the child divs.

1. Add `flex-grow: 1;` to the `#child1` CSS rule.

	`flex-grow` allows a flex item to expand to fill as much space as is available.

1. Add `flex-grow: 2;` to the `#child2` CSS rule.

	The extra horizontal space in `#parent` is divided between `#child1` and `#child2`. `#child2` will try to occupy twice as much of that space, because its `flex-grow` value is twice as much.

1. Add `flex-direction: column;` to the `#parent` CSS rule.

	The flex items display in a column, because we set `flex-direction` to `column`. Extra space is divided in the same way as before, only vertically.

## SLIDE 38
## 4. Student Do: Your First CSS Flexbox Layout Activity (15 min)

**TAs:** Slack out the following Activity file and review it with the class: [18-Week/02-Activities/18.1/18.1_01-Your-First-Flex-Layout](https://docs.google.com/document/u/1/d/11rafjCljboDVLhrT7XrIiFzMjueDqAPX4HlGYZMAHPI/).

> :globe_with_meridians: Online Recommendation: Keep everyone in the main Zoom room during this activity. With the TAs, monitor the students as they work and offer encouragement where needed. If many students have the same question, ask everyone to pause and watch your screen as you explain how students can solve the issue.

### Summary

Let’s show students how easy it is to create layouts using CSS Flexbox. In this activity, students will make **two** CSS Flexbox containers using the `flex-direction` property.

### Instructions

Students will use HTML and CSS to build a one-column layout and a one-row layout using Flexbox.

_If students struggle:_ Check the student's CSS: make sure they're using `flex-direction: row;` or `flex-direction: column;`. If you're not experienced at web development, lean on the solved file to show students how their code is different.

_If students complete the activity early:_ share this [resource](https://yoksel.github.io/flex-cheatsheet/) with them.

### Instructors and TAs

_If you're a skilled front-end developer:_ Support students who have problems with flex. Answer their questions and help them understand why they ran into their problem.

_If you are not a skilled front-end developer:_ If a student asks you for help and you don't know how to solve the problem, direct them toward the solved file.

### Deliverable

Students will create two layouts: one layout will display a column, and the other will display a row.


## SLIDE 39
## 5. Instructor Do: Your First CSS Flexbox Layout Activity Review (5 min)

Bring everyone's attention back to your screen and lead a review of the activity.

Aim to review the work of two to three students (have a few volunteers share work in Slack).

A few questions to prompt a discussion:  

1. What are some different UI elements you have seen recently on the web that were either a column or a row? If the students are having a hard time thinking of UI elements, pull up [Amazon.com](https://www.amazon.com) or another big-name website like [Netflix](https://www.netflix.com/) and point out content that is arranged in a column or a row.
2. Did you find using flex to be easy or hard? Why?
3. Do you have a point or concept you would like to talk about? If so, feel free to bring it up.

Offer students actionable feedback that they can apply to their work, for example:

1. Suggest to students to try specifying height as a percentage for any column layout that has been built with CSS Flex. CSS Flex can make the height of our content responsive, as well as the width.
2. Tell your class that they should try specifying width, margins, and padding to flex items to see how your layout reacts when using CSS Flex.

Next, ensure that the concepts are sinking in with a review:

> globe_with_meridians: **Online Recommendation:**: Students should speak their answers aloud. But it's acceptable for them to type answers into Slack; have TAs monitor those questions.

**Ask:**

- "Why do we use flex?"

	_We use flex to create columns and rows with responsive children elements._

- "What kind of layouts can we create using flex? One-dimensional or two?"

	_One-dimensional._

- "What does it mean to create a one-dimensional layout?"

	_One-dimensional layouts are referring to a layout that is either a column or a row._

## SLIDE 40
Review

## SLIDE 41
Being able to align content in flex is one of the most attractive features of flexbox. We’ll discuss the following two CSS properties:

- `align-items`

- `justify-content`

## SLIDE 42
Review

## SLIDE 43
### The `align-items` Property

The `align-items` property defines the default behavior of flex items as they fill the container and specifies their layout within that container along the cross axis (top-bottom). The property aligns items vertically.

## SLIDE 44
Review

## SLIDE 45
The following values can be used with `align-items`:

- `flex-start` aligns items at the beginning of the container (or top).

## SLIDE 46
- `flex-end` aligns items at the end of the container (bottom).

## SLIDE 47
- `center` centers content vertically in its parent container.

## SLIDE 48
- `baseline` aligns items so that their baselines align.

## SLIDE 49
- `stretch` items stretch to fill the container top-bottom or left-right.


## SLIDE 50
Review

## SLIDE 51
### The `justify-content` Property

The CSS property `justify-content:` is used to distribute content across the left- and right-side of containers, very similar to `margin-left: auto`, or `margin: 0 auto;`.

## SLIDE 52
The following values can be used with `justify-content`:

- `flex-start` flex items align at the start line (this is the default).

- `flex-end` flex items are aligned at the end.

- `center` flex items are aligned in the center of the container similar to `margin: 0 auto;`.

- `space-between` items evenly distributed in the line; the first item is on the start line, the last item is on the end line.

- `space-around` items are evenly distributed in line with equal space around them.

- `space-evenly` items are distributed so that the spacing between any two adjacent alignment subjects, before the first alignment subject, and after the last alignment subject, is the same.


## SLIDE 53
> :key: **Key Tech Note:** You can use `align-items:` and `justify-content:` together to perfectly center items inside of flex containers. These two properties will automatically position items inside their parent container with no need to mess with media queries.

## SLIDE 54
## 7. Student Do: Aligning CSS Flexbox Items Activity (15 min)

**TAs,** Slack out the following file, and review the instructions with students: [18-Week/02-Activities/18.1/18.1_02-Aligning-Flex-Items](https://docs.google.com/document/d/1f3FKw-D7awDDZm93EuImavaOgX2axsskHsv1C1zQgGA/).

> globe_with_meridians: **Online Recommendation:** Keep everyone in the main Zoom room during this activity. With the TAs, monitor the students as they work and offer encouragement where needed. If many students have the same question, ask everyone to pause and watch your screen as you explain how students can solve the issue.

### Summary

In this activity, students learn how easy it is to align items inside their parent containers using CSS Flexbox.

### Instructions

This activity includes three main tasks:

1. The first part is aligning content from top to bottom with `align-items` to see how it affects HTML elements.
2. The second part is using `justify-content` to align items left-right in our HTML.
3. The third part is using both in tandem to see what kinds of alignment you can achieve.

*If students struggle:* Make sure they use the correct CSS property. Check the student's code for the CSS properties `align-items` or `justify-content` (depending on the directions given). If you aren't an experienced web developer, lean on the solved file to show students where their code is different from the solved.

*If students complete the activity early:* you should share the following resources with them about [justify-content](https://yoksel.github.io/flex-cheatsheet/#justify-content) or [align-items](https://yoksel.github.io/flex-cheatsheet/#align-items). 

> globe_with_meridians: **Online Recommendation:**: Alternatively, you can ask the student to show you their portfolio design and you can start a discussion about it—using a breakout room.

### Instructors and TAs

Monitor students' progress with your TAs and offer help where needed. Encourage students to help one another as well.

**Say:** "Take note of how these two categories of tools are different and similar and be prepared to share what you find with the class."

_If you aren't an experienced front-end developer:_ Feel free to lean on the solved activity file located in the Google Drive zip. Help students understand how their code is different from the solved file.

## SLIDE 55
## 8. Instructor Do: Aligning CSS Flexbox Items Activity Review (5 min)

Bring everyone's attention back to your screen and lead a review of the activity.

Aim to review the work of two to three students (have a few volunteers share work in Slack). Be sure the feedback you and your TAs provide is *actionable*.

**Ask:**

- "Did you have any difficulty with this activity? What problems did you encounter?"

- "What are some examples (or layouts) of how aligning elements using `align-items` and `justify-content` would be useful?"

- "Can you perfectly center content using `align-items` and `justify-content`?"

	_Yes._

- "What does the CSS property `align-items` do?"

	_`align-items` positions flex children in a flex container top-bottom._

- "What does the CSS property `justify-content` do?"

	_`justify-content` positions flex items left-right._

- "How are they different?"

	_They align flex children in opposite directions._

- "How are they similar?"

	_They use the same CSS properties: `flex-start`, `flex-end`, `center`, `space-between`, and `space-around`._

### Common Misconceptions and FAQs

Complete the review by covering a few common misconceptions or FAQs about Flexbox and aligning items.

1. `align-items` and `justify-content` are applied to the parent container and control content contained inside.
2. Using `align-items` and `justify-content`, it is possible to achieve almost any layout that requires responsive alignment.

> **Instructor Note:** Take questions.


## SLIDE 56
1. Open the [demo in CodePen](https://codepen.io/2u-uxuxi-bootcamp/pen/QWpGoXB).

	**Say:** "We are picking up from where we left off in the previous demo."

1. Walk through the code before making any changes:

	- `#parent` is the main flex container.

	- Inside of the flex container are three flex items, named `#child1`, `#child2`, and `#child3`.

	- New in this demo are three `.card` elements inside of `#child2`.

1. In `#parent`, change the `flex-direction` property to `row`.

	Point out how the three new `.card` elements did not change. They are still in a column, because they are not flex items.

	**Say:** "An element is only a flex item if its immediate parent is a flex container."

1. In `#child2`, add `display: flex;` to transform `#child2` into a flex container.

	**Say:** "`#child2` is now a flex container and a flex item.`

1. In `#child2`, add `justify-content: space-between;` to make the cards space out.

	This demonstrates that `#child2` can use properties for both flex containers and flex items.

1. In `.card`, add `flex-grow: 1;` to make the cards fill the space.

	This demonstrates that children of `#child2` are flex items, because they can use properties for flex items.

1. In `#parent`, revert the `flex-direction` property back to `column`.

	Then, in `#child2`, add `flex-direction: column;`.

	This demonstrates how two independent flex systems can combine to create a complex layout.

> :briefcase: **Employer Competitive Note:** Knowing how to "flex nest" allows you to create complex layouts more easily. Consider it another tool in your layout toolbox.

## SLIDES 57-58
Review

## SLIDE 59
Review

## SLIDE 60

## 10. Student Do: Play CSS Flexbox Froggy Activity (15 min)

**TAs:** Slack out the following URL to students: [Flex Box Froggy](https://flexboxfroggy.com/).

Note: There is no Google Doc for this activity.

> :globe_with_meridians: **Online Recommendation:** Keep everyone in the main Zoom room during this activity. With the TAs, monitor the students as they work and offer encouragement where needed.

### Summary

Have the students play Flexbox Froggy for 15 minutes to help reinforce the concepts we lectured about in class today before students move onto the day's coding challenge.

### Instructions

For the next 15 minutes, students should play the web game Flexbox Froggy to help gain an understanding of how Flexbox works in practice.

*If students struggle:* You should encourage them to research the CSS Flex property that the student is stuck on (depending on where they are in the game).

*If students complete the activity early:* invite them to find some helpful information about Flex and share a couple of links with the class on Slack.

### Instructors and TAs

> globe_with_meridians: **Online Recommendation:** Use Slack or create a breakout room to assist struggling students. 

Monitor students' progress with your TAs and answer student questions.

_If you aren't an experienced web developer:_ Share your screen and play the game yourself! Flexbox Froggy will help you sharpen your developer skills to better assist students in the future. 

_If you are an experienced web developer:_ Keep an eye out for students who are having difficulty or have questions. Help lead the student to the correct answer by describing what property they are trying to manipulate during the game.

### Deliverable

There are no deliverables for this assignment. Students should just work hard and have fun.

## SLIDE 61
## 11. Instructor Do: Play CSS Flexbox Froggy Activity Review (5 min)

Call attention back to your screen and lead a review of the concepts that students practiced while playing Flexbox Froggy.

Get the conversation started and test for student competency with the following question:

**Ask:** "Why would you want to nest a flex container inside another?"

You nest flex containers inside each other in one of two scenarios:

1. If you want to control the children of a flex container with `justify-content` or `align-items`.
2. When you need a complex flex structure like a column with rows or vice versa.

While this might seem like a simple review, understanding why you would nest flex containers inside each other is important and can be used to create complex flex layouts.

**Provide actionable feedback.**

Students will need actionable feedback that they can apply to their work. Make some suggestions that will make their work easier the next time they work with flex. For example:

1. When building nested CSS flex containers, try using `align-items` and `justify-content` to control the position of the nested flex containers.
2. Students should annotate design files, planning which containers are going to be rows or columns. Pre-planning what HTML elements you'll build will save class time and frustration.

## SLIDE 62
## 12. Break (15 min) 


## SLIDE 63
## 13. Instructor Do: Introduce Jake's Eatery Activity (5 min)

> :pushpin: **Important Point:** The goal of the following activity is to give students time to hone their skills and challenge themselves to create a real layout. Students must practice on their own without guidance when learning front-end development. Remember, it is not enough to just do one activity and think you have mastered the concept. This lecture supports learning objective No. 4: apply CSS Flexbox skills in a coding activity called Jake's Eatery.

Creating layouts is a fundamental part of becoming a front-end developer. Students must practice if they are to truly understand the concepts involved in building layouts.

> **Instructor Note:** During this coding activity, students will put all the skills we lectured about earlier to the test. Students will attempt to re-create Jake's Eatery using flex. During this time, students will also be developing something else: their workflows as front-end developers.

**Say:** "Believe it or not, what we have learned so far is plenty to make some pretty nice (and responsive) layouts!"

> **Instructor Note:** Some students are likely still not confident in their programming abilities and might struggle with imposter syndrome. The best way for students to get over this feeling is by building cool stuff. That's the idea behind this activity.

This activity will challenge students by requiring them to:

1. Use flex to create responsive layouts.
2. Nest flex items inside each other to create complex designs.
3. Think critically about how they approach front-end development as well as develop personal workflows.

**Say:** "Today, we'll build a flex layout for Jake's Eatery. We already have the skills needed to build a decent-looking website by hand, and we just need practice and repetition to become great front-end developers!

Now that students know what they'll build, let's turn them loose to code!

## 14. Student Do: Jake's Eatery Activity (45 min)

**TAs,** Slack out the in-class challenge with students [18-Week/02-Activities/18.1/18.1_03-Jake's Eatery](https://docs.google.com/document/d/1lg2ughJBrhsHEi7gfSVXB-Seru-GEEdevBR7DNsOxqc/)

> globe_with_meridians: **Online Recommendation:** Keep everyone in the main Zoom room during this activity. With the TAs, monitor the students as they work and offer encouragement where needed. If many students have the same question, ask everyone to pause and watch your screen as you explain how students can solve the issue. Alternatively, have a TA create a breakout room to offer help to struggling students.

### Summary

Students will build Jake's Eatery from scratch, starting from the HTML up. This is largely an exploratory project that emphasizes self-learning and applying what they've learned to build the site correctly.

### Instructions

Students will build a complete layout by hand. Be prepared for student questions about getting CSS Flexbox to work correctly.

*If students struggle:* During this activity, the goal is to challenge students to apply the CSS properties that were practiced earlier in order to construct a layout. If a student has a question, help them research their problem. Alternatively, you can always lean on the solved file to show the student how their HTML or CSS is different.

*If students complete the activity early:* Challenge the student to continue to work on the layout and iterate on it. Help the student come up with ideas of how they might iterate on the design. What do you like about the design? What might you do differently?

### Instructors and TAs

> :globe_with_meridians: **Online Recommendation:** With the TAs, monitor students as they work and be prepared to step in and offer help throughout this particular activity.

_If students struggle during this activity:_ Make sure you review the solution file located in Activities/Jakes_Eatery/solved. If a student is stuck and you do not know the answer to their questions, you have two options:

1. Help them find the solution on the web. This has the added benefit of increasing your front-end developer knowledge while you help your students solve their problem.

2. Show students how their code is different from the solved file. Encourage the student to review the solved file to see how the element they were struggling with was built.

### Deliverable

The deliverable for this activity is a finished Jake's Eatery webpage.

> Instructor Note: For an example of how this looks, please consult the solved file.

## 15. Instructor Do: Jake's Eatery Activity Review (15 min)

Call attention back to your screen. 

First, lead a discussion of Jake's Eatery activity.

- Ask students to share their work via Slack.
- Open up one or two piece of work and point out things the students did well:
_Did it respond well?_
_Did it look nice?_

- To stimulate a discussion, consider the following:
  - Ask, "Did anyone have any questions about flex from the activity?"
  - _If you are an experienced front-end developer,_ ask, "Did anyone have any trouble with their code that they want to work through together?"

**Provide actionable feedback.**

Students will need actionable feedback that they can apply to their work. Here are some general takeaways for CSS Flexbox:

1. When setting `display: flex` to an HTML element, the flex items will automatically format as a row. Try using `flex-direction` to create a column using CSS Flex.
2. Tell your class to try to apply box model properties (margin, padding, height, and width) to the flex children to see how the Flexible Box Model reacts.
3. Remember that CSS Flexbox can only make one-dimensional layouts---layouts that are either a row or a column. Tell your students that next class, we'll build complex two-dimensional layouts.

**Concepts Review.**

Now, review the topics discussed in the lesson via active recall:

**What does it mean when we say that flex is a one-dimensional layout?**

_Answer:_ Flex can be used to create responsive, flexible containers in either rows or columns.

**What does the CSS property `align-items` do?**

_Answer:_ `align-items` positions flex items vertically in a flex container.

**What does the CSS property `justify-content` do?**
_Answer:_ `justify-content` aligns items horizontally in a flex container.

**Why would you want to nest a flex container inside another?**
_Answer:_ You nest flex containers inside each other in two instances:

1. You want to control the contents of that div with `justify-content` or `align-items`.
2. You need a complex flex structure.

> 💼 **Employer Competitive Note:** Flexbox is on the cutting edge of front-end technology. Having working knowledge of the tool used to create flexible layouts  will make you stand out in your hunt for a UX job.

- Cite two key benefits of Flexbox.
- Invite a TA to share why they appreciate Flexbox and how it has benefitted their projects.
- Invite students to predict or imagine how they may use Flexbox in their future work.

Take any final questions and then move on to discuss this week's challenge.

## 16. Instructor Do: Challenge 18 and End Class (5 min)

Now it's time to introduce the challenge for the week and field any questions students may have.

For Week 18's challenge, students will continue to build their portfolio webpage. This week students will build out two more sections for their portfolio webpage using CSS Flex and CSS Grid. Students will also make their webpage responsive by writing custom media queries for mobile devices.

- Open the challenge instructions and review them with the class.

**TAs:** Slack out Week 18 challenge File: [18-Week/03-Homework/](https://docs.google.com/document/d/1Fd4hTrCtgg7Q4v60r5-rX8H2JD9FjP67PJxK5gs7G6U/)

**Say:** "You have some of the skills required to complete this assignment already, so be sure to get started on your challenge assignment right away."

**Challenge Requirements**
In this challenge, students must have:

1. A flex container (navigation would be easiest)
2. A grid that contains contents
3. A wireframe of your website

Thank the class. Let the students know that we'll cover CSS Grids in the next lesson.

Dismiss the class and stay online to hold office hours.

---

## We Want Your Feedback!

Please submit any issues or comments on the UX/UI curriculum to our Google Form.

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

With this form you can now view the status of your submission and other issues here:
[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing)

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved. 	
