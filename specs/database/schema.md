# Database Schema

## Table: users
- id (string, primary key)
- email (string, unique)
- name (string)
- created_at (timestamp)

## Table: tasks
- id (integer, primary key)
- user_id (string, foreign key -> users.id)
- title (string, required)
- completed (boolean, default false)
- created_at (timestamp)
- updated_at (timestamp)

## Relationships
- One user can have many tasks
- Each task belongs to exactly one user



