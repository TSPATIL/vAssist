# vAssist - Vehicle Breakdown System

Welcome to the Vehicle Breakdown System repository! This system is designed to help users, administrators, and mechanics efficiently manage vehicle breakdown situations. It incorporates various features to streamline the process and provide a seamless experience for all stakeholders.

## Features

### 1. User Types
The system supports three user types:

- **User:** Can request assistance for vehicle breakdowns, track appointments, and make payments.
- **Admin:** Manages user requests, validates mechanics, and oversees the overall system.
- **Mechanic:** Receives and fulfills service requests, updates appointment status, and provides assistance.

### 2. Map Integration (React-Leaflet)
The system utilizes the React-Leaflet library to integrate interactive maps. This enables users to pinpoint their location during breakdowns, making it easier for mechanics to reach them quickly.

### 3. Nodemailer Contact Form
Contact forms are crucial for user communication. Nodemailer is used to implement an email contact form, allowing users to get in touch with administrators and mechanics easily.

### 4. Razorpay Payment Integration
To facilitate seamless transactions, Razorpay is integrated into the system. Users can make payments securely for the services rendered.

### 5. Appointment Tracking
Users and mechanics can track appointment details, including scheduled times, service types, and location information. This ensures transparency and efficient scheduling.

### 6. Mechanic Validation
Admins validate and manage mechanic profiles to ensure a qualified and trustworthy pool of service providers. Mechanic validation enhances user confidence in the system.

## Getting Started

To get started with the Vehicle Breakdown System, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vehicle-breakdown-system.git

2. Install dependencies:

cd vehicle-breakdown-system
npm install
cd backend
npm install
Set up the environment variables for API keys, email configuration, and other sensitive information.

3. Install mongodb and mongodb compass in your computer.

4. login to razorpay and generate test api key for development phase

5. in .env add port, razorpay key id and secret, jwt-secret string.

6. in contact.js in backend/route fill appropriate details for nodemailer

7. Run the application:
   
cd .. (in vehicle-breakdown-system folder)
npm run both

8. Visit the following URLs in your browser:

User Interface: http://localhost:3000
Admin Dashboard: http://localhost:3000/admin
Mechanic Dashboard: http://localhost:3000/mechanic

9. Feel free to explore the system and provide feedback and suggest your features/ideas to its development.

Project made by
Tanmay Patil
