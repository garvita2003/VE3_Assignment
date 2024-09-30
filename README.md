# VE3_Assignment - MERN Task Manager Application
This Website deals with the Task Management System based on Authentication as well as Authorized Users : An Individual can not only create a task for them but also prioritize them - low, medium and high categories. While creating a task we can even add the title, description,due date of the task, task completed or pending status. We can even perform CRUD operation to create a new task, update the task, delete the task, read / view a task created on a current date. In this application we can even navigate separately over the Pending, Overdue and Completed Tasks. We have a star icon while creating a task we can complete the task by clicking on that star icon. Along with that we also have a feature of Statistical Representation of Users overall task details. 


## Features

### User-side features
- Signup
- Login
- Logout
- Add tasks
- View tasks
- Update tasks
- Delete tasks

### Developer-side features
- Toasts for success and error messages
- Form validations in frontend and backend
- Fully Responsive Navbar
- Token based Authentication
- Use of 404 page for wrong urls
- Relevant redirects
- Global user state using Redux
- Custom Loaders
- Use of layout component for pages
- Use of theme colors
- No external CSS files needed (made using Tailwind CSS)
- Dynamic document titles
- Redirect to previous page after login
- Use of various React hooks
- Custom hook also used (useFetch)
- Routes protection
- Middleware for verifying the user in backend
- Use of different HTTP status codes for sending responses
- Standard pratices followed


## Tools and Technologies
- HTML
- CSS
- JavaScript
- Tailwind CSS
- Node.js
- Express.js
- React.js
- Next.js
- Redux
- MongoDB


## Dependencies

### Backend:
- npm init
- npm i

### Client:
- npx create-next-app@latest client
- npm run dev
- npm install
- npm i axios moment react-hot-toast
- npm i recharts
- npx shadcn@latest add chart
- npm install framer-motion
- npm install react-gtm-module --save


## Prerequisites
- Node.js must be installed on the system of version 18.17.0 or above.
- You should have a MongoDB database.
- You should have a code editor (preferred: VS Code)


## APIS :

### Backend API : Task 
- Create Task : POST - "/task/create"
- Get Tasks : GET - "/tasks"
- Get Task : GET - "/task/:id"
- Update Task : PATCH - "/task/:id"
- Delete Task : DELETE - "/task/:id"

### Backend API : User
- Regiter User : POST - "/register"
- Login User : POST - "/login"
- Logout User : GET - "/logout"
- Get User : GET - "/user"
- Update User : PATCH - "/user"

### Backend API : Admin
- Delete User : DELETE - "/admin/users/:id"
- Get All Users : GET - "/admin/users"

### Backend API : Server
- User Login Status : GET - "/login-status"
- Verify Email : POST - "/verify-email"
- Verify User : POST - "/verify-user/:verificationToken"
- Forget Password : POST - "/forgot-password"
- Reset Password : POST - "/reset-password/:resetPasswordToken"
- Change Password : PATCH - "/change-password"


## Installation and Setup

1. Install all the dependencies
   ```sh
   npm run install-all
   ```

2. Create a file named ".env" inside the backend folder. Add data from .env.example file and substitute your credentials there.Add these variables in your .env file
- MONGO_URI=your_mongo_uri
- JWT_SECRET=secret or anything random
- CLIENT_URL=http://localhost:3000
- PORT=8000

4. Start the application
   Client : 
   ```sh
   npm run dev
   ```

   Backend : 
   ```sh
   npm start
   ```

6. Go to http://localhost:3000


## Overview 
![1](https://github.com/user-attachments/assets/44b6c3af-b0fd-4432-b3ec-890785f2a0ac)
![2](https://github.com/user-attachments/assets/7a8cd4f3-5989-4f50-bdf3-3a3d2aaf23bc)
![3](https://github.com/user-attachments/assets/249e46e3-278b-4ef2-9719-448a9afd5e91)
![4](https://github.com/user-attachments/assets/62defc34-65b2-46c5-97cb-90efa80ae641)
![5](https://github.com/user-attachments/assets/8ad52780-7d1b-48c8-86a1-d4c6e78e7575)
![6](https://github.com/user-attachments/assets/bdc71568-f25d-4b81-b368-7a59e89555b8)
![7](https://github.com/user-attachments/assets/a846428e-6360-40f8-a552-83df24600cf9)
![8](https://github.com/user-attachments/assets/dde2fcb6-b4e5-498a-be55-e9651be453ad)
![9](https://github.com/user-attachments/assets/f8101147-77b4-4444-af88-12581055cfb3)
![10](https://github.com/user-attachments/assets/1620435c-6c22-42ce-8d1b-adbbb23c007b)
![11](https://github.com/user-attachments/assets/1c2a7c5f-fe6a-406a-aba1-953f9b46d055)
![12](https://github.com/user-attachments/assets/8cd587a8-01b7-464e-b49b-792be06f5174)
![13](https://github.com/user-attachments/assets/d72fa578-199c-4eae-b863-04d27c78e5ed)
![14](https://github.com/user-attachments/assets/70dfc4c1-c25e-4f9c-bf37-81f6f3c7557d)
![15](https://github.com/user-attachments/assets/b353d1e8-b7b3-4822-9557-2a2c1b4cbe14)
![16](https://github.com/user-attachments/assets/cb1bc4ff-9b61-4d13-a3c9-83adbcdf065a)
![17](https://github.com/user-attachments/assets/53eff095-289e-4e68-987c-db1a7b508c2a)
![18](https://github.com/user-attachments/assets/924f8d3e-147f-4585-bd57-09cbcdd97465)
![19](https://github.com/user-attachments/assets/96befaba-a1f0-4994-9044-b99c2290aaa3)
![20](https://github.com/user-attachments/assets/898910f5-923c-4466-9cb0-95f4a4c76dc0)
![21](https://github.com/user-attachments/assets/c55389e6-f6c6-4f0d-8196-8c650d2842a5)
![22](https://github.com/user-attachments/assets/2cb2d19d-d20d-4303-a3ef-00d8b861f407)
![23](https://github.com/user-attachments/assets/39e64260-b827-4870-9a04-6a8fac9f1e7e)
![24](https://github.com/user-attachments/assets/1b263224-cfd6-467f-82e5-963520c1b8d7)


