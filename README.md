
# <p align="center"> Part A

<p align="center"> 
  <img width="100" src="./Img/daisy.png">
</p>

</p>



 <p align="center"> 
 A project by Esther Csoke, Nikki Waelkens and Rose Hernandez.
</p>





## R1. Description of the Website

### Purpose

The purpose of the website is to provide a place for women, and who identify as women whom are beginner programmers to:

- Connect with other women who are starting off in the tech industry.
- Post and find git collaborations. 
- Find local meet ups.
- Provide support and tools through forums.
- Allow women to practice blog writing by posting tech blogs.
 

### Functionality/ Features


The features of the website are aimed to provide a place for users to safetly interact with one another.

<b> Forums </b>
  * Contains a full selection of forum categories to post on that include:
    * Forums by programming language.
    * Career progression/work advice.
    * Getting to know/'Introduce Yourself' forum.
  * Creation of posts and comments on forums.
  * Display preferred pronouns under user info. 

<b>Blogs</b>
  * Writing and submiting a blog to be made public.
  * Commeting on other user's blogs.

<b>User profile management</b>
  * Creating, editing, and deleting an account.
  * Login with a username.
  * User authentication.
  * Display pronouns
  * Modifying a skill table for other users to see.
  * Have the ability to display publicly the meet ups they are attending.
  * Display git projects and blogs on their profile.

