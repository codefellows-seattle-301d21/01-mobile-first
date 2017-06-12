![CF](https://i.imgur.com/7v5ASc8.png)  Lab 01: Mobile First
=======
[Code of Conduct](https://github.com/codefellows/code-of-conduct)

Welcome to your first lab assignment for Code 301!!

Today we'll be kicking off our Blog App by applying what we learned in lectures to implement a mobile-first design, using responsive web design techniques. You'll also need to spend some time getting familiar with the new Git/GitHub & Pair Programming workflow that we'll utilize throughout this course.

*Please take the time to read carefully through each of the READMEs for lab assignments as they have detailed information regarding your assignment, such as: how to get started, resources, goals, grading rubrics, and how to submit your work.*

## Submission Instructions
When you are finished with lab, follow these steps to submit your work. Create one Pull Request (aka: "PR") from your Forked repo to the CF repo with your changes, and you'll each submit that same PR link in Canvas.

1. Ensure that all your local changes are committed, and pushed to your origin repo.
1. Visit the origin repo on github.com, and ensure that all of your completed work has been merged to master via Pull Requests within your repo.
1. Create a new PR from your Fork to the CF repo and ensure the branches look correct.
1. Fill in the template based on the text box prompts:
  1. Write a good descriptive summary of your changes:
    1. Be sure to include how much time you spent on it, and who you worked with.
    1. Briefly reflect on and summarize your process.
1. When you create the PR, it will have a unique URL. Copy this link, share with your partner, and paste it into the assignment submission form in Canvas. Both the driver and the navigator will submit the same PR link.

---

### Set up your repo

![High-level Overview: Git Workflow](gitflow_front.png)

Here is the recommended workflow (*We reviewed this in class*):

1. Driver: fork the CF Lab 01 repository if you haven't done so already.
1. Your **forked repo** on GitHub will be your "origin" repo. Clone **your fork** to your local development environment:
  1. If you haven't done so yet, create a directory named "301" - `mkdir 301/` (This will be your parent 301 directory and set you up for organizational success!)
  1. Next, `cd 301/`
  1. `mkdir lab-assignments` to house the pair assignment repos.
  1. `cd lab-assignments`
  2. `mkdir my-forked-labs`
  3. `cd my-forked-labs`
  1. `git clone` this repo.
  1. `cd` into this repo.
  1. Immediately `git checkout -b <driverName-navigatorName>` (ex: `git checkout -b rick-brian`).  

### Write code together!

Find those `TODO` items in the code, and tackle one of them.

1. Driver: In your terminal, ensure that:
   - you are on a branch with you and your partner's namesake.
   - you are currently within the starter-code directory.

1. Type `atom .` to open this starter-code folder as a project in Atom.
1. Use the Atom "Find in Project" (command shift "f" if on a Mac) to locate all the `TODO:` items.
1. Work through one or two TODO items before switching roles (or one hour, whichever arrives first), testing your code as you go.
1. In your terminal type `git status` to view the files that you have changed. You should only see the files that you have worked on.
2. Type `git diff` to see line-item changes with your down arrow key. (Type `q` to exit this mode!)
1. Type `git add file1 file2` where file1, file2, etc. are the files that you have changed.
1. Type `git status` to view the files that have been added to your commit. You should only see the files that you worked on.
1. Type `git commit -m "some meaningful multiline message"` where the message (present-tense) **thoroughly** explains the "why" of your changes.
1. Type `git status` to ensure there is nothing left to commit.
1. Type `git push origin your-name-partner-name` to push this branch to your forked repo on GitHub.
2. On GitHub, Add your navigator as a collaborator (go to settings -> collaborators).
3. Once they have been added, `Slack` to your partner your forked repo link for them to clone down.

### Switch roles

1. Navigator (AKA new Driver): You can now clone the driver's fork, to your own local dev environment. If you haven't already:
2. `mkdir 301/` that will be the parent directory for all things 301.
3. `cd 301/`
4. `mkdir lab-assignments`
5. `cd lab-assignments`
6. `mkdir partners-forked-labs`
7. `cd partners-forked-labs`
8. The new driver (original navigator):
  1. `git clone` the repo your partner Slacked you into your navigator folder.
  2. `git fetch origin` branch-name
  2. Now open the starter-code in Atom. It's your turn to have the hands on the keyboard!

---

## Learning Objectives
* What is Mobile First design?
* What is Responsive Web Design vs. Adaptive Web Design? - Discuss the difference between the two
* Formula for flexible layouts
  * Percentage-based Media
  * Media Queries: include logical operators, and media types
  * Fluid Layout
* Viewport and initial-scale meta tag
* Provide as a way for students to test their own portfolio on mobile by starting live-server and connecting to their own IP locally.
* Review embedded media in RWD; challenges, etc.
* Understanding SMACSS and benefits
* Breakdown common SMACSS stylesheets and usage
* Introduction to icomoon icon fonts, how to setup, and usage
* Introduction to students about the use of a vendor directory, as some may not be familiar with the  regular use of third-party code.
* Understand the basics of the :before and :after pseudo elements - these will be used to display icons on the front end.

---

## Resources  
<!-- a list of links if any are necessary for the assignment-->
- [Video: Mobile Testing Tip for Your Phone] (https://www.youtube.com/watch?v=2t4E_tc8TKM)

---

## Feature Tasks  
<!-- a list or description of the feature tasks you want the students to implement -->
1. Set up the viewport and fluid media rules so content fits on mobile devices.
1. Add a "Hamburger" menu button, that reveals the nav links when tapped on a mobile device.
2. Ensure the images are responsive

### Stretch Goals
<!-- Include any additional stretch goals for this assignment, which can vary depending on the class and their overall preparedness for additional work. -->
1. Use media queries to re-style the header and navigation on desktop-width screens. Nav should be tab-like links on one row.

---

## Rubric  
<!-- a list of grading requirements with associated points, scaling to 10pts possible -->
Criteria | Pts
---|---
Meets all Assignment Reqs | 6
Uses idiomatic code style | 3
Follows proper Git workflow | 1
**Total** | **10**

<!-- links -->
