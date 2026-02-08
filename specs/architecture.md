# System Architecture

## Overview
The Todo application will be a full-stack web app with separate frontend and backend.

## Components

### Frontend
- Built using Next.js
- Provides user interface
- Sends API requests to backend

### Backend
- Built using FastAPI
- Exposes REST API endpoints
- Handles business logic
- Verifies JWT authentication

### Database
- PostgreSQL (Neon Serverless)
- Stores users and tasks

## Flow

User → Next.js Frontend → FastAPI Backend → PostgreSQL Database → Response → Frontend