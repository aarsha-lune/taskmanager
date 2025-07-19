# Project: Java & Web Development, IU University, Germany: Task Manager for Software Developers

## Tech Stack: MERN Stack (MongoDB, Express.js, React.js, Node.js), Git, JavaScript & so on



### GUI of the Project
<img width="538" alt="image" src="https://github.com/user-attachments/assets/091acb05-d8ff-420b-b551-f82ff7b16d4e" />
<img width="1613" height="900" alt="image" src="https://github.com/user-attachments/assets/8f5a1a08-d623-4d26-a637-ac5131321b21" />

<img width="1613" height="891" alt="image" src="https://github.com/user-attachments/assets/967275e3-0519-4bc3-9962-de03d51417be" />






### Project Code: DLBCSPJWD01

---

## **Project Overview**
Taskflow is a powerful Task Management Web Application designed specifically for software developers and teams. Built using the MERN Stack (MongoDB, Express.js, React, Node.js), this project helps users create, assign, update, and track tasks effectively. It also features an admin panel for managing users, task priorities, project statuses, and developer assignments.

With full responsiveness, role-based access, and seamless API integrations, Taskflow ensures a productive and collaborative environment for software development team

---


## **Tech Stack**

### **Frontend:**
- **React.js:** Dynamic and interactive UI
- **Redux Toolkit:** Efficient state management
- **Vite:** Lightning-fast build tool
- **TailwindCSS:** Customizable and responsive design
- **Axios:** For seamless API requests
- **React-Router-Dom:** Smooth page routing

### **Backend:**
- **Node.js:** High-performance backend environment
- **Express.js:** Lightweight framework for handling requests
- **MongoDB:** NoSQL database for scalability and flexibility (via Mongoose)
- **Bcrypt.js:** Secure password hashing
- **JSON Web Token (JWT):** User authentication and authorization

---

## **Features**
-  User Authentication & Authorization: Signup, login

-  Task Management: Create, assign, edit, and track tasks with statuses (To Do, In Progress, Done)

-  Project Dashboard: Filter and search tasks by priority, assignee, or project

-  Responsive Design: Mobile and desktop-friendly UI
 
-  Developer-Friendly: Designed with teams and agile workflow in mind
---

## **Installation and Setup Instructions**

### **Prerequisites**

Ensure that the following are installed on your system:

- [Node.js](https://nodejs.org/en/) (v14 or later)
- [MongoDB](https://www.mongodb.com/) (for database)
- [Git](https://git-scm.com/) (for version control)

### **Cloning the Repository**

1. Clone the project to your local machine:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

### **Backend Setup**

1. Navigate to the backend directory:
    ```bash
    cd backend
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Start the backend server:
    ```bash
    npm run dev
    ```

### **Frontend Setup**

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Start the frontend server:
    ```bash
    npm run dev
    ```


### **Environment Variables**

Create a `.env` file in the root directory and configure the following environment variables:

```bash
JWT_SECRET=your_jwt_secret
MONGO_USER=your_mongodb_connection_string
MONGO_PASS=
MONGO_CLUSTER=cluster0.t5l2pir.mongodb.net
MONGO_DB=Taskflow
----------

Running the Application

Ensure MongoDB is running locally or provide a MongoDB Atlas connection string in your .env file.

Once both the frontend and backend servers are running, the app will be accessible at:
        Backend: http://localhost:4000
        Frontend: http://localhost:5173
