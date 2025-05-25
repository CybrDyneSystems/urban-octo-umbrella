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
