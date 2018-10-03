# Lab 7: Odd Student Out

*Due date for the **Information Architect**'s content and intent: **Friday, October 5, 2018***<br>*Due date for the final website: **Wednesday, October 10, 2018***

The goal of this assignment is to build a completely new, two-page website that uses everything new we've learned so far in CSC 174, plus all the best practices and standards from CSC 170.

- Refer to the [Assignment 2 (or 1) directories](http://csc174.org/assignment02/) on the class web server to find content
- Use  [this list (Google Sheet)](https://docs.google.com/spreadsheets/d/1gXQP-1Rmra6w3PH9GzKOG9Y8-VlKk-DjlCFYFQHo0MM/edit#gid=493379955) to establish your role in a city-team

Remember: you have to **complete each role (IA, Designer, Coder) at least once** during the semester.

This is a **team assignment**, however you will be graded for the work you do as an individual within the team.  

## Requirements

The team is responsible for delivering a website with the following elements:

- [ ] **Two webpages only.**  A home page (index) that uses a Z-pattern, and a long-scrolly page that uses an F-pattern
- [ ] Information about **three students**, two of whom have something in common, and one who is different

Note: the Information Architect and Designer must work together to decide how the content will be structured in HTML (the IA's job) and how the presentation layer will convey the Z- and F-patterns (the Designer's job).

### Information Architect's Requirements

The IA must deliver basic "content and intent" by **Friday, October 5 (by end-of-day or so)**:

- [ ] The **intent** must be represented in a **readme.md** file that contains the following information

  - Name of the **city-team**
  - List of the team members and **who is doing what**
  - **Link to the team's website** on the class webserver which won't be available immediately but will exist eventually. (You need to add this before you turn-in the assignment on Wednesday.)
  - A short description of the website's information architecture in terms of its: **ontology**, **taxonomy**, and **choreography**

Note: the purpose of the information architecture in the readme is to provide guidance for the designer (and to a lesser extent, the coder), so write it for *them*!

- [ ] The **content** must be represented in a set of  **initial documents, structured in HTML** in two files (the homepage and the one sub-page).  There must be enough structure and content for the Designer and Coder to begin work.
  - The IA will be graded on correct naming of files and semantic usage of *all* HTML tags.
  - In addition to the first-level tags that surround content (e.g. P tags, H tags, et cetera), all content must be positioned (nested) in structural elements (e.g. main, section, article, et cetera).
  - Note: even though the Designer and Coder may change the tags used in the HTML documents while they work, the IA will be graded for the HTML structure in the final delivery.  So the IA must watch how the team members add or change their HTML documents!  If they make mistakes, the IA will lose points for it. 

Note: for grading, the IA will be held to the standards introduced in earlier in CSC 174 including the rubrics for Assignment 4 and Assignment 5.

### Design Artist's Requirements

The Designer's due date is the same as the due date for the overall website: **Wednesday, October 10 (by end-of-day or so)**:

Note: the Designer needs to take direction from the IA, but only as described above.  Other than that, the Designer must *make their own choices* for which they will be graded.

- [ ] The Designer must clearly demonstrate understanding of the **C.R.A.P. principles**
  - Design choices such color choices and use of the box model (remember that?) will determine the Designer's grade.
- [ ] The Designer must implement the **Gutenberg rule** on the home and sub-page, specifically:  Z- and F-patterns, respectively
- [ ] The Designer must implement a **CSS strategy** that is easily understood and obvious.  (Hint: write a comment-block at the top of your CSS file(s) that describes the architecture and where things can be found.)

Note: an extra challenge for the designer is the two-page-ness of this website.  If you use a navigation element, how do you style the "you are here" indicator with only two menu items?  (Also, think about this: do you even need a traditional navigation element? ...it's up to you.)

Also note: the "hero" for the homepage is one of your challenges.  You probably don't have a photo that makes sense at this point.  But you have a camera on your phone, right?  (Hint, hint, hint)

### Coder's Requirements

The Coder's due date is the same as the due date for the overall website: **Wednesday, October 10 (by end-of-day or so)**:

- [ ] The website must follow industry best practices and standards which includes:
  - The file structure and files used for the website
  - HTML and CSS validation (within reason)
  - File sizes and feasibility of the code to run quickly and reliably in modern web browsers
  - Use of PHP includes to factor out common elements (within reason)
  - Correct implementation of JavaScript solutions, if any

## Installation

- [ ] The website must be installed on the class web server in the folder named: **assignment07** (…which already exists); then create a folder with a name based on the team city that you're in.  

### Web Server Credentials

Each team will use the same FTP account. Be careful *not* to disturb other teams' files.

```
FTP Server (a.k.a. Hostname): ftp.csc174.org
FTP Port: 21
FTP Username: assignment07@csc174.org
FTP Password: coffee1N/!18
```

*Notice that the username is different from last time:* assignment**07**@csc174.org

## Submit the Assignment

Note: even though you worked as a team, everyone will be graded as an individual based on the work you did. To get credit for your work:

- Everyone on the team must make a submission in Blackboard, in the assignment:<br> **Assignment 7: Odd Student Out**

- In the submission you must provide the following information:

  - **Your city-team name**
  - A list of **everyone's name** in your team (including your own) **and their role** (IA, designer, or coder)
  - A link to the **website**
  - A link to the **repository**

  *NOTE: do not write this information (above) in the comments section in Blackboard.  Use the "Write Submission" area*