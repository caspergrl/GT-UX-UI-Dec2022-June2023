# 11.3 Lesson Plan: Mobile First and Developer Handoff

---

## Overview

In today's class, students will add to their UI design skills by studying the unique challenges of designing for mobile. They will learn the best practices designers follow to overcome them.

For context, the first two lessons of Unit 11 built on students' UI skills by creating responsive webpage prototypes and analyzing them with usability user tests. We introduced students to new aspects of responsive web design (RWD), including handling imagery, A/B testing, and building versions of homepages for group A/B testing. As a whole, Unit 11 enables students to deepen their responsive UI design skills through designing high-fidelity RWD prototypes for testing and rapid iteration.

## Learning Objectives

By the end of class today, students will be able to:

1. Define fluid design and explain how it is measured and why.
2. Apply simple navigation principles to a mobile blog redesign.
3. Test mobile display type size preference with users.
4. Summarize the 10 navigation pattern types and their uses.
5. Execute an RWD redesign of a blog post.
6. Use Adobe XD type tools and Zeplin.io to hand off work to collaborators.

## Class at a Glance

- Today's class is about RWD for mobile. It is divided into four parts:

  - Part 1 introduces mobile first blog layout and legibility.
  - Part 2 covers legibility and mobile testing.
  - Part 3 explains RWD and handing off work to the front-end developer.
  - Part 4 provides practice for students to design a unique RWD blog, with testing and handing off assets using Figma/Adobe XD and Zeplin.io.

- By the end of today's class, students will have gained confidence in building responsive UI for mobile screen states.


## Instructor Notes

Many of our activities were written for in-person classes, so we've added in-line callouts (usually indicated by this icon: 🌐) to let you know how to adapt an activity for online delivery.

Remember, you can lose the class’s focus in the time it takes to open a new tab. Practice your transitions to and from the slideshow.

🌐 **Online Recommendation:** Narrating what you're doing during transitions eases students’ feelings of uncertainty and fills awkward silences. Here are some examples of what you can say during common transitions:
- From sharing the slideshow to Zoom gallery view: “I’m going to stop sharing my screen for a moment while we review this activity.”
- From sharing the slideshow to sharing a tab on your browser: “Bear with me as I switch over to my browser for the next demonstration.”

Transitions and activities tend to take longer in virtual classrooms. If you find that you are running short on time, feel free to combine the activity and review sections by doing some of the activities together as a class instead of creating breakout groups. 

> **Instructor Note:** If needed, review the Strategies for Class Online in the unit README.

## Preparing for Class

