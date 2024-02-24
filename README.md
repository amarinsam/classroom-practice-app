# Classroom Practice App

Repetition! You guys got it, just drill it in and go at it. The more times you do it, the more natural it'll feel!

## Before Getting Started

Choose a database. The application doesn't have a database dependency currently. Remember, if you're using mySQL, you need to ```npm install mysql2```, and if you're using mongoDB, ```npm install mongoose```. 
I've only built out some of the boilterplate! Don't feel bad about referencing previous projects. Aim to do it again and again until you don't have to!

## Getting Started

Don't forget to ```npm install```!

Build command:
```
  npm run build
```
or - with auto rebuild
```
npm run client-dev
```

Start command:
```
  npm start
```
Note: You wont be able to start anything until you create a server! 
<p>* Do you remember which middleware allows us to serve the client side?</p>


## Goals -
1. Build out the backend with 5 endpoints
   - Getting all students
   - Getting a student by name
   - Add a student
   - Edit a student's age
   - Delete a student

2. Build the client-side
    - Show a list of students
    - Each list-item should display the student's name and age
    - A way to add a student to the backend
    - A way to delete a student
    - A way to edit the student's age

3. Challenges
    - Let the client-side filter by age
    - Create a middleware to log ```'I got this!'``` when a request comes in
  
## Building the Application
You're going to build a Fullstack classroom list application! At the end, you'll want to be able to see the student's name and age. You want to be able to add students, edit them, and delete them.

### Step 1
Lets build some of the backend first,

- [ ] Create a server with express, make sure you have ALL the needed imports/tools
- [ ] We need a connection to the db - do you need a model? or schema.sql file?
- [ ] Build out some controllers - lets start with getting the full list and adding a student
- [ ] Create routes, to get all students and add a student * What type of requests are these?

``` Think about separation of concerns, what is the job of each file? ```

### Step 2
Connect the frontend, if you've properly built the server, you should now be able to build and serve up the client-side!

- [ ] Get the list from our database - think about how we get it and where we store it!
- [ ] Display the list - think about component-based architecture
- [ ] Build out a way to add students

``` Remember how props work, delve into where it make SENSE to create functions ```

### Step 3
Lets build a bit more functionality,

- [ ] Lets make a way for us to delete a student, starting on the backend
- [ ] Create a button on the frontend to allow the above! Pay attention to where this is!
- [ ] Do the same for editing the student's age!
- [ ] Create a button to edit!

``` At this point, we can go back and forth, just make sure you are keeping track of what you're working on ```

### Step 4
Challenge stuff! You're on your own :D

Again, you got this!
