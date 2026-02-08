# Feature: Task CRUD Operations

## Description
Users can create, view, update, delete, and complete todo tasks through the web app.

## User Stories

- As a user, I can create a new task
- As a user, I can see all my tasks
- As a user, I can update a task
- As a user, I can delete a task
- As a user, I can mark a task as complete or incomplete

## Acceptance Criteria

### Create Task
- Title is required
- Task is linked to logged-in user

### View Tasks
- Only tasks of current user are shown
- Each task shows title and completion status

### Update Task
- User can change title
- Only owner can update

### Delete Task
- User can delete their own task only

### Complete Task
- User can toggle completed status



task-crud.md