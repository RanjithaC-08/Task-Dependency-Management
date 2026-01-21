# Task-Dependency-Management
#### A full-stack task management system with dependency tracking, circular dependency detection, automatic status updates, and interactive graph visualization.

## Features
### Core Requirements
#### *Task Management: Create, read, update, delete tasks
#### * Circular Dependency Detection: DFS algorithm detects and prevents cycles
#### * Auto Status Update: Tasks automatically update based on dependencies
#### * Graph Visualization: Interactive SVG graph showing task relationships
#### * Real-time Updates: Live updates without page refresh
### Task Status Rules
#### * All dependencies completed → Status: in_progress
#### * Any dependency blocked → Status: blocked
#### * Dependencies exist, not all completed → Status: pending
#### * No dependencies → Status stays as set

## Tech Stack
### Backend
#### * Framework: Django 4.x with Django REST Framework
#### * Database: MySQL 8.0+ (SQLite for development)
#### * Language: Python 3.9+
#### * Validation: Custom circular dependency detection algorithm
## Frontend
#### * Library: React 18+ with functional components and hooks
#### * Styling: Tailwind CSS (no UI component libraries)
#### * Visualization: SVG-based graph (no D3.js/Cytoscape)
#### * HTTP Client: Axios for API calls
#### * Icons: React Icons

## Installation
### Prerequisites
#### * Python 3.9+
#### * Node.js 18+
#### * MySQL 8.0+ (or SQLite for development)
#### * Git
