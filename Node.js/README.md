# Node.js Scripts

This Folder contains all the Node.js scripts 
Contributors: 

_Ashwin Gopi Krishna_

**progress_calc.js:**

Script that stores nudge time and last visited time values on the server (MongoDB) realtime.

**store_stats.js:**

Stores progress updates and time for tasks in MongoDB realtime

**store_task_stats.js:**

Stores details of tasks created, and modifications to the task.

**desk.js:**

Old script that hosted the desk_fragment.js script

**home.js:**

Main server side script running on port 8991, hosting all node endpoints for the applicaiton.

**home_fragment.js:**

Script that returns a json array used in old HomeFragment of application

**save_task.js:**

Script that is used to accept a request to join a task. Added to improve security.

**send_notif.js:**

Script in development. Used to send a notification. Added to improve security

**today.js:**

Used to return a json used in the current HomeTab of the application

**upcoming.js:**

Used in old HomeTab screen where upcoming tasks would be displayed.

**card_api.js:**

Old script used with old database schema to get task names under a card, as per Suhas' instruction to help some of his scripts. Parameters were email and card name

**getshit.js:**

Old script with old db schema, gets cards and tasks under a user, as per Suhas' instructions to help some of his scripts. Param: email.

**port_db.js:**

Script written to change the database schema from sharing cards to sharing tasks.

**server.js:**

Script used to host Suhas' helper scripts and the old schedule endpoint

**socket_init.js:**

socket_stream.js, webrtc_js.js: Scripts used for the WebRTC video calling

**task_api.js:**

Another one of Suhas' helper scripts, returns details of users working on a specific task by providing taskName and cardName

**appear.js:**

Old script that was used to handle a schedule or reschedule request

**constants.js:**

Contains the types of notifications used in the application.

**del_cards.js:**

Script used to change the desk schema to the current desk schema by deleting cards under the desk.

**get_task.js:**
	
Script to get task details with taskKey, using old db schema.

**notification.js:**

contained the definition of a notification object

**nudge.js:**

Script that nudges user based on their progress and due date.

**nudge_demo.js:**

Script intended to be used for the demo to demonstrate nudge to the audience.

**port_admins.js:**

Script that converted card admins to task admins. Used to change the db schema to what it is now.

**task.js:**

Contained a basic object for a task.

**test.js:**

First node script testing out the firebase admin sdk. Loaded basic tasks.

**user.js:**

Contained a user object and a method for finding tasks of user.

**drive_client.js:**

Drive authentication via Node(abandoned)

**change_db.js:**

Converts old checkpoint db struct to current

**jitsi.js:**

Videocalling using jitsi.

**speech.js:**

Used to convert base64 file to text

**suggestions.js:**

Gives suggestions on how much time to work on a task each day

**updateUsers.py:**

Script used to add phone number to user's authentication method, to port to new login flow.
