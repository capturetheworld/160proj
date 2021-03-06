# Pastime
**Project Description:**
Our goal is to develop a web app for citizens of a “smart city” to find recreational activities for them, their friends, and their families. It will have the ability to filter by age- category (preschool, 10-12, adults, seniors, etc.), type (coding, sports, design, etc.), and proximity (5 miles, 10 miles, 15 miles, etc.). Cost, dates, and times are additional filters that can be added. The web app will allow users to buy points for the activity they are interested in. These points are stored in an electronic card. 

These cards are used to “pay” for a set activity price. The set activity price is specified by the activity organizer (known as the service provider). Admins have accounts and complete control over all activities, but activity providers can only edit their created activity.


## Sprint Deliverables 

**Sprint 1 RD Feb 28**
-  [x]  Markdown Document (Receivables Analysis Document) which includes Spring beginnings (what), roles, responsibilities 

**Sprint 1 March 7**
-  [x] Research HTML/CSS
-  [x] Implement HTML/CSS for homepage
- [x] Create AWS server and a basic HTML web page in NodeJS and HTML/CSS, upload to git

**Spring 2 RD March 14**
### Front End:
- [x] Bootstrap header
- [x] NavBar
- [x] More CSS/HTML changes
- [x] Add cards using bootstrap
- [x] Research Activities name and add ratings
- [x] User profile page

### Back End:
- [ ] Look at the server configurations
- [x] Connect back end to front end
- [ ] Treknicalte.ch
- [ ] 2 docker containers (mongoDB Atlas & Phabricator)
- [ ] Figure out compilation issue on AWS
- [ ] Install and configure NGINX
- [x] Reinstall mongoDB
- [x] Create collections (User Info) for mongoDB

**Sprint 2 March 21st**
### Front End:
- [x] Bootstrap header
- [x] NavBar
- [x] More CSS/HTML changes
- [x] Add cards using bootstrap
- [x] Research Activities name and add ratings
- [x] User profile page

### Back End:
- [x] Connect back end to front end
- [x] Treknicalte.ch
- [x] 2 docker containers (mongoDB Atlas & Phabricator)
- [x] Figure out compilation issue on AWS
- [ ] Install and configure NGINX
- [x] Reinstall mongoDB
- [x] Create collections (User Info) for mongoDB
- [x] Connect mongoDB Atlas to node.js
- [x] User Authentication
- [x] User Signup
- [x] Deploying Heroku 
- [x] Hosting Mongo on AWS

**Sprint 3 April 18th**
* TBD

**Sprint 4 May 2nd**
* TBD

**Presentation May 4th**
* TBD

**Final report + Github May 14th**

## Feature Description
### Home Page (What All Users See)
- [x] Introduction, About Us
- [x] Search bar
- [x] Slideshow of Cards, Pictures and Descriptions to grab users' attention
- [x] Sign up/Login prompt

### Sign Up/Login webpage
- [x] Enter username and password; username must be email
- [ ] Different selections for Service Provider, Citizen, Admin
- [ ] Different fields for different roles

### My Account/Dashboard
- [x] First name, last name, email address, password
- [ ] Wallet, payment methods, add points
- [ ] Preferences
- [ ] History of transactions
- [x] Sign out
- [x] Admin Roles
  - [ ] User management
  - [ ] Assignment and revocation of roles and rights
  - [ ] User lock
  - [ ] Reset user password
- [x] Gallery of activities
  - [x] Description of each activity
  - [x] Price of the activity
  - [ ] Search bar
- [ ] The following four user roles will be supported in our system
  - [ ] Anonymous user
  - [x] Parent/Citizen
  - [ ] Service provider
  - [x] Admin
- [x] Connect mongoDB Atlas to node.js
- [x] User Authentication
- [x] User Signup


## Personas & Scenarios
Name | Persona | Scenario | User Stories
------ | -------------------------- | ------------------------- | --------------------------------
Peter Parker (Anonymous citizen) | 21-year-old college student who is looking for some activities to do on the weekend. He likes adventurous activities and looks forward to low-cost activities. | One of the weekends, Peter is free as he doesn’t have any assignments due. He looks for low-cost activities to do in the city on the website for himself and his friends. | 1). Peter booked his weekend marathon activity using his credit card on the website. <br>2). Peter is looking for activities that are close to his location.
Anthony Edwards (Parent/Citizen) | 38 yr old who has never used an online booking or planning service. Anthony is a moderate user of the internet of things, like mobile devices and web browsing. He has a 12-year-old son that enjoys physical, outdoor activities, such as playing sports. Anthony believes that spending outdoor time with his son will further strengthen their bond between father and son. | Summer is approaching and its weather will present a perfect opportunity for outdoor activities. Anthony and his son want to search for a specific sport to enjoy and in which both the parent and child can participate. Anthony has a moderate budget to spend on a sport’s activity for him and his son. | 1). Anthony is looking for a high rated activity for him and his son. <br>2). Anthony is looking for cheap activities due to money constraints.
PhysX (Service Provider) | PhysX is a service provider that plans and hosts a variety of events. This organization conducts its operations in multiple parts of the city and throughout the year. Operations include outdoor activities, such as a marathon, and indoor activities, like a technology expo. | PhysX has released an outdoor event of volleyball and card games in the park with an entry fee. PhysX has added a description of the activity on the website with the location and time of the event. | 1). As an event manager, I need a convenient tool to plan and organize an event or multiple events.<br> 2). As an event planner, our organization wants to have a feature that notifies all of our constituents about an upcoming event and updates with regards to that event.     
Administrator | A senior IT administrator who has decades of experience managing big data systems for enterprises. He currently leads a small team of administrators for Pastime | A user has been reported to repeatedly register for activities and cancel/refund their appointments at the last minute. The user has been warned by the automatic system which detects this suspicious activity but he/she continues. The administrator has to give out a punishment and applies the feature of banning the violating user for a certain amount of time. After the ban is lifted, he/she will be put on the admin’s watchlist to be monitored for future violations. | 1). The administrator wants to remove an account from the website due to policy violations. <br>2). The administrator wants to reset the password of one of the accounts.
</div>



## Developers
> Ian SooHoo - @capturetheworld

> Pruthvi Punwar - @pruth17

> Le Duy Vu - @LeDuy-Vu

> Michael Huynh - @MVHJ

## Management Tool
> Phabricator


## Responsibilities:

1. Ian SooHoo (Team Leader)
   1. UX design and HTML implementation
2. Michael Huynh
   1. Database Implementation
3. Pruthvi Punwar
   1. CSS, Bootstrap and Research
4. Le Duy Vu
   1. REST APIs, NodeJS
 
