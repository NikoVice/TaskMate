# TaskMate

The idea of this project was taken from the GPT chat + its own improvisation and visualization. 

Technical specification:

Project Description:
Creating an application for managing user tasks on the Android platform. The application should have the functions of adding new tasks, editing, deleting and viewing them. You also need to add a reminder functionality about upcoming tasks and deadlines. The ability to share tasks with other users within the framework of teamwork or project activities should also be implemented. It is necessary to develop a function for analyzing task completion statistics.

Functional requirements:
1. Adding a task: The user can add a new task by specifying its name, description, due date and priority.
2. Editing a task: The user can change the information about the task, for example, the name, description, due date or priority.
3. Deleting a task: The user can delete a task from the task list.
4. View Tasks: The user can view a list of their tasks with the ability to sort by various parameters, such as priority or due date.
5. Task Reminder: The application should send notifications to the user about upcoming tasks and deadlines.
6. Sharing tasks with other users: The user should be able to share tasks with other users, including by creating shared access to tasks or inviting other users.
7. Analysis of task completion statistics: The user should be able to see task completion statistics for a certain period, such as the number of completed tasks, the effectiveness of user actions within projects, etc.

Technology requirements:
1. Programming language: Application development should be done in Kotlin.
2. Database: to store information about tasks and operations with them, you need to use SQLite.
3. User Interface: The development of the application interface should be done using the Android SDK and XML markup.

Notes:
- To ensure the security of user data, it is necessary to implement an authentication and authorization mechanism using Firebase Authentication.
- It is recommended to develop data backup to prevent information loss in case of system failures.
- Provide for the possibility of scaling the system to handle a large number of users and tasks.
- Development should be carried out in stages, with regular verification and testing of the functionality.
