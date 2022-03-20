# Lab Instructions

# Step 0: Create a GitHub account
1. If you don't have a GitHub account already, [create one](https://github.com/join). If you do, **record the name of your handle in your lab report** and **record a link to one repository you either follow or star**.
2. If you don't already have _git_ installed on your development machine, [do so](https://git-scm.com/downloads).
3. Install a text editor or some sort of application for local development. Lately, I'm partial to [Visual Studio Code](https://code.visualstudio.com/) and my instructions assume it's use, but you're welcome to diviate. _Each one should choose their own sword, etc. etc._

# Step 1: Fork this repository and create your lab report file
1. After logging in, navigate to the [root](https://github.com/trevordbunch/cis411_lab3_uiux) of this repository.
2. Fork this repository to your personal GitHub account (hint: read the page).
3. Navigate to your forked repository in your GitHub account and copy the reference to your repository in from the <button class="btn btn-sm btn-primary">Clone or Download</button> button.
4. Open the terminal or command line interface on your development machine, navigate to your chosen working directory, and execute the following command: ```git clone [YOUR COPIED GITHUB CLONE REFERENCE]```.
5. Navigate to that directory ```cd cis411_lab3_uiux```.
6. Create a lab report mardown file (ex. ```cp labreports/LAB_Template.md labreports/LAB_[GITHUB USERNAME].md``` ).
7. Add your lab report ```git add *```
8. Add the file to your branch ```git commit -a -m "your commit message"```.
9. Push the change to GitHub ```git push -u origin main```.
10. As you make additional changes to the lab report, commit and push your changes.

**Note:** you are free to work with classmates on this assignment (*and it is expected for Step 3*).  However, if you work with colleagues:

1. You must specifically note your collaborators by name at the top of your report.
2. You may not completely copy each others work (diagrams and descriptions, even if your solutions are identical).

# Step 2: Analyze Two Online Job Search Sites
1. Select two different online job sites: one that you believe you will like, and one that you believe you will not prefer.  
1. Conduct the following two actions on each site, capturing screenshots along the way for each and recording them your report, including simple captions and the URL of the pages you visited.
   - Create an account on the site and update your skills or preferred job interests on each (if you already have an account on a given site, note that in advance, record the process of getting to your profile, and update your profile with additional / refined skill or experience information).  
   - Search for a job and take all the necessary steps right up to applying for the job (you are not required to complete the application).    
   - For each step (and under each screenshot), briefly note your observations of your relative experience using the given page. Was there anything you like? Is there anything you hate? What would you change? (You don’t need to answer these questions for every step, but these are provided to help trigger your thinking).  
   - At the end of the two actions, take stock of the experience and grade the usability of the experience using the table found in the lab template.

# Step 3: Conduct Competitive Usability Test
With your newly formed team and your assigned product, complete the following steps:
1. Document one use case that your team believe you will need to be able to fulfill for your upcoming project. Provide that use case as a part of your submission.
2. Research sites / services / applications that you can consider legitimate competitors or adjacent tools to the project you intend to build. Document the software/site on which you intend to conduct your test.
3. Document a basic series of actions as an outline for your usability test, steps that you plan to ask a willing participant to achieve. Provide that test plan as a part of your submission.
4. Invite your participant (a roommate or team member) to sit down in front of a computer device and walk them through the series of actions you recorded in Step 3, taking care not to tell them what to do but to simply ask them to figure it out and record their responses.  Make observations around the following areas:
   - On each step, ask them to verbalize what they see and what they think they should do to fulfill your requested action.
   - After they take an action, ask them for a reaction. Was that what they expected? Was anything unexpected? Was anything frustrating? Were there any pleasant surprises?
   - Take notes / record (with their permission) this session to help you document your findings later. I recommend screen recording if possible but not required.
   - Record and document your findings in this report.
   - What were the steps that the user took to accomplish their task? (If it’s helpful, you’re welcome to diagram it vs. write it out.)
   - Were they successful? Why or why not?
   - If the user was ever frustrated in the usability lab, what was the cause of their frustration?
   - If the user was delighted / pleasantly surprised by an experience, what was it and why do you believe it was a positive experience?

5. Document your overall findings and recommendations in the following areas:
   - Provide at least 3 improvements you believe could be made to the usability of the workflow in question.
   - Outline at least 2 experiences in the workflow that you believe were of benefit to the user.
   - What do you believe your team did well in conducting the usability test?
   - What could your team improve for next time (hint: there will be a next time)?
   - Offer a brief statement (no more than several sentences) about your experience conducting a usability test.

# Step 4: Submitting a Pull Request
Once you've completed your report markdown, reviewed your markdown formatting, and have committed all your changes to your (primary) main branch, initiate a Pull Request in GitHub to submit your Lab Report.
1. Navigate to the root of your forked repository (ex. https://github.com/YOURHANDLE/cis411_lab3_uiux).
2. Click the _New pull request_ button.
3. Choose the base fork _trevordbunch/cis411_lab3_uiux_ is the target and that your fully updated _main_ branch is the source.
4. Enter a title and description for the Pull Request (PR), **referencing at least one other student in the content via their GitHub handle**, and submit the PR.
5. Submit that URL to canvas as your lab report work.

# Extra Credit
Steve Krug outlined 10 rules, starting with [*Don't Make Me Think!*](https://www.amazon.com/Dont-Make-Me-Think-Usability/dp/0321344758) that we discussed in class.  For extra credit, write your own pithy useability rule to live by, and then explain why it is important.  (I'm looking for a single headline, and 1 supporting paragraph).
