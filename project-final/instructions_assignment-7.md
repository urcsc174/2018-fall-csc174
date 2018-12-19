# CSC 174  Optional Final Assignment 7: Information Architect, Design Artist, and Technical Coder

*Due: Friday, December 21 2018 (last day of exam week)*

This is an **optional assignment**, only required if you need to do, or re-do all three team roles:

- **Information Architect**
- **Design Artist**
- **Technical Coder**

For this assignment you need to develop an Information Architecture, create the presentation layer (styles), and then the behavior layer which includes use of a database.

## Step 1: Topic

The professor will assign a domain (a topic) to you, and give you specific instructions regarding the primary and secondary goals of the website.

- [ ] Send a DM in Slack to the professor.  Say that you want to do *"Optional Final Assignment 7."*

The professor will reply with a domain that is unique to everyone else who is doing an optional final assignment.  

- [ ] You are required to use the domain the professor provides to build your architecture.  You may not add to it or embellish it.  Only do what the professor instructs you to do.

##  Step 2: Gather Content

Note: as you gather content, keep in mind you may have to edit it to meet the requirements below.  It's okay if you take content from Wikipedia and manipulate it within reason.  (And as always, remember to cite your sources in a logical place in the content.)

- [ ] Within the domain assigned by the professor, you choose the **ontology** (the limits of the domain) and compile content: text and images only
    - At least four images (JPGs, PNGs, or GIFs only)
    - Text: at least 900 words

*Think ahead as you gather content.  You will need to "chunk" the content as described below.  Also, the images must relate to the content in some way.*

- [ ] Create a document outline (not necessarily in HTML yet) with lots of headings to divide the content into sections.
    - There must be a **choreography** (logical order) to the way you arrange the content.  
    - There must be **two major sections**, i.e. sub-topics, within the domain.
    - Each of the two major sections must have **four sub-divisions** (smaller sections)
    - Each sub-division must have **multiple headings** that logically divide it into smaller "chunks" of content using an clear and obvious **taxonomy** (consistent structure and language).
- [ ] Make sure you have short, captions for the images that relate to a specific area of the textual content in some way.

### Architecture of Behaviors

- [ ] Add a **contact form** into the architecture
    - Remember: the content (fields) of the the form, as well as the location must makes sense in terms of the ontology, taxonomy, and choreography.
    - Remember to include in the choreography, what happens after the user clicks the submit button.
    - Suggestion: just don't dump the contact form in front of the user.  Be sure to add content to entice the user to fill it out - give them a reason.
- [ ] Add a separate web page that provides access to the database where the contact form data is stored.  That page must provide the **four database functions**:
    - View
    - Add
    - Edit
    - Delete
- [ ] In an area of the website that makes logical sense, add a login/account creation process.  When a user is logged-in, they will have access to the separate web page with the four database functions.
    - When a user is not logged-in, there must be no way to access the separate webpage with the database functions

## Step 3: Structure the Content

You may have done this at the same time you did Step 2.

- [ ] Create two HTML documents for the primary content of the website using the HTML5 document template.  Make more HTML documents as needed for the behaviors - however you see fit.
    - Note: there are many ways to architect the contact form, the user login, and the admin page(s). It's up to you.
- [ ] Add your textual content from Step 2 and apply the appropriate HTML5 tags, ensuring all content and document structure is clean and semantically tagged.
- [ ] Write the appropriate HTML to insert your images and their captions into positions that make sense from a choreography standpoint.

## Step 4: Create the Presentation Layer

Note: you **do not** have to create a readme.md file to describe your own intended layout and mood decisions.  In this case, you'll simply do what the the IA would typically write in a readme file.

- [ ] You need to create a design (layout and embellishments) that supports the information architecture, i.e. you cannot make random choices.  You need to demonstrate your **use of styles in support of an information architecture**.

    - [ ] The layout needs to promote **the intended choreography**

    - [ ] The typography, color pallets and general embellishments must **support the intended "mood"** of the website

- [ ] The design must demonstrate your understanding of:

  - **Z- and F-Patterns** (layout) ...you need to one or both somewhere in the website
  - **C.R.A.P. Principles** (styling) ...you need to demonstrate at least three of the four

  Note: use of a **CSS Framework** is *optional* (not graded)

- [ ] Install **two well-paired fonts** and demonstrate your understanding of: Typography, in terms of **readability** and **legibility**

- [ ] Arrange your custom CSS code using any **CSS Architecture** (a standard architecture or your own variation)


  - Note: if you use a CSS Framework, you still need to demonstrate your understanding of CSS Architecture

- [ ] Style the other content (contact form, user login, admin page(s)) in a logical way that makes sure those pages look like they belong to the same website (architecture).


## Step 5: Install the Behavior Layer

Note: you **do not** have to create a readme.md file to describe behaviors.  In this case, you'll simply *do* what the the IA would typically write in a readme file.

- [ ] Using your localhost, create a **MySQL database** for powering the HTML forms using **PHP**
  - One HTML form for the **Contact Form**
  - One HTML form for the **User Account Creation** process 
  - One HTML form for the the **User Login** Process
  - As many HTML forms and PHP scripts as necessary to enable the **four database functions** (described earlier) in the administration area
- [ ] Ensuring that the entire website meets **web standards** and follows **best practices**

## Step 6: Turn it in

Do **not** upload your files to the class webserver or share your files in any way.  

- Export your MySQL database on your localhost to a file named **export.sql**

- [ ] ZIP (compress) all your files (including the .sql file) into a single ZIP file
- [ ] Upload your ZIP'd file to the assignment in Blackboard titled: **Final Assignment 7** on or before the due date.