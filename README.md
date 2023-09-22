# 01 HTML, CSS, and Git: Code Refactor

## Description
This excercise was to change an existing code for a website to fulfill the User's desire to follow accessibility standards
It demonstrated the ability to edit pre-existing code to add a feature (accessibility) without changing the functionality of the code itself.
This excercise also provided an opportunity to Debug code as well, as certain aspects of the code were missing, causing the product to not look identical to what the finished product should look like. Even though this was not directly stated in the acceptance criteria that was initially provided by the user. 
Below is the criteria provided by the user.


## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Instillation

First when I was went through the code, I noticed that one of the nav buttons didn't work. So I added an ID tage to the search engine optimization div to ensure that the nav link would properly go to that part of the page when clicked. 

Next, I started on the first criteria. I changed all of the div's to semantically correct tags to improve accessibility. By changing the element names, I also had to edit part of the css in the style sheet to reflect the changes made in the HTML code.

Further improving accessibility, I added alt tags to the pictures throughout the page. This helps with visually impared people that may be using a reader to navigate the page.

To clean up the css code, I moved a section of code further up in to better reflect what parts it was pertaining to. This allows someone to find it easier when inspect the css code in the style sheet.

To fulfill the final criteria of the user, I added a title more fitting to the application.

Lastly I cleaned up the code, consolidating certain css selectors that had Identical code.

## Link 

https://markrbishop.github.io/wk1-challenge/

!(https://github.com/MarkRBishop/wk1-challenge/blob/main/wk1-challenge-ss1.png)

!(https://github.com/MarkRBishop/wk1-challenge/blob/main/wk1-challenge-ss2.png)