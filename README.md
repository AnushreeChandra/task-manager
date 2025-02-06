# task-manager
2. Task Management System
Purpose: Create a Kanban-style task management tool.

Key Features:
- User authentication and authorization.
- Create, update, and delete tasks with drag-and-drop functionality.
- Save user preferences in MongoDB.
- WebSocket for real-time updates (e.g., multiple users collaborating).
- Integration with a calendar view.

- Personal Mode
  Functionality:
  - Single-user task management.
  - Only the logged-in user can create, update, or delete tasks.
  - Storage: Save tasks in MongoDB tied to the user's account.
    
- Collaborate Mode
  Functionality:
  - Multiple users can access the same task list.
  - Real-time updates using WebSocket (socket.io).
  - Permissions system (e.g., owner vs contributors).
  - Storage: Shared task lists with unique IDs stored in MongoDB.
