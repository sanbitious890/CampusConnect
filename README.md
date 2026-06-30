# CampusConnect

A full-stack web application for college students to manage daily campus activities in one place.

**Live Demo:** https://campusconnect-cf4ef.web.app

---

## Why I Built This

I noticed college students use multiple apps for different things - WhatsApp for clubs, Google Calendar for events, physical notice boards for lost items. I wanted to create one platform where everything comes together in one place.

---

## Features

- **Authentication** - Sign up and login with email and password using Firebase Auth
- **Lost & Found** - Report lost items or check if someone found your stuff
- **Events** - Create and view campus events with date and location
- **Club Registration** - Register for clubs and see all active clubs
- **Notes Sharing** - Share notes with other students
- **Dashboard** - See all your activity with real-time statistics
- **Dark/Light Mode** - Toggle between themes (saved in browser)
- **Search & Filter** - Find lost items by category or search term
- **Responsive Design** - Works on phone, tablet, and desktop

---

## Tech Stack

### Frontend
- HTML5
- CSS3 (Glassmorphism design)
- Vanilla JavaScript (no frameworks)

### Backend & Database
- Firebase Authentication (Email/Password)
- Firebase Firestore (Real-time NoSQL database)

### Deployment
- Firebase Hosting

---

## Project Structure

```
CampusConnect/
│
├── index.html          # Main application (all code in one file)
├── README.md           # Project documentation
├── firebase.json       # Firebase hosting configuration
├── .firebaserc         # Firebase project settings
├── .gitignore          # Git ignore rules

```

---

## Installation & Setup

### Prerequisites
- Node.js installed on your computer
- Firebase account (free)

### Steps

1. Clone the repository
```bash
git clone https://github.com/sanbitious890/CampusConnect.git
```

2. Go to the project folder
```bash
cd CampusConnect
```

3. Open in VS Code (optional)
```bash
code .
```

4. Create a Firebase project
   - Go to https://console.firebase.google.com
   - Click "Add project"
   - Name it "CampusConnect"
   - Enable Authentication (Email/Password)
   - Create Firestore Database (start in test mode)

5. Get your Firebase config
   - Go to Project Settings
   - Scroll to "Your apps"
   - Click the web icon (</>)
   - Copy the firebaseConfig object

6. Replace Firebase config in `index.html`
   - Open index.html
   - Find the firebaseConfig object
   - Replace with your own config

7. Install Firebase CLI
```bash
npm install -g firebase-tools
```

8. Login to Firebase
```bash
firebase login
```

9. Deploy to Firebase Hosting
```bash
firebase deploy
```

10. Your app is live!
    - Go to: https://YOUR_PROJECT.web.app

---

## How It Works

1. User signs up with name, email, and password
2. User logs in with email and password
3. Dashboard shows statistics of all activities
4. Lost & Found - Report an item or search for lost items
5. Events - Create events or view existing ones
6. Clubs - Register a club or view registered clubs
7. Notes - Share notes or view shared notes
8. All data is saved in Firebase Firestore
9. Profile - View profile and logout
10. Settings - Toggle dark/light mode or delete account

---

## Challenges I Faced

- **Firebase Authentication** - Managing user sessions and handling errors properly
- **Real-time Data** - Structuring data in Firestore and performing CRUD operations
- **Responsive Design** - Making glassmorphism UI work on all screen sizes
- **State Management** - Managing application state without any framework

**How I solved them:** Read Firebase documentation, practiced with small examples, refactored code multiple times. Broke down each feature into small, testable pieces.

---

## What I Learned

- Building a complete full-stack web application from scratch
- Integrating Firebase Authentication and Firestore
- Handling user sessions and protected routes
- Creating responsive UI with CSS Grid and Flexbox
- Implementing dark/light mode with localStorage persistence
- Deploying to production with Firebase Hosting
- Using Git and GitHub for version control
- Debugging and problem-solving in JavaScript

---

## Future Improvements

- **Chat Feature** - Real-time messaging between students
- **Push Notifications** - Notify users about new events or lost items
- **Image Upload** - Upload images for lost items and events
- **Timetable** - Full timetable management with class schedule reminders
- **Admin Panel** - Admin dashboard to manage all users and content
- **Password Reset** - Forgot password functionality
- **Email Verification** - Verify email addresses during signup

---


## License

This project is for learning and portfolio purposes.

---

## Author

**Saniya Lochan**

GitHub: [sanbitious890](https://github.com/sanbitious890)


---

## **Push to GitHub:**

```bash
git add README.md
git commit -m "Add complete README with all sections"
git push
```

---