# burger-Logger_app


## Table of Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contribution](#contribution)

 
 ## Description

 Welcome! I would like to present to you my Burger Logger Application!

 Here is my HEROKU link : https://yjk-burgerapp.herokuapp.com/

In this homework assignment, I have created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. I have followed the MVC design pattern; using Node and MySQL to query and routing data in my app, and Handlebars to generate my HTML.

** Here is my Portfolio: https://youjmi.github.io/PorfolioSubmission/index.html  **

## Installation 


To begin, I had to install the following:

I created a package.json by running the following on the command line:
```
npm init
```

I then installed the following packages:

```
npm install express
npm install express-handlebars
npm install mysql
```

Then application will be invoked by using the following command:

```
nodemon server.js OR node server.js
```

This was to help me visualize the application before finalizing everything and DEPLOYING to HEROKU.

## Usage
Once that is invoked or the deployed Heroku Link is accessed, the user will be brought to this page: 

![Screen Shot 2021-02-17 at 8 32 59 PM (2)](https://user-images.githubusercontent.com/73494581/108290986-7f822700-715f-11eb-827c-a96d9d589ae4.png)

Here, you will noticed some default burgers I've added on MySQL. Each side represents if a Burger has been consume OR if the burger has NOT been consumed

![Screen Shot 2021-02-17 at 8 33 09 PM (2)](https://user-images.githubusercontent.com/73494581/108290993-81e48100-715f-11eb-9027-7ee0dd413da6.png)


When you add a burger (access found on the bottom) It will populate to either side indicating if the burger has been consumed or not. One thing I would like to make note is to notice that I have added several buttons that will either:

1.  DELETE the burger entirely
2.  Devour the burger, therefore moving to the other side
3.  The user changing his or her mind when they don't feel like consuming the burger... ultimately moving the    
    burger option to the corresponding side. 

<img width="559" alt="Screen Shot 2021-02-17 at 8 39 06 PM" src="https://user-images.githubusercontent.com/73494581/108291395-3c748380-7160-11eb-800c-1ed86f3c0e3d.png">

Here you will notice that after I have clicked the Button "DEVOUR IT" the Original Cheese Burger has been notated on MySQL as 'devoured'

![Screen Shot 2021-02-17 at 8 33 17 PM (2)](https://user-images.githubusercontent.com/73494581/108291010-86a93500-715f-11eb-9d87-e9ce2f453627.png)

Here you will noticed that I have DELETED the Original Cheese Burger

<img width="534" alt="Screen Shot 2021-02-17 at 8 38 29 PM" src="https://user-images.githubusercontent.com/73494581/108291399-3ed6dd80-7160-11eb-83f0-26d03040db9b.png">

Last picture represents that MySQL has updated AND DELETED the Original Cheese Burger information

## Contribution

Thank you for having the time to view my work.

I would like to give special acknowledgement to my study group as well. We assist one another by providing Feedback, Brainstorming, and general support:

```
1. Rachel Wanke - https://github.com/rwanke14
2. Amir Ashtiany - https://github.com/Alexfit4
3. Johnnie Simpson - https://github.com/balokdecoy
4. Frankie Rosado - https://github.com/Franciscorosado09
```