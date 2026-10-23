# Employee Management System

## Overview

The Employee Management System is a web application developed as a group project by **Team Falcon at Sri Lanka Technological Campus (SLTC)**. It is designed to simplify employee administration by providing a centralized platform for managing employee records, leave requests, projects, timesheets, and payroll-related operations.

The application features role-based access for administrators and employees, allowing each user to access the functions relevant to their responsibilities. Built with React.js and a .NET Core Web API, the system provides an organized and efficient approach to employee and workplace management.

### Website

[Employee Management System](https://loquacious-cucurucho-cb7e57.netlify.app/)

## Features

- **User Authentication:** Separate login access and privileges for administrators and employees.
- **Employee Management:** Maintain employee records, personal information, departments, and organizational details.
- **Leave Management:** Submit, review, and manage employee leave requests.
- **Project Management:** Organize and manage company projects and related tasks.
- **Task Management:** Allow employees to view and manage their assigned tasks.
- **Timesheet Management:** Record and review employee working hours and timesheet logs.
- **Employee Contact Directory:** Access employee contact details and communication information.
- **Role-Based Access:** Provide different features and permissions according to user roles.
- **Centralized Management:** Bring essential employee administration functions together in one application.

## Technologies Used

- **Frontend:** React.js, JavaScript, HTML5, CSS3
- **Backend:** .NET Core 3.1 Web API
- **Database:** Microsoft SQL Server
- **Development Tools:** Visual Studio Code
- **Build Tool:** Vite
- **Version Control:** Git & GitHub
- **Deployment:** Netlify (frontend)

## System Requirements

- Node.js and npm
- A modern web browser
- Visual Studio Code or another code editor
- Access to the backend API
- Microsoft SQL Server for the backend database
- .NET Core 3.1 SDK/runtime and compatible backend configuration, if running the backend locally

## Installation & Setup

### 1. Clone the Frontend Repository

```bash
git clone <your-frontend-repository-url>
cd <your-frontend-folder>
```

### 2. Install Dependencies

```bash
npm install
```

If dependency installation fails, review the error messages and project compatibility. Options such as `npm install --legacy-peer-deps` may help with peer dependency conflicts, but should only be used when appropriate.

### 3. Configure the Backend API

The frontend requires the backend API to retrieve and manage employee information.

Open `variables.jsx` and configure the API URL to point to the appropriate hosted API or your local backend, following the existing project configuration.

If using a local API, start the backend service before using the frontend.

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Open the Application

Open the local URL displayed in your terminal after the development server starts. Vite commonly uses:

```text
http://localhost:5173/
```

The exact port may vary depending on your configuration.

## Usage

1. Open the application in your browser.
2. Log in using an account configured for the system.
3. Access the available features according to your user role.

**Administrator functions:**
- Manage employee records.
- Review and manage leave requests.
- Manage projects and tasks.
- Review timesheet logs.
- Access employee contact information.

**Employee functions:**
- View assigned tasks.
- Manage personal timesheets.
- Submit leave requests.
- Access employee contact information.

## Backend API

The frontend communicates with a separate backend API built using .NET Core 3.1.

- **Backend Repository:** [Falcons Employee Management Web API](https://github.com/NdaAZ/Falcons_employee_mangement_web_api)

The backend must be accessible and correctly configured for API-dependent features to work.

## Contributing

As a group project, improvements and suggestions can help enhance the application.

1. Fork the repository or create your own development branch.
2. Create a branch for your changes:

   ```bash
   git checkout -b feature-name
   ```

3. Implement and test your changes.
4. Commit your work:

   ```bash
   git add .
   git commit -m "Improve employee management"
   ```

5. Push your branch and submit a Pull Request.

## License

Refer to the original repository for its license and redistribution requirements. Preserve the original project's license and team attribution when reusing or adapting the code.

## Contact
For any inquiries or feedback, please contact us at:
- **Email:** erandidahanayaka@gmail.com
- **GitHub** https://github.com/UppalaD
