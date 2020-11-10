## Project Title
Horiseon web application 
## Description
This Application allows you to increase your visibility and find the right customers for your business.
## Table of Contents

* [Features](#features)
* [Installation](#installation)
* [Known Bugs](#known-bugs)
* [Support](#support)
* [Technologies Used](#technologies-used)
* [Contribution Guidlines](#contribution-guidlines)
* [Tests](#tests)
* [License](#license)

## Features
* Search ingine optimization.
* Online reputation management.
* Social media marketing.
## Installation 
* Clone this repository.
* Open repository in your browser.
## Known Bugs
The Search Engine Optimization link is not working - known issue 
## Support
Please email me for further questions at nasozontova@gmail.com
## Technologies Used
HTML
CSS
JavaScript
## Contribution Guidlines 
Direct link to repository: https://github.com/NataliaSozontova/homeworkWeek2NataliaSozontova
## Tests
Scenarios below written to test UI of the application 

Scenario #1 User is able to navigate from the navigation links to the related articles 
    Given user navigates to Horiseon website url
    And user sees the home page
    And the header contains Search Engine Optimization, Online Reputation Management, Social Media Marketing links
    When user clicks on the Search Engine Optimization link 
    Then users navigates to Search Engine Optimization article
    And user clicks on the Online Reputation Management link
    Then user navigates to Online Reputation Management article
    And user clicks on Social Media Marketing link
    Then navigates to Social Media Marketing Link article
    And user leaves the website 

Scenario #2 User sees articles on the right section of the home page 
    Given user navigate to Horiseon website url
    And user sees the home page
    When user navigates to section on the right 
    Then user sees Lead Generation, Brand Awareness, Cost Management headers 
    And user sees icons and articles related to each header 
    And user leaves the website

Scenario #3 User sees footer on the bottom of the home page
    Given user navigate to Horiseon website url
    And user sees the home page
    When user navigates to footer of the page
    Then user sees text "Made with love (heart symbol) by Horiseon 
    And user sees "2019 Horiseon Social Solution Services, Inc." text
    And user leaves the website

## License
Copyright(c) 2020 Natalia Sozontova.