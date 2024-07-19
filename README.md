This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# CarePeak: Healthcare Management System

CarePeak is a comprehensive healthcare management system built with Next.js, Shadcn UI, Appwrite, and Twilio. It streamlines patient registration, appointment scheduling, and administrative tasks.

## Features

- Patient registration and management
- Appointment scheduling and cancellation
- Admin dashboard for managing appointments
- SMS notifications via Twilio
- Form validation using Zod
- Responsive UI with Shadcn UI components

## Tech Stack

- [Next.js]- React framework for building web applications
- [Shadcn UI]- Customizable UI components
- [Appwrite]- Backend server for authentication and database
- [Twilio]- SMS notifications for appointments
- [Zod]- TypeScript-first schema validation

## Getting Started

1. Clone the repository:

```bash
https://github.com/pravee1701/carepeak.git
```
2. Install dependencies:
```bash
cd carePeak
npm install
```
3. Set up environment variables:
Create a `.env.local` file in the root directory and add the following:
```bash
PROJECT_ID="your-project-id"
API_KEY="your-api-key"
DATABASE_ID="your-db-id"
PATIENT_COLLECTION_ID="your-patient-collection-id"
DOCTOR_COLLECTION_ID="your-docor-collection-id"
APPOINTMENT_COLLECTION_ID="your-appointment-collection-id"
NEXT_PUBLIC_BUCKET_ID="your-public-bucket-id"
NEXT_PUBLIC_ENDPOINT="your-cloud-endpoint"
NEXT_PUBLIC_ADMIN_PASSKEY="admin-passkey"
```
4. Run the development server:
```bash
npm run dev
```
5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.


## Key Features

### Patient Registration
- Patients can create accounts and manage their profiles
- Form validation ensures accurate data entry

### Appointment Scheduling
- Patients can view available time slots and book appointments
- Admins can manage the appointment calendar

### Admin Dashboard
- View and manage all appointments
- Cancel appointments with reason logging
- Access patient information

### Notifications
- SMS notifications for appointment confirmations, reminders, and cancellations

## Deployment

1. Choose a hosting platform (e.g., Vercel, Netlify)
2. Connect your GitHub repository
3. Set up environment variables in the hosting platform
4. Deploy the application

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request