                                                            Design Milestone for Bot
                                                            
Bot of Choice: FocusBot “Help community members be productive”

----Help community members be productive, e.g. recommending open task to worker, or recommending best workers to task
----Help to identify potential players, e.g. “cheap talker[1]”, “collusion[2]”
----Provide productivity aids, such as daily reminders, new task alert, new competitor alert, mute incoming notifications, etc. to a community member.


Problem Statement:
---- The problem that the FocusBot helps to alleviate is insufficient productivity and focus. It helps the community members be more productive in their work by recommending open tasks to the worker or recommending the best worker to work on a single task. The intention of the bot is to cut down on downtime and tasks that are considered to be “unfocused” and to help improve productivity. This helps save the team time and keeps the members on track to do better work.

Bot Description:
----Our focus bot will help community members be productive, e.g. recommending open tasks to workers, or recommending best workers to task. In addition, it’ll help to identify potential players, e.g. “cheap talker”, “collusion”. Finally, it’ll also provide productivity aids, such as daily reminders, new task alert, new competitor alert, etc. to a community member.
    The bot will both provide analytical reports of user 
    “Do your work, stop being lazy!” - the bot
    
Use Cases:

Use Case 1: Review current task
Precondition: Have a current task selected
Main Flow: User clicks on the current tasks [S1]. User will be given a list of all their current task to choose from [S2]. Bot will display what the current task is and gives more in depth information on it, including other people who have been working on it [S3]. 
Subflows:
[S1] There is a button to click to open the current task if they have one.
[S2] User will be given a list of their current task based on date and also importance with the option to star the important task
[S3] The bot will display the details on the task to the user
Alternative Flows: There is no current task so the user is prompted to select one.

Use Case 2: Set a Daily Reminder
Precondition: None
Main Flow: User goes to the daily reminders to set up a new one[S1]. User will be prompted with a stickies-like interface to write a note [S2]. The bot will display the daily reminder the next day the user starts up their computer [S3]. 
Subflows:
[S1] The user will go to the daily reminders interface where they can choose a recurring reminder or a one time one.
[S2] The user will put in the desired note to remind themselves with.
[S3] The bot will display the data at either a desired time the next day or at startup of the system.
Alternative Flows: [E1] User exits the daily reminder interface. [E2] The user deletes a daily reminder.
