# Welcome Candidate!

So you've been selected to progress to stage 2 of the interview process... the technical assessment! Below we will outline the specifications and guidelines you will need to complete this task. In this test you will be demonstrating your technical capabilities in both front and backend environments.


### The Assessment

Your task is to create a brand new Laravel *(8.x)* installation, featuring a functional login page, a dashboard displaying reporting statistics with the ability to create, read, update and delete a list of members.


### The Requirements

 - Your Laravel version must be 8 or above
 - Your front end must be a Vue SPA utilising the Vue Router
 - Your database must be setup using migrations
 - Your assessment must follow the Volution coding standard, this will demonstrate your ability to follow coding guidelines set out to all employees

### Login Page

The login part of your application should follow the design at the below link, however for the main dashboard you must use your creativity. This is to assess your ability to follow visual guidelines, and your ability to create appealing features without guidance

https://volution-dev.s3-eu-west-1.amazonaws.com/full-stack-test/Assets+and+Designs.zip

### Dashboard

The following statistics should be added to the dashboard. For you to correctly write the Eloquent statements for this data you will need to add the Date of Birth and Gender to each user within the database migrations.

 - Number of new users created this calendar month
 - The gender ratio of these users (58% Female, 42% Male)
 - The average age of these users

Below the stats, render a tabled list of users. Each user should display the following information.

 - Name
 - Email
 - Age (Calculated from DOB)
 - Gender

There must be the ability to create new users, edit and delete existing users which will automatically refresh the list once new updates are made.

For creating and editing users you can either open a modal within the same page, or direct the user to a new page, your choice.

For deleting a user, there must be a modal that will pop out to confirm they want to perform this action.

You should be able to sort the table by Name and Age by clicking the appropriate table header.

### Other Information

***Colours***
Red: **#EF5350**
Blue: **#0070D2**
Grey: **#EDEEF0**
