# NextStep Readiness
<p align="center">
  <img src="website.png" width="500"/>
</p>
A study website that provides students a platform to sort and practice SAT math questions. Users could log in and personalize the topic they would like to focus on and the details of their SAT exam. Within the home page, there are options to filter through questions based on topic and difficulty or start answering questions with specified parameters.  

## Technical Stack 
- Vite.js
- Django REST framework
- MySQL
- Firebase Authentication
- Firestore

## Features 
### Authentication
<p align="center">
  <img src="setting.png" width="500"/>
</p>
Firebase Authentication is used to authenticate and create new users on the website. Users can specify the topics they want to focus on and details about their SAT exam within the settings page. This information would be stored using Firestore.

### Home Page
<p align="center">
  <img src="recommend.png" width="500"/>
</p>

#### Pick Question Tab
Within the home page, users could filter through SAT questions based on the section, topic, and difficulty of the SAT question. 

#### Recommendation Tab
Users could also choose to continuously answer questions from a specified field using the recommendation cards. 

### Answers Page
<p align="center">
  <img src="answer.png" width="500"/>
</p>

#### Drawing Tool
Users could draw on the answer page using the drawing tool. There are 4 ink colors and an eraser available
#### Calculator Tool
On a calculator-allowed question, users could click on the calculator icon to pull up a drawer that would display a graphing calculator using Desmos API
#### Reference Tool
Users could click on the book icon to pull up a drawer that would display the reference sheet at the start of an SAT exam

## Website Link
The website is deployed [here](https://alexy4744.github.io/capstone/)
