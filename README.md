# Project and Task Manager Backend

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/razanEmad/Project-and-Task-Manager-BackEnd.git
cd project_manager
```

### 2. Install Dependencies

Before running the project, you need to install all required packages.
```bash
npm install
```

### 3. Set Up Environment Variables
Create a .env file in the root directory and add the following:
```bash
MONGO_URI=your_mongodb_atlas_connection_string
PORT=3000
```

### 4. Run the Server
```bash
node server.js
```

# 📡 API Endpoints

## 📁 Projects

### Get all projects
- **Method:** `GET`
- **Endpoint:** `/projects`
- **Description:** Retrieves all projects

---

### Create a new project
- **Method:** `POST`
- **Endpoint:** `/projects`
- **Description:** Creates a new project

---

### Update project
- **Method:** `PATCH`
- **Endpoint:** `/projects/:id`
- **Description:** Updates project details by ID

---

### Delete project
- **Method:** `DELETE`
- **Endpoint:** `/projects/:id`
- **Description:** Removes a project by ID

---

## ✅ Tasks

### Get all tasks
- **Method:** `GET`
- **Endpoint:** `/tasks`
- **Description:** Retrieves all tasks

---

### Create a new task
- **Method:** `POST`
- **Endpoint:** `/tasks`
- **Description:** Creates a new task

---

### Get task by ID
- **Method:** `GET`
- **Endpoint:** `/tasks/:id`
- **Description:** Retrieves a single task by ID

---

### Delete task
- **Method:** `DELETE`
- **Endpoint:** `/tasks/:id`
- **Description:** Removes a task by ID
