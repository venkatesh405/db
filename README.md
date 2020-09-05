Only Backend work
Nodejs 
Express js
MongoDB


Create an rest api's with crud functionality for worker/manager task dashboard.

Manager

Able to login/signup with email and password.
Able to post/edit the tasks (with details), set estimated time to complete the full task(minute, hour, days) and the points(1-500) to be rewarded for the task on completion.
Able to view the task submitted by the user and rate the task. (Rewards to be assigned to users if a task is approved).
Able to view the tasks done/assigned/pending on using a date filter.

Worker

Able to login with email and password.
Able to view the tasks posted by any manager. (paginated tasks).
The new page/modal window should open when the user clicks on a task and shows the task details.
Users should do the task and submit the task details (images/docs or text) for review. it will go to the manager and it will be approved/rejected.
Able to search the task.
Able to view/edit his profile details.
Able to view the completed task history (paginated) and the total rewards.

Bonus Task

Email Verification of user and worker while signup.
Workers should be able to filter the task based on the category.
The task posted should be updated on the user dashboard by refreshing the page. 
The Manager should be able to delete the work if there are no users accepted.
The Manager should be able to activate/deactivate the user.
The Worker /Manager should be able to change the limit for pagination (10,2040,80).


Technology
Required a node application with the front end(Angular 8+) and any database (local/cloud) preferable PostgreSQL or MongoDB


