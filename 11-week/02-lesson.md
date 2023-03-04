# 11.2 Lesson Plan: RWD Rules and A/B Testing

---

## Overview

Today's class will delve into new aspects of responsive web design (RWD): handling imagery, A/B testing, and building versions of homepages for group A/B testing.

During the last lesson, students created responsive webpage prototypes and analyzed them with user tests. In the next lesson, they will design for mobile and learn about design best practices. As a whole, Unit 11 enables students to improve their responsive web UI design skills, iterate their high-fidelity UI prototypes, and test their UI solutions with A/B testing.

## Learning Objectives

By the end of class today, students will be able to:

1. Capture a variety of breakpoints for webpages using Chrome Inspect.
2. Crop and resize image samples that satisfy the requirements of RWD.
3. Wireframe an RWD homepage for mobile, tablet, and desktop, and transform into prototypes using Figma/InVision.
4. Articulate how A/B testing is a valuable methodology for identifying UI weaknesses.
5. Generate a Version A and a Version B of a homepage design to test assumptions with a team.
6. Execute A/B testing through Figma/InVision with a team and capture results.

## Class at a Glance

- Today's lesson is about RWD rules and A/B testing. It is divided into two parts:

  - Part 1 covers RWD concepts and homepage production, including:
    - Website breakpoints
    - Image cropping
    - Media queries

  - Part 2 covers testing design assumptions via A/B testing, including:
    - Wireframing versions of homepages
    - Setting up InVision prototypes for creating versions for A/B testing
    - Performing A/B testing in teams

- By the end of today's class, students should appreciate why A/B testing leads to better results for users and clients' businesses alike.


## Instructor Notes

Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.

🌐 **Online Recommendation:** Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here are some examples of what you can say during common transitions:
- From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”
- From sharing the slideshow to sharing a tab on your browser: “Bear with me as I switch over to my browser for the next demonstration.”

Transitions and activities tend to take longer in virtual classrooms. If you find that you are running short on time, feel free to combine the activity and review sections by doing some of the activities together as a class instead of creating breakout groups.  

## Prepare for Class

