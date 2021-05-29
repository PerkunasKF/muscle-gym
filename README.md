# Muscle Gym

![Muscle gym hero image](assets/images/hero-image_pexels-estudio-polaroid-3112004.jpg)

[View the live project here](https://perkunaskf.github.io/muscle-gym/)

##Table of contents
1. [Introduction](#Introduction)
2. [UX](#UX)
    1. [Ideal User Demographic](#Ideal-User-Demographic)
    2. [User Stories](#User-Stories)
    3. [Development Planes](#Development-Planes)
    4. [Design](#Design)
3. [Features](#Features)
    1. [Design Features](#Design-Features) 
    2. [Existing Features](#Existing-Features)
    3. [Features to Implement in the future](#Features-to-Implement-in-the-future)
4. [Issues and Bugs](#Issues-and-Bugs)
5. [Technologies Used](#Technologies-Used)
     1. [Main Languages Used](#Main-Languages-Used)
     2. [Additional Languages Used](#Additional-Languages-Used)
     3. [Frameworks, Libraries & Programs Used](#Frameworks,-Libraries-&-Programs-Used)
6. [Testing](#Testing)
     1. [Testing.md](TESTING.md)
7. [Deployment](#Deployment)
     1. [Deploying on GitHub Pages](#Deploying-on-GitHub-Pages)
     2. [Forking the Repository](#Forking-the-Repository)
     3. [Creating a Clone](#Creating-a-Clone)
8. [Credits](#Credits)
     1. [Content](#Content)
     2. [Media](#Media)
     3. [Code](#Code)
9. [Acknowledgements](#Acknowledgements)
***

## Introduction

This website was designed for a fictional gym, "Muscle Gym". The purpose of this website was to establish an online presents for new, current clients to find out relevant information about the gym ant it's offering services.

This is the first Milestone Project from necessary for the project to complete the Full Stack Web Development Program at The Code Institute.

The main requirement was to make a static and a responsive website with minimum three pages using primarily **HTML** and **CSS3**.

[Back to top ⇧](#Muscle-Gym)

## UX

### Ideal User Demographic
#### The ideal user of this website is:
- New/potential clients
- Current clients

### User Stories
#### New/Potential clients:
1. As a new client, I want to easily navigate through the website to find the relevant content, effortlessly.
2. As a new client, I want to learn more about the gym in order to know if it can supply me with desired services.
3. As a new client, I want to easily navigate to the gym's social links in order to keep up with the latest news and events.
4. As a new client, I want to be able to see gym's photos so I could evaluate equipment used.

#### Current Clients Goals:
1. As a current client, I want to easily find out about upcoming events so I can book a place.
2. As a current client, I want to find out about new services that the gym provides.
3. As a current client, I want to easily log in to my membership account to manage my membership.

### Development Planes

In order to create a comprehensive and informative website, the developer gathered information from social forums to add required functionality to the site and how would it answer user stories, as described above.

#### Strategy

Broken into three categories.
The website will focus on the following target audience:
- **Roles:**
     - Current clients of Muscle Gym
     - New clients of Muscle Gym

- **Demographic:**
     - 16 and plus year olds
     - People with rigid time schedules

The website needs to enable the **user** to:
- Retrieve desired information:
     - Gym opening and closing overs
     - Membership plans and prices
     - Upcoming events
     - Contact information
     - Get information about possible services

The website needs to enable the **Gym** to:
- Develop an online presence 
- Provide an easily navigable website for users to find relevant information

#### Scope
A scope was defined in order to clearly identify what needed to be done in order to align features with the strategy previously defined.
- **Content Requirements**
     - The user will be looking for:
          - Gym membership plans and price
          - News about the gym and events
          - Possible gym services
          - Contact details
          - Social Links
- **Functionality Requirements**
     - The user will be able to:
          - Easily navigate through the site in order to find the information they want
          - Contact Gym staff for any raised question
          - Get the latest news about the gym's events and new services

#### Structure
The information architecture was organized in a **hierarchial tree structure** in order to ensure that users could navigate through the site with ease and efficiency.

![Site Map](assets/images/page-layot-plan.png)

#### Skeleton 
Wireframe mockups were created in a [Figma Workspace](https://www.figma.com/file/Wd7fHpgJvJui9r4ixh1Xaz/Muscle-Gym?node-id=0%3A1):

Home Page:
(prideti paveiksla)

Pricing Page:
(prideti paveiksla)

Community Page:
(prideti paveiksla)

Conntact Page:
(prideti paveiksla)

### Design

#### Colour Scheme
The main colors used are a mixture of black, orange, grey and white.

#### Typography
Font [Roboto](https://fonts.google.com/specimen/Roboto "Link to Roboto Google font") is used, throughout the website with Sans Serif as the fallback font.

#### Imagery
Images were provided from [Pexels](https://www.pexels.com/) All credits are given to respective image authors credited before the image in the code.

Logo images were created on [Free logo design](https://www.freelogodesign.org/).

[Back to top ⇧](#Muscle-Gym)

## Features

### Design Features
Each page of the website features a consistent responsive navigational system:
- The **Navigation bar** is fixed to the top of the page so the user can always use the navigation links.
- The **Logo** in the top left corner on the click will redirect the user to the home page.
- All navigation links (Home, pricing, community and contacts) disappear on smaller screen sizes and a **toggler** icon will appear with a drop down menu for all navigation links and a **Log in* button.
- The footer contains a **Logo** image witch after clicking will redirect the user to the home page, **social media icons** will redirect user to the respective social media pages.
- The footer contains **Contacts** button, witch after clicking drops down a menu with navigation to the front desk and trainer contact.
- The footer contains **subscribe for newsleter** forum, after uses submits their email they will be notified about news and events at the gym.

<dl>
    <dt><a href="index.html" target="_blank" alt="Muscle Gym Home Page">Home Page</a></dt>
    <dd>
        <ul>
            <li>
                <strong>Hero Image</strong> - Occupying 100% of the page width, on the right side there is cover text. On smaller screens the image changes from the desktop image (Man with a barbell) to a dumbbell rack. The images were chosen because they give a neutral feel to the gym so to appeal to a wider rage of the people.
            </li>
            <li>
                <strong>Feuter section</strong> - Occupies 95% of the page width. The section is divided into title container and feauter containers. The title container is styled differently to separate from the feature and feature containers have a brief description of the gym's services and features. On smaller screens this feature containers is fitted into a carousel so not to occupy too much space.
            </li>
            <li>
                <strong>Gallary section</strong> - The section is placed to show gyms events, looks and equipment so to attract attention.
            </li>
        </ul>
    </dd>
</dl>

<dl>
    <dt><a href="pricing.html" target="_blank" alt="Muscle Gym Pricing Page">Pricing Page</a></dt>
    <dd>
        <ul>
            <li>
                <strong>Membership plans</strong> - The section is divided to three separate cards witch have their own images. Under every card there is a list of the features of the membership plan and the price. On smaller screens the cards become staked.
            </li>
            <li>
                <strong>Group training</strong> - Contains of title container and group container. Title container is stylistically different to separate from the group containers. Every group container has a name of the group training program and a background image to represent the name of the group training program. On smaller screens containers are fitted into a carousel so not to occupy too much space on the screen.
            </li>
            <li>
                <strong>Trainers</strong> - Section consists of the navigation bar and a card. The navigation bar consists of the trainer name and on focus the background and font color changes to indicate on which car the user is located. The card changes depending on the witch navigation link were chosen. Card consist of the trainers profile picture, description and footer with the trainer's contact information. The profile picture is on the left, description on the right and the footer on the bottom of the description. On smaller screen card component become staked, profile picture on top, description in the middle and footer at the bottom.
            </li>
        </ul>
    </dd>
</dl>

<dl>
    <dt><a href="community.html" target="_blank" alt="Muscle Gym Community Page">Community Page</a></dt>
    <dd>
        <ul>
            <li>
                <strong>Page division</strong> - Section is divaded in to navigation bar and the contant container. The navigation bar has **News** and **Gallery** links. This links change backgraound color and forn color on focus so user can indedify on witch section of the content tehy are.
            </li>
            <li>
                <strong>News</strong> - The container is made in the overflow container so don't feel the entire page with news. News are divided with cards. Cards are composed of two pats image and description. The images are located on the left and description on the right. On smaller screens cards become State: image moves to the top and description goes to the bottoms. All events and news relating only with the gym are marked with gym logo and anything that are related outside the gym or
            <li>
                <strong>Gallary</strong> - All images are displayed in their original aspect ration. And fitted in four columns. On the small screen sizes, images are stacked.
            </li>
        </ul>
    </dd>
</dl>

<dl>
    <dt><a href="contacts.html" target="_blank" alt="Muscle Gym Contacts Page">Contacts Page</a></dt>
    <dd>
        <ul>
            <li>
                <strong>Contact information</strong> - This section has gym's address, phone number and email. The title is separated with a bottom border and font color is white so to define it from the background image. On smaller screen content becomes staked.
            </li>
            <li>
                <strong>Google map location</strong> - Add a responsive google map location container. The location is fiction and not real for the gym. On smaller screen content becomes staked.
            </li>
            <li>
                <strong>Question form</strong> - The form consists of title, text submission container, email submission container and a submission button. Containers are lined with orange border and background is transparent on focus the background becomes black and font color white so to clearly separate the two. On hover the button changes background color and font color. On smaller screen content becomes staked.
            </li>
        </ul>
    </dd>
</dl>

### Existing Features