<b>Meet up Search</b>
  * Search for local Meet ups by State using the [Meetup](https://www.meetup.com/meetup_api/) API.
  * Save these meetups on personal profile.

<b>Git Project Collaborations</b>
  * Create a project listing to find other women developers to collaborate with.
  * Find and join git collaboration projects.
  

<b>Contact Staff</b>
  * Have the ability to email staff on: 
    * Bullying/Harassment.
    * Technical issues on the website.

    

### Target Audience

This website is catered for women whom are located in Australia. More specifically, women interested in technology and coding. Offering features for those whom are beginning their technlolgy careers, have established a career and/or looking to connect with likeminded women within the industry.

### Tech Stack

- [React](https://reactjs.org/).
- [JavaScript](https://www.javascript.com/).
- [Ruby on Rails](https://rubyonrails.org/).
- [Ruby](https://www.ruby-lang.org/en/).
- [Amazon S3](https://aws.amazon.com/).
- [Heroku](https://heroku.com/).
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html).
- [Git](https://github.com/).
- [PostgreSQL](https://www.postgresql.org/).


--- 

## R2. Dataflow Diagram

Below we have included a level one dataflow diagram which outlines the flow of information throughout our application. It represents different processes, requests and how they are handled by our application components to deliver a repsonse to the user.

<p align="center"> 
  <img  src="./Img/DataflowDiagram.png">
</p>


## R3. Application Architecture Diagram

Below we created an architecture diagram which outlines our initial application structure and tech stack.

It outlines how user requests are handled between the front-end, back-end and database. Once a request is made on the front-end, a request is sent to the back-end of the application, which is handled by the controller layer of the Ruby on Rails framework. The 'controller' layer interacts with the 'model' layer which handles database requests. Data is then passed back to the controller and on to the front-end which is delivered to the user as a response.

<p align="center"> 
  <img  src="./Img/archDiagram.jpeg">
</p>


# <p align="center"> R4. User Stories
</p>

#### User 1:

![Natalie Broughton](./Img/UserAvatar/nat.png)

Residing in Brisbane, Natalie has been working in the technlogy industry for five years. Currently 27 years of age, Natalie studied computer science at university and is currently working as a mid level software developer. She is wanting to connect with other females in the tehconology industry, at all stages of their careers, as she finds the industry male dominated. She wants to provide and receive mentoriship, advice and build her skills.

<i>"I want to continue to build my career in technology by building my network and working on my skills through new collaborations" </i>

As a web developer I want to:
- Be able to connect with other female web developers in Brisbane and Australia to build my professional network.
- Be able to share my experience as a female web developer in a safe and non judgemental environment.
- Be able share and receive career, personal and technology realted advice as I want to progress in my career and help other women in the industry.



####  User 2:

![Amber](./Img/UserAvatar/amber.png)

Amber, a 35 year old mother of two who is wanting to get into tech for a career change. She is currently working as a nurse part time. She is a self taught beginner coder. Amber doesn't know anyone who codes, so she doesn't have anyone to collaborate with. Amber's goal is to learn how to solve merge conflicts like a pro. 

<i>"I am wanting to establish myself in the tech industry by meeting other women who are passionate about programming. I want to collaborate in a judge free zone"</i>


As a beginner coder I want to:
-  be able to socially connect with other beginner coders while feeling assured my data and personal information is protected. So that I can make personal connections with women in Australia.
- I want to find collaborations with other beginner programmers so I can practice using source control and working as a team.
- I want to have the ability to post my own git colloration listing so that I may find other women to complete mini projects with.
-  I want to have the ability post blogs and have other users comment and give critique of my blog so that I can practice my blog writing skills.




#### User: 3

![Sonya](./Img/UserAvatar/Sonya.png)

Sonya is in her early twenties currently working irregular hours in the hospitality industry. She loves to code as a hobby and is undecided regarding whether to make the transition into technology. Sonya is a transgender woman and she would like to connect with people in a safe, non-judgemental environment with like minded people. She would like to build on her current skills and to gain more perspective on whether the technology industry is worth making the career change.

<i>"I am wanting to connect with other women and transgender women whom enjoy coding in a non-judgemental and safe environment."</i>

As a coding enthusiast I want to:
- Be able to connect with all kinds of likeminded women whom are ineterested in technology.
- Be able to report if someone that makes me feel unsafe or judged so I can can continue using the platform.
- Be able to reach out to other transgender women to network and connect with socially.
- Be able to gain an insight of the techonology industry to help me decide if a career change is worth making.




####  User: 4

![Melissa](./Img/UserAvatar/melissa.png)

Melissa, a 14 year old highschool student who likes video games and has an interest in tech but she sees that tech and video games are dominated by men. She would like to learn how to code but does not know where to start.

<i>"I am wanting to find a community where I feel safe and not afraid of asking questions."</i>

As a beginner coder I want to:
- Be able to find a supportive community of women in tech.
- Be able to ask questions.
- Be able to meet women that share the same interests.
- Be able to gain knowledge and tools needed to enter the world of coding.

## WireFrames
 
 The WireFrames below were created using Figma.

 

![homepage](./Img/WireFrames/Homepage.png)


![meetupsearch](./Img/WireFrames/meetupSearch.png)


![signup](./Img/WireFrames/signup.png)


![contact page](./Img/WireFrames/contactPage.png)


![git collabs](./Img/WireFrames/gitCollabs.png)


![git listings](./Img/WireFrames/gitcollabListings.png)


![blog menu](./Img/WireFrames/BlogMenu.png)

![blogpost](./Img/WireFrames/blogPost.png)


![create a blog](./Img/WireFrames/createABlog.png)


![forum menu](./Img/WireFrames/forummenu.png)


![forum for language](./Img/WireFrames/forumForLanguage.png)


![forum for topic](./Img/WireFrames/ForumForTopic.png)


![profile page](./Img/WireFrames/Profile.png)

![profile page](./Img/WireFrames/privatemessage.png)

![profile page](./Img/WireFrames/siteMap.png)

## Planning

Our team decided to use the Kanban planning methodology (an agile approach) with the use of a Trello board. The Kanban method allowed us to manage our work to increase productivity and flexibility, improving our workflow and quality. Our planning developed in having team standups to talk about the project. The team opted for a simple kanban workflow columns of 'To Do', 'Working On' and 'Completed', as the group collectively decided we didn't require any additional workflows for the documentation. All documentation that was to be completed began in the 'To Do' section of the Trello board. While we set days for each item's due date, we allowed for flexibility and would discuss the 'Working On' column for the day. Once a task was done, we moved it to the Completed column. 

#### Day 1 
###### 13/07/2020

  <img width="400" src="./Img/Day1Planning/Created-tasks.png">

We decided to begin with first writing the description of the website, as this could give us a better understanding of how the website would run overall. 

  <img width="400" src="./Img/Day1Planning/description-of-website.png">

#### Day 2
###### 14/07/2020

<img width="400" src="./Img/Day2Planning/day2.png">

We began the day off with a stand-up. We decided to finish off the web and mobile WireFrames, as we previously decided them to be finished today. As we were using figma, it allowed us to all work together. We assigned each team member to either work on the web components or the mobile components, in order to make sure tasks were clear. We additionally decided on finishing up the user stories. We were all allocated to make individual user stories. 


<img width="400" src="./Img/Day2Planning/trello_7142.png">

#### Day 3
###### 15/07/2020

Following our Trello board, today we worked on our Dataflow and Architecture diagram. We used Lucidchart for both of them. We decided it was best to work on them together rather than separately. We worked on the Dataflow diagram first and after lunch we worked on the Architecture diagram, to make sure everything was right we decided to ask Harry for some feedback. We finished both our diagrams just before the class ended.

  <img width="400" src="./Img/Day3Planning/trello_715.png">
  <img width="400" src="./Img/Day3Planning/day3trello1.png">

#### Day 4
###### 16/07/2020

We had a stand-up today, before having the meeting with Mike we discussed what things we could ask Mike. After working together on the feedback Mike gave us about our Dataflow diagram, we tried to find a name for our project as we still can’t decide on a name, we ended up with a short list of names but we decided that we need more time to choose the right name. We worked together on the presentation using Google Slides and finished it before lunch as planned.

<img width="400" src="./Img/Day4Planning/trello_716.png">
<img width="400" src="./Img/Day4Planning/trello_7162.png">
<img width="400" src="./Img/Day4Planning/trello_7163.png">

#### Day 5
###### 17/07/2020

Following the mornings mentor talk we made a breif presentation, introducing our temporarily named "Project Daisy" to the class. We discussed our target audience, features, user stories and our wireframes. Following the presentations we regrouped and had a breif stand up discussing what we needed to finalise our submission for 'Part A' of our assignment. Also, we decided to create the front-end and back-end of our project before the weekend. Last'y,We decided to use Jira as our project management system, adopting a more agile methadogly going forward with out assignment. We spent time learning and experimenting with this software before next week.

<img width="400" src="./Img/Day5Planning/trello_717.png">
<img width="400" src="./Img/Day5Planning/trello_7171.png">
<img width="400" src="./Img/Day5Planning/jira.png">
