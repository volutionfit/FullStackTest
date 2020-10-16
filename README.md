# Welcome Candidate!

So you've been selected to progress to stage 2 of the interview process... the technical assessment! Below we will outline the specifications and guidelines you will need to complete this task. In this test you will be demonstrating your technical capabilities in both front and backend environments.


### The Assessment

Your task is to create a brand new Laravel *(8.x)* installation, featuring a functional login page, a dashboard displaying reporting statistics with the ability to create, read, update and delete a list of members.


### The Requirements

 - Your Laravel version must be 8 or above
 - Your front end must be a Vue SPA utilising the Vue Router
 - Your database must be setup using migrations
 - Users should not be able to access the Dashboard or Member List without being logged in

### The Build

The Login and Dashboard pages should follow the attached design (This has been stripped back of all non essential design relevant to this assessment so don't worry if your build looks bare). However for the Member List you will have to use your own creativity. This is to assess your ability to create functionality and visual aspects without guidance.

https://xd.adobe.com/view/5f5c4dcd-0426-4fcc-9b10-3d3285973006-0a0f/

### Dashboard

We expect the figures for Gender and Age within the Dashboard to be connected to an API which will calculate each value from the database.  For you to correctly write the Eloquent statements for this data you will need to add the Date of Birth and Gender to each user within the database migrations.

### Member List

For this list we would like the following data to be shown with each user in the table:

 - Name
 - Email
 - Age (Calculated from DOB)
 - Gender

There must be the ability to create new users, edit and delete existing users which will automatically refresh the list once new updates are made.

For creating and editing users you can either open a modal within the same page, or direct the user to a new page, your choice.

For deleting a user, there must be a modal that will pop out to confirm they want to perform this action. The User model should use Soft Deleting.

You should be able to sort the table by Name and Age by clicking the appropriate table header.

### Other Information

We do not expect the search or profile within the header to have any functionality.

If you have not used all of the technologies within this stack, this will greatly demonstrate your ability to quickly learn new things.
