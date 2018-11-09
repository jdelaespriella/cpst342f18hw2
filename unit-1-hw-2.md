# Assignment 2

## Conditions:

* Follow all instructions and naming conventions for full credit.
* You may work with a classmate on this assignment (all parts or nothing).

## Objective 1 (100 pts, 125 w/ Extra Credit)

### Summary:
You will be modifying your welcome page from HW1 to include styling, a few basic common design components, and a CSS Grid.

### Tasks/Rubric
Use HTML5 to complete the following tasks:
  
* REQUIRED FOR ASSIGNMENT CREDIT: Create a public GitHub repository named _cpst342f18hw2_ -- you may wish to _fork_ your existing HW1 instead.
* REQUIRED FOR ASSIGNMENT CREDIT: Add a README to the file (README.md or README.txt) which states all team member names. Without this, I cannot grade your submission. **Be sure to note any extra credit opportunities you completed, in the readme.**
* (100 pts) index.html styling
    * (5 pts) Add Eric Meyer's CSS Reset. Add it to the correct place.  
    * (5 pts) Style your `<h1>` tag. Give it a different size, font color, weight, and a serif font-face.
    * (5 pts) Style your `<h2>` tag. Give it a different size, font color, weight, and a sans-serif font-face. It should be visibly different than `<p>` and `<h1>` tags.
    * (5 pts) Style your `<p>` tags. Apply a line-height so the lines are not so close together. Add a 30px margin to the bottom of the paragraphs so each paragraph clearly has spacing after.
    * (10 pts) Add a full-width header and full-width footer to the page. See the sample 4 column grid for an example. Make each have a different background color than the rest of the site.
    * (10 pts) Move your link(s) to the header and again to the footer. Use the `<ul>` tag for the list of links. Wrap the `<ul>` tag in a `<nav>` tag. Ensure the link(s) still work for full-credit.
    * (20 pts) Create your own 12-column grid (automatically earned if you use Bootstrap).
    * (5 pts) Make the `<h1>` tag span one row and 4 columns.
    * (5 pts) Make the `<h2>` tag span one row and 8 columns.
    * (5 pts) Make the 2 `<p>` tags span one row (one row for both, **not** one row each!) and 5 columns each. Add a 2-column spacer between the two paragraph columns.
    * (25 pts) Style the about page to use the same grid and styling. Heading tags can span as many columns as you like on about.html. 
    * (Extra Credit: 5 pts) Correctly import and use 1 or 2 Google Font(s).
    * (Extra Credit: 20 pts) Write your CSS using SCSS instead. Be sure to compile to CSS and include all files in your repository. Does not apply if you use Bootstrap since it's already in SCSS.

### Automatic 0 conditions
You will receive a zero on this objective if you...
    
* Cheat or do not cite sources where you 'liberated' code 
* use `<table>` for non-tabular data (ie: do **not** use it for layouts!)
* use `<frameset>`
* Do not use HTML5 
* Use Bootstrap version 3 or lower

### Hint
Use the existing 4-column grid (in Sakai > Resources) and expand it to 12, or use the new `grid-*` CSS properties, or use Bootstrap **4**.

#### Using the new CSS grid setup:
* Use this guide to get started: <https://css-tricks.com/snippets/css/complete-guide-grid/> 

#### Bootstrap Steps
* Download and install Bootstrap 4 from <http://getbootstrap.com/> (or skip the download, and use the CDN links to install directly to your site). 
* You **must** use Bootstrap version 4 if you use Bootstrap.
* You do **not** need to install the JavaScript components at this stage. 
* You may wish to start with this template [Bootstrap 4 Starter Template](http://getbootstrap.com/docs/4.1/examples/starter-template/), or use any of the other [Example Templates](http://getbootstrap.com/docs/4.1/examples/). 

## Objective 2 (20 pts)

At regular intervals, and at project finish, commit and push your entire website to the repository created in objective 1

### Rubric

* (20pts): Completed assignment pushed to repository. 5+ commits. Descriptive commit messages.
* (10pts): Completed assignment pushed to repository. Less than 5 commits or non-descriptive commit messages
* (0pts): Completed assignment is not pushed to repository.

## Submission Instructions

**One submission per team** - submit the URL to your github repository, like: <https://github.com/elliottpost/cpst342f18hw2> 

Good luck!