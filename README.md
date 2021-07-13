# Welcome Candidate!

So you've been selected to progress to stage 2 of the interview process... the technical assessment! Below we will outline the specifications and guidelines you will need to complete this task. In this test you will be demonstrating your technical capabilities in both front and backend environments.


### The Assessment

Your task is to create a brand new Laravel *(8.x)* installation, featuring a functional login page and a list of members with the ability to create and delete.


### The Requirements

 - Your Laravel version must be 8 or above
 - Your front end must be a Vue SPA utilising the Vue Router
 - Your database must be setup using seeds and migrations
 - Users should not be able to access the Member List without being logged in

### The Build

The Login and Dashboard pages should follow the attached design (This has been stripped back of all non essential design relevant to this assessment so don't worry if your build looks bare).

### Member List

For this list we would like you to build an API to fetch rows within the Users table, the following data to be shown with each user in the table:

 - Name
 - Email Address
 - Club Location (this should be a relationship onto the User - you will need to create a migration for a 'gyms' table. For this demonstration the gyms only need to have a name. You can manually enter entries into this table from a seeder and do not need to be able to manage these from the GUI.)
 - Membership Type (this can be hard coded, we only added it to pad out the design!)
 - Registration Date (formatted from the created_at column)

There must be the ability to create new users and and delete existing users which will automatically refresh the list once new updates are made.

### Creating a User

As per the design you should be able to create a user within a modal. The Club Location field such dynamically pull rows from your gyms table and populate a select field.

### Deleting a User

Clicking a trash icon on one of the user rows should pop out a confirmation modal, once the delete confirmation button has been pressed and the API to delete the user has been called, you should update the list to reflect the deleted user.

When deleting a User, the model should use Soft Deleting.

### Other Information

If you have not used all of the technologies within this stack, this will greatly demonstrate your ability to quickly learn new things.

This task will demonstrate your ability to integrate APIs with front end builds, and your ability to use some of Laravels core techniques such as Database Migrations and Seeds, the Eloquent ORM and RESTful APIs.

### Time

We know that your time is valuable so we don't want to take up too much of it, however we do want to make sure we have the right person for the job!

Please spend a maximum of 2 hours 30 minutes on this task. If you don't manage to get all of the functionality completed in this time then don't worry.

### Designs

The design for this test can be found on the following Google Drive link. The designs are built in Adobe XD which you can download and use for free.

https://drive.google.com/drive/folders/1FLr7Ss2ja8Q0rJ1WZdTODU1uQ_s_glik?usp=sharing