Review the slides for the lecture: [11-Week/01-Slides/11.3-UI Mobile First and Dev Handoff Slides](https://drive.google.com/open?id=1dIEE9R5UNfmlXqcS3-zZlNOpO11EJ0iI7jjVGPlpG4c).

Prepare to give two demos by practicing them before class:
  1. Figma/Adobe XD text tool and responsive type rules (Section 10)
  2. Figma/Adobe XD and Zeplin.io for handing off work to developers (Section 17)

Be aware that two activities run back-to-back in sections 4 and 5.
  - As students work through those activities, you and the teaching assistants (TAs) will navigate across students' screens, helping address questions as well as transitioning students to the next activity.

---

## Time Tracker

- Keep track of the clock. Have TAs consult the [11-Week/04-Time Trackers/11.3 TimeTracker](https://drive.google.com/open?id=1vtIc5-47OFek1tdcUT5UbDTBGkruptyY3nU3zKmBg7c).

- Use an online timer to manage in-class activities. Google Chrome has one: [Stopwatch & Timer](https://chrome.google.com/webstore/detail/stopwatch-timer/eoiibkbchfmgmhlodifjceiginokllbj?hl=en).

---

## Office Hours: Reviews and Practice (45 min before class)

> **Instructor Note:** Encourage your students to make the most out of class and not to be afraid to ask questions.

---

## 1. Instructor: RWD and Today's Objectives (4 min)

- Open the slides for the lecture: [11-Week/01-Slides/11.3-UI Mobile First and Dev Handoff Slides](https://drive.google.com/open?id=1dIEE9R5UNfmlXqcS3-zZlNOpO11EJ0iI7jjVGPlpG4c).
  - Make a copy and share it in Google Drive for class.

> :globe_with_meridians: **Online Recommendation:** Start with a quick-start engagement or warm up strategies to welcome the class and get your students attention as well as start the class with good energy.

- **TAs:** Share slides in #_in_Class_Chat Slack channel.
- Tell students that UI design will continue to get harder, so they should be practicing at home.

  - Specifically, remind students that they should be spending 20 hours out of class each week, digging deeper into these concepts. If they find great resources, they should share them.

### Connect Today's Learning

- Now, connect what students learned in the UX portion of the class to what they are studying today. This will help students value how much their knowledge is deepening:
  - UX is fundamentally iterative, and today, we will practice iterating our RWD UI decisions through testing.
  - In the UX section, we explored how the design process is not a singular pursuit. Today we will extend our UI skills by growing teamwork communication through developer hand-off tools and prototype documentation.

- Next, to get students' minds warmed up for thinking about RWD for mobile, give them a high-level view of what good design for mobile does for the user experience. For example:

  - More users read *The New York Times* newspaper on their phone than they do in actual print. Being able to meet your users where they are means making it work on their phones.
    - [https://www.nytimes.com/2020/02/06/business/new-york-times-earning.html](https://www.nytimes.com/2020/02/06/business/new-york-times-earning.html)

  - Mobile orders are projected to make up 11% of all QSR sales by 2020. Quick Service Restaurants (QSR) include McDonalds, Taco Bell, Wendy's, Chick-fil-A, etc. [https://poppinpay.com/10-staggering-statistics-about-mobile-order-ahead-for-restaurants/](https://poppinpay.com/10-staggering-statistics-about-mobile-order-ahead-for-restaurants/)

> :gem: **Designer Insight:** Share an experience you have had with working on a mobile project.

- Ask one or two students or your TAs to share their experience designing for mobile with the class briefly.

**Review today's learning objectives.**



## 2. Instructor Do: RWD Layouts and Fluid Design (5 min)

> :pushpin: **Important Point:** Your goal is to define fluid design for students. Explain why content is measured in "units" rather than pixels, and share best practices for small screen design (mobile). This lecture supports today's first two learning objectives, which are defining, understanding, and applying fluid design.

> :globe_with_meridians: **Online Recommendation:** This section is heavy in class discussion. When asking questions, stop sharing your screen and switch to Zoom Gallery View as students offer their answers. Begin sharing your screen again once students have finished suggesting answers.

### Fluid Design

Start off by defining **fluid design** and explaining the tradeoffs designers make when designing for mobile. This will prepare students for later practice applying the concepts by redesigning a blog for mobile.

- **TAs:** Slack out the following RWD links in the #resources channel, along with any others the instructor suggests—for students to read at home:
  - [http://blog.froont.com/9-basic-principles-of-responsive-web-design/](http://blog.froont.com/9-basic-principles-of-responsive-web-design/)
  - [https://www.w3schools.com/html/html_responsive.asp](https://www.w3schools.com/html/html_responsive.asp)
  - [https://developers.google.com/web/fundamentals/design-and-ux/responsive/](https://developers.google.com/web/fundamentals/design-and-ux/responsive/)
  - [https://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/](https://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/)
  - [https://www.popwebdesign.net/popart_blog/en/2018/10/fluid-vs-adaptive-vs-responsive-design/#:~:text=Fluid%20design&text=It%20is%20based%20on%20relative,adjustable%20to%20various%20screen%20sizes.&text=That%20is%20why%20fluid%20design,the%20same%20percentage%20of%20space.](https://www.popwebdesign.net/popart_blog/en/2018/10/fluid-vs-adaptive-vs-responsive-design/#:~:text=Fluid%20design&text=It%20is%20based%20on%20relative,adjustable%20to%20various%20screen%20sizes.&text=That%20is%20why%20fluid%20design,the%20same%20percentage%20of%20space.)

### Define Fluid Design

- Fluid design refers to RWD solutions based on relative units and proportional widths, making pages scalable and adjustable to various screen sizes. Whenever the screen size changes, elements of a fluid layout spread over the same percentage of space.
  - An example of fluid design is when a UI element scales down smoothly as you drag your browser window width in.

### Discuss Fluid Page Layout

Responsive design can use fluid page layouts. A **fluid page layout** (sometimes called “liquid” or “fluid width”) uses relative units instead of fixed units.

- An example: 100% vs. 1440px

- Typically, a fluid or liquid, layout will use percentages instead of pixels, and relative units should be applied to all content, including typography.

  - An example: Ems are used for typography and font size of the parent, in the case of typographical properties like font size, and font size of the element itself, in the case of other properties like width.

    - font-size = 16px = 1em so 1.5 em = 24px (16px base em + 8px (1/2 an em))

> :gem: **Designer Insight:** Take a moment to share how fluid page layout shows up in your design work.

- Ask: ***"Show me on screen with a thumbs up or thumbs down if you are following."***

> :globe_with_meridians: **Online Recommendation:** When you pose questions to the class, switch to Gallery View in Zoom to see your class on one screen. Ask your students to raise their hands to ask a question or pose an idea by clicking Raise Hand in the webinar controls.

### RWD Uses Relative Units

A relative unit is relative to something else. For example, the size of the parent element's font width is ems or rems (root ems), or the size of the viewport (screen width), which is a percentage.

- In RWD, a webpage can be a desktop, tablet screen, mobile screen, or anything in between. Pixel density and monitor resolution can also vary, so we use relative units (ems, rems, percentages) that are flexible and allow our coded webpages to work on all screens.

  - Relative units can resize as the screen size changes. We'll apply this more during web coding in front-end development (units 16 through 24).

  - Explain the relationship between fluid design and relative units: By using relative units in the code of a webpage, your webpage content can respond to the screen size. Think about how your content stretches and shrinks, and you will help your developers build the best user experience.

> :gem: **Designer Insight:** Take a moment to relate the relative units that have shown up in your design work.
>
> - Alternatively, ask a TA to share an example of relative units from their work.

> :briefcase: **Employer Competitive Note:** As a UX/UI designer, you will work with developers who will help code your RWD solutions. Being able to speak about fluid design technology and RWD concepts makes you more employable. These skills should be included in your resume and your LinkedIn skills profile.

Students now have a basic understanding of how fluid design is defined. Explain what is different about designing for mobile and the special considerations that come into play in the next section.

## 3. Instructor Do: Design Considerations for Mobile Web (10 min)

> :pushpin: **Important Point:** Your goal is to review the best practices, or tradeoffs, that designers must make to create great mobile designs. This section also supports today's first two learning objectives, which are defining, understanding, and applying fluid design.

In this section, you'll explain what makes designing for mobile displays challenging, such as size constraints for graphics and legibility of text on a small screen. We'll also cover best practices for saving time and ensure a successful result—frictionless user interaction.

- Review how ***small screens are hard***.

  - It is the UI designer's job to take on this challenge.

  - Don't take screen real estate for granted.

- Ask: ***"What else makes mobile hard?"***

  - Mobile challenges:
    - Mobile performance can vary.
      - A webpage loading via Wi-Fi or cellular.
    - Context of use can affect the experience.
      - Using on the train, in traffic, etc.
    - Designers strive to keep pace with new products and constant tech innovation. Every six months, there is a new mobile device from a different technology provider.
    - Time spent on mobile webpages is not the same as time spent on a desktop. The size of the device influences how long a user spends consuming mobile content.
    - Users will start on mobile, then move to tablet or desktop, all doing the same task.

### Keep Mobile Navigation Simple

- Prioritize navigation based on functionality.
- Minimize the levels of navigation.
  - No one likes to dig through menus.
- Ensure labeling is clear and concise for navigation.
- Offer short-key access to different features.
- Maintain a 44 x 44px space (iOS) for touchscreen tap points.
- Define distinct interaction states and links while making it clear they have been activated.

> 💎 **Designer Insight:** Briefly share a personal story of working on mobile navigation.

### Keep Content to a Minimum

Don’t overwhelm users. Respect the small screen space.

- Ensure that content is universally supported on all devices (e.g., if it requires Adobe Flash, don’t use it).

- Make page descriptions short and to the point for relevant bookmarks.

### Optimize User Time and Reduce User Inputs

- Keep URLs short.
- Offer alternative input mechanisms (video, voice, etc.).
- Minimize input on forms.
- Allow permanent sign-in.
- Keep scrolling to a minimum and only allow scrolling in one direction.

### The Future Is Mobile

Mobile access and commerce are driving forces in emerging economies where many consumers are more likely to have a smartphone or a feature-phone than they are to have a desktop or laptop computer.

> **Instructor Note:** Have a short discussion about the dominance of mobile technology.

Ask: **"How many of you could get through the day if you lost your mobile phone?**"

- Many of you will work for companies that need this kind of thinking.

- For example:
  - Apple has created an app to find my iPhone. One reason was to deter theft, and the other was a response to the panic and anxiety that users bring into an Apple store when they have lost their phone. Our lives, for better or worse, take place on smart devices.

Ask: **"How many phone numbers do you know by heart?**"

- For example:
  - The lack of memorizing phone numbers has literally offloaded that cognitive responsibility onto the phone. This also requires us to trust the device with that role and is linked to the issue of losing your phone or recovering your contacts.

Now it's time for students to practice some of these mobile considerations.

Next, students will jump into two activities to apply what they've learned with hands-on practice.

The following two back-to-back activities provide an opportunity to design and test a mobile blogs. These activities support the third and fourth learning objectives, test mobile display type size preferences with users, and execute a RWD of a blog post.

> **Instructor Note:** Pause for any questions before moving into the activity.

## 4. Student Do: Mobile Blog Redesign Activity (15 min)

**TAs:** Slack out to students the following Google Doc activity:

[11-Week/02-Activities/11.3/11.3-01-Mobile-Blog-XD-Mirror-Activity Google Doc](https://docs.google.com/document/d/1pTCHNm25RqFSWxjVqZLGhmSq3szq5PT3qm6gXmxbK9k/edit?usp=sharing)

Before students jump into the two following activities, share how their ability to test mobile display type size preferences with users will make them attractive job candidates.

> :briefcase: **Employer Competitive Note:** As a UX/UI designer, you will be expected to quickly create mobile solutions and work with real content. For example, you might be asked to redesign a blog as your first assignment on the job. Add this skill to your resume and your LinkedIn skills profile.

**Summary**

Students will practice creating a mobile screen that challenges their ability to solve an RWD problem quickly.

**Instructions**

Working alone, students experiment and design RWD layouts. Students can use Figma or Adobe XD.

> :globe_with_meridians: **Online Recommendation:** Students will work individually, so have everyone share their screen via Zoom. TAs can dive in where they see students struggling with wireframe components.

> **Instructor Note:** Highlight a few students throughout the activity and shorten the review time if needed.

**Instructor and TAs**

Set a timer for 15 minutes to keep on track.

TAs, keep an eye on Slack and utilize a breakout room if students need more help.

**Deliverable**

Students will post mobile blog solutions for feedback to Slack.

## 5. Student Do: Mobile Blog Design Test Activity (10 min)

**TAs:** Slack out to students the following Google Doc activity:

[11-Week/02-Activities/11.3/11.3-02-Mobile-Blog-Test-Activity Google Doc](https://docs.google.com/document/d/1zQoicl7eO7MegiREArCGyRALJkR1TxjvpAH1Fg-JVBo/edit?usp=sharing)

Briefly explain how the ability to redesign a blog post can help students be more attractive to employers.

> :briefcase: **Employer Competitive Note:** As UX/UI designers, your ability to demonstrate your mobile testing skills will be essential in your job search and should be featured in your portfolio case studies, too. UX teams are seeking designers who care about their users. Having done testing shows your dedication to getting the "right" solution. Add mobile user testing to your resume and LinkedIn skills profile.

**Summary**

Students will practice mobile testing screens, challenging their ability to solve an RWD problem quickly.

**Instructions**

First, students will iterate their design, then prepare for testing with a partner

> globe_with_meridians: **Online Recommendation:**: Put students into pairs in breakout rooms with a partner. They will share tools from Figma/Adobe XD for screen sharing and testing their mobile solutions.

Next, students will work with a partner to test. They'll share their blog as a prototype in Figma/Adobe XD and use screen share for testing. Once the test is complete, they'll switch roles.

Finally, the pair will discuss and gather feedback on what did and did not work.

**Instructor and TAs**

Set a timer for 10 minutes to keep on track.

Be on the lookout for possible struggles students may have with sharing their prototypes through Figma/Adobe XD or Zoom.

> globe_with_meridians: **Online Recommendation:**: Recommend that the pairs of students use the remote control feature in Zoom, allowing them to click through their partner's prototype.

- Navigate from screen to screen and check in with students who need help with mobile testing.

**Deliverable**

Students will post the mobile blog iterations for feedback to Slack that show their ability to scale typography decisions between screens.

## 6. Instructor Do: Mobile Blog Review (10 min)

Bring everyone back to the main Zoom room and lead a review of the activity outcomes.

- Aim to review four to six blog design samples, if possible.

- Call on the first student, using Zoom's spotlight feature to ensure all students are focused. Ask:
  - *What worked about your blog redesign?*
  - *What did you find challenging?*
  - *Did it help to look at your blog design on your phone? Why or why not?*

- Now, take a moment to share a few common misconceptions and *actionable* feedback for the students. For example:
  - *Common misconception:* There is no replacement for looking at a solution on the actual device itself.
    - Robust mobile user testing involves looking at websites on all major platform devices from Apple, Samsung, Android, Windows, and even Huawei. Don't mistakenly assume that if you design for Apple X your mobile solution will look great on other operating systems—it won't.
  - *Actionable feedback:* If mobile type is too small or too close to the edges of the screen, increase spacing.

> **Instructor Note:** Professional designers will often use two phones during mobile user tests to capture testing experiences.

## 7. Instructor Do: Size Testing and Size Controls (5 min)

> :pushpin: **Important Point:** Your goal is to introduce students to the idea of size testing and specifically size controls. This ties into the third learning objective about defining user controls and user testing for type size.

Here you'll go deeper into how to design for mobile. Specifically, focus on type size, a critical component of UI.

**As UI designers, we need to care about how our users engage with our content.**

### Testing and the Fat Thumb

- Consider your users' fingers (e.g., the fat thumb).

  - > **Ask:** "Everyone, give me a thumbs up and put your thumb toward the camera. Look at all those different thumbs!"

### Make Your Screen Legible Through Size Testing 

- A big consideration is typography and legibility.
  - We discussed typography in units 8 and 9. However, choosing typography and using typography in your design layouts can result in different executions.
  - *Legibility:* Designers must consider how easy it is for the user to read words (typography) on the screen in the presented context, which could be a smartwatch, tablet screen, smartphone, etc.

- We need to build versions of our copy and test how readable our content is on each device. Why? Typography and legibility are part of usability. We want to make useable solutions because if we care about our users, we will present them with a readable content.

> :gem: **Designer Insight:** Share an experience working with a lot of text on a mobile experience.

> **Instructor Note:** Ask one to two students to briefly share their experiences interacting with type on a screen—have they increased type size, zoomed in, found type difficult to read, etc.?

- Typography is about consistency: consistent sizing, consistent styling, consistent legibility, etc.

### UI Controls Are Essential for Interaction and Accessibility

Giving your users control over their UI sizes.

- We don't all have the same proportions, have the same eyesight, or the same hand dexterity. Allowing your user to modify the size of their typography, UI elements, and contrast will improve accessibility.

- Not all users' eyes work equally well; allowing users to modify the sizing will improve accessibility for all users.

  - Legibility and the "right" size is achievable through testing, which could mean training your user to modify the type size for themselves.

- **TAs:** Share this link: [https://mashable.com/2018/05/17/iphone-accessibility-features-for-everyone/](https://mashable.com/2018/05/17/iphone-accessibility-features-for-everyone/) — for students to read at home.

> :gem: **Designer Insight:** Share how you approach size testing and user controls in your client work.

This was a brief but important topic. Students will understand it better after completing the following activity. Next, they'll play with type size and discover what test users prefer.

> **Instructor Note:** Pause for any questions before moving into the activity.

## 8. Student Do: Three Bears Type Test Activity (10 min)

**TAs:** Slack out to students the following files:

- [11-Week/02-Activities/11.3/11.3-03-3-Bears-Blog-Type-Test-Activity Google Doc](https://docs.google.com/document/d/1D_KxP2ILnlrGxLKn1BhFCvENENccWQbmlb3Zyo8Sdh8/edit?usp=sharing)

- [11.3-03-Goldilocks-and-the-Three-Bears-Type-Test-Figma-Template](https://www.figma.com/file/nKpheCXbqGRJDUs8QZKEmi/11.3-03-Goldilocks-and-the-Three-Bears-Type-Test)

**Summary**

In this activity, students will practice creating mobile-type versions, challenging their ability to solve an RWD problem quickly.

**Instructions**

Students will work alone, then get into groups of two. Students can use Figma or Adobe XD.

They will build three different versions of their mobile UI and test each version on users/classmates. Like Goldilocks, the user will determine the "just right" type.

**Instructor and TAs**

Set a timer for 10 minutes to keep on track.

Navigate from screen to screen and jump into breakout rooms and help students create type samples.

> :globe_with_meridians: **Online Recommendation:** Students will be working individually for the first part of the activity, so have everyone share their screen. **TAs:** Navigate from screen to screen and help students struggling with wireframe components. Highlight a few students throughout the activity to allow them to talk through their big, medium, and small decisions with type.

- Shorten the review time if needed.

**Deliverable**

Students will post the version the tester preferred and explain why in Slack.

## 9. Instructor Do: Three Bears Type Review (10 min)

Close out the breakout rooms and bring everyone's attention back to your screen to lead a review of the testing results.

- Aim to review three to four typography samples.
- Call on a student with a promising solution, using the spotlight Zoom feature to help students focus on them.
- > **Ask:**
  - *"Why did you choose this size?"*
  - *"Does anyone see something they find confusing or that could be iterated?"*

> :gem: **Designer Insight:** Share a personal story about working with mobile type solutions. Alternatively, invite a TA to share.

Now, take a moment to share a few common misconceptions and *actionable* feedback for the students. For example:

- *Common misconception:* "Expert typographers don't need to do versions." *False!* Design and typography are hard; if you don't create versions, you won't have a frame of reference for making decisions.
- *Actionable feedback:* 
    - Try going too big at first. Then, if too big is obnoxious, work down from there. Encourage students to take a nuanced approach to their decisions.
    - Look out for widows (one word at the end of a paragraph) or line length errors (ideally about 65 characters per line). If students violate these, identify them and recommend fixes.

Before moving on to your demo, remind students that they can always ask for more feedback on their mobile blog during office hours.

## 10. Instructor Do: Demo - Figma/Adobe XD Text Tool and Responsive Type Rules (5 min)

> :pushpin: **Important Point:** Your goal with this brief demo of Figma/Adobe XD type tool is to show students how we maintain UIs and responsive websites in Figma/Adobe XD. After the demo, students will work with Adobe XD type tools in the activity that follows.

> :globe_with_meridians: **Online Recommendation:** If you choose to demo Figma, follow similar steps from the Adobe XD demo version.

**Demo Adobe XD:**

1. Download and open the Adobe XD resource:

    - [https://drive.google.com/open?id=1Gg5uKn3M-rvNOwAkgOx9dXYyNzQDgwta](https://drive.google.com/open?id=1Gg5uKn3M-rvNOwAkgOx9dXYyNzQDgwta)

    - ![Images/01-XD-Assets-Demo.png](Images/01-XD-Assets-Demo.png)

2. Review the Adobe XD file.
3. Open the Assets panel.
4. Select a typeface.
5. Add a type style to the assets.
6. Control select or right-click to edit the typestyle.

> Pause for questions before moving on. Reassure students that they'll get faster at creating UI solutions the more they practice with Adobe XD.

Next, students can apply what they learned in the following activity.

## 11. Student Do: Figma/Adobe XD Type Styles Activity (5 min)

**TAs:** Slack out to students the following Google Doc activity:

[11-Week/02-Activities/11.3/11.3-04-Define-Type-Styles-Activity Google Doc](https://docs.google.com/document/d/1zEFqqKkoGebC3ByTbmE7DsT8bShg66tiSkStmwwn8yY/edit?usp=sharing)

**Summary**

Students will define design type styles in Figma/Adobe XD. This also gives them additional practice working with Figma/Adobe XD, ultimately speeding up their page design work.

**Instructions**

Working alone, students experiment and design RWD layouts. Students can use Adobe XD or Figma.

**Instructor and TAs**

Set a timer for 5 minutes to keep on track.

Use this time to target any students who are struggling with Figma/Adobe XD. Possible struggle spots include:

- Students are not making text boxes.
- Using the return key rather than allowing copy to follow on resize.
- Applying *lorem ipsum* rather than real content.

> :globe_with_meridians: **Online Recommendation:** Students will work individually, so have everyone share their screen via Zoom. TAs should navigate from screen to screen, diving in to help students struggling with wireframe components.

- Use the spotlight feature of Zoom to showcase a few students throughout the activity. Have them come off mute and talk through their actions.

- Shorten the review time if needed to give students more time for this activity.

**Deliverable**

Students will post type style solutions for feedback to Slack that show their ability to make typography decisions for a UI system.

## 12. Instructor Do: Figma/Adobe XD Type Styles Activity Review (5 min)

Bring all breakout rooms back to the main room, draw attention to your screen, and lead a review of the type styles activity.

- Remind students to share their work in Slack.
- Scroll through the solutions posted in the Slack channel, then choose two or three to review with the class.

- Stimulate discussion with the following questions:
  - *What surprised you about working with type styles?*
  - *What worked well?*
  - *What could have worked better?*
  - *Raise your hand if you think you need more practice!*

Now, take a moment to share a few common misconceptions and *actionable* feedback for the students. For example:

- *Misconceptions:* "Defining typography styles is the job of a graphic designer, not a UX/UI designer." *Possibly true.* It's likely you won't work on a product that has a large amount of oversight from your graphic designers or typographers.
- *Actionable feedback:* 
    - If typestyles are not labeled with the font name or size, remind students that their design decisions are meant to be shared. Make sure they communicate with others who are using the same styles.
    - Use common HTML/CSS code type conventions H1, H2, H3, H4, p, for your type style labels.

Pause for questions.

Invite students to ask for more feedback on their type styles work during office hours.

Next, you'll dive into how designers handle navigation for mobile design.

## 13. Instructor Do: Mobile Navigation (10 min)

> :pushpin: **Important Point:** Our goal is to discuss strategies for designing mobile navigation and why users might prefer specific navigation interactions. This lecture supports today's fourth learning objective, defining the 10 types of navigation patterns.

At this point, students should understand how font choice and type size impact a user's experience of a mobile webpage or app. They also know that simplicity is key when designing for mobile screen size. Now, dive into another aspect of mobile design: navigation.

Start by connecting knowledge of user mobile preferences with job competitiveness:

> :briefcase: **Employer Competitive Note:** As UX/UI designers, your role is to apply usable typography decisions across a UI from content to navigation. Application of a UI system is key to getting a new job. Add mobile navigation best practices to your resume skills as well as your LinkedIn skills profile.

### Navigation Is About Orientation

All navigation should help your users understand: Where am I? Where can I go? And where have I been?
- Review some desktop navigation strategies.

1. Desktop vertical navigation (left or right side)
2. Full-screen navigation
3. Fixed sticky navigation (stay at the top or bottom during a scroll)
4. Parallax scrolling (content scrolls at different speeds)

> :gem: **Designer Insight:** Share a personal anecdote about your eyes being opened to user preferences when it comes to mobile design or ask a TA to share briefly.

### Responsive Navigation Is Essential

- Users will start their viewing experience on the phone, then jump to a computer and complete it on a tablet.
- Ask yourself the following navigation questions:

  - How can you reduce the complexity of your navigation as much as possible?
    - If your structure is seven levels deep, few users will be up for that challenge.
  - How can you ensure that the navigation doesn’t get lost throughout your resolution adaptations?
  - Have you tested it thoroughly to ensure that the navigation aligns with the user’s goals in visiting the website?

### Review the 10 mobile navigation patterns and strategies.

1. Hamburger navigation:
   - A UI designer's choice that has persisted
2. Tab bar navigation:
   - Requires swiping between tabs
   - Limited based on screen size
   - Contrasts with hamburger navigation
   - Reduces discoverability by half when main navigation is hidden
   - Increases task time and perceived task difficulty
3. Do very little navigation
4. Multilevel toggle navigation
5. Simple toggle navigation
6. Full-screen navigation
7. Shelf navigation (desktop and mobile)
8. Overlay navigation (desktop and mobile)
9. Drop-down menu navigation
10. Multi drop-down menu navigation

> :gem: **Designer Insight**: Share how these navigation patterns guide your work.

> :globe_with_meridians: **Online Recommendation:**  Take a moment to check in with the class and see how comfortable they're feeling with mobile navigation patterns and strategies. Stop sharing your screen for a moment and switch to Gallery View in Zoom to see your class on one screen.

Next, round out this discussion on the 10 navigation patterns by reviewing a few key navigation tips.

## 14. Instructor Do: Navigation Tips (5 min)

> :pushpin: **Important Point:** The goal is to review navigation tips students should be using as they contemplate designing their mobile interfaces.

Share some essential navigation design tips to prepare students for creating their own navigation UI for mobile screens.

All students—and designers—should test for the following qualities and build them into every screen and UI they design.

1. Make it visible.

   - It seems easy enough, but if your user cannot see or understand it, they will not be able to use it.
   - Designers must test for this.

2. Show the task in the menu.

   - Make your user's interaction visible. Drop-down menus have a down arrow and change colors.

3. Communicate location.

   - Breadcrumbs—or clear steps—and visible navigation label states help orient your user.

4. Don't hide the menu.

   - Keep the menu easily available and not only at the top of the page.

> :gem: **Designer Insight:** This is a good moment to add your own "tips" for navigation design.

Remind students that there are numerous tips and best practices for improving a UI, and they will develop their own as they learn and grow as designers.

> **Instructor Note:** Pause for questions and then announce the break.

## 15. Break (15 min)

It's time for a break.

Let students know that after the break, you will dive into a lecture about asset handoffs and working with developers, followed by a demo.

**Optional:** If students are energetic, feel free to shorten the break.

> :globe_with_meridians: **Online Recommendation:** We all need a break, but do not close your Zoom or stop recording.

- Be creative with what you share during break. YouTube timers, gifs, Jeopardy song, etc.

## 16. Instructor Do: Asset Handoff and Working With Developers (10 min)

> :pushpin: **Important Point:** The goal is to introduce students to the practice of working with a team and sharing their UI solutions. This lecture supports the sixth learning objective, using Adobe XD type tools and Zeplin.io to hand off work to collaborators.

In this section, you're pivoting away from mobile screen design to the design process: how to collaborate with developers and members of your design team.

> :briefcase: **Employer Competitive Note:** As a UX/UI designer, your role will be involved in the production of solutions, which means that you will be working with developers to execute a solution in code. You're an asset to a design team if you can get along with and communicate effectively with developers. Add asset delivery or developer handoff skills to your resume, and LinkedIn skills profile.

### Katica Babarczi's Quote

Ask a student to read the quote from Katica Babarczi, Hungarian UX/UI designer and creative director at Tep fitness app. Babarczi focuses on accessibility concerns and is a self-proclaimed "super-empathetic designer with a strategic mindset."

### The UX/UI/Development Team

It is unlikely students will wireframe, design, and code every screen themselves as designers. Therefore, teamwork and collaboration are essential skills to possess and demonstrate when interviewing.

> :gem: **Designer Insight:** Share a brief anecdote that illustrates the critical importance of teamwork abilities for emerging designers.

### Communicate: Empty State

Developers need to understand the states of a UI, and empty is one of them. This is especially so if you are working on a solution that has users' input or user-generated content (UGC). When a user first creates a space to put their content, that space is empty, waiting to be filled.

> :gem: **Designer Insight:** You or a TA should tell a brief anecdote that emphasizes the importance of using empathy for your user when considering the empty design state.

### Edge Cases

- Edge cases include things like designing the most extended German version of a label.
  - For example:  "Donaudampfschifffahrtselektrizitätenhauptbetriebswerkbauunterbeamtengesellschaft" at 80 characters is the longest German compound word. It translates as "association of subordinate officials of the head office management of the Danube steamboat electrical services."

    - [https://www.thoughtco.com/longest-german-word-in-the-world-4061494](https://www.thoughtco.com/longest-german-word-in-the-world-4061494)

  - Atypical use-cases might come up.
    - For example: A headline tile under 60 characters.

  - Collecting edge cases in a spreadsheet and providing some written specifications might help simplify things for developers.

### Provide Assets: Icons and Pictures

- Assets need to be complete. All icons should be provided as .svg as they are vector elements.

### Consistency Is Key

- Building a style guide for developers and turning it into a design system will make your designer-developer collaboration manageable and your product consistent.

- **TAs:** Slack out to #resources channel for students to read at home:
  - [https://uxstudioteam.com/ux-blog/design-system-sketch/](https://uxstudioteam.com/ux-blog/design-system-sketch/)
  - [https://fireart.studio/designing-for-edge-cases-3/](https://fireart.studio/designing-for-edge-cases-3/)

Now that students know that collaboration is integral to the design, we'll show how designers share and collaborate on their work using Figma/Adobe XD with developers.

## 17. Instructor Do: Demo - Figma/Adobe XD Development Specs and Zeplin.io (15 min)

> :pushpin: **Important Point:** The goal is to introduce students to how developers code UIs and responsive websites. This requires sharing and communicating on developer's terms (e.g., specs and design assets).

> :globe_with_meridians: **Online Recommendation:** Since you’ll be sharing your screen during this demo, students might be hesitant to come off mute and ask questions. Alternatively, you can ask students to share their questions in the Zoom chat and have the TA share afterwards.

### Demo Steps for Adobe XD

Review how to share with developers.

1. Open the Adobe XD blog resource.

   - [https://drive.google.com/open?id=1Gg5uKn3M-rvNOwAkgOx9dXYyNzQDgwta](https://drive.google.com/open?id=1Gg5uKn3M-rvNOwAkgOx9dXYyNzQDgwta)

2. Click Share UI > Share With Developers.

   ![02-XD-Share-developers.png](Images/02-XD-Share-developers.png)

3. Change the share setting to Web.

   ![03-Set-for-Web.png](Images/03-Set-for-Web.png)

4. Follow the Share link to review the assets and development rules.

   ![04-Development-Public-Share.png](Images/04-Development-Public-Share.png)

5. Review the assets and select an item and review the development rules.

   ![05-Dev-rules.png](Images/05-Dev-rules.png)

### Demo Steps for Zeplin.io

Other tools can improve handoffs with front-end development.

**Zeplin.io** is one option for a collaboration tool.

1. Go to Zeplin.io.

   - [https://zeplin.io/](https://zeplin.io/)

2. Create an account.

3. Download the iOS app.

   ![06-Zeplin.io-Download.png](Images/06-Zeplin.io-Download.png)

4. Open the Zeplin.io app.

   ![07-Open-ZeplinApp.png](Images/07-Open-ZeplinApp.png)

5. Select a web project.

   ![08-Select-Web.png](Images/08-Select-Web.png)

6. Go back to Adobe XD > File Export to Zeplin.

   ![09-In-XD-Export-to-Zeplin.png](Images/09-In-XD-Export-to-Zeplin.png)

7. Go to the Zeplin app to select a project.

   ![10-Uploads-Screen-Select.png](Images/10-Uploads-Screen-Select.png)

8. Select an asset to review development review.

   ![11-Explore-Around-Assets.png](Images/11-Explore-Around-Assets.png)

9. Select a second asset.

   ![12-More-Dev-Assets.png](Images/12-More-Dev-Assets.png)

- **Ask,** "Any questions?"

  - Zeplin.io allows one free project, but learning it will make you more useful with a development team.

Now, at last, students can put into practice what they've just learned in a design and handoff activity using Figma/Adobe XD and Zeplin.

## 18. Student Do: RWD Blog Post and Development Handoff Challenge Activity (20 min)

**TAs:** Slack out to students the following file:

[11-Week/02-Activities/11.3/11.3-05-RWD-Blog-Zeplin-Handoff-Activity Google Doc](https://docs.google.com/document/d/1PIfQG6fqx9uPdu5i16nlyKqqql68spHU9er3eP8bys8/edit?usp=sharing)

**Summary**

Students will practice iterating mobile solutions for screens that represent their ability to solve and hand off an RWD solution quickly. Students can use Adobe XD or Figma.

**Instructions**

Working alone, students will practice iterating, designing RWD layouts, and packaging assets.

> :globe_with_meridians: **Online Recommendation:** Students will be working individually, so ask everyone to share their screen. TAs should navigate from screen to screen, helping students who struggle with wireframe components.

- Use the spotlight feature to focus on a few students during the activity, asking them to unmute and share what they are working on.
- Shorten the review time if needed.

**Instructor and TAs**

Set a timer for 20 minutes to keep on track.

Use this time to target any students who are struggling with iterating their RWD blog, including trouble spots like the following:

- Students not creating more type styles but rather individually updating all type usage.

- Students not sharing their screen and not sharing their Figma or Adobe XD screen in Slack.

> :globe_with_meridians: **Online Recommendation:** Create a one-on-one breakout room where you can help students with iterating their RWD blog. Have TAs monitor the class and send students to your breakout room for help with design or Zeplin.io questions.

**Deliverable**

Students will post Zeplin.io solutions for feedback to Slack that show their ability to design and share solutions with developers.

## 19. Instructor Do: RWD Blog Post and Development Handoff Review (10 min)

Bring all breakout rooms back to the main room and lead a discussion of the activity.

Remind everyone to share their Adobe XD development and Zeplin.io links in Slack.

- Aim to review two or three student work samples.
- Call on the first student who has a promising solution.
- > **Ask:**
  - *"Tell us what strategy you used to hand off your RWD solution."*
  - *"Who can offer a critique? What do you think works well and doesn't work well?"*

> :gem: **Designer Insight:** Help students connect this learning to the real world by sharing a personal story about working with RWD navigation solutions.

- Now, take a moment to share a few common misconceptions and *actionable* feedback for the students. For example:
  - *Misconceptions:* "Zeplin.io is the only way to share with developers." *Sooo false!* There are many, but Zeplin.io is a very good one.
  - *Actionable feedback:* 
    - Use clear and specific details and descriptions.
    - Never share just a Zeplin.io link. Make sure to include your contact information, too, for questions. Also be sure to link to the prototype.

- Remind students that they should be making progress on their challenges.
- Keep the day moving and remind students that they should stay for office hours if they want more feedback.

You *did* it! All that's left for tonight's lesson is a review of the mobile RWD design concepts covered in class.

## 20. Instructor Do: Recap and End Class (5 min)

Call the class back to attention and recap tonight's class.

**Review the concepts students learned today.**

Help students anchor today’s learning. Ask them to raise their hands—or post answers in Slack—and respond to questions about the following concepts from today's class:

- What are the characteristics of fluid design?

  - Answer: Any time content has to work between multiple screen states (RWD).

- How is fluid design measured (in units)?

  - Answer: Relative units (%, Fr, Ems, etc.).

- Why is it valuable to test the size of type on users?

  - Answer: Legibility is usability, and caring about your users means you care about how they can read.

- Who can name some of the 10 navigation patterns we covered?

  - Answer refresher:
      - 1. Hamburger navigation
      - 2. Tabbed navigation bar
      - 3. Do very little navigation
      - 4. Multilevel toggle
      - 5. Simple toggle
      - 6. Full screen
      - 7. Shelf navigation (desktop and mobile)
      - 8. Overlay Navigation (desktop and mobile)
      - 9. Drop-down menu
      - 10. Multi drop-down menu

- What is a design "handoff," and what tools are used for it?

  - Answer: When pixel-perfect design assets are delivered to a development team through tools like Zeplio.io.

- Encourage students to work on their challenges, which spans weeks 11 and 12.

### Office Hours Are After Class

> **Instructor Note:** Take questions and wish everyone a good night.

---

## We Want Your Feedback!

Instructor, how did tonight's class go?

Please submit any issues or comments on the UX/UI curriculum to our Google Form.

[Submit Issues](https://docs.google.com/forms/d/e/1FAIpQLScTc104D7Fd-2fDk3E4IIwxuOe-BNhPhWffIE9VBt7_e-t3DA/viewform)

With this form, you can now view the status of your submission and other issues here:
[Issue Status](https://docs.google.com/spreadsheets/d/1UyRh0f6fwtMD5SfExvk3BZxIIioicTNhXWixjmnes1c/edit?u

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.