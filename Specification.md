# URL to team 01 Github repository: https://github.com/NhaDAlvarado/CMPE131-Project-Team01

# TEAM MEMBER NAME:

Nha D Alvarado - Github user: NhaDAlvarado

Youhao Chen 	- Github user: youhaoSjsu

Khuong Huynh   - Github user: huynhkhuong69

Jose Betancourt Jr.Huizar -Github user: h0se69

# PRODUCT NAME: 

ProStudent

# USE CASES NAME:

#### General Feature

1/ Ability for users to sign-up, login/logout.

2/ Be able to delete account

3/ Light/ dark mode (h)

#### Memorizing

1/ input a markdown file and ouput flash cards. 

2/ Share flash cards (add to their account) 

3/ Give hints if the user doesn't know the result 

4/ Give pictures to make it easier to remember 

5/ Mind map of flash cards

#### Notes

1/ render markdown notes

2/ convert markdown notes to pdf 

3/ share notes with other people (add to their account) 

4 / to - do list 

5/ Email/ SMS Reminder for Assignments 

#### Time Management:

6/ Create time blocks (using markdown) (k)

7/ Use pomodoro timer. 

8/ Time spent on assignment (y)

9/ Break alert when users learn too long (h)

# Use Case Description

**Use Case Name: ** Mind map of flash card

Summary 

Help students to note down only the most important information using key words, then make connections between facts and ideas visually.

Actors

1. Students	
2. Teachers
3. share your own note to get pay

\## Preconditions

\* precond 1: Users click "start" button on "Mind map" task

\* precond 2: Users click "link" to my mind map.

Triggers

The exams are coming, so it is time to review.

Primary Sequence

1. Use different colors for difderent tasks
2. Find keywords and example relate to that
3. Include pictures  

\## Primary Postconditions

\* postcondition: click to review flash card

\* postcondition: all flash card related to key word pop up when search 

 \### Alternate Trigger: do not want to forget the lecture

\### Alternate Postconditions

=====================================================

**Use Case Name:** render markdown notes

\## Summary

Create a plain-text formatting syntax for user to take note

 \## Actors

1. Students
2. Teachers
3. Anyone who want to learn something new

 \## Preconditions

\* precond 1: users click on the app icon for quick access to markdown

\* precond 2: a plain page for user to edit their note

 \## Triggers

Users want to take quick note about something they don't want to forget, while mark down note provide them beautiful note 

\## Primary Sequence

1. Different font size for task and sub- task
2. Easy to access since things are easy to be forget

\## Primary Postconditions

\* postcondition: auto fix the note following task and sub-task format

\* postcondition: ask user to name the note

\### Alternate Trigger

\### Alternate Postconditions

========================================================

**Use Case Name:** use pomodoro timer

\## Summary

every 25 minutes working, users deserve to have 5 minutes break

\## Actors

1. Students
2. or anyone who want to focus

 \## Preconditions

\* precond 1: click on the clock, then set timer for studying

\* precond 2: set timer for break

\* precond 3: don't need to manually set up everytime use only if want to change

 \## Triggers

users want to focus on reviewimg or studying or learning

\## Primary Sequence

1. show how much time left
2. users can use the display of a clock they want
3. Notice user when time
4. Let users chooe same timer if nothing change

 \## Primary Postconditions

\* postcondition: play some musical music when break

\* postcondition: ask users if anything can improve in this features

 \### Alternate Trigger: timer when cook, or run

\### Alternate Postconditions

==================================================

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Case Name: ** Light & Dark mode toggle

## Summary
	- Users will be able to toggle from a light to dark mode and
	  vice versa

## Actors
	- App User (Student)

## Preconditions
	- Access the website

## Triggers
	- Click Toggle Button (Moon logo/Sun Logo)
	- Likely positioned on navbar

## Primary Sequence
	- Step 1: Access Site
	- Step 2: Locate navbar & click button

## Primary Postconditions
	- Screen background changes from dark to light or vice versa
	- Buttons, Text, etc are updated to match color format

======================================================================================
**Case Name: ** Share Flash Cards

## Summary
	- Users will be able to share flash card information with other
	  users registered on the website via email.

## Actors
	- App User (Student)

## Preconditions
	- Access the website
	- Logged into site
		- Regsiter if not signed up

## Triggers
	- Click share button

## Primary Sequence
	- Step 1: Access Site
	- Step 2: Login or Register
	- Step 3: Navigate to Flash Card Section
	- Step 4: Select what flash cards to share
	- Step 5: Click share flash cards button

## Primary Postconditions
	- Pop-up appears asking for the recipients email/username
		- Sends flash cards

## Alternate Sequences (If user is not registered)
	- Step 1: Register 
	- Step 2: Confirm email address (avoid spam)
	- Step 3: Return back to flash card section
	- Step 4: Ask user to create flashcards before attempting to share
	
======================================================================================

