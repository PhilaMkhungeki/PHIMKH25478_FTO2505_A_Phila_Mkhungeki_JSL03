# JSL03 Project Brief: Console-Based Task Manager

## Important Prerequisite

1. Reviewed and corrected JSL02 project using the provided solution.
2. Checked the project user stories in the student dashboard to make sure I understand what is required for each feature.

## Overview

This project involves creating a **simple task management system** where users can add **up to three new tasks** to an existing task array. Tasks are **stored as objects in an array**, each with a **unique incremental ID**. Users will enter task details via prompts, and the system will allow filtering to view only completed tasks. The project focuses on **array manipulation, user interaction via prompts and alerts, and console logging for task management**.

## Key Objectives

## Technologies used

- HTML, CSS & JAVASCRIPT

### Logic & User Interaction

- Stored tasks as **objects inside an array** for structured data management.
- Allow users to **add up to three new tasks** to the existing task list through the "+Add New Task" button.
- Prompt users to enter **task details (title, description, status)** and store them in an object.
- Increments each new task's ID from the last task in the array.
- Users get an alert message when they reach the task limit with the message:
  _"There are enough tasks on your board, please check them in the console."_
  Implemented a **filter function** to display only tasks with the status "done".
- Log **all tasks** in the console with a clear label of "All tasks"  for easy review.
-Completed tasks with status: "done" get logged in the console under a "Completed Tasks" label.

## Code Quality & Maintainability

- Used meaningful variable and function names to ensure readability and maintainability.
- Followed consistent indentation and formatting to enhance code clarity.
- Included comments explaining key logic and functionality to support future modifications.

## Expected Outcome

A **structured and limited task management system** that enables users to add, review, and filter tasks efficiently while ensuring.

**Console Log of all and completed tasks**

![console log](./explainer-images/console%20log.png)
