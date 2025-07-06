# EasyTransfer

**EasyTransfer** is a smart and secure file sharing web application that leverages **free Google Drive storage** to transfer files across devices or users via unique links. It is a lightweight, fast, and reliable alternative to bulky file-sharing systems.

---

## 🌟 Why EasyTransfer?

Most free file transfer tools have limitations — either in storage, speed, or file expiry. **EasyTransfer** solves this by integrating with Google Drive’s **free cloud space**, ensuring:

- High reliability and speed
- Free and scalable storage (via Free Google Drive Space)
- Easy uploads and access from anywhere

---

## 📂 Key Features

- ✅ Upload any type of file securely
- 🔗 Get a **unique shareable link** for each file
- 🌐 Transfer files across devices within the same Wi-Fi or across the internet
- 📥 Easy downloads without signup (for recipients)
- 🔐 Secure file handling with private link-based access
- ☁️ **Utilizes your Google Drive’s free storage space** as a backend
- 📱 Mobile-friendly design with drag-and-drop support

---

## 🛠️ Tech Stack

| Frontend           | Backend Cloud & APIs   |
|--------------------|------------------------|
| HTML, CSS, JavaScript | | Google Drive API  |

---

## ⚙️ How It Works

1. **User uploads a file**
   - The file is uploaded to the linked Google Drive account using the API.

2. **Shareable link is generated**
   - A download URL is provided to the user.

4. **Recipients can download**
   - Users can download the file using the link — without login (as per config).


---

## 📦 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/elvish-patel/EasyTransfer.git
cd EasyTransfer