**Case Name: ** Email + SMS Reminders

## Summary
	- Users will be reminded days/hours before an assignment
	  is due via Email and/or SMS.

## Actors
	- App User (Student)
	- API's used

## Preconditions
	- Access the website
	- Logged into site
		- Regsiter if not signed up
	- Enable Notifications in settings
	- Add Phone Number / Email in settings

## Triggers
	- Settings checkbox/button to enable notifications
	- Select assignments user wishes to be notified for

## Primary Sequence
	- Step 1: Access Site
	- Step 2: Login or Register
	- Step 3: Navigate to Settings
	- Step 4: Add email and/or sms 
	- Step 5: Navigate back to assignments tab
	- Step 6: Select assignments you wish to recieve notifications for

## Primary Postconditions
	- Pop-up appears asking to confirm reminders
	- Same pop-up asks when each reminder should occur (Every 6hours, day, etc)
		- Sends notifications when the timer condition is met

## Alternate Sequences (If user is not registered)
	- Step 1: Register 
	- Step 2: Confirm email address (avoid spam)
	- Step 3: Return back to settings
	- Step 4: Ask user to Add email and/or sms
	- Step 5: Add assignments before receving notifications
	- Step 6: Select assignments you wish to recieve notifications for

======================================================================================


**Case Name: ** Break Alert

## Summary
	- Users will be alerted to take a break every 'x' amount of time 
	  to avoid stress, eye damage, etc.

## Actors
	- App User (Student)
	- API's used

## Preconditions
	- Access the website
	- Logged into site
		- Regsiter if not signed up
	- Set up break alert time interval in settings

## Triggers
	- Automatic

## Primary Sequence
	- Step 1: Access Site
	- Step 2: Login or Register
	- Step 3: Navigate to Settings
	- Step 4: Set break interval & save settings

## Primary Postconditions
	- Pop-up appears letting the user know its time for
	  a break.

## Alternate Sequences (If user is not registered)
	- Step 1: Register 
	- Step 2: Confirm email address (avoid spam)
	- Step 3: Return back to settings
	- Step 4: Set break interval & save settings

>>>>>>> 3c8a7a39f8d897cd33128450e8c725af8a35e34e

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

===============================================

#Use Case Description: User login to the system to access the funtionality of the system 

Date: 09/15/21
Product Name: ProStudent
Problem Statement: Add shared notes feature to web app
Non-functional Requirements: 

1. When clicking the share note button, it will take 1-2 seconds
2. User can add many email addresses to share their note
3. User can navigate to the notes page by clicking on the link

**Use Case Name: **Share Notes

##Summary: 

All users can use this feature to share their notes with others.

## Actor - student, teacher, admin, parents, users

##Preconditions - need to connected to wifi or network

##Postconditions - system will send a notification to user email address

## Trigger - help classmates study, study group

##Primary Sequence
	1. User clicked on the share notes button
	2. User entered email address
	3. User clicked sent

## Primary Postconditions - system will notified if the notes is sent or failed.

==============================================

#Use Case Description
Date: 09/15/21
Product Name: ProStudent
Problem Statement: Add input markdown feature to web app
Non-functional Requirements: the system will highhight the words that we have marked

**Use Case Name: ** Input Markdown

##Summary: All users can use this feature to make notes or memos.

## Actor - student, teacher, admin, parents, users

##Preconditions - Click on the word then select highlight

##Postconditions - the system will highlight words with different colors and display the input that the user has made

## Trigger - make it easier for users to remember

##Primary Sequence
	1. User clicked on the word
	2. User notes or highlight
	3. User clicked saved

## Primary Postconditions - system will show a note below the word highlighted word

========================================================

#Use Case Description
Date: 09/15/21
Product Name: ProStudent
Problem Statement: Add time blocks feature to web app
Non-functional Requirements: 

1. help users learn more effectively
2. Time blocks can be created in less than 30s
3. Users should be able to setup the clock within a few click

**Use Case Name: ** create time blocks

##Summary: Time blocks is the best way to prepare for test, and time management

## Actor - student, teacher, admin, parents, users

##Preconditions - User use time blocks to test their understanding 

##Postconditions - User know if they make it on time or not

## Trigger - Prepare them for exams

##Primary Sequence
	1. User clicked create time block
	2. User clicked setup time
	3. User clicked save
	4. User clicked the start button to start answering question

## Primary Postconditions - After a period of time answering all questions, the system will display the results on the screen

=============================================================

**Use Case Name:** Give pictures to make it easier to remember

##Summary: This feature is available to all the users.

## Actor - student, teacher, admin, parents, users, kid

##Preconditions - words/equations that difficult to remember

##Postconditions - help memorize words or definitions faster

## Trigger - Images help user remember difficult concepts 

##Primary Sequence
	1. Users clicked on images that they thought were associated with the word
	

## Primary Postconditions - system will notified if the answer is right or wrong.

