![React](https://img.shields.io/badge/Built_with-React-61DAFB?logo=react&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Styled_with-TailwindCSS-38B2AC?logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28?logo=firebase&logoColor=black)
![Twilio](https://img.shields.io/badge/SMS_Tool-Twilio-F22F46?logo=twilio&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

# Repair Tracker App

This app allows a repair shop to manage multiple repair tickets, assign multiple technicians, and provide customers with live ticket tracking.

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Replace Firebase config in `src/firebase.js`

3. Start development server:
```bash
npm start
```

4. To build for production:
```bash
npm run build
```

5. For Firebase Hosting:
```bash
npm install -g firebase-tools
firebase login
firebase init
npm run build
firebase deploy
```
