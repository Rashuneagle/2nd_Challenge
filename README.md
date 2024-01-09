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
```

## Decompositon

//HTML
// Create title of website using Header element
// Create a section to various links about the developer in the next row using the nav element
// Create the next row showing the developers name, a recent photo or avatar(Include the contact info in the footer)
// Create section for each web application complete using main element and include an image of the application with a title
// Make links to the different sections go the that particular section
// Make it so when the image is clicked on it takes you to the deployed application
// Make sure the view on the site is responsive and can work on various screen types using viewport meta tag, set images max width to 100%, use media queries etc...

//CSS
// Make sure the image is in the web application section is larger than others
// Make sure the page is responsive using viewport meta tag, set images max width to 100%, use media queries etc... 

## Pattern Recognition

// Create row for title
// Create Row for links
// Create sections for each web application
// Create Footer for contact information
// Create columns wihtin each row
// Sytle each row
// Style each column

## Abstraction 
// User and Portfolio Interaction:
// Objective: View a potential employee's deployed portfolio.
// Essential Characteristics:
// Interaction to view portfolio.
// Display of web applications.

// Navigation Interaction:
// Objective: Navigate through different sections.
// Essential Characteristics:
// Clickable navigation links.
// Scroll to corresponding sections.
// Clear separation of sections (developer information, web application, contact).

// Work Sample Interaction:
// Objective: Interact with Web application.
// Essential Characteristics:
// Clickable images of applications.
// Direct access to deployed applications.

// Responsive Layout:
// Objective: Ensure a responsive layout.
// Essential Characteristics:
// Adaptable to various screen sizes.
// Consistent user experience across devices.

## Testing and Debugging

1. Add necessary meta tags for responsiveness

2. Display Header with "Michael Scott's Portfolio"

3. Create different section for Portfolio: about me, Web Applications, and contact.
    a. Create links to different sections

4. In "about me" section: 
    a. create columns for relevant information about me

5. In the "Web Applications" section
    a. Display heading "Web Application"
    b. For each Web Application: 
        i. Display a placeholder image link to the deployed application.

6. In the "Contact Information" section:
   a. Display a placeholder for contact information.

7. Implement the basic structure and styles:
   a. Define general styling for fonts, colors, and spacing.
   b. Ensure readability and a clean visual appearance.

8. Test the initial structure on a desktop browser:
   a. Verify that the core elements are present and readable.
   b. Confirm that the basic structure aligns with the design.

9. Iterate on the design and styles:
   a. Make adjustments based on feedback and design preferences.
   b. Enhance visual appeal and layout.
s
10. Introduce responsiveness:
    a. Use media queries to address responsiveness concerns.
    b. Adjust the layout, fonts, and spacing for different screen sizes.
    c. Ensure a consistent user experience on desktop, tablet, and mobile devices.
    d. Ensure links go to correct destinations

11. Test responsiveness:
    a. Test the portfolio on various devices and screen sizes.
    b. Verify that the content adjusts appropriately to different viewports.

12. Debugging and adjustments:
    a. Identify and resolve any responsiveness issues.
    b. Use browser developer tools to inspect and debug CSS styles.

14. Finalize the web page for deployment.