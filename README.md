# burger-Logger_app


## Table of Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contribution](#contribution)

 
 ## Description

 Welcome! I would like to present to you my Burger Logger Application!

 Here is my HEROKU link : https://yjk-burgerapp.herokuapp.com/


 Here is the link to my video tutorial: https://drive.google.com/file/d/1mlAl1Db10I4w3rwA4OJeufxc71HdvjHd/view


In this homework assignment, I have created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. I have followed the MVC design pattern; using Node and MySQL to query and routing data in my app, and Handlebars to generate my HTML.

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

![pic1Burg](https://user-images.githubusercontent.com/73494581/108283749-daad1d00-7151-11eb-8502-e2bb78af2606.png)

Here, you will noticed some default burgers I've added on MySQL. Each side represents if a Burger has been consume OR if the burger has NOT been consumed

![pic2ofBurg](https://user-images.githubusercontent.com/73494581/108283746-d97bf000-7151-11eb-9353-55a618050b43.png)

When you add a burger (access found on the bottom) It will populate to either side indicating if the burger has been consumed or not. One this I would like to make note is to notice that I have added several buttons that will either:

1.  DELETE the burger entirely
2.  Devour the burger, therefore moving to the other side
3.  The user changing his or her mind when they don't feel like consuming the burger... ultimately moving the    
    burger option to the corresponding side. 

![pic3ofburg](https://user-images.githubusercontent.com/73494581/108283744-d97bf000-7151-11eb-933d-57d5e16b765f.png)

Here you will notice that after I have clicked the Button "DEVOUR IT" the Original Cheese Burger has been notated on MySQL as 'devoured'

![pic4ofburg](https://user-images.githubusercontent.com/73494581/108283742-d84ac300-7151-11eb-8692-a4fa6b6c2ce7.png)

Here you will noticed that I have DELETED the Original Cheese Burger

![picfinalofburg](https://user-images.githubusercontent.com/73494581/108283741-d7b22c80-7151-11eb-8339-bc3b140a794a.png)

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