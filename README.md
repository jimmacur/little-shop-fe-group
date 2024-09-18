# Little Shop | Group Project | Frontend Starter Repo

## 🌀 Abstract
This Little Shop FE Boilerplate is built to consume and display the data from the BE Rails API built in the Mod 2 Group Project. In this group project our team worked on building an E-Commerce application using service-oriented architecture, where the back and front ends are separate and communicate via APIs. Built with javascript, html and CSS, this front end component brings functionality to the project.

The changes made to this boilerplate include the following features and refactors:

CSS Styling: 
- Hover effects, such as the pointer transforming and pulsing over all buttons
- Rounding of corners
- Color change upon hovering to highligh key components and indicate key functional components of the site 
- A soothing teal color scheme with a pop of peach upon hover to add interest
- Flexbox was applied to items elements in order to create a more dynamic view rather than a linear vertical list of items

HTML: 
- The layout was largely kept as-is but minor tweaks were make to classes in order to apply styling elements appropriately.

Javascript:
- For loops in the filterByMerchant and findMerchant functions were refactored into array prototype methods. These refactors were good practice for the team as we continue to build our javascript skills. In terms of functionality, a 'for loop' could have an edge in performance because it avoids the overhead of callbacks. Nevertheless, in this context, the difference is performance is neglegable and the array prototype methods made our code slightly more readable and useful for maintainability. 
- In a 'choose your own adventure' componenet of the project, our team decided to incorporate some client-side validation to by disallowing an empty merchant name field to be submitted. Refactors to the submitMerchant function accomplish this goal.


## ⚙️ Installation Instructions
1. Fork repo
2. Clone forked repo and rename it `git clone <repo> <new name>` 
3. `cd` into cloned repo
4. Run `npm install`
5. Run `npm run dev` to start developing.
6. You'll see in the terminal that the project has opened at "http://localhost:5173/"
7. This front end application is built to consume data from an associated Rails API. This API must be open and running on localhost:3000.

## 👀 Preview of App
<!-- ![Little Shop Home page](littleShopHome.png) -->
<img src="LittleShopHome.png" alt="Little Shop Home Page" width="700" />

## 📝 Context
In only one weeks time, our group of five Turing School of Software and Design students built a back end API and added functionality to this data by linking it to this front end boilerplate repo featured here.  

## 👥 Contributors
Candice Cirbo https://github.com/CCirbo</br>
Lito Croy https://github.com/litobot</br>
Jim Macur https://github.com/jimmacur</br>
Melchor De La Rosa https://github.com/MDelarosa1993</br>
Terra Manning https://github.com/TDManning

## 🌱 Overall Learning Goals
* Practice refactoring and writing javascript
* Work in CSS to make our app more functional and visually appealing
* Use ActiveRecord and SQL to write queries that deal with one-to-many database relationships
* Expose API endpoints to CRUD database resources
* Validate models and handle sad paths for invalid data input
* Test both happy and sad path functionality based on JSON contracts
* Use MVC to organize code effectively, limiting data logic in controllers and serializers
* Time Management
* Breaking down large projects into small pieces
* Breaking down a problem into small steps
* Practice individual research (reading documentation, articles, videos, mentors)

## 🏆 Wins + ⛰️ Challenges:
Wins: 
* Incorporating flexbox and button animations both make the application much more user friendly.
* Having fun making changes and sharing those with the other group members

Challenges:
* The pulsing effect was only viewable on one team members computer after everyone pulled down the changes. As a result, we needed to add some additional code to other group members CSS files. What was originally a frustation turned into a win. 
* Two team members added styling to the same elements, so once merged, some changes were not being applied. We had to sort through the changes as a team and decide which ones we wanted to implement in the final product. 
