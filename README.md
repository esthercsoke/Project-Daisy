
# <p align="center"> Part A
</p>

 <p align="center"> 
 A project by Esther Csoke, Nikki Waelkens and Rose Hernandez.
</p>

 <p align="center"> 
  <img width="200" src="./Img/girl-at-computer.png">
</p>



## R1. Description of website

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


# <p align="center"> R4. User Stories
</p>

#### User: Natalie

![Natalie Broughton](./Img/UserAvatar/4.png)

Residing in Brisbane, Natalie has been working in the technlogy industry for five years. Currently 27 years of age, Natalie studied computer science at university and is currently working as a mid level software developer. She is wanting to connect with other females in the tehconology industry, at all stages of their careers, as she finds the industry male dominated. She wants to provide and receive mentoriship, advice and build her skills.

<i>I want to continue to build my career in technology by building my network and working on my skills through new collaborations </i>

As a web developer I want to:
- Be able to connect with other female web developers in Brisbane and Australia to build my professional network.
- Be able to share my experience as a female web developer in a safe and non judgemental environment.
- Be able share and receive career, personal and technology realted advice as I want to progress in my career and help other women in the industry.



####  User: Amber

![Amber](./Img/UserAvatar/8.png)

Amber, a 35 year old mother of two who is wanting to get into tech for a career change. She is currently working as a nurse full time. She is a self taught beginner coder. Amber has weekends and afternoons to practice, as her husband is fully supportive of her career change. 

<i>I am wanting to establish myself in the tech industry by meeting other women who are passionate about programming </i>


As a beginner coder I want to:
-  be able to socially connect with other beginner coders while feeling assured my data and personal information is protected. So that I can make personal connections with women in Australia.
- I want to find collaborations with other beginner programmers so I can practice using source control and working as a team.
- I want to have the ability to post my own git colloration listing so that I may find other women to complete mini projects with.
-  I want to have the ability post blogs and have other users comment and give critique of my blog so that I can practice my blog writing skills.




#### User: Sonya

![Sonya](./Img/UserAvatar/6.png)

Sonya is in her early twenties currently working irregular hours in the hospitality industry. She loves to code as a hobby and is undecided regarding whether to make the transition into technology. Sonya is a transgender woman and she would like to connect with people in a safe, non-judgemental environment with like minded people. She would like to build on her current skills and to gain more perspective on whether the technology industry is worth making the career change.

<i>I am wanting to connect with other women and transgender women whom enjoy coding in a non-judgemental and safe environment.</i>

As a coding enthusiast I want to:
- Be able to connect with all kinds of likeminded women whom are ineterested in technology.
- Be able to report if someone that makes me feel unsafe or judged so I can can continue using the platform.
- Be able to reach out to other transgender women to network and connect with socially.
- Be able to gain an insight of the techonology industry to help me decide if a career change is worth making.




####  User: Melissa

![Melissa](./Img/UserAvatar/1.png)

Melissa, a 14 year old highschool student who likes video games and has an interest in tech but she sees that tech and video games are dominated by men. She would like to learn how to code but does not know where to start.

<i>I am wanting to find a community where I feel safe and not afraid of asking questions.</i>

As a beginner coder I want to:
- Be able to find a supportive community of women in tech.
- Be able to ask questions.
- Be able to meet women that share the same interests.
- Be able to gain knowledge and tools needed to enter the world of coding.

## Wireframes
 
 The wireframes below were created using Figma.

<p align="center"> 
  <img width="800" src="./Img/Wireframes/Homepage.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/meetupSearch.png">
</p>


<p align="center"> 
  <img width="800" src="./Img/Wireframes/signup.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/contactPage.png">
</p>


<p align="center"> 
  <img width="800" src="./Img/Wireframes/gitCollabs.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/gitcollabListings.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/BlogMenu.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/blogPost.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/createABlog.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/forum menu.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/forumForLanguage.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/ForumForTopic.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/Profile.png">
</p>

<p align="center"> 
  <img width="800" src="./Img/Wireframes/private message.png">
</p>








## Planning

#### Day 1 
###### 13/07/2020

The team first created a Trello Board to provide a clear outline of what needed to be done and when by. We allowed some extra time between tasks to allow for any issues that could possibly rise. 

  <img width="400" src="./Img/Day1Planning/Created-tasks.png">

We decided to begin with first writing the decription of the website, as this could give us a better understanding of how the website would run overall. 

  <img width="400" src="./Img/Day1Planning/description-of-website.png">

#### Day 2
###### 14/07/2020

We began the day off with a stand-up. We decided to finish off the web and mobile wireframes, as we previously decided them to be finished today. As we were using figma, it allowed us to all work together. We assigned each team member to either work on the web components or the mobile components, in order to make sure tasks were clear. We additionally decided on finishing up the user stories. We were all allocated to make individual user stories. 

#### Day 3
###### 15/07/2020

Following our Trello board, today we worked on our Dataflow and Architecture diagram. We used Lucidchart for both of them. We decided it was best to work on them together rather than separately. We worked on the Dataflow diagram first and after lunch we worked on the Architecture diagram, to make sure everything was right we decided to ask Harry for some feedback. We finished both our diagrams just before the class ended.

#### Day 4
###### 16/07/2020

We had a stand-up today, before having the meeting with Mike we discussed what things we could ask Mike. After working together on the feedback Mike gave us about our Dataflow diagram, we tried to find a name for our project as we still can’t decide on a name, we ended up with a short list of names but we decided that we need more time to choose the right name. We worked together on the presentation using Google Slides and finished it before lunch as planned.

#### Day 5
###### 17/07/2020
