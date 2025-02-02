# Barbershop Scheduling System

## Description

A complete solution for scheduling appointments in barbershops, integrating a web interface, a robust API, and a mobile application. It allows online appointment booking, service management, and mobile access.

## Features

- **Online Scheduling:** Real-time appointment booking.
- **Service and Staff Management:** Registration and control of services and professionals.
- **Mobile Integration:** An app for checking and managing appointments.

## Technologies

- **Turborepo:** Monorepo management for organizing modules (web, API, and mobile).
- **Next.js:** Responsive web interface.
- **NestJS:** Scalable and modular API.
- **React Native:** Native mobile application.
- **Prisma ORM:** Database management and migrations.

## Prerequisites

- Node.js (LTS version)
- npm or yarn
- React Native environment (Android Studio/Xcode)

## Installation and Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/brutal_beard.git
   cd brutal_beard
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Database Setup:**

   - Update the `.env` file with your credentials.
   - Run Prisma migrations:

     ```bash
     npx prisma migrate dev
     ```

4. **Running the Application:**

   - **API (NestJS):**

     ```bash
     cd apps/backend
     npm run start:dev
     ```

   - **Frontend (Next.js):**

     ```bash
     cd apps/frontend
     npm run dev
     ```

   - **Mobile (React Native):**

     ```bash
     cd apps/mobile
     npx react-native run-android  # for Android
     npx react-native run-ios      # for iOS
     ```

## Contribution

Contributions are welcome. To contribute:

1. Fork the project.
2. Create a branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes.
4. Push your branch (`git push origin feature/your-feature-name`) and open a Pull Request.

## Contact

For questions or suggestions, contact: [matvno@gmail.com](mailto:matvno@gmail.com)

---