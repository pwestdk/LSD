# Large System Development (LSD)

## ROLES
Product Owner
- Phillip Brink (**PO** )
Test Manager
- Emilie H. Nielsen (**TM**)
Scrum Master (**SM**)
- Philip West
Developer
- Emilie H. Nielsen
- Kasper Vetter
- Philip West
- Phillip H. Brink

## Requirements

### Need to have
#### USER
  LOGIN
    * As a **user** I want to be able to registered on the site so that I can post stories and comments
    * As a **user** I want to be able to log on to the site so that I can post stories and comments

  STORIES
    * As a **user** I want to be able to write stories so others can comment
    * As a **user** I want to be able to see stories so I can view stories
    * As a **user** I want to be able to click on comments so that I can read the comments
    * As a **user** I want to be able to click stories so I can be directed to the repository

  COMMENTS
    * As a **user** I want to be able to write comments on stories so I can discuss the story
    * As a **user** I want to be able to reply on comments so I can discuss the story

  VOTES
    * As a **user** I want to be able to up vote on others comments based on my karma so that I can show my apprication
    * As a **user** I want to be able to down vote on others comments based on my karma so that I can show my apprication
    * As a **user** I want to be able to up vote on stories based on my karma so that I can show my apprication
    * As a **user** I want to be able to down vote on stories based on my karma so that I can show my apprication
    * As a **user** I want to be able to gain karma points so that I can vote

  SPAM
    * As a **user** I want to be able to mark stories as spam so that irrelevant stories can be removed
    * As a **user** I want to be able to mark comments as spam so that irrelevant comments can be removed

#### ADMIN
  SETUP
    * As **PO**  I want to have a server running so I can build an application
    * As **PO**  I want to have a database running so I can save da

  DATABASE
    * As **PO**  I want to store all comments in the database so that I have integrity
    * As **PO**  I want to store all stories in the database so that I have integrity

  RELIABILITY STATUS
    * As **PO**  I want the site to be available at all times so that **user** can access the site

### Nice to have
USER
  STORIES
    * As a **user** I want to be able to edit stories so I can correct my posts
    * As a **user** I want to be able to delete stories so I can remove my stories
    * As a **user** I want to be able to edit my information so I can change it

  COMMENTS
    * As a **user** I want to be able to edit my comments on stories so I can correct my comment
    * As a **user** I want to be able to delete my comments on stories so I can remove my answer

ADMIN
  PROCESS
    * As **PO**  I want to have a basic plan for the workflow so I have continuous integration
    * As **PO**  I want a repository to the application so I can upgrade the system

  SECURITY
    * As **PO**  I want a secure website so that **user** are safe
    * As **PO**  I want to secure my content so I still have data if the site goes down
    * As **PO**  I want to secured **user** passwords so I comply with GDPR

IDEAS
    * As a **user** I want to be able to post stories through an API
    * As a **user** I want to be able to comment on stories through an API
    * As **PO**  I want to connect my web application and database together
