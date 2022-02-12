# HTML CSS Git Challenge: Code Refactor

## Purpose 
This week's challenge brought an opportunity to refactor, or reorganize, the way a stylesheet affects the functions and apparence of a website. Simplifying navigation for users makes a world of a difference!

## Built With
The main players in this assignment were CSS and of course, HTML.

## Installation
Simple changes like adding the name of the site, Horiseon, to the <title> element can help viewers easily see the specific page because the tab is labeled. I learned the importance of making sure the div tags and classes in the HTML line up with the names of classes in the CSS, which leads to effective functioning when a user clicks on a certain element. 

Navigation was made possible simply by adding the <nav> elements inside of the header of the body. Not only does this section organize the subheaders in a presentable and easy-to-use format, but effectively it points the reader to the detailed section(s) corresponding to their headers.

For example, the <header class="header"> section allows all the elements in the CSS labeled ".header {" to apply to everything related to the header in the HTML. Essentially it enables the site user to click on the header tabs and they drop down to the section lower on the page that describe more details about the specific section.

## Usage
I learned that just labeling parts of the stylesheet incorrectly will fail to present a working website. At first, I labeled my list elements with '.header div {','.header div ul li {, and so on. Just changing those 'div's to 'nav' elements spaced out the headers across the top evenly instead of bullet-pointing under the web title.

Incorrect Format of the CSS and browser view:
  
[incorrect CSS](assets/images/CSS-incorrect.png)
  
[incorrect web view](assets/images/website-incorrect.png)

Corrected Format of the CSS and browser view: 

[correct CSS](assets/images/CSS-correct.png)

[correct web view](assets/images/website-correct.png)


It turns out that not only the function, but the layout of words on a web page determines its quality, and can either attract or repel a visitor. 
