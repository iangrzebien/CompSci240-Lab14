# Lab 14: Github Setup
 
## Objective
To set up a Github repository for your team project.

 
## Details
Using Github will allow you to more easily share code between team members and keep your project in sync. In order to set this up, you will need to do the following:

Everyone on the team needs to make a Github account, if you do not already have one. To do that, Navigate to https://github.com/join to sign up for an account. Fill in your details for step 1. For step 2, choose the free plan. For step 3, you can put in your interests if you like. You must also verify your email address. Log in to your email and click the verification link. To collaborate with Github, each team member needs their own account.

One person on the team should make the central repository. The instructions for doing so are available on the CPSC 225 notes. You can make the repository public for this project. Also, add a README file, and choose a .gitignore for Java code.

This step also includes inviting your team members to the project. You will need to put in their Github user names to be able to find them. This gives them permission to make changes to the code in this repository.

Everyone should clone the repository into IntelliJ. To do this, choose “Get from VCS” on the IntelliJ start screen:



Then copy the Github project URL and paste it into the project URL in IntelliJ:



Click “clone”. When it asks if you wish to trust the project, you should choose yes. It should then pull open the project including the README file you made.

Everyone should test to make sure that they are able to save their changes to the project. To do this, do the following with your team:
Have one person make a file called “AUTHORS.txt” for storing the names of the people working on the project. They should right-click on the project name, and choose “New→File” and name it “AUTHORS.txt”. IntelliJ should ask automatically if you wish to add it to the Git repository. Say yes. This person should add their name into the file.

This person should now send it to the central repository at Github. There are two steps in doing this. First, choose “Git→Commit” from the main menu. Enter a message, like “Added first author” or something. Then click commit. The first time it will ask your name and email address.

Now choose “Git→Push” from the main menu. This will require you to login through Github. When that is completed, the change you made of adding the AUTHORS.txt file should be sent to Github. If you refresh the project page, it should appear.

The next person should choose “Git→Pull” from the menu which should download the AUTHORS.txt file into their copy of the project. They should then add their own name to this file and then do the “Git→Commit”, and “Git→Push” sequence to send the update to Github.
Repeat step B for all team members who haven’t put their name in the file yet.
Finally, everyone should perform a git pull, which should download the newest version of AUTHORS.txt with everyone’s names. This ensures that everyone has both read and write access to the repository.
 
## Using the Repository
As you work on the project, you should follow the basic steps for working with Git:

Start with “Pull” to make sure you are up to date before making any changes of your own.
Work on the project until you are at a point where you want to save your work. If you add new files, be sure to add them to the repository. If you decline doing this when the file is made, you can right-click on the file and choose “Git→Add”.
Perform a “Commit” to save your work into your own repository. You can make multiple commits to your own repository before sharing with your team.
When you want to share your progress, do a “Push”. This sends the code you’ve worked on to the central repository. Next time your teammates do a git pull they will get your new stuff.
Repeat!
 
## Submitting
For this lab, you should enter the URL of your Github repository as a text entry on the Canvas assignment for this lab.

Everyone on the team should do this for the lab which will tell me that each person has Github set up correctly and is ready to contribute!
