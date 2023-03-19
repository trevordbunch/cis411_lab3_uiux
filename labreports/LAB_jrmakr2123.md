# Lab Report: UX/UI
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Jonah Robinson  
**GitHub Handle:** [jrmakr2123](https://github.com/jrmakr2123)  
**Repository:** [CIS411_Lab3_UIUX](https://github.com/jrmakr2123/cis411_lab3_uiux)  
<!-- **Collaborators:**    -->
___

# Step 1: Confirm Lab Setup
- [x] I have forked the repository and created my lab report
<!-- - [ ] If I'm collaborating on this project, I have included their handles on the report and confirm that my report is informed, but not copied from my collaborators. -->

# Step 2: Evaluate Online Job Search Sites

## 2.1 Summary
| Site | Score | Summary |
|---|---|---|
| [Indeed.com](https://www.indeed.com) | Score 1 | Summary 1 |
| [Flexjobs.com](https://www.flexjobs.com) | Score 2 | Summary 2 |

## 2.2 Site 1: Indeed.com
<!-- Insert Recorded Screenshots with captions and steps. -->
### Indeed homepage
![Indeed homepage](/src/indeed%201.png)
From the homepage, Indeed feels exactly how a job searching website should be. The homepage opens up to available jobs in your area. Since my preferred location is remote (being in college and all), remote is automatically selected and jobs appear. 

![Indeed jobs](/src/indeed%203.png)
The jobs are all listed to the left.
Once you select a job . . .
![Indeed jobs](/src/indeed%202.png)
then the selected job will appear on the right. This will then show details like the job description, the job benefits, and even the wages. I will admit, the thoroughness of the descriptions on indeed will change from employer to employer. To actually apply for the position you hit the blue Apply Now button or blue Apply on company site button. 

| Category | Grade (0-3) | Comments / Justification |
|---|---|---|
| 1. **Don't make me think:** How intuitive was this site? | 3 | Quite intuitive. The website easily conveys its purpose to the user and guides them to applying for a job.   |
| 2. **Users are busy:** Did this site value your time?  | 3  | Short answer: yes. The moment you go on Indeed.com you see jobs even if you are not signed in.  |
| 3. **Good billboard design:** Did this site make the important steps and information clear? How or how not? | 1  | To actually apply, you click the apply now button. This step is clear. Everything after this is objectively not clear.  The information required to apply and the length of the process is unknown. |
| 4. **Tell me what to do:** Did this site lead you towards a specific, opinionated path? | 3  | Absolutely. So long as you a signed in, the information, things you are interested in (job wise), and the location you want to work will influence the results you receive.  |
| 5. **Omit Words:** How careful was this site with its use of copy? |2   | The site obviously copied a couple of key phrases to help entice potential applicants. This was seen more on the employer side though.   |
| 6. **Navigation:** How effective was the workflow / navigation of the site? |  2 | The site included a simple enough interface that helped me understand the process.   |
| 7. **Accessibility:** How accessible is this site to a screen reader or a mouse-less interface? | 3   | Just by using my keyboard, I was able to select a suitable job and run a pseudo application for it.   |
| **TOTAL** | 17  |   |

## 2.3 Site 2: Flexjobs.com
<!-- Insert Recorded Screenshots with captions and steps. -->
### Flexjobs Website
![Flexjobs.com jobs search](/src/flexjobs%201.png)
This is about as far as I was able to go. You could indeed select a job and look at the information. If you want to see a clearer and more concise version of this websites job description, look at the photos of Indeed's application process. This website was rough. You cannot view the job application or description without a flexjobs account. To my understanding, you need to pay money for an account of this stature. The website is not stylish or clean enough for me to spend any money on. The job titles and nondescript and show no inclination ont he description. 

| Category | Grade (0-3) | Comments / Justification |
|---|---|---|
| 1. **Don't make me think:** How intuitive was this site? | 1  |  Emulated the Indeed site design. Used too many colors and became distracting. Also information bombed the user on the information that did not pertain to the job. |
| 2. **Users are busy:** Did this site value your time?  | 0  | Absolutely not. It did show some job offers if you go to the site without logging in, but other than that, the information is vague, and you need to search for it.   |
| 3. **Good billboard design:** Did this site make the important steps and information clear? How or how not? |  0 | There is too much information for any information to be relevant. Furthermore, the user needs an account to view the job description unlike Indeed. The colors were red flags showing the user information that is important but not needed.   |
| 4. **Tell me what to do:** Did this site lead you towards a specific, opinionated path? | 0  | No. If I searched for a specific job, it showed that generic jobs do exist but did not go further to tell me what the job was about.  |
| 5. **Omit Words:** How careful was this site with its use of copy? | 1  | Copied a ton. The descriptions all sounded the same.  |
| 6. **Navigation:** How effective was the workflow / navigation of the site? | 1  | It looked well enough for a website full of its own advertisements. Other than that, it was too cramped to navigate easily.  |
| 7. **Accessibility:** How accessible is this site to a screen reader or a mouse-less interface? |  1 | You can go around on a keyboard, however it takes forever to change from the jobs side of the website to the job description side of the site. The keyboard could only move on one side, not the other.  |
| **TOTAL** |  4 |   |


# Step 3 Competitive Usability Test

## Step 3.1 Product Use Case

| Use Case #1 | |
|---|---|
| Title |Student checks the Lottie Nelson menu. |
| Description / Steps | The student first opens our app. Then they navigate over to the Lottie Nelson menu widget. After pressing on the widget, the menu will open up, automatically showing the menu for the corresponding week.|
| Primary Actor |The student |
| Preconditions |App must be installed. User must know how to use a smart phone.|
| Postconditions |none. |

## Step 3.2 Identifier a competitive product

List of Competitors
<!-- 1. Competitor 1 [www.awesomesauce.com](https://www.awesomesauce.com)
2. Competitor 2 [Bangarang Peter](https://www.youtube.com/watch?v=4PNOccSUb1Q) -->
Nothing really exists like this on the market. Our main competitor is Falcon Link since this application seeks to improve the usability of its services over mobile devices.

## Step 3.3 Write a Useability Test
Notice, for the following usability test, the test will be performed by testing functions and action flags corresponding to the average user response. In simpler terms, when the user presses a button, the flag or function that is ran is what the usability test will actually be manipulating. 

| Step | Tasks | Notes |
|---|---|---|
| 1 | Load application view.  |  This will run the function that loads the main application.  |
| 2 | Load Lottie Nelson widget view.  | This will run the function that opens the Lottie Nelson dinning menu.  |
| 3 |  Pull current lunch information from messiah.edu | This will test the function that retrieves the menu information and returns and error message otherwise.   |
| 4 | Update graphical interface to account for new display.  | Takes the menu information and turns it into a readable graphic.  |

<!-- ## Step 3.4 Observe User Interactions

| Step | Tasks | Observations |
|---|---|---|
| 1 |   |   |
| 2 |   |   |
| 3 |   |   |
| ... |   |   |
| n |   |   | -->

## Step 3.5 Findings
To try to explain the process of my test subject through a graph would be interesting. The tester opened the testing graphic and tested almost every function on paper. The subject did not actually run the test until they clicked on the menu button. As soon as they clicked the button, the test also subsequently finished. My tester recommend the Lottie Nelson menu should be a smaller, dark blue button. The testers curiosity was more or less captivated by their interest at the moment. That being said, it took them quite a bit to actually click the button. 

Lessons learned: Try to test for a different narrative. Sure everything behind the scenes can be tested in an automatic tester, but the actual UX/UI testing is less thrilling unless the user has a job to do. Since the menu is not a really important function (objectively) it should not take up as much space as any of the other buttons (like the course scheduler or degreeworks). When this was addressed after the test, the tester agreed with this sentiment. 

<!-- # 4. Your UX Rule (Extra Credit)
If you opt to do extra credit, then include it here. -->
