# Moodokka ✨

Moodokka is an aesthetic, privacy-focused mood diary application designed to provide a secure and expressive space for tracking daily emotions. Built with the MERN stack and featuring a playful "Quokka-inspired" UI, it combines modern full-stack development with a high-contrast, "aesthetic scrapbook" design.

---

<p align="center">
  <img src="/client/public/images/dashboard.png" width="48%" />
  <img src="/client/public/images/moodwheel.png" width="48%" />
</p>

<p align="center">
  <img src="/client/public/images/moodokka.gif" width="700" />
</p>

## 🎨 Key Features

- **Interactive Mood Wheel**  
  A physics-based spinning wheel for selecting your daily mood with smooth animations.

- **Aesthetic Diary Editor**  
  A custom-designed, translucent editor that supports titles, mood descriptions, and handwritten-style typography.

- **Secure Authentication**  
  User sign-up and login powered by Firebase and JWT (JSON Web Tokens) to ensure entry privacy.

- **Mood Analytics**  
  Visualized tracking of emotional trends over time.

- **Cloud Image Storage**  
  Ability to add and delete images within your memories via Cloudinary.

- **Dynamic Dashboard**  
  A clean grid layout displaying recent memories with a floating "toggle" button that integrates the Mood Wheel seamlessly.

---

## 🛠️ Tech Stack

**Frontend:** React.js, Vite, CSS Modules  
**Backend:** Node.js, Express.js  
**Database:** MongoDB (MERN architecture)  
**Security & Auth:** Firebase Authentication, JWT  
**Cloud Storage:** Cloudinary (for image uploads)

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16+) and npm installed  
- A MongoDB Atlas account and connection string  
- Firebase and Cloudinary API credentials  

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ankita-kuntal/moodokka.git
cd moodokka

```

### 2. Backend Setup
Navigate to the server directory:

```bash
cd server
```

Create a .env file based on the server/.env.example file and add:
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_URL=your_cloudinary_url
FIREBASE_API_KEY=your_firebase_key
```
Install dependencies and start the server:
```bash
npm install
npm run dev
```
### 3. Frontend Setup
1. Navigate to the client directory.
2. Install dependencies:
```bash
npm install
```
3. Start the development server:
```bash
npm run dev
```
## 📂 Project Structure
```bash
client/src/components/   # Core UI elements like MoodWheel, Card, Header
client/src/pages/        # Main application views (Home, Login, AllEntries)

server/controllers/      # Backend logic for diary management & auth
server/models/           # MongoDB schemas (Diary, User)
server/routes/           # API endpoints
```
