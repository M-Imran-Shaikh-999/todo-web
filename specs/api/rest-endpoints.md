# REST API Endpoints

## Base URL
/api

## Authentication
All endpoints require JWT token in header:
Authorization: Bearer <token>

---

## Endpoints

### GET /api/tasks
Get all tasks of logged-in user

Response:
- List of tasks

---

### POST /api/tasks
Create new task

Body:
- title (string)

---

### PUT /api/tasks/{id}
Update task title

Body:
- title (string)

---

### DELETE /api/tasks/{id}
Delete task by ID

---

### PATCH /api/tasks/{id}/complete
Toggle task completion status

