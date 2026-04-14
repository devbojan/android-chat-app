# Android Chat Application

## 🚀 Author
Bojan Brankovic 

## Project Overview
This project is a real-time Android chat application designed to demonstrate core messaging functionalities, user interaction, and mobile app behavior under different scenarios.

The application simulates a typical messaging system with focus on usability, responsiveness, and real-time communication.

## Features
- User authentication (login/register)
- Real-time messaging
- One-to-one chat functionality
- Message sending and receiving
- Basic UI for chat interface
- User session handling

Modern chat apps typically rely on real-time communication and backend services (e.g. Firebase, sockets), enabling instant message delivery and user interaction. :contentReference[oaicite:0]{index=0}

## Tech Stack
- Java / Kotlin (Android)
- Android SDK
- Firebase / Real-time database (if applicable)
- Android Studio

## Scope of Testing
- Login & authentication flow
- Sending and receiving messages
- Message delivery behavior
- UI responsiveness
- Session handling (login/logout)

## Tools Used
- Manual Testing
- Android Emulator / Real Device
- Logcat (debugging)
- Postman (if API is used)

## Testing Types
- Functional Testing
- UI/UX Testing
- Exploratory Testing
- Regression Testing

## Deliverables
- Test Cases
- Bug Reports
- Test Execution Report

## Key Issues Identified
- Message not delivered in real-time under certain conditions
- UI breaks on smaller screen sizes
- Session not properly invalidated after logout
- Delayed message synchronization

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/devbojan/android-chat-app.git
