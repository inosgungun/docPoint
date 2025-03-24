# DocPoint
DocPoint is a doctor appointment booking platform that enables patients to book appointments seamlessly while allowing doctors and admins to manage their profiles, appointments, and earnings efficiently.

## Project Link
-   https://docpoint-frontend.onrender.com/

## Admin/Doctor Panel
-   https://docpoint-admin.onrender.com/
-   Email:- admin@email.com
-   Password:- qwerty123


## Features

### Frontend (Patient Portal)

-   User authentication (Login/Register)
-   Book appointments with available doctors
-   View appointment history
-   Manage profile details
-   Responsive UI built with ReactJS

### Backend

-   Manage doctor profile (edit details such as name, specialty, and fees)
-   Check appointment schedules
-   Cancel or reschedule appointments
-   View earnings and performance statistics
-   Secure authentication and authorization

### Admin Panel / Doctor Panel

-   View and manage all doctors and patients
-   Add/Edit Doctor Details
-   Monitor and track earnings of doctors
-   Book or cancel appointments on behalf of patients
-   Comprehensive dashboard for tracking system performance

## Tech Stack

### Frontend

-   **ReactJs** - UI Development
-   **Tailwind CSS** - Styling
-   **React Router** - Navigation
-   **Axios** - API calls

### Backend

-   **NodeJS** - Backend server
-   **ExpressJS** - REST API framework
-   **MongoDB** - Database for storing user and appointment data
-   **Cloudinary** - Image storage for doctor profiles
-   **JWT** - Authentication & security

### Admin Panel

-   **ReactJS** - UI for admin functionalities
-   **ExpressJS** - Backend support
-   **MongoDB** - Database management

## Installation

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Setup Instructions

1.  Clone the repository:
    
    ```
    git clone https://github.com/inosgungun/docPoint.git
    cd docpoint
    ```
    
2.  Install dependencies for frontend:
    
    ```
    cd frontend
    npm install
    npm run dev
    ```
    
3.  Install dependencies for backend:
    
    ```
    cd backend
    npm install
    npm start
    ```
    
4.  Setup environment variables:
    
    -   Create a `.env` file in the backend directory with the following keys:
        
        ```
        MONGO_URI=your-mongodb-uri
        JWT_SECRET=your-secret-key
        CLOUDINARY_CLOUD_NAME=your-cloudinary-name
        CLOUDINARY_API_KEY=your-cloudinary-api-key
        CLOUDINARY_API_SECRET=your-cloudinary-api-secret
        ```


## Usage

1.  Navigate to the frontend at `http://localhost:3000`.
    
2.  Sign up or log in as a patient to book an appointment.
    
3.  Access the admin panel to manage appointments and users.

## Contact

For further info email at :- gungunbps2018@gmail.com



```
