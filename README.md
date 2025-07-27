# 📋 Todo Task Management App

A sleek, user-friendly Todo Task Manager built using *React Native (Expo)* for both Android and iOS. Users can authenticate via *Google Sign-In* and manage personal tasks with full CRUD operations. The app offers *offline support, smooth **animations*, and a polished, responsive UI.

---

## 🚀 Features

### ✅ Authentication
- Secure login using *Google Sign-In*
- Displays proper error states on login failure

### 📌 Task Management
- *Create, **Read, **Update, **Delete, and **Mark Complete* tasks
- Each task includes:
  - Title
  - Description
  - Due Date
  - Status (Open/Completed)
  - Priority

### 📱 User Experience (UX)
- Tabbed navigation with React Navigation
- Search & filter tasks by title/status
- Floating Action Button (FAB) for adding new tasks
- Smooth list animations (add/edit/delete/complete/view priority)
- "No data" empty state screens

### 📦 Offline Support
- Local task storage using *SQLite* 
- No need for external databases


---

## Tech Stack

| Feature           | Library / Framework                  |
| ----------------- | ---------------------------------- |
| Framework         | [React Native (Expo)](https://expo.dev/)        |
| Authentication    | expo-auth-session                  |
| Navigation        | @react-navigation/native           |
| State Management  | Redux Toolkit                     |
| Local Storage     | expo-sqlite (SQLite)              |
| Animations        | lottie-react-native               |
| Swipe to Delete   | react-native-swipe-list-view      |
| UI Components     | React Native Paper / React Native Elements |
| APK Generation    | Expo EAS Build (`eas build -p android`) |


---

## 🌐 Live Demo

- You can try out the Apk version of TaskList below:
- **TaskList**: https://drive.google.com/drive/folders/1gFlYxlCuZ4RIvwSiXY5wzBFeuc3cRvja
- Feel free to explore the application, add Tasks, and start your task management journey!

## 🎥 Video Explanation

- *Watch a full walkthrough of TaskList*:  
  [Video Walkthrough] :https://drive.google.com/drive/folders/1gFlYxlCuZ4RIvwSiXY5wzBFeuc3cRvja

  ---

## 📦 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/todo-task-manager.git
cd todo-task-manager

# 2. Install dependencies
npm install
npm install -g expo-cli
npm list --depth=0

# 3. Start the development server
npx expo start




---

**Todo Task Management App** — # 📋 Cross-Platform Todo Task Management App  
A sleek, user-friendly Todo Task Manager 🚀🎓  
This project is a part of a hackathon run by  

[https://www.katomaran.com](https://www.katomaran.com)
