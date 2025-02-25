# GymX5000
GymX5000 is a fitness app that brings health, fitness and a fun video game aspect to living a healthy lifestyle, providing users with an all in one experience where you can stay motivated, eat healthy, get stronger, and compete with friends.  This app uses a multipurpose card system that dynamically renders many different activties from a polymorphic postgreSQL database. GymX5000 includes a unique challenge feature that contains interactable 3D models of trophies that are awarded upon completing tasks. 

![image](https://lh3.googleusercontent.com/g91D-KmK_R3ajx9XSY7l6d9kJkfXZhBUmzW7yUajU7FW5ffk9rHmrmDU7P__xtALIA1RCrF4X7P5JnNC7z14vwf0V_gqPHoPU7x3O0YWUeoiuV0L8I8kbUHZy2v9NYmm4U-HTyW9FQ=w2400)

This project was a brief 1-week sprint where our team tried to complete an MVP for an external user Chad. As a team, we decided to build the database in a polymorphic design where more categories could be easily added in future updates. With a short period of time, we narrowed down the features to the top must haves of the client to meet a very short deadline. Meet the team who made this possible!


## Contributers

**[Walter Latimer](https://github.com/floridamaniac)**\
*Project Manager*

**[Dami Kim](https://github.com/es98dame)**\
*Architecture Owner*

**[Andrew Orodenker](https://github.com/aorodenker)**\
*UI Owner*

**[Alexander Cannon](https://github.com/theVikingMan)**\
*Fullstack Engineer*

**[Benjamin Cope](https://github.com/BenjaminRCope)**\
*Fullstack Engineer*

**[Hunter Motko](https://github.com/hunterMotko)**\
*Fullstack Engineer*

**[Ivy Wong](https://github.com/ivykw)**\
*Fullstack Engineer*

**[Ryan De Leon](https://github.com/ryand8008)**\
*Fullstack Engineer*

**[Owen Yoshishige](https://github.com/OwenMY)**\
*Fullstack Engineer*


<br/>

## Front-End
![image](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![image](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) ![image](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![image](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![Threejs](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white) ![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black) ![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)

## Back-End
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![image](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

## Testing
![cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)

<br/>

## App User Interface

### Activities
The activities page displays a list of cards where a user can filter the cards by category and further search through them by tag using the search bar.
Near the top of the page is a random motivational quote that changes everytime you refresh the page. Each card can be favorited by clicking the star icon and are added to the profile page upon click. Clicking a cards title will take you to another page displaying more information about that card. 
>>
![image](https://media.giphy.com/media/gZGKgbMA7zDn0raCKj/giphy.gif)
>>
### Classes
In the classes section is a carousol of favorited classes and a list of classes a user has booked and completed.  Below that is a list of upcomming classes you can also book that are not in your favorites list.  Pressing the 'Book' button will show a prompt verifying that you have booked a class.  At the moment, there is no way to delete classes or unbook them. This feature will be added in a future update.
>>
![image](https://media.giphy.com/media/IaYQDYErZuqPvZVybO/giphy.gif)
>>
### Challenges
The challenges page showcases a display of 3D interactive badges that can be earned by completing challenges.  Beneath it is a leaderboard that displays the top users who have earned the most points by completing challenges, a feature not yet implemented. Challenges for the month can be found at the bottom of the page where clicking on one will take you to a page with more information about that challenge.  The points system and challenge information will be implemented in a future update.
>>
![image](https://media.giphy.com/media/P8IWfYps4PD4OtpoCM/giphy.gif)

### Profile Page
The profile page consists of a users information, badges earned and favorited activity cards.  The friends and messaging features are not implemented and will be added in a future update.
>>
![image](https://media.giphy.com/media/o4uXO0ayp3Cfi5cHcM/giphy.gif)

<br/>

## Back-End Structure
![image](https://lh3.googleusercontent.com/12j7fKqRnWREx77PXufgg4JM2Hw-JbmocQ9JSkaITUHvBs6Mv9DdB_KFb8Ej4EijSUPrM2C5b1q1hb6QnUnsUqqJsbNizfj2BFOnSTAVKSgRAtwIhQHtS2JjyC2CYpPCk5dbWXPMlw=w2400)
<br/>

## Testing

<br/>

## Our Journey
  The app that you see before you did not come without it's challenges.  Our client desired an all inclusive app with a long list of features that was impossible to build within a week and despite narrowing down the scope of the project presented many questions to be answered. Luckily our client was satisfied with our proposal of building a gym app that included just challenges to be completed. 

<br/>

## Setup

1. Download depencies with npm install
   > `npm install`

2. Run webpack in development with:

   > `npm run client-dev`

3. Run server with:

   > `npm run server-start`

5. Visit local site at http://localhost:3000
