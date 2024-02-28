# Artic Case Manager

Artic Case Manager is a website designed to support Public Protection workers in local government to manage their cases.

Visit the deployed website [here](https://project-4-artic-case-manager-0cfe222fc6e4.herokuapp.com/)

## Table of Contents

1. [User Experience](#user-experience)
    * [Database](#database)
    * [Wireframes](#wireframes)
    * [User Stories & Projects](#user-stories--project)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Testing](#testing)
    * [Automated](#automated)
    * [Manual](#manual)
5. [Deployment](#deployment)
6. [Credits](#credits)

## User Experience

### Project
#### Purpose
 Develop an incident recording system to track Public Protection incidents, actions taken, and photos

#### Objectives
* Enable users to record incidents promptly
* Facilitate efficient incident investigation
* Store incident details securely
* Allow users to upload relevant photos

#### Scope
* Incident recording functionality
* Incident details
* Actions taken in response to incidents
* Photo upload feature

#### Key Deliverables
* A web-based incident recording application
* User-friendly interface for recording incidents
* Incident database for storage
* Photo upload functionality
* Application security

#### Assumptions
* Users have basic computer literacy
* Incident data will be stored securely
* Users will have access to the system via web browsers

### Database

The database diagram was written in [dbdiagram](https://dbdiagram.io/). The database used for this project is [PostgreSQL](https://www.postgresql.org/) which is a type of relational database

![Database Diagram](assets/readme-files/dbdiagram.png)

### Wireframes

### User Stories & Project Plan

See project plan [here](https://github.com/users/JoeLew709500/projects/3)

**Stage 1**
![Stage 1](assets/project-timelines/stage1.png)
**Stage 2**
![Stage 2](assets/project-timelines/stage2.png)
**Stage 3**
![Stage 3](assets/project-timelines/stage3.png)
**Stage 4**
![Stage 4](assets/project-timelines/stage4.png)
**Stage 5**
![Stage 5](assets/project-timelines/stage5.png)
**Stage 6**
![Stage 6](assets/project-timelines/stage6.png)
**Stage 7**
![Stage 7](assets/project-timelines/stage7.png)
**Stage 8**
![Stage 8](assets/project-timelines/stage8.png)
**Stage 9**
![Stage 9](assets/project-timelines/stage9.png)
**Stage 10**
![Stage 10](assets/project-timelines/stage10.png)
**Stage 11**
![Stage 11](assets/project-timelines/stage11.png)
**Stage 12**
![Stage 12](assets/project-timelines/stage12.png)
**Stage 13**
![Stage 13](assets/project-timelines/stage13.png)
**Stage 14**
![Stage 14](assets/project-timelines/stage14.png)
**Stage 15**
![Stage 15](assets/project-timelines/stage15.png)

[Back to table](#table-of-contents)

## Features
### General
* Responsive across all platforms
* Navigation Bar
![Navigation Bar](assets/readme-files/Navbar.png)
    * Contains all page links and displays current user logged in
* Footer
![Footer](assets/readme-files/footer.png)
    * Contains copyright and social media links

### Pages
#### Home Page
![Home](assets/readme-files/home.png)
    
    This page welcomes the user and describes what the website is about and displays a common picture that relates to a Public Protection Case management system

#### Incidents Page
![Incidents](assets/readme-files/incidents.png)
    
    This page shows all cases that they have created they can search the cases by incident category and received date.
    
    If the user is using a laptop/desktop they can hover over the row which will display the detail of the case before they click into that case

    From this page the user can create a new incident

#### Incident Detail Page
![Incident](assets/readme-files/incident.png)

    This page is used to create and display an incident

    The form has mandatory fields where the user can't update/create if those fields are empty

    The user can also delete a incident if they are viewing a current incident

    The user can then click on the actions button so they can where they would be able to see all of they're actions they had done in relation to the incident

#### Actions Page
![Actions](assets/readme-files/actions.png)


    This page shows all the actions done against the incident they were looking at
    
    If the user is using a laptop/desktop they can hover over the row which will display the detail of the action before they click into that case

    From this page the user can create a new action

#### Action Detail Page
![Action](assets/readme-files/action.png)

    This page is used to create and display an action

    The form has mandatory fields where the user can't update/create if those fields are empty

    The user can also delete an action if they are viewing a current action

    The user can then click on the photos button so they can where they would be able to see all of they're photos they have uploaded

#### Photos Page
![Photos](assets/readme-files/photos.png)

    This page is to upload/delete/display photos that have been linked to the action

## Technologies Used

### Languages Used
* HTML
* CSS
* JavaScript
* Python

[Back to table](#table-of-contents)

### Frameworks, Libraries and Packages
* Django
* allauth
* Crispy Form
* Bootstrap 5
* Font Awesome
* Cloudinary
* Gunicorn

[Back to table](#table-of-contents)

### Other
* ElephantSQL
* Heroku
* favicon.io

[Back to table](#table-of-contents)

## Testing

### Automated

[Back to table](#table-of-contents)

### Manual

[Back to table](#table-of-contents)

## Deployment
This project was developed using Visual Studio Code

### Deployment via Heroku
To deploy this repository via Heroku follow the below steps

1. Clone this repository
2. Sign into Heroku
    1. Select 'Create new app'
    2. Give a name to the app and select a location
3. Create a ElephantSQL postgres database (ensure its postgres 13 or higher)
4. Create a Cloudinary account
5. Set up Config Vars
    1. Go to the settings in your app
    2. scroll to Config Vars and select Reveal Config Vars
    3. Add CLOUDINARY_URL as key and then your URL provided by Cloudunary as the value
    4. Add DATABASE_URL as key and then your URL provided by ElephantSQL key as the value
    5. Add SECRET_KEY as key and then your secret key as the value
6. Deploying
    1. Go to the Deploy tab and select your cloned repository for deployment
    2. Scroll down to the bottom and deploy from the main branch

[Back to table](#table-of-contents)

## Credits
* Pop-up messages was taken from [Code Institute's](https://codeinstitute.net/) django-blog project.

[Back to table](#table-of-contents)
