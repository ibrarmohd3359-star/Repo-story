# 🚀 STO App (Story To Online)

STO App एक modern storytelling + social media platform है, जो Wattpad + Instagram Reels जैसा experience देता है।

---

## 📱 Features

### 📝 Stories System
- Users अपनी stories लिख सकते हैं
- Images के साथ story upload
- Admin approval के बाद ही publish होती है

### 🎬 Reels System
- Short video upload (TikTok style)
- Vertical scrolling feed
- Like, comment, share support

### ❤️ Social Features
- Like system
- Comments
- Share option
- Views tracking

### 🛡️ Admin Panel
- Story approval system
- User management
- Content moderation

---

## ⚙️ Tech Stack

- Frontend: HTML, CSS, JavaScript (Vite)
- Backend: Firebase (Auth, Firestore, Storage)
- Android: Capacitor
- CI/CD: GitHub Actions

---

## 📦 Android APK Build System

This project supports automatic Android APK generation using GitHub Actions.

### Build Flow:
npm install  
npm run build  
npx cap sync android  
cd android  
./gradlew assembleDebug  

---

## 🚀 CI/CD Features

- Auto build on push to main branch
- APK generation automatically
- Upload to GitHub Artifacts
- Release APK download ready

---

## 📂 Project Structure
