# Unit 10: OOP Team Profile Generator
## Description

The focus of this unit was Object Oriented Programming and unit testing. The objective for this project was to build a Node.js command-line application that takes in information about employees on a software engineering team, and with that information generates an HTML webpage that displays the user input data. One requirement of the application was to make use of Constructors and Classes to create the employee objects. Among these were the Employee, Manager, Engineer, and Intern classes. In addition to building the application, this project also required the use of Jest and Inquirer to conduct unit tests of every part of the code to ensure that it would pass each test. A demonstration of the node application and the testing is shown below.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Screenshot](#screenshot)
- [Walkthrough Video](#walkthrough-video)
- [Credits](#credits)
- [License](#license)

# User Story

```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```

## Screenshot
This is a screenshot of the generated HTML webpage.

![Team Generator HTML Webpage Screenshot](./assets/Team-Profile-Generator_Screenshot.png)

## Walkthrough Video
![Team Generator Walkthrough Video](./assets/10_OOP-Team-Profile-Generator-Demo_Final.gif)
## Credits
- Trilogy Education Services, LLC: https://www.trilogyed.com/ 
- Bootstrap: https://getbootstrap.com/
- NodeJS: https://nodejs.org/en/
- Jest: https://www.npmjs.com/package/jest
- Inquirer: https://www.npmjs.com/package/inquirer

## License

This project was created by James L. Jenks as part of the curriculum for the MSU Coding Boot Camp and Trilogy Education Services.

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
    