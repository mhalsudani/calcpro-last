# CalcPro - Advanced File Manager

## Overview
CalcPro is an intelligent file management platform disguised as a calculator, featuring advanced security, cloud storage, and bilingual support.

## Key Features

### Security
- 4-digit PIN authentication system
- Security questions for PIN recovery
- Data encryption and secure sessions

### User Interface
- Mobile-first responsive design
- Arabic and English language support
- Intuitive emoji-based navigation
- Clean calculator interface for privacy

### Storage Options
- **Free Version**: Local storage with 50MB limit
- **Premium Version**: Unlimited cloud storage
- Automatic file synchronization
- Offline functionality with sync on reconnect

### File Management
- Automatic organization: 📸 Images, 🎥 Videos, 📄 Documents
- Smart file compression
- Instant file preview
- Download and sharing capabilities

## Technology Stack

### Frontend
- React 18 with TypeScript
- Tailwind CSS for styling
- Radix UI components
- React Query for data management
- Wouter for routing

### Backend
- Node.js with Express
- PostgreSQL database
- Drizzle ORM
- Stripe for payments

### Storage
- PostgreSQL for cloud storage
- IndexedDB for local storage
- Smart synchronization system

## Usage

### Access
1. Open the application (appears as calculator)
2. Enter 4-digit PIN
3. Press "=" to access files

### Default PINs
- `1234`: Premium version (unlimited cloud storage)
- `7360`: Free version (50MB local storage)

### Create New PIN
1. Enter new 4-digit PIN
2. Choose security question and answer
3. Press "Create PIN"

### PIN Recovery
1. Click "Forgot PIN?"
2. Select same security question
3. Enter correct answer

## Project Structure
