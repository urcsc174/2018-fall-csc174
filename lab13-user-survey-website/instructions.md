# Assignment 13: User Survey Website

This is a complex assignment.  You will have two weeks to complete it.

*Due date for the final website: **Monday, December 10, 2018***

This is a **team assignment**, however you will be graded for the work you do as an individual within the team.  

## Guidelines for the Technical Coder

*Due date for the **Coder**'s first set of responsibilities is: **Wednesday, November 28, 2018***<br>

If the **Coder** fails to complete the following in a timely fashion so the IA and Designer can start their work, then the professor will re-assign the role of Coder to someone else and the Coder will get a zero for this assignment.

- Setup a public repository in Github (anywhere, so long as it's public)
- Add the team members as Collaborators to the repository
- Ensure the team members are able to replicate the repository to their localhost

Note that it is the **responsibility of the IA and/or Designer** to contact the professor (via DM in Slack) by end-of-day on Wednesday, November 28 regarding their concerns about the Coder's progress.  If the team members do not contact the professor in a timely fashion (by Wednesday, end-of-day) then failure by the Coder will impact the other members' grades.

## Guidelines for the Information Architect

*Due date for the **Information Architect**'s <u>basic</u> content, structure and intent: **Friday, November 30, 2018*** (five days)<br>

If the **Information Architect** fails to complete enough of their responsibilities in a timely fashion so the Designer and Coder have enough content and structure to begin their work, then the professor will re-assign the role of IA to someone else and the IA will get a zero for this assignment.

- It is the **responsibility of the Designer and/or Coder** to contact the professor (via DM in Slack) by end-of-day on Friday, November 30 regarding their concerns about the IA's progress.  If the team members do not contact the professor in a timely fashion (by Friday) then failure by the IA will impact the other members' grades.
- The IA's team and the professor will determine if the IA has done enough work in a timely fashion or not.  
- The professor's decisions in this matter are final.

## General Instructions

- [ ] For this assignment your city-team will build a **new website around a topic** of your city-team's choice.  
  - The appropriateness of the topic will impact the IA's grade.
    - By "appropriate" I mean a topic that can be pulled-together in a coherent way that will be easy to understand.
    - Note: the topic can literally be about anything.  E.g. shoe strings, ...whatever, so long as the content is architected, designed, and coded properly.
  - You may reuse/repurpose any content from any CSC 174 assignment.
- [ ] **The PRIMARY goal of the website** is to get website visitors to **fill-out a survey** that is related to the topic.
- [ ] The **survey, its content, and the post-survey response** must also be architected, designed, and coded properly.
- [ ] Results of the survey will be stored in a **MySQL database**.
- [ ] The website will also provide a **login for administrators** so they can access a private section of the website that is off-limits to non-logged-in visitors.  The login will be accessible from the public website but in a non-conspicuous location.
- [ ] The **administrator login, and its content (the four database functions)** must also be architected, designed, and coded properly.
- [ ] In the private section (the administrator's area), administrators will be able to perform these **four functions on the database table** that holds the survey data:
  - [ ] Ability to **see** all the surveys, in table form
  - [ ] Ability to **add** records to the database table
  - [ ] Ability to **edit** any of the records in the database table
  - [ ] Ability to **delete** any of the records in the database table

*NOTE: there are many ways to accomplish the four functions.  You do not necessarily have to use AJAX, JSON or other advanced techniques we never covered in CSC 174.  You can do it "the old fashioned way" using four separate PHP scripts on four separate webpages ...it doesn't matter, so long as it works as part of the overall website.*

## Information Architecture

The following is in effect, the rubric for the IA:

- [ ] Come up with the **ontology** within the chosen domain that gets represented in a **semantically-clean document structure in HTML** (i.e. the IA creates all the HTML documents and initially sets all the HTML structural tags around the words and pictures)
  - [ ] Besides the content of the website, the Information Architect is *also* required to define the user survey (including the content that the user sees after they fill out the survey), and the administrator web pages.
- [ ] Words in the structure need to clearly demonstrate a **taxonomy** used to describe the ontology (i.e. the headings need to be consistent and clear ...and lots of them)
  - [ ] The taxonomy must extend to the survey, and the administrator area.
- [ ] The structure, which may (typically) include multiple webpages, must indicate an optimal **choreography** by which the website visitor should progress through the website; that includes website navigation as necessary (sometimes, multiple menu systems!)
  - [ ] The choreography must include the path to the survey and post-survey content, plus the path to the administrator login, administrator account creation process, and the administration area itself.
- [ ] The IA will need to communicate the following by way of a **readme.md** file in the team's shared repository (*not* part of the website!):
  - [ ] **Ontology** - a **list** of "classes" and "relationships"
    - [ ] E.g. student *has a* major; student *has a* profile picture; et cetera
    - [ ] Remember, the user filling out the survey, and the website administrator are also classes!
  - [ ] **Taxonomy** - a short **list** of terms that will be used in the website to describe the ontology which includes terms used in the survey and terms used in the administrator webpages.
  - [ ] **Choreography** - a **list** (or lists) about the path(s) a user should take through the website for an optimal experience (which includes the survey, post-survey, and administrator web pages)

## Design Artist

The following is in effect, the rubric for the Design Artist:

- [ ] **Execute the layout(s)**: in CSS: layouts based on the direction from the Information Architect (that includes the layout of all HTML forms, login systems, and administration areas)
- [ ] **Implement all formatting** including font installation, color choices and embellishments based on the direction from the Information Architect (keep in mind that the entire website - including the administration area - must look like it belongs to one, unified website)<br>Specific attention to:
  - [ ] Best practices of **page layout** 
    - [ ] Not necessarily (but probably) Z- or F-patterns, used appropriately
  - [ ] Best practices of **typography** including well-chose and paired fonts, in terms of **readability** and **legibility**
  - [ ] The **principles of page design** in terms of use of the C.R.A.P. principles
- [ ] Use of a **CSS architecture** - any

There is no requirement for the Designer to write anything in the **readme.md** file.

## Coding

The following is in effect the rubric for the Technical Coder:

- [ ] Create the **team's repository** and ensure the members of the team can access and sync with it.

- [ ] Creation of a **MySQL database** and powering of the HTML forms using **PHP** to write POST data to the database tables; and to retrieve data from the database to display in HTML tables
    - [ ] One HTML form for the **User Survey**
    - [ ] One HTML form for the **User Account Creation** process 
    - [ ] One HTML form for the the **User Login** Process
    - [ ] As many HTML forms and PHP scripts as necessary to enable the **four database functions** (described earlier) in the administration area
- [ ] Ensuring that the entire website meets **web standards** and follows **best practices**

### One weird thing

NOTE one thing about this website that will *not* be real-worldy: IT IS OKAY that anyone can create an account on this website to become an administrator so they can login and get into the private area of the website. Obviously that wouldn't make sense on a real, production website, but for this academic exercise, it's okay.

## Installation

- [ ] The website must be installed on the class web server in the folder named: **assignment13** (…which already exists); then create a folder with a name based on the team city that you're in.  

  FTP into the *assignment13* directory and then create your city-team folder

  ```
  FTP Server (a.k.a. Hostname): ftp.csc174.org
  FTP Port: 21
  FTP Username: assignment13@csc174.org
  FTP Password: [the same password]
  ```

- [ ] The **database** must be installed on the class web server using the city-team database created for your team

Note: databases for each city-team already exist.  If there are any problems using/connecting to them, ask the professor or TA for help.

## Submit the Assignment

You will *each* create your own submission in Blackboard.

- Everyone needs to create their own Blackboard submission in: **Assignment 13: User Survey Website**
- In the "Write Submission" area, submit a **link to the website** on the class web server
- Also write-in 
  - The **city-name** of your team
  - The names of **each team member** and the **role** they performed (including your own)
  - Also, submit a **link to the repository** the team used.  (Make sure the repository is "public")