Review the slides for the lecture: [11-Week/01-Slides/11.2-RWD Rules and A/B Testing Slides](https://drive.google.com/open?id=1MoKNxeRNRjTDgi-AfhA6JN8akljSbA37DOky4VZDGvY).

The knowledge and skills taught today form a foundation for the UI as well as front-end development projects.

Prepare to give two demos by running through them in advance:
- Section 2: Use the Chrome Inspect tool to reveal page breakpoints.
- Section 14: Use Figma/Adobe XD and InVision to create versions of prototypes for A/B testing.
    - If you are new to InVision, practice exporting screens and setting up a mobile prototype before class.

Think about how to be engaged with students:
  - Plan to encourage the use of office hours for giving feedback.
  - There are tons of RWD resources, so encourage your TAs and students to use Slack to share links, reading, and video resources with students.

If needed, review the Strategies for Class Online in the unit README.

---

## Class Video

- [Class Video:](https://codingbootcamp.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=d53ff1cd-a3b9-4f5e-9e86-aa9a01731807) Watch a sample video of this class being taught by Hannah Patellis.

## Time Tracker

- Keep track of the clock. Have TAs consult the [11-Week/04-Time Trackers/11.2 Time Tracker](https://drive.google.com/open?id=1mF2OmydcpS9W-ub1rxdg64za0cgWn7BFhnh-ITSv1gY).

- Use an online timer to manage in-class activities. Google Chrome has one: [Stopwatch & Timer](https://chrome.google.com/webstore/detail/stopwatch-timer/eoiibkbchfmgmhlodifjceiginokllbj?hl=en).

---


## Office Hours: Reviews and Practice (45 min before class)

Encourage your students to use office hours. By the same token, encourage them to make the most out of class by asking questions, which has benefits for their classmates.

---

## 1. Instructor Do: RWD 2.0 and Today's Objectives (2 min)

- Welcome students to class, and launch today's slides: [11-Week/01-Slides/11.2-RWD Rules and A/B Testing Slides](https://drive.google.com/open?id=1MoKNxeRNRjTDgi-AfhA6JN8akljSbA37DOky4VZDGvY).

  - Make a PDF copy and share it in Google Drive for class. Share slides in Slack.
- Tell students that the UI will continue to get harder, but you and the TAs are here to help students gain these skills.
  
  - > **Say:** "Your growth will be astounding, but it will take work."

**Review today's class.**

- Since you'll be jumping right into a demo of Chrome Inspect, take a moment to whet students' appetites for today's lesson:
  - A good mindset for learning about RWD rules and media queries is that of baking. Bake a cookie in too hot an oven, and you can burn it, bake it in one too low, and the cookie goodness won't happen. By following the rules, you can "bake a great cookie".
  - A good mindset for learning about A/B testing is like finding the best cookie recipe. To get the best cookie, you need to taste different recipes against one another.

> :gem: **Designer Insight:** Speak to your own experiences that might help students get into an RWD mindset.

- Convince students their UX weeks connect to what they're learning now, for example:
  - The UX design process quickly iterates and learns from mistakes—today, we are going to apply that to UI decisions.
  - The UX design process tests and validates ideas—today, we will refine our ideas through rapid UI testing.

**Review the learning objectives.**

- Walk through today's objectives with the class.
- Emphasize that today will be very hands-on and fun: RWD image cropping, RWD homepage design, and A/B testing.

> **Instructor Note:** Pause for any questions before jumping into the lesson.

## 2. Instructor Do: Demo - Chrome Inspect (3 min)

>:pushpin: **Important Point:** Your goal here is to generate excitement about seeing "behind the curtain" of responsive webpages. This ties into the first learning objective, using Chrome Inspect to capture a variety of breakpoints for webpages.

Begin by connecting knowing how to use Chrome Inspect to being a desirable job candidate.

> :briefcase: **Employer Competitive Note:** As a UX/UI designer, you should be able to use the same tools that developers use. The web is not magic: you must be able to use tools to "see" behind the visual veneer of the web as well as talk about what you see with design teams. Add "familiarity with Dev Tools (Chrome Inspect)" to your resume and LinkedIn skills profile.

Show students how Chrome Inspect is used to see the inner workings of responsive webpages. You will show them where breakpoints occur in the code of a site. This activity will prepare them to do this on their own, and plant the seed for future front-end development learning.

> :gem: **Designer Insight**: Share how you've used Chrome Inspect.

> **Instructor Note:** We will discuss developer tools in much deeper terms during the front-end dev units 16-24. For now, touch on these tools and encourage some light research if students want to dig in.

### Definition of Chrome Inspect
Chrome Inspect is a Document Object Model (DOM) tool, built into the Chrome browser originally created to help developers debug a webpage. Designers in UX/UI use it to see how the web browser is representing the code to build their user experience.

Now, take a look at a few of the websites that students like:

> **Ask:** "*Does anyone have a favorite responsive website?*"

- Have them put their links in Slack.

- Open your browser and demo two to four of the students' favorite websites.
- > **Ask:** *"How do we know if this site is responsive?"*

> :gem: **Designer Insight**: Ask one of the TAs to mention a website or two they are fond of.

### Chrome Inspect

- Show students how to find the Chrome Inspect tool:
  - Right-click the webpage and select the Chrome Inspect tool.
  - Drag the width of the page to show how the webpage responds in the browser.
  - Point out aspects of the code that relate to RWD.
  - Invite students to ask questions about what they are seeing.

> **Instructor Note:** Pause for questions before moving on.

**Encourage students to explore further.**

Below is a list of sites that students should explore on their own to gain experience evaluating responsively designed websites.

- **TAs:** Slack out in the #resources channel these responsive website resources:
  - [https://mediaqueri.es/](https://mediaqueri.es/)
  - [https://www.awwwards.com/websites/responsive-design/](https://www.awwwards.com/websites/responsive-design/)
  - [https://www.webbyawards.com/](https://www.webbyawards.com/)
  - [https://www.cssdesignawards.com/website-gallery?feature=responsive](https://www.cssdesignawards.com/website-gallery?feature=responsive)
  - [https://www.invisionapp.com/inside-design/examples-responsive-web-design/](https://www.invisionapp.com/inside-design/examples-responsive-web-design/)

Doing is believing. The next activity is simple but powerful, as it allows students to play with the Chrome Inspect tool and spot the features of RWD on their own.

## 3. Student Do: RWD Website Breakpoint Activity (5 min)

**TAs:** Slack out to students the following activity in Google Docs: [11-Week/02-Activities/11.2/11.2-01-RWD-Website-Breakpoint-Activity-Google-Doc](https://docs.google.com/document/d/1R5UbYSaxrplCWWgZCLVfOHA1f9XrSgANt0zjg_X3hE4/edit?usp=sharing).

**Summary**

Students will explore some popular responsive webpages and practice using Chrome Inspect to validate the webpage's responsiveness.

**Instructions**

Working alone, students should experiment with viewing the breakpoints for popular responsive webpages.

> :globe_with_meridians: **Online Recommendation:** Students will work alone. Have everyone share their screens for visibility. Use Slack for chatting and the Zoom raised-hand feature for questions.

**Instructor and TAs:** During this five-minute activity, work with the TAs to check in with students and help them identify RWD breakpoints.

Remind students to use screen capture or awesome screenshot extension to capture the webpages' responsive views.

**Deliverable**

Students will post RWD samples to Slack.

## 4. Instructor Do: RWD Website Breakpoint Activity Review (5 min)

Get everyone's attention and lead a review of students' findings.

- Remind everyone to share their RWD samples on the Slack channel.
- Call on two or three students to share their process with the class, and spotlight each student's screen:
  - **Questions to consider asking:**
    - *Why did you choose this webpage?*
    - *What makes it successful from an RWD perspective?*
    - *Which was designed first: mobile or desktop?*

> :gem: **Designer Insight:** Discuss how RWD standards play out in the brands you have worked with.

Now, provide a bit of actionable feedback for the class and address a couple of common misconceptions about RWD considerations:

- Actionable feedback: It is helpful to capture the URL of the webpages, so when showing these samples, you can go back to that webpage.

- Misconceptions: A majority of your users will use Chrome to view your webpage. False. Although Chrome is a modern web browser, billions of people use computers to access the web through a variety of web browsers.

Now that students understand breakpoints, next, they'll learn how designers implement them. This activity will bring their understanding of breakpoints full circle.

## 5. Instructor Do: RWD Media Queries (5 min)

> :pushpin: **Important Point:** The goal of this section is to go deeper into breakpoints by introducing students to media queries. Students might have many questions about media queries. Reassure them that they'll "get it" soon. Focus on the value of media queries, not how to code them.

Here you'll introduce media queries and explain how designers communicate breakpoints so that websites can display as desired across devices.

### Media Queries in a Nutshell

Media queries dictate how a webpage displays on various device sizes. They dictate how a site displays on a smartphone versus a laptop. Just as a dashed line on paper indicates where to cut with scissors, a media query tells the webpage where to "cut" for different display types.

- In order to fully understand media queries, we need to understand HTML and Cascading Style Sheets (CSS) .

- **What is HTML?**
  - HTML is Hypertext Markup Language, which sets the structure and content of a webpage.
  - HTML is the language of the web, which we'll cover in more depth during units 16-21.

- **What is CSS?** CSS is the visual design rules of a webpage. They control the layout of webpages. CSS transforms the design you create in Figma/Adobe XD or other design software into code that presents well online. CSS is used with HTML, the language of the web, which we'll cover in more depth during units 16-21.

  - **Next, what are media queries again?** Media queries are a CSS command that tells the webpage to adapt its content for different screen sizes.
  - **Don't worry about CSS or code:** All we need to know right now is this basic concept: media queries dictate how a webpage displays various device sizes.
  - **Media queries and RWD:** Media queries are rules built into CSS code that allow us to modify a website or app depending on the device's general size (such as screen resolution or browser viewport width).
    - Media queries are a fundamental part of RWD, as they allow us to code content experiences across multiple screens. They are used to customize the appearance of websites for multiple devices.

> **Instructor Note:** Acknowledge that aspects of the media query concept stray into web development (such as CSS). Let students know that we'll cover this during the lecture on front end later on (in units 16-21). Take questions. Ensure that students grasp media queries.

> :gem: **Designer Insight**: Briefly explain how media queries function in your work.

Students should now have a good grasp on how webpages display differently across devices, and that breakpoints and media queries drive that change. It is time for students to consider how breakpoints impact webpage images.

## 6. Instructor Do: RWD Breakpoints and Imagery (15 min)

> :pushpin: **Important Point:** The goal is to get students to consider the primary screen widths to support while solving RWD visual solutions and content. This lecture supports today's second learning objective, cropping and resizing images samples according to RWD requirements.

Now that students understand that we create breakpoints through media queries, it is time to look at the effect of breakpoints on webpage imagery. The following lecture will explain how designers approach the creative constraints that RWD breakpoints pose for imagery.

> :briefcase: **Employer Competitive Note:** As a UX/UI designer, you will be expected to design high-fidelity solutions for RWD. You must know how to use content effectively in a design system. Your portfolios and case studies must illustrate how you think and move from low fidelity to high fidelity.

> :gem: **Designer Insight**: Make breakpoints tangible by sharing how you think about breakpoints—perhaps refer to a recent client project.

Pose these questions to students:

*If webpages display differently across various devices, what does that mean for the images on those webpages? How do breakpoints impact images?*

- A breakpoint is a layout design target for approximating devices.

- Typical breakpoints are:
  - Mobile (<767 px)
  - Tablet (768 to 959 px)
  - Desktop (>960 px)

- Defining your breakpoints is key to your design requirements.

- Content is like water:

  - Content in responsive design uses the same information on all screens.

  - Web content: Copy, images, etc. flow in one fluid screen.

  - RWD is about considering how content works across these UI modalities.

- How you crop matters:

  - RWD uses imagery often, so we must consider how this content is treated between screen sizes as imagery will be cropped, especially on mobile sizes.

- Image rule:

  - Never distort an image's proportions—it looks bad and irritates the photographer or content maker.

- Review sample:

  - Adobe Photoshop, Adobe XD, Figma etc. let you distort an image, but never do it!

- Review the viewport:

  - The width of the screen defines the viewport size.

- Review the viewport content .gif:

  - Discuss how the height of the viewport also impacts the sample. Many webpages scroll. Therefore, the height of the viewport will not modify the image's height, just its width.

- Review resizing versus cropping:

  - Resizing keeps the image composition and changes the size based on the screen size.

  - Cropping is when the image is cut off to achieve a new size or shape based on the screen size.

- Review RWD scaling and cropping:

  - The image size needs to be considered from largest to smallest.

  - Point out the largest size, as it uses most of the image composition.

- Discuss requesting images that have more "air" around the subject. “Air” is associated with the cropping of imagery and the amount of space around a subject in a photograph.

  - When you work with a photographer, discuss how images will be cropped in your RWD to improve content display.

  - Recommend that students work with a photography expert who has experience creating imagery for the web.

- Let's practice this ourselves.

Now that students have the basic idea of how to handle imagery for breakpoints, help them put it into practice. In the following activity, students will crop and resize images for varied screen sizes.

## 7. Student Do: RWD Image Cropping Activity (15 min)

**TAs:** Slack out to students the following activity in Google Docs:

- [11-Week/02-Activities/11.2/11.2-02-RWD-Image-Cropping-Activity Google Doc](https://docs.google.com/document/d/1mi7zLsWvFvNIj-I9Ic1dlyxNi1u_PANcXTO42dCdl_c/edit?usp=sharing)

- [11-Week/02-Activities/11.2/Image Cropping Template](https://drive.google.com/open?id=1ILtAc1yBew1V0DHa9Z0PCpuNfNbaGokw)

- [11.2-02-RWD-Image-Cropping-Figma-Template](https://www.figma.com/file/iB1NAar84M9xsnhljlpJgs/11.2-02-RWD-Image-Cropping)

**Summary**

Students will practice creating RWD content that challenges their ability to quickly lay out a system of screens.

> :globe_with_meridians: **Online Recommendation:** Have everyone share their screens. Work with the TAs to navigate across students' screens, offering support with image cropping. Spotlight individual students throughout the activity and invite them to talk through their actions.

**Instructions**

Working alone, students should experiment and design RWD layouts. Students can use Figma or Adobe XD.

- [Adobe XD Responsive Resize](https://helpx.adobe.com/xd/help/using-responsive-resize.html)
- [Figma responsive components](https://uxdesign.cc/how-to-create-responsive-mobile-components-in-figma-1661189d1503)

**Instructor and TAs**

Float among students and assist with cropping decisions and the use of masking tools in Figma or Adobe XD.

**Deliverable**

Students will post RWD content to Slack, which shows their ability to scale between screens.

## 8. Instructor Do: RWD Image Cropping Activity Review (10 min)

Call attention back to your screen and lead a review of the students' findings.

- Remind everyone to share their RWD samples in the Slack channel.
- Call on two or three students to share.

> :globe_with_meridians: **Online Recommendation:** Have everyone share their screens. Call on a few students to share, and be sure to spotlight the Zoom screen and have them come off mute.

**Some questions you can ask:**

- *Why did you choose this image?*
- *Which cropping strategy did you use?*
- *What makes it successful from an RWD perspective?*

Now, provide a bit of actionable feedback for the class and address a couple of common misconceptions about RWD navigation considerations:

- Actionable feedback: Images should never ever be stretched or squished. Start with high-quality large images and crop them from the biggest screen desktop down to the smallest.

- Actionable feedback: RWD is now a standard. This is important when designing for others.

- Misconceptions: We add "real images" at the end of the design process. False: If you have content early, you can create high-fidelity faster.

Now that students have some practice—and appreciation—for handling images in RWD, they're ready to shift back to thinking about webpages as a whole. Next up: Responsive wireframes.

## 9. Instructor Do: RWD Wireframing and UI Systems of Scale (5 min)

> :pushpin: **Important Point:** The goal is to get students to consider how their government agency UI systems can be responsive. This lecture supports today's third learning objective, wireframing an RWD homepage for mobile, tablet, and desktop and transforming them into InVision prototypes.

Now it is time to get into some of the details of images, such as resolution size and retina display. An understanding of images will help students select, import, and manipulate them for their designs.

> :briefcase: **Employer Competitive Note:** As UX/UI designers, you will be responsible for working with content in responsive solutions and testing high-fidelity prototypes. These skills must be on display in your portfolios in order to be a desirable job candidate.

### Safe Design Resolutions

Let's dig deeper into RWD. Considering UI systems is challenging. It will require more software and production skills as the number of assets you have to create goes up depending on the breakpoints you support during design. Typically, a design team will build mobile, tablet, and desktop versions.

> **Instructor Note:** Students should be advised to dive into more research and articles about UI systems. They'll be expected to practice using Figma or Adobe XD building with assets, components for responsive layouts.

**What we mean by wireframing and systems of scale.**

  - Using our UI design tools is about gaining efficiency and control over a large set of components.
    - Example: If you have ever experienced having to update a color on dozens of cards or individual buttons, you know this pain. But using design tools allows you to quickly update your UI in every place it is used.
  - In the real world, you will help manage global brands and learn to design and scale a UI system through your tools. Having a scalable process will be important and valuable to your success as a designer.

- **TAs:** Slack out resources for responsive features in Adobe XD and Figma:
  - Adobe XD
    - [https://theblog.adobe.com/how-to-design-with-responsive-resize-xd/](https://theblog.adobe.com/how-to-design-with-responsive-resize-xd/)
    - [https://letsxd.com/videos/responsive-resize](https://letsxd.com/videos/responsive-resize)

  - Figma
    - [https://help.figma.com/hc/en-us/articles/360040451373-Create-dynamic-designs-with-Auto-Layout](https://help.figma.com/hc/en-us/articles/360040451373-Create-dynamic-designs-with-Auto-Layout)
    - [YouTube Figma Autolayout](https://www.youtube.com/watch?v=NrKX46DzkGQ)

### Safe Design Resolutions

- Review safe design resolutions.

  - Generally, 1024 × 768 pixels for desktop and tablet and 320 × 480 pixels for mobile are safe resolutions to work with.

  - However, these standards are always changing.

  - Design for the size at which the user will see it on their device.
- Review retina resolution.
- Build systems that scale:
  - Be organized about where all the screens of a webpage can potentially live.
  - Use  Adobe XD and Figma export tools when sharing assets for retina screens.
- Considering your user across every screen is what UX is all about, including defining what will be supported and what will not.
- User research and user data will help you determine what devices your users are concentrating their experience on (hint, hint: it is probably mobile).

> :gem: **Designer Insight**: Say something about how you approach image selection in your own work. Alternatively, a TA could share an anecdote from client work.

**Pause for questions.**

> **Instructor Note:** Ask if there are any questions and use the 30-second trick by waiting for a count of 30 seconds before moving on (invariably, a question will arise).

Next, students are going to shift gears a bit and sketch out webpage wireframes on paper—for mobile, desktop, and tablet.

## 10. Student Do: RWD Homepage Wireframe Challenge Activity (25 min)

**TAs:** Slack out to students the following:

1. [11-Week/02-Activities/11.2/03-RWD-Homepage-Wireframe-Challenge-Activity Google Doc](https://docs.google.com/document/d/1RnYnMAXykfsgy0WXZsfmGVLjRdl3ndOakRISzIzSZ2M/edit?usp=sharing) and the [User-Persona.pdf](https://drive.google.com/open?id=1Sxux8JbZdz9KgjiPCGfmSE7I8vY9PWHf)

2. [11-Week/02-Activities/11.2/Sketching Template](https://drive.google.com/open?id=1sJiBK4AP0cgNE9N_LQbG38nvQQRLljLi)

3. [11-Week/02-Activities/11.2/Startup Desktop Wireframe Sample](https://drive.google.com/open?id=13dd2qkttQWOJ12IvPrS3Yp3prhdWhpVL)

4. [Adobe XD Resource: https://xdresources.co/resources/big-wireframing-kit](https://xdresources.co/resources/big-wireframing-kit)

5. [Figma Wireframe Kit](https://www.figma.com/resources/assets/wireframe-kit/)

**Summary**

In this activity, students will explore creating a homepage wireframe in RWD and use sketching and Figma/Adobe XD to quickly produce an RWD solution.

**Instructions**

Working alone, students will experiment and design RWD layouts. Students can use Adobe XD or Figma.

Students can work from the supplied list of defined requirements, which will speed up the process. In the real world, they will likely be required to define what they are supplying.

**Instructor and TAs**

Set a timer for 25 minutes.

> :globe_with_meridians: **Online Recommendation:** Have everyone share their screen. You and the TAs can navigate from screen to screen, helping students who need help wireframing responsive content.

**Deliverable**

Students will post RWD wireframe solutions to Slack that show their ability to scale between screens.

## 11. Instructor Do: RWD Homepage Wireframe Challenge Activity Review (10 min)

Call attention back to your screen and lead a review of the sketched wireframes.

- Remind everyone to share their sketches on the Slack channel.
- Scroll through all the samples and choose two or three that have all the content from the supplied wireframe.
- Call on the first student—spotlight each student's screen when they begin to present their work.

**Possible discussion questions:**

- Why do you think Jack Brewster, our user, will use this mobile version?
  - Which type of content did you find the hardest to translate into mobile?
- What could you have done differently?

> :gem: **Designer Insight:** Share a story about successfully educating a client about going with an RWD approach to their website.

Now, provide a bit of actionable feedback for the class as well as address a couple of common misconceptions about RWD navigation considerations:

- Actionable feedback: Look at how content has been cropped and give recommendations for improving screen layout.

- Misconceptions: Homepages are the most important webpages of a website. False. Although they are useful and require attention, not all your users will enter a website through the front door. But if your homepage is flawed, that will likely impact all pages below it.

Now that students have a sense of how to make decisions about a webpage design to suit different screen sizes, let's get them thinking about testing different ways to display webpage content.

## 12. Instructor Do: A/B Testing and the Power of UI Data (10 min)

> :pushpin: **Important Point:** Your goal is to prepare students to test their UI. Without testing and validating solutions with users, UI solutions are just assumptions. This ties into today's fourth learning objective, articulating the value of A/B testing for identifying UI weaknesses.

Students have several new skills to pull together—the role of breakpoints, imagery, and how to plan the layout of content for varied screen sizes. The next step is to get feedback, specifically through A/B testing their UI design.

Testing creates a vital feedback loop for validating UI ideas, making mistakes quickly, and innovating faster. We want to test our solutions to make sure they are usable, useful, valuable, delightful, and hopefully, shareable.

> :briefcase: **Employer Competitive Note:** As a UX/UI designer, your ability to execute usability tests to provide proof that your solutions work with users is essential to landing a job. This skill will also help clients improve their ROI. Add "proficient in A/B usability testing" to your resume and your LinkedIn skills profile.

Students will be reluctant to test their work at first.

- Share your personal stories along the way. Let students know that, although what you think matters, you are not their user!

- **Ask,** "Anyone ever been part of an A/B test?"
- Have you ever used Amazon?

  - You have been in an A/B test then!

- A/B tests are used all over web design to validate and gather data on what works and what doesn't work with users.

### A/B Testing

A marketing experiment wherein you "split" your audience to test several variations of a campaign and determine which performs better. In other words, you can show version A of a piece of marketing content to one half of your audience and version B to another.

> :gem: **Designer Insight:** Take a moment to share your own experiences with "split" or A/B testing, and invite the TAs to share theirs.

### A/B Vs. "Split" Testing

The terms are used interchangeably in the design community.

- Designers must ask, "How are you defining the parameters of an A/B test?" Each time they run a test, they need to be sure that they are all on the same page and gathering meaningful data.

### **Review when and why to use A/B testing.**

**When do designers use A/B testing?**

Use A/B testing during the validation and usability assessment. It can be used throughout the creative process to help refine UI versions and improve solutions iteratively. Also, A/B testing can be used throughout the UI design process, but in the “real world,” it is typically performed on high-fidelity solutions.

**Why bother with A/B testing?**

Testing A/B versions can help improve or optimize under-performing aspects of UX/UI. It can also supply feedback data to designers to validate a design hypothesis.

- **We can't always sit with our users and watch over their shoulders.**
- **Ask,** "What is a KPI?"
  
  - KPI stands for "key performance indicator.""
  
- User retention:
  
  - Which group, A or B, is accomplishing the task better?
  
- User revenue:
  
  - Which group, A or B, is spending more money?

**A/B testing should test aspects of the UX that are unique.**

- Calls to action (CTAs) (buttons matter)
- Titles, labels, and production descriptions (context is critical)
- Forms: length and types of fields (forms can be improved)
- Layout or style (more work for design should be done with wireframes, not code)
- Price or promotion (requires business approval)
- Images (composition matters)
- Text (what is your user reading, and why?)

**Review samples of the A/B test.**

Which version will convert better? Stack with an option to expand for more details or all details and swipe left or right for more.

- **TAs:** Slack out these links into the #resources channel for students to read at home:

  - [https://blog.hubspot.com/marketing/how-to-do-a-b-testing](https://blog.hubspot.com/marketing/how-to-do-a-b-testing)
  - [https://www.invisionapp.com/inside-design/ab-testing-beginners-guide/](https://www.invisionapp.com/inside-design/ab-testing-beginners-guide/)

- **Ask,** "Any questions before we break?"

  - We'll practice A/B testing throughout the remainder of the boot camp, so be prepared to validate your design decisions.

Students are now ready to test out these ideas about A/B testing themselves—once they're back from the break.

## 13. Break (10 min)

Time for a 10-minute break.

Let students know that they'll see a demo of how to use InVision for creating versions for A/B testing when they return from break. Following that, they'll begin a lengthy testing activity.

> :globe_with_meridians: **Online Recommendation:** Don't stop sharing your screen. Put up a Google timer or a YouTube timer video to help get students back into the Zoom room on time.

## 14. Instructor Do: Demo - InVision Version A/Version B (10 min)

In this demo, you will show students how to set up their A/B tests using InVision as a versioning tool.

> **Instructor Note:** This demo is the final piece of knowledge students need before getting into groups for A/B testing. This demo will prepare students to run A/B tests with classmates and users successfully.
>
> - This demo also prepares students for today's fifth learning objective, generating A and B versions of a homepage design for team testing.
> - The activity that follows will help students achieve today's sixth, and final, learning objective, executing A/B testing using InVision with a team.

**Demo option:** Invite a TA to demo this process for students.

> :globe_with_meridians: **Online Recommendation:** Demo creating an A/B version with the Figma resource.

### Adobe XD and InVision Demo Steps

**Part 1:**

1. Open Adobe XD Resource: 11.2-AB-Mobile-Test-Wireframe-v1.1

   - [https://drive.google.com/open?id=1LZObvzZM-I59mrq_UV7odaKtoN1Z6Jnv](https://drive.google.com/open?id=1LZObvzZM-I59mrq_UV7odaKtoN1Z6Jnv)

   - Each date picker version is a four-screen flow.

   - Point out screen labels for organizing during exporting.

2. Review Version A Date Picker and Version B Date Picker.

3. Export mobile version screens.

![Images/01-XD-Export-Screens.png](Images/01-XD-Export-Screens.png)

**Part 2:**

1. Open InVision.
2. Create two new mobile prototypes:
   - Label 1: Mobile Date Picker Prototype Version A
   - Label 2: Mobile Date Picker Prototype Version B

   ![Images/02-XD-InVision-Prototype-Creation.png](Images/02-XD-InVision-Prototype-Creation.png)

3. Upload exported mobile screens to InVision.

   - Quickly connect each screen with hotspots.

   ![Images/02.1-XD-InVision-Prototype-Creation.png](Images/02.1-XD-InVision-Prototype-Creation.png)

4. Connect screens through hotspots for Version A and Version B.

   ![Images/03-InVision-Hotspots.png](Images/03-InVision-Hotspots.png)

5. Review and share the A/B prototype versions via InVision.

   ![Images/04-InVision-Share-Prototypes.png](Images/04-InVision-Share-Prototypes.png)

- Your demo should conclude with two prototypes in InVision. Make sure students are labeling them Version A and Version B.

- Take any questions, but remind students that they'll practice what you just showed them in the next exercise.

Now it's time for students to get hands-on and run their own A/B tests.

## 15. Student Do: A/B Team Testing Activity (45 min)

**TAs:** Slack out to students the following activity in Google Docs: [11-Week/02-Activities/11.2/04-RWD-A-B-Team-Testing-Activity Google Doc](https://docs.google.com/document/d/1qe9_EG25bixY55aJCayDPUU_VQoMfN1zi4Aa7MUAOJw/edit?usp=sharing).

**Summary**

Students will practice validating RWD A/B tests that challenge their ability to solve an RWD problem quickly.

**Instructions**

In this activity, students will create an alternative homepage wireframe for a responsive webpage using Adobe XD, Figma, and/or InVision, then run A/B tests in groups.

> :globe_with_meridians: **Online Recommendation:** Recommend using Figma to execute the A/B test. Allow student to work individually then transition them into breakout rooms (two or three students) for A/B testing.

- Students can use either Adobe XD and InVision or Figma to execute their quick test.

**Instructor and TAs**

Jump into breakout rooms and see if students need help with creating an A/B hypothesis for testing.

- Set a timer for 35 minutes to keep on time.
- When there are 5-7 minutes left, confirm that students are wrapping up their final A/B tests and discussing any patterns in their groups.

**Deliverable:**

Students will post RWD A/B feedback to Slack.

## 16. Instructor Do: A/B Team Testing Activity Review (10 min)

Call everyone's attention back to your screen and lead a review of the A/B testing results.

- Ask everyone to share their test results on the Slack channel.
- Call on two or three students to present their work—be sure to spotlight their screen when each student speaks.

**Possible questions to ask:**

- *What similarities did you notice between the A/B tests?*
- *If you had to conduct an A/B test again, what would you do differently?* 
- *What about this A/B testing process surprised you?*
- *Which version did your users prefer?*
- *What did you learn by conducting A/B testing?*

> **Instructor Note:** Take time to address questions as you lead this review process.

Now, provide a bit of actionable feedback for the class and address a couple of common misconceptions about RWD navigation considerations:

- Actionable feedback: Evaluate the results of a student's A/B test. Did they get a definitive result from the test? Did everyone vote for A vs. B? If not, help them define a larger A/B data set to see if this helps guide a direction.

- Misconceptions: A/B tests can be used on every aspect of a UI. False. Some aspects do not lend themselves well to A/B testing, or would require too much work for not much ROI. A/B testing should be used to evaluate and refine a UI solution.

Remind students not to worry if they feel insecure about their A/B testing skills, to use their time outside of class to do more versioning with InVision and Adobe XD and Figma, and to use Facebook or other social media to test the various designs on friends and family.

## 17. Instructor Do: Recap and End Class (5 min)

> **Instructor Note:** Pause for questions, then move on to the recap.

**Review the key concepts students learned in this lesson.**

Spend a few minutes helping students anchor today’s learning by asking students to "raise their hands" via Zoom—or post answers in Slack—and answer questions about the following concepts, all learned today in class:

- Who can define breakpoints and media queries? (*Answer(s)*: The designers and developers together. Know what sizes and platforms your website will be supported on.)

- What is the name of the tool that reveals the responsive code of a website? (*Answer(s)*: Chrome Inspect Dev Tools.)

- How is A/B testing defined, and what is its value to designers? (*Answer(s)*: A binary testing method for choosing A vs. B. For designers, it helps us validate our assumption and refine our user experiences.)

- What is something we never do with A/B tests? (*Answer(s)*: A/B tests should never be used on a too-specific user target. For example, only test A/B on women. It is not about manipulating your user; it's about validating more effective solutions.)

- How does RWD make you a better UI designer? (*Answer(s)*: RWD is the standard and your user expects the same experience across their screens. Matching and exceeding your user's needs is where you, as a UX/UI designer, can provide your value.)

You did it!

- **Reminder:** Office hours are after class.

Once you have addressed all questions, wish everyone a good night.

---

## We Want Your Feedback!

Instructor, how did class go?

Please submit any issues or comments on the UX/UI curriculum to our Google Form:

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

With this form, you can now view the status of your submission and other issues here:

[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?usp=sharing).

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
