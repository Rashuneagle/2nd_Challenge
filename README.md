# 2nd_Challenge
This is the second challenge for the Washington Univeristy Bootcamp

Computational thinking

## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```


## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```s

## Decompositon

//HTML
// Create title of website using Header element
// Create a section to various links about the developer in the next row using the nav element
// Create the next row showing the developers name, a recent photo or avatar(Include the contact info in the footer)
// Create section for each web application complete using main element and include an image of the application with a title
// Make links to the different sections go the that particular section
// Make sure the image is in the web application settings is larger than others
// Make it so when the image is clicked on it takes you to the deployed application
// Make sure the view on the site is responsive and can work on various screen types using viewport meta tag, set images max width to 100%, use media queries etc...

//CSS

