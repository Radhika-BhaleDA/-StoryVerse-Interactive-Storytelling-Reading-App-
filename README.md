 📚 StoryVerse – Interactive Storytelling & Reading App  
 *Built using HTML, CSS, JavaScript + MockAPI.io + WebIntoApp

StoryVerse is a fully interactive storytelling and reading web app designed to give users a fun, animated, and immersive reading experience.  
The project is created using **HTML, CSS, and JavaScript**, and later converted into an Android application using **WebIntoApp**.

The app includes **genre selection, story browsing, pagination, voice narration, animations, user login system, and API-based story loading**.

---

🌟 Features

🔐 1. User Authentication**
- Registration & Login created with pure JavaScript  
- Stores user data using browser `localStorage`  
- Animated login/register UI

📚 2. Interactive Story Library**
- Categories:
  - 🌟 Magic Tales  
  - 👻 Ghost Stories  
  - 🧠 Sci-Fi World  
  - ❤️ Romantic Reads  
  - 🦸‍♂️ Hero Saga  
  - 🕵️‍♀️ Mystery Files  
  - 🐉 Dragon Legends  
- Click a category to view stories from MockAPI  
- Search bar to find stories instantly

📝 3. Story Reader**
- Page-by-page reader (automatic pagination from paragraphs)  
- Story header + title  
- Background theme and smooth animation  
- Works on both app and web

 🔊 4. Text-to-Speech Narration**
- Reads the story aloud  
- Supports pause, stop, and resume  
- Auto goes sentence-by-sentence

🎨 5. Animated UI & Floating Characters**
Includes:
- ⭐ Magic star  
- ❤️ Heart  
- 👻 Ghost  
- 🌙 Moon  
- 🎩 Magic hat  
- 📖 Flying book  
- 🐇 Rabbit  
- 🐦 Realistic bird  
- 📷 Camera  

All moving across the screen using CSS animations.

---

 🌐 6. API Data Using MockAPI.io
 https://68b84911b71540504327be04.mockapi.io/api/v1/stories

 
Each story follows this structure:

json
{
  "id": "1",
  "category": "🌟 Magic Tales",
  "title": "The Enchanted Lantern",
  "content": "Story content goes here...",
  "publishedOn": "2025-01-12"
}

📱 7. Converted Into Android App
Using WebIntoApp.com, the website was compiled into a mobile app with:
App name: StoryVerse
Splash screen
Offline support
WebView integration
This makes StoryVerse run like a native Android reader app.

🛠️ Technologies Used
Component	                                        Technology
Frontend	                                   HTML, CSS, JavaScript
Animations	                                 CSS keyframes, SVG floating elements
API Backend  	                               MockAPI.io (REST API + JSON)
TTS	                                         Web Speech API
App Build	                                   WebIntoApp
Storage	                                     localStorage  

📂 Project Structure
StoryVerse/
│── index.html         # Main UI, login, library, story reader
│── project.css        # Full animations, floating characters, layout
│── project.js         # Logic: login, API fetch, pagination, TTS
│── stories.json       # Sample stories (MockAPI export)
│── README.md

🚀 How It Works
User logs in or registers
User enters the Story Library
Selects a genre or uses search
App fetches story data from MockAPI.io
User selects a story → opens reader
Story is split into pages automatically
User can:
read,
move between pages,
or enable voice narration

🎯 Purpose of This Project
This app demonstrates:
Building an interactive UI purely in web technologies
Using MockAPI to simulate backend stories
Converting a website into an installable Android app
Implementing voice narration using browser TTS
Creating animated visual experiences without any framework

Screenshots / Demos Show what the dashboard looks like[dashboard preview](
<img width="1856" height="881" alt="login interface" src="https://github.com/user-attachments/assets/9a0418b9-4b5e-40b8-9b73-654a2920b97d" />
<img width="1825" height="888" alt="genres" src="https://github.com/user-attachments/assets/60a17278-672f-442a-827d-d88a65f68987" />
<img width="1843" height="886" alt="story choices" src="https://github.com/user-attachments/assets/3809d8d1-ae92-43bc-9883-a5a964f83385" />
<img width="1843" height="883" alt="story page" src="https://github.com/user-attachments/assets/a6ed681e-58ea-4fcc-aa0a-0ae71ff2a89c" />





Stories are fetched from a custom MockAPI endpoint:

