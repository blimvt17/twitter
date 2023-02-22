# Twitter clone

Notes:
- do not commit anything directly to master branch. let's practice PR reviews
- make sure to document any `How Tos`, like setting up DB, how to run the app, etc so anyone can run this on their machines
- make sure to document any errors/learnings you face in this document
- tweet is text only content with up to 100 chars - for now
- we'll create BE first then work on FE
- try not to copy and paste much
- feel free to restructure this `readme`

## TODO
- [ ] create a gitignore file
- [ ] take screenshots of login page, home page, and posting a tweet page from Twitter, and link them to requirements section
- [ ] download and install postman, docker, intellij community
- [ ] create a new folder, spin up a new spring boot service using https://start.spring.io/ and add it there - maven, java 17
- [ ] create an ERD - assume we're using SQL, come up with tables with columns. just write in text file
- [ ] decide which db we're going to use and document why - explore what kind of SQL dbs are there
- [ ] create and document REST API paths and params
- [ ] watch controller - ser
- [ ] implement each endpoint with mock data
- [ ] write unit tests
- [ ] create db and write some dummy data
- [ ] replace mock data with db

## TODO for later
- [ ] create system architecture
- [ ] sign up & login using oauth
- [ ] deploy to cloud - aws vs gcp
- [ ] CI/CD
- [ ] search
- [ ] add a brief analysis on maven vs gradle on backend section - just a couple bullet points
- [ ] brief analysis on FE frameworks
- [ ] brief analysis on BE frameworks
- [ ] create onboarding documentation

## Front End

Tech stack: React

### Requirements
Users need interface to interact with other users
- [ ] sign up page
- [ ] log in page
- [ ] scrollable home page
- [ ] posting a tweet
- [ ] like button on a tweet
- [ ] comments on a tweet
  
## Back End

Tech stack: Spring Boot, Maven

### Requirements 
DB storing information
- personal info
- tweets
- pictures/videos - to simplify things, we'll do text only tweets in the first phase


## References
- https://github.com/dudwk814/petppy
- https://github.com/wlswo/MoCo