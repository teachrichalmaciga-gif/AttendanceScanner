# Attendance Scanner

A simple web application for scanning attendance using QR codes, deployed via Firebase Hosting.

## Features
- QR code scanning interface (simulation)
- Automatic deployment to Firebase Hosting via GitHub Actions

## Deployment
This project is configured to automatically deploy to Firebase Hosting on every push to the `main` branch.

### Prerequisites
- Firebase project
- `FIREBASE_SERVICE_ACCOUNT_ATTENDANCE_SCANNER_EE0F4` secret added to GitHub repository.

## Local Development
To view the application locally, you can use any static file server:
```bash
npx serve public
```
