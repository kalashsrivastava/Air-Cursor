# ✨ Air Cursor – Touchless Computer Control System

🎥 **Demo Video:** [Watch on Google Drive](https://drive.google.com/file/d/1nd8-mcqYRFy_v36XESFARpgyYR0SR4zR/view?usp=sharing)  
> ⚠️ _Due to backend system-level integrations (voice, gesture, and desktop control), this project is not deployable on free hosting platforms like Vercel, Netlify, or Render. Please refer to the video for full functionality._

---

## 🧠 About the Project

**Air Cursor** is a smart desktop assistant that enables users to control their computer using **voice commands** and **hand gestures**, eliminating the need for a keyboard or mouse. Designed for hands-free environments (e.g., medical, accessibility, or futuristic UI), it brings together AI, CV, and system automation in a single touchless interface.

---

## 🚀 Features

- 🎙️ **Voice-Controlled Assistant (Aura)** – Built with OpenAI's GPT API
- ✋ **Real-time Hand Gesture Recognition** – Controls mouse, scroll, volume, brightness, etc.
- ⚡ **Desktop Automation** – System-level actions like app launching and file navigation
- 🖼️ **Custom UI** – Lightweight frontend built with HTML/CSS/JS via Eel

---

## 🗂️ Project Structure

Air-Cursor/<br/>
│<br/>
├── web/ # Frontend files (HTML/CSS/JS)<br/>
├── Aura.py # Voice assistant (GPT + SpeechRecognition)<br/>
├── Gesture_Controller.py # Hand tracking and gesture-based control<br/>
├── app.py # Main entry point to run the system<br/>
├── .gitignore<br/>

---

## 🧰 Tech Stack

**Core Technologies:**  
Python, OpenAI GPT API, MediaPipe, OpenCV, PyAutoGUI, SpeechRecognition, Eel (for Python-JS UI)

---

## 🛠️ How It Works

1. **Run `app.py`** to launch the assistant interface.
2. `Aura.py` handles voice input, interprets the intent using GPT, and triggers actions.
3. `Gesture_Controller.py` uses webcam input to track hand gestures and control system UI.
4. `web/` holds the frontend served using Eel, allowing a unified experience.

---

## 📌 Limitations

- ❌ Not deployable on cloud/web platforms due to system-level integrations.
- ✅ Fully functional when run locally with access to hardware (microphone, webcam).

