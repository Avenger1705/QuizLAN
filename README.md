# QuizLAN 2.0 🧠📡✨

**The ultimate local multiplayer quiz platform, now better than ever.**

Original Repo : 
https://github.com/Avenger1705/QuizLAN

A fast, lightweight, Kahoot-style quiz system designed to run entirely on your local network (LAN/Wi-Fi).
Includes a full Teacher interface and Student interface, real-time updates, and PIN-based game sessions.

## 🚀 What's New in v2.1?

We've enhanced the platform with privacy-focused features and a refined user experience:

*   **🔒 Local QR Code Generation**: QR codes are now generated locally on your server using Python, eliminating dependency on external APIs for better privacy and offline support.
*   **� Enforced Dark Mode**: Beautiful dark theme across all pages for reduced eye strain and a modern look.
*   **☀️ Smart Light Mode**: QR code and PIN section uses light mode for optimal scanning and readability.
*   **💎 Premium PIN Display**: Elevated card design with shadows and smooth animations for a polished look.
*   **✨ Enhanced Copy Feedback**: Bright green "COPIED!" message with stable box sizing when copying the game PIN.
*   **📱 Larger QR Codes**: Increased QR code size (110px) for easier scanning from mobile devices.
*   **🎨 UI Polish**: Removed theme toggles, refined spacing, and improved visual consistency.

### Previous Updates (v2.0)

*   **🌗 Dark & Light Themes**: Toggle between sleek dark mode and clean light mode.
*   **✅ True or False Questions**: Binary choice question type for quick assessments.
*   **⏱️ Custom Timers**: Set specific time limits for each slide.
*   **🏠 New Landing Page**: Beautiful central hub for teachers and students.
*   **🛠️ Reliability Fixes**: Improved answer submission accuracy.

---

## ✨ Core Features

### 👩‍🏫 Teacher Interface
*   **Create & Customize**: Build quizzes with multiple question types and custom timers.
*   **Live Game Management**: Start sessions, control slides, and skip questions on the fly.
*   **Real-Time Monitoring**: See student connections and responses as they happen.
*   **QR Code Sharing**: Automatically generated QR codes for easy student access.
*   **History**: Automatically saves quiz sessions for future review.

### 👨‍🎓 Student Interface
*   **Easy Join**: Enter a PIN code or scan QR code to join instantly.
*   **Instant Feedback**: Clean, responsive answering interface with immediate visual confirmation.
*   **Personalized**: Choose from 20 fun avatars to represent yourself on the leaderboard.

### 🌐 Local Network Support
*   **100% Offline**: No internet required. Runs entirely on your classroom or home Wi-Fi.
*   **Privacy First**: All data stays on your machine. QR codes generated locally.
*   **No External Dependencies**: No reliance on third-party APIs.

---

## 🧱 Tech Stack
*   **Backend**: Python, Flask
*   **Frontend**: HTML, CSS (Vanilla + CSS Variables), JavaScript
*   **Data**: JSON-based quiz storage
*   **QR Generation**: Python qrcode library with PIL

## 🚀 Installation & Usage

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
# This installs: flask, qrcode[pil]
```

### 2️⃣ Run the Server
```bash
python app.py
```
*The server will start on port **3000**.*

### 3️⃣ Access the App
Open your browser and navigate to:
*   **Landing Page**: `http://<your-ip>:3000/`
*   **Teacher Hub**: `http://<your-ip>:3000/teacher`
*   **Student Join**: `http://<your-ip>:3000/student`

*Replace `<your-ip>` with your local IP address (e.g., `192.168.1.12`) to let others join!*

---

## 📸 Screenshots
/screenshots/lobby.png

---

## 📜 License
This project is open-source under the MIT License.
Users may copy, modify, or distribute the project freely.

## 🙌 Credits
QuizLAN was built as a robust local alternative to Kahoot, focused on speed, simplicity, and flexibility.
