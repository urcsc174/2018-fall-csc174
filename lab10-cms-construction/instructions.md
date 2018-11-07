# Lab 10: CMS Construction

*Due: Wednesday, November 14, 2018 (one week)* 

For this assignment, you will work as a team to build a working content management system using WordPress, and install it on the class production web server.

## Coder Responsibilities

The coder is responsible for doing the setup activities *within the first two or three days* of this assignment so the other team members have time to do their work.

_If the Information Architect and/or Designer are concerned that the Coder is not doing their job fast enough, contact the professor immediately if for no other reason, just to let the professor know that there are concerns.  The professor will monitor the situation and adjust grades accordingly ...but only if he's alerted early in the process!_

The coder is responsible for doing the following:

- [ ] Stand-up a database on the class web server (name the database after your city-team)
- [ ] Install WordPress on your localhost (using the remote database - not local)
- [ ] Create user accounts in WordPress for the other members of the team
- [ ] Create a repository in Github and push the local WordPress website there
- [ ] Add the team members to the repository as collaborators

Note: the Coder is responsible for making sure the team members are able to sync the WordPress website from the repo and get it running on their localhost.  (Any problems, ask the professor for help.)

And then, later...

- [ ] Install a plugin as chosen by the Information Architect; install a theme as chosen by the Designer
- [ ] Ensure the quality of the finished website in terms of industry standards and best practices
  - As always: file and folder naming conventions; appropriate file sizes (especially images); validation within reason, and general execution and operation of the website
  - HOWEVER (also as always): the Coder is not responsible for fixing errors/problems caused by the framework (WordPress), its plugins and/or themes.

Also, since this website will *not* be used as a blog, the Coder is responsible for turning off *all* comments and comment related functions in the system.  

## Information Architect Responsibilities

The topic of the website can literally be anything.  The content can come from anywhere but be sure to cite the sources.

For this assignment, we will **forego the requirement for a readme** file.  But still...

- [ ] There should be a obvious **ontology** within your chosen domain
- [ ] The **taxonomy** should be clear and consistent
- [ ] The **choreography** should make sense

Note: one of the typical IA mistakes when using a CMS is to let the system and theme make choreography choices for you.  Be aware of what shows-up where, and how the navigation works.  (You'll be graded on it.)  Any questions, ask the professor to review your work before you submit it for grading.

Also note, you have the concept of "Pages" and "Posts" built-in to the system.  Feel free to use or *not* use any features you want.

- [ ] The quantity of content is not defined but there needs to be **"enough" content** to demonstrate that you know something about ontology, taxonomy, and choreography.

The Information Architect must also:

- [ ] Select a **plugin** for the CMS - preferably one that add value to the *front-end* of the website, like an image slideshow or gallery - those are typical/simple choices.  
  - Chose the plugin - make sure it makes sense, i.e. add value to the content you're presenting
  - Have the Coder install the plugin (or install it yourself - it doesn't matter - but maybe the coder can help)
  - Learn how to use the plugin you selected/installed.  Here too, the Coder should help.  BTW - if it turns out the plugin is too complicated (or buggy) rip it out and try another one.
- [ ] If the plugin requires content to work (typical, e.g. photos for a slideshow), the Information Architect must **get and prepare the content**.  Make sure the content makes sense, i.e. adds value, to the rest of the website.

## Designer Responsibilities

Although the design of the website will be driven by the theme, the designer is still bound by the design principles covered in CSC 174.  

The Designer needs to: 

- [ ] Select a **theme** for the CMS - preferably one that demonstrates a classic page pattern and one that gives them customization options.
  -  Chose the theme - make sure it makes sense, i.e. adds value to the content as provided from the Information Architect
  - Have the Coder install the theme (or install it yourself - it doesn't matter - but maybe the coder can help)
  - Learn how to use the theme and customize it.  Apply the principles of page design and position the content into as much of the Z- or F-patterns as possible.  (You'll be graded on it!)
    - Note: you probably won't have clearly defined Z- or F-patterns to work with, to the degree you *can* position content correctly, you should!  (Remember: the *terminal* area is the most important area; if something is there, it better be important.)

Note: the Designer is responsible for the entire presentation of the content on every page of the website - not the selection of the content nor the technical operation of it.

## Installation

More coder responsibilities:

- [ ] The website must be installed on the class web server; create a folder named after your city-team and install your website there
- [ ] IMPORTANT: when the website is moved to the production web server, the "host" needs to be changed from `66.147.242.186` to `localhost`
  - ...even though that doesn't make sense!  The professor will explain why.

### Web Server Credentials

Each team will use the same FTP account. Be careful *not* to disturb other teams' files.

```
FTP Server (a.k.a. Hostname): ftp.csc174.org
FTP Port: 21
FTP Username: assignment10@csc174.org
FTP Password: [the same password]
```

*Notice that the username is different from last time:* assignment**10**@csc174.org

## Submit the Assignment

Note: even though you worked as a team, everyone will be graded as an individual based on the work you did. To get credit for your work:

- [ ] Everyone on the team must make a submission in Blackboard, in the assignment:<br> **Assignment 10: CMS Construction**

- [ ] In the submission you must provide the following information:

  - **Your city-team name**
  - A list of **everyone's name** in your team (including your own) **and their role** (IA, designer, or coder)
  - A link to the **website**
  - A link to the **repository**

  *NOTE: in Blackboard, do not write the required information in the comments section.  Use the "Write Submission" area*