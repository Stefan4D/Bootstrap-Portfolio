# Bootstrap Portfolio

## Description

Submission for Module 3 of the University of Birmingham Skills Bootcamp in Front-End Web Development &amp; UX.

For this assignment, there was no starter code and I built the skeleton HTML from scratch. This project uses the Bootstrap library for styling of the web app, which I customised using Sass as well as a custom CSS file.

The production website is deployed [here](https://stefan4d.github.io/Bootstrap-Portfolio/).

![Screenshot of deployed webpage](./images/deployed-app.png)

This has been developed to meet the following Acceptance Criteria:

| Acceptance Criteria                                                                                                                                                                      | Solution                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Navigation bar** <br /> A navigation menu at the top. <br/><br/> Include links that are applicable to your portfolio. <br/><br/>Links should navigate to the appropriate sections      | Navbar component with collapse class and custom styling for right alignment on small screens.<br/><br/>Links to sections included for About, Work, and Contact. |
| **Hero Section** <br /> A jumbotron featuring your picture, your name, and any other information you'd like to include.                                                                  | Jumbotron included with title, sub-title, and placeholder text.                                                                                                 |
| **Work Section** <br/> A section displaying your work in grid. <br /><br /> Use Bootstrap cards for each project. <br /><br /> The description should give a brief overview of the work. | Work section included.<br/><br/>Bootstrap cards used and customised.<br/><br/>Description included for each.                                                    |
| **Skills Section** <br /> List out the skills you expect to learn from the bootcamp.                                                                                                     | Skills section included listing HTML, CSS, React etc.                                                                                                           |
| **About Me Section** <br /> An About Me section in the same row as the skills section.                                                                                                   | About me section included with placeholder text in same row as skills.                                                                                          |
| Footer Section <br/><br/>All hyperlinks should have a hover effect<br/><br/>All buttons should display a box shadow upon hover                                                           | Footer section included<br/><br/>Hyperlinks have a hover effect <br/><br/>Links when hovered use a fill effect to mimic shadow.                                 |
| Solution should minimise the use of media queries                                                                                                                                        | No media queries used outside of standard Bootstrap breakpoints.                                                                                                |

## Learning Outcome

- I have learned how to make use of the Bootstrap library for rapidly prototyping and iterating on an application design.

- I found the Bootstrap Grid system to much simpler to use than the raw CSS required to build out a grid or a set of flexbox containers and items.

- I have also learned how to customise Bootstrap cards to achieve my desired hover effect, separating two parts of the card to achieve the end result.

- I have learned how to customise Bootstrap using Sass, contained within the file [here](./sass/main.scss).

## Resources Used

In completing this challenge exercise, I made use of the following resources:

- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [Net Ninja: Bootstrap 5 Tutorial](https://youtube.com/playlist?list=PL4cUxeGkcC9joIM91nLzd_qaH_AimmdAR)
- [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass)
- [Huemint Bootstrap Theme Generator](https://huemint.com/bootstrap-plus/)

## Mark Scheme Compliance

### Technical Acceptance Criteria

| Item                                            | Evidence                                                                   |
| ----------------------------------------------- | -------------------------------------------------------------------------- |
| Satisfies all of the above acceptance criteria. | The built application satisfies the acceptance criteria, as set out above. |

### Deployment

| Item                                              | Evidence                                                                      |
| ------------------------------------------------- | ----------------------------------------------------------------------------- |
| Application deployed at live URL.                 | Live application deployed at: https://stefan4d.github.io/Bootstrap-Portfolio/ |
| Application loads with no errors.                 | No visual defects <br /> No console errors                                    |
| Application GitHub URL submitted.                 | URL submitted                                                                 |
| GitHub repository that contains application code. | This repository contains all code.                                            |

### Application Quality

| Item                                                                 | Evidence                                                                                                       |
| -------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Application resembles the functionality of their previous portfolio. | Application resembles my previous portfolio although I have adopted a different visual style for this project. |

### Repository Quality

| Item                                                                                                    | Evidence                                                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Repository has a unique name.                                                                           | Unique name used                                                                                                                                                                                                                          |
| Repository follows best practices for file structure and naming conventions.                            | Standard HTML and CSS file names used and assets are stored in appropriate directories (./css/ and ./images/)                                                                                                                             |
| Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.  | All multi-word CSS IDs and classes use lowercase and hyphens. <br /> Indentation within code follows best practice and document flow <br /> Comments have been included within the files to describe behaviour and/or intent of the code. |
| Repository contains multiple descriptive commit messages.                                               | Multiple commits included demonstrating incremental build of final submission. Each has a clear description of changes made.                                                                                                              |
| Repository contains quality README file with description, screenshot, and link to deployed application. | This README document.                                                                                                                                                                                                                     |

## License

Released under the MIT license. Full details in [LICENSE](./LICENSE).
