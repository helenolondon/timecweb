# TimerWeb - Calendar Application

A full-stack calendar application built with Angular 19, FullCalendar, Node.js, Express, and SQLite.

## Features

- Weekly calendar view with 15-minute time slots
- Right-click on any time slot to create a new appointment
- Appointment fields: Description, Start Time, End Time, Jira Number
- Local SQLite database for data persistence
- RESTful API for CRUD operations

## Prerequisites

- Node.js (v18 or higher)
- npm or yarn

## Installation

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Start the backend server:
```bash
npm start
```

The backend will run on `http://localhost:3000`

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the Angular development server:
```bash
npm start
```

The frontend will run on `http://localhost:4200`

## Usage

1. Make sure both backend and frontend servers are running
2. Open `http://localhost:4200` in your browser
3. Right-click on any time slot in the weekly calendar view
4. Fill in the appointment details in the modal
5. Click "Create" to save the appointment
6. Click on an existing appointment to delete it

## API Endpoints

- `GET /api/appointments` - Get all appointments
- `GET /api/appointments/:id` - Get a specific appointment
- `POST /api/appointments` - Create a new appointment
- `PUT /api/appointments/:id` - Update an appointment
- `DELETE /api/appointments/:id` - Delete an appointment

## Database

The application uses SQLite for local data storage. The database file (`calendar.db`) will be created automatically in the backend directory when the server starts.

## Tech Stack

- **Frontend**: Angular 19, FullCalendar, TypeScript
- **Backend**: Node.js, Express
- **Database**: SQLite
"# timecweb" 
