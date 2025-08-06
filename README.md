# 📩 Message Website

This is a simple and minimal web app that lets you **create and share secret messages through URLs**. Enter a message, click generate, and you'll get a unique URL that reveals your message when visited!

---

## 🌐 Live Demo

👉 [View Live Website](https://faizanmessage.netlify.app/)  

---

## ✨ Features

- 🧠 Encode any custom message into a sharable URL
- 🔗 View message automatically when visiting the link
- 🎨 Simple and clean UI with centered form layout
- 🔒 No data stored — everything is encoded in the URL

---

## 🛠️ Technologies Used

- **HTML5** – Structure and layout
- **CSS3** – Styling and animations
- **JavaScript (ES6)** – Message encoding and URL handling
- **Base64** – Message encryption using `btoa()` and `atob()`

---

## 🧠 How It Works

1. You enter a message into the form.
2. On submission, the message is Base64-encoded and added to the URL hash (`#`).
3. The website reads the hash from the URL and decodes the message.
4. The decoded message is displayed on the screen automatically.

