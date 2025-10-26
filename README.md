# 📝 To-Do App

A simple and elegant **Assignment Reminder App** built with **Python (PyQt5)** — now available as a **Windows executable (.exe)**.  
It helps you manage assignments, stay organized, and get notified before deadlines — all from your desktop.

---

## 🚀 Features

- ✅ Fetches assignments automatically from your Aurora portal  
- 🔔 Sends reminder notifications for upcoming deadlines  
- 💾 Saves login details and API URL securely in your Documents folder  
- 🖥️ Runs in the background through the **system tray**  
- 🎨 Clean and user-friendly interface  
- ⚙️ Simple setup — no installation required  

---
## 🧭 How to Use

1. **Download and extract** the ToDoApp folder from the release section.  
2. Run `ToDoApp.exe`.  
3. On first launch, enter:
   - Your **Login Details** (in JSON format)  
   - Your **Assignment API URL**
4. Click **OK** to save.  
5. Your assignments will appear in a table view.  
6. Closing the window hides it to the **system tray** (it keeps running in the background).  
7. To exit completely, right-click the tray icon → **Quit**.

---

## 🔧 SetUp
- Login Details
    - [Watch How to Get Login Details](readme-assets/LoginDetails.mp4)
- Assingment URL
    - [Watch How to Get Assignment URL](readme-assets/Assignment%20URL.mp4)
- Startup
    - Open the app folder and create shoutcut of the app (Right click -> Show more options -> Create Shortcut)
    - Click on the shortcut and press Ctrl + X 
    - Press Windows Key + R and Type `shell:startup` and Press Ctrl + V to paste the Shortcut

---
## 💡 Notes

- The app automatically checks for upcoming deadlines every hour.  
- Notifications will appear in the Windows **Action Center**.  
- All settings are stored locally in your `Documents/data.json` file.  

---

## 🧑‍💻 Developer

**Tekumalla Manikanta**

---
> ⚠️ Keep the **Every** folder in the same directory as `ToDoApp.exe`.  
> The icon and resources won’t load if the folder is missing.
---

## 📜 License

This project is intended for **educational and personal use**.  
You may reuse or modify it with proper credit.

---

## 🌐 Project Overview

This desktop app was designed to provide a quick and efficient way for students to **track assignments and deadlines** without needing to open a browser or log in repeatedly.  
It combines the simplicity of a To-Do list with the power of background reminders and tray notifications.