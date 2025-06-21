## mundane
A React frontend for mundane that provides task and board management with real-time data synchronization, interactive drag-and-drop, and user collaboration features.
<br>
Part of a two-repository project, including a backend API, WebSocket server, and MongoDB database.

## Live Demo
To view the live app, click below:
<br>
[![mudane logo](https://github.com/user-attachments/assets/8e728004-e699-446c-be3e-5215bba3c43e)](https://mundane.onrender.com/)

## Features

- Interactive board and task views  
- Sidebar displaying task details via nested routing (`Outlet`)  
- Real-time data change UI updating
- Real-time live chat between users  
- Integration with backend REST API for data fetching and mutations
- User login and session handling  
- Drag and drop for tasks and groups  
- Search and sort for tasks  

## Technologies

- React (hooks)  
- React Router  
- Redux  
- Sass  
- Axios  
- WebSocket client  
- Vite  
- JavaScript (ES6+)  

## Setup

1. Clone the repo  
2. `cd client && npm install`  
   - If running locally without a backend: `npm run dev:local` (uses browser local storage to simulate backend data)  
   - If connecting to the backend: `npm run dev` (make sure MongoDB is running locally, or update the connection string in the backend config)

## Screenshots
Board View
<!-- spacer -->
![mundane](https://github.com/user-attachments/assets/d6677f55-4327-4638-ac77-78c785f9d035)
<!-- spacer -->
Live Chat
<!-- spacer -->
![chat](https://github.com/user-attachments/assets/293c53da-e0e2-4aab-8d1f-a88fa2cbcaee)
<!-- spacer -->
Login / Signup
<!-- spacer -->
![login signup](https://github.com/user-attachments/assets/b7e2b53b-70e2-4c43-899e-04701da29937)
<!-- spacer -->
Phone View (Scrollable)
<!-- spacer -->
![phone view](https://github.com/user-attachments/assets/8774a52c-13c5-44df-adba-902589d6c79a)
<!-- spacer -->
Search
<!-- spacer -->
![search](https://github.com/user-attachments/assets/5a7bcd42-a92f-4884-8803-e4a8e5399ad6)
<!-- spacer -->
Sort
<!-- spacer -->
![sort](https://github.com/user-attachments/assets/012fec1a-734b-4b62-aa9a-4938e00bf62d)
<!-- spacer -->
Filter
<!-- spacer -->
![filter](https://github.com/user-attachments/assets/b7a72e6d-f740-4d30-a0f2-68ad0dc55b43)
<!-- spacer -->
Hide
<!-- spacer -->
![hide](https://github.com/user-attachments/assets/505f529a-71c8-4071-a580-38e6255636c4)
