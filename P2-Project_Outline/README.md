# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
For my project, I want to build a trouble-ticketing/helpdesk software. An employee, client, etc. with the account role `user` will be able to log in, create a trouble ticket (e.g. my printer won't print, I'm getting an error message when trying to do x, etc), and the ticket will be assigned to one of the users with account role `tech`. The `tech`/`user` will be able to correspond within the trouble ticket, and emails will be sent to the `user`'s or `tech`'s email account with updates that are added to the ticket. For anyone with the account role `tech`, time spent on the ticket will automatically be tracked. 
I do a lot of help-desk type work at my job, and have found the trouble-ticketing software used to be lacking. Many issues are attempted to be handled over email alone, and from experience it can be easy to miss an email when you are receiving upwards of 100 a day. I'd like to see if there might be a way I could make it easier, faster, and potentially more efficient. 
### Features
**User Login** - `user`s will be able to login to check on their open tickets, and `tech`s will be able to log in to view their queue of work. As this is intended as an internal trouble ticketing system, new accounts will be created by an account with an `admin` role.
**Create/Update/Close Ticket** - `user`s will be able to create tickets, and both `user`s and `tech`s will be able to update the ticket with new information/status updates and close tickets when the work has been completed.
**Time Tracking** - time spent in the ticket by accounts with `tech` roles will be automatically tracked and added to a `time-spent` total, to track both tech efficiency and productivity.
**Statistics** - `tech`s will have a profile page with statistics about their performance, with average time per ticket, total tickets open, total tickets closed, etc. 
### Technologies
Java  
Springboot  
MySQL  
Hibernate  
Thymeleaf  
Angular  
### What I'll Have to Learn
JavaScript/Angular for time tracking while page is active
### Project Tracker
I will be using GitHub Projects for project tracking. 
