# Budget Tracker Application

![GitHub license](https://img.shields.io/badge/Made%20by-%40Eng.JordanNaei-orange)
![License](https://img.shields.io/badge/License-ISC-blue.svg "License Badge")

# Description

This project objective was to add a new feature to our client 'Budget Tracker' application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline
  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.


# Application Image

![Application main page](https://github.com/JordanNaei/budgetTracker/blob/master/public/img/app1.PNG?raw=true)

<hr>

# Application Local Machine Icon

![Application Local Machine Icon](https://github.com/JordanNaei/budgetTracker/blob/master/public/img/DTIcon.PNG?raw=true)

<hr>

# Application Local Machine Version

![Application Local Machine Version ](https://github.com/JordanNaei/budgetTracker/blob/master/public/img/appDT.PNG?raw=true)

<hr>

# Application Local Machine Version Offline Mode

![Application Offline Mode](https://github.com/JordanNaei/budgetTracker/blob/master/public/img/AppOffline.PNG?raw=true)

<hr>

- [Application URL](https://guarded-waters-71708.herokuapp.com/)

## Technologies and Frameworks Used
- Node.js.
- Express.
- Mongo db.
- Mongoose.
- Manifest.
- Service Worker.
- PWA Application.


# Installation
- Run npm i.
- Run node server.js.

# Database Design
- MongoDB 'budget'.
- IndexedDB at the client side.

## Business Context
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.(Pass)

# Repository

- [Project Repo]()
