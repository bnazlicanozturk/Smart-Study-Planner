Smart Study Planner
Project Description

Smart Study Planner is a simple tool designed to help students organize their study schedules more easily. Many students struggle with managing their time and keeping track of their tasks, especially during busy academic periods. The goal of this project is to create a system where students can plan their study activities, set tasks, and monitor their progress in a more structured way.

The system allows users to create study plans, add tasks to those plans, and set reminders for important deadlines. It also provides a basic progress tracking feature so users can see how much of their study plan they have completed.

This project was developed as part of a coursework assignment and focuses on demonstrating basic system design concepts such as UML modeling and data organization.

Main Features

Creating and managing study plans

Adding and editing study tasks

Setting reminders for tasks

Tracking study progress

System Components

The system is built around several main components:

User: Represents the student using the system. Users can create and manage their study plans.

StudyPlan: Stores the overall study schedule including start and end dates.

Task: Represents individual study activities that belong to a study plan.

Reminder: Helps notify users about upcoming tasks or deadlines.

ProgressTracker: Calculates and shows how much of the study plan has been completed.

UML Diagram

The UML diagram included in this repository shows the relationships between the main system classes and how they interact with each other.

Purpose of the Project

The main purpose of this project is to practice software design and system modeling. By developing this planner, we aimed to better understand how different components of a system interact and how UML diagrams can be used to represent software structure.
MVP source code
Login system: username/password screen
Task management: users can create work plans and add specific tasks to them
Tracking: The system shows progress as a percentage based on the number of completed tasks

Sprint Board
We managed the project development process through GitHub Projects. We organized it into to-do, ongoing, and completed tasks. We could easily see which stage we were in. We used the Agile method.

Link: https://github.com/users/bnazlicanozturk/projects/2/views/1

CI/CD
We used GitHub Actions in the project. This system automatically checks whether the code has errors each time we upload it (Build check).
We ensure that the code is always working.

Documentation
We used UML Class Diagrams when designing the system.
We have schematized the communication between classes such as User, StudyPlan, Task, and ProgressTracker. It is available in the relevant file.
Risk updates
Data storage: All study plans are deleted when the user closes the browser
Time management: We kept it simple in the MVP (UI) phase, focusing on the main functions

Demo plan
Login screen
We will create a plan called "Final Week" and add tasks
We will show how the progress section changes as we complete tasks
