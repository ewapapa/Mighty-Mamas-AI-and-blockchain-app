# Mighty Mamas
Mighty Mamas App – Empowering Women Through Work, Training & Technology

Mighty Mamas is a Flutter-based mobile app designed to transform the lives of single mothers and widows in Sierra Leone by connecting them to domestic work opportunities and empowering them through training, financial literacy, and technology.


---

Key Features

Domestic Job Marketplace: Clients can easily book reliable "Mamas" for services like:

Cleaning

Laundry

Cooking

Babysitting

Elderly care

Errands and market runs

Home tutoring (basic literacy)

Housekeeping


AI Integration:

Smart rating system based on client feedback

Calculates total work hours and performance

Determines loan eligibility after graduation


Training Portal:

Admin uploads free or subsidized training courses

Mamas can apply, track progress, and graduate


Blockchain Integration:

All savings and earnings are recorded securely

Bitcoin-based loan eligibility via smart contracts

Transparent and tamper-proof system for financial tracking


SMS Notifications via Twilio:

Keeps users updated even with limited internet access




---

Tech Stack

Frontend: Flutter (Android-focused)

Backend: Node.js/Express with Twilio and Blockchain APIs

Database: PostgreSQL

Blockchain: Bitcoin-compatible smart contract system

AI: Feedback-based scoring and loan calculator

Hosting: Replit (demo), GitHub for source control
A web platform connecting women in Sierra Leone with domestic work opportunities, featuring service listings, job tracking, and performance analysis.

![Mighty Mamas Logo](client/src/assets/mighty-mamas-logo.jpg)

## Project Overview

Mighty Mamas is a platform designed to connect skilled and semi-skilled women in Sierra Leone with domestic work opportunities. The application tracks work performance, supports SMS notifications via Twilio, and provides training and upskilling features.

### Features

- User authentication with different roles (client, service provider, admin)
- Service listings with search functionality
- Booking management system
- SMS notifications for booking confirmations and updates
- Service provider profiles with ratings and reviews
- Earnings tracking and performance analytics
- Training and upskilling modules

## Technology Stack

- **Frontend**: React, TypeScript, TailwindCSS, shadcn/ui
- **Backend**: Express.js, Node.js
- **Database**: PostgreSQL with Drizzle ORM
- **SMS Integration**: Twilio
- **Hosting**: Replit

## Development

### Prerequisites

- Node.js 18+ 
- PostgreSQL database
- Twilio account (for SMS functionality)

### Environment Variables

```
DATABASE_URL=postgresql://...
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mighty-mamas.git
   cd mighty-mamas
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the database:
   ```bash
   npm run db:push
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

### Building for Production

```bash
npm run build
```

## Mobile App Conversion

To convert this web application to a mobile app:

1. Install Capacitor:
   ```bash
   npm install @capacitor/core @capacitor/cli
   npx cap init
   ```

2. Add Android platform:
   ```bash
   npm install @capacitor/android
   npx cap add android
   ```

3. Build the web app:
   ```bash
   npm run build
   ```

4. Copy web assets to native project:
   ```bash
   npx cap copy
   ```

5. Open in Android Studio:
   ```bash
   npx cap open android
   ```

## Creating an APK

1. Open the Android project in Android Studio
2. Select Build > Build Bundle(s) / APK(s) > Build APK(s)
3. The APK will be generated in the project's android/app/build/outputs/apk/debug/ directory

## License

This project is private and proprietary.
