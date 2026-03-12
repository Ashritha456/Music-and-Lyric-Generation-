
 🎵 Music and Lyric Generation System

A Generative AI based web application that automatically generates **song lyrics and music** from user prompts.  
This system uses **OpenAI models for lyric generation** and **Meta MusicGen models for music generation**.

Users can enter a **song title and emotion**, generate lyrics, and then generate **AI-based music from the lyrics or custom prompts**.

---

🚀 Features

- 🎤 AI-based **lyrics generation**
- 🎼 **Music generation** using AI models
- 📝 Generate lyrics from **song title and emotion**
- 🎧 Generate **music using lyrics context**
- 🎹 Generate **music using custom prompts**
- 🔐 **User authentication** (Signup / Login)
- 💾 View previously generated music
- 📥 Download generated music parts

---

 🏗️ Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- Sequelize ORM

### Database
- PostgreSQL

### AI Models
- OpenAI API – Lyrics generation
- Meta MusicGen – Music generation

---

## 📁 Project Structure

Music-and-Lyric-Generation
│
├── harmony/ # React Frontend
│
├── harmonyBackend/ # Node.js Backend
│
├── package-lock.json
│
└── README.md


⚙️ Installation

 1️⃣ Install Node.js

Download and install Node.js from:

https://nodejs.org

Verify installation:

```bash
node -v
````

---

2️⃣ Install PostgreSQL

Download PostgreSQL and install it.

During installation:

* Set database username
* Set password
* Keep the default port


 🔧 Setup the Project

Clone the repository:

```bash
git clone https://github.com/Ashritha456/Music-and-Lyric-Generation.git
```

```bash
cd Music-and-Lyric-Generation
```

---

## 📦 Install Dependencies

### Install Frontend Packages

```bash
cd harmony
npm install
```

### Install Backend Packages

```bash
cd harmonyBackend
npm install
```

---

🗄️ Database Setup

Inside the **harmonyBackend** directory run:

```bash
npx sequelize-cli db:drop
```

```bash
npx sequelize-cli db:create
```

```bash
npx sequelize-cli db:migrate
```

This will create and migrate the PostgreSQL database.

 🔑 API Keys Setup

 OpenAI API Key

Create an API key from:

[https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)

Add the key inside the **backend configuration file**.



 MusicGen API Token

Create token from:

[https://huggingface.co/facebook/musicgen-small](https://huggingface.co/facebook/musicgen-small)

Add the token inside the **LyricsGenerator file in frontend**.


## ▶️ Run the Application

### Start Backend Server

```bash
cd harmonyBackend
npm run dev
```

Backend runs at:

```
http://localhost:3000
```

---

### Start Frontend Application

```bash
cd harmony
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 🎮 How to Use the Application

1️⃣ Signup and create an account

2️⃣ Login to the system

3️⃣ Enter

* Song title
* Emotion

4️⃣ Click **Generate Lyrics**

5️⃣ Choose one option

* Generate music from lyrics
* Generate custom music

6️⃣ Download generated music

---

## 📊 System Workflow

User Input
⬇
Lyrics Generation (OpenAI API)
⬇
Music Generation (MusicGen AI)
⬇
Download Music

---
 👩‍💻 Author

**Ashritha Kotagiri**

Master’s in Data Science
University of North Florida



