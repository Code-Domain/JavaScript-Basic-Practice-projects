# 🔐 Caesar Cipher Message Converter

A simple and responsive Caesar Cipher web application built using **HTML, CSS, and JavaScript**.

This project allows users to encrypt and decrypt messages using a custom shift value.

---

## 🚀 Features

* 🔑 Encrypt text using Caesar Cipher
* 🔓 Decrypt encrypted text
* 📱 Fully responsive design
* 🎨 Modern gradient UI
* 🚫 Prevents numbers in message input
* 🧠 Preserves spaces and special characters

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling & Responsive Layout
* **JavaScript** – Logic & DOM Manipulation

---

## 📖 How It Works

The Caesar Cipher shifts each letter in the alphabet by a fixed number.

Example (Shift = 3):

a → d
b → e
c → f
...
z → c (wrap around)

### 🔐 Encryption Formula

```
(old_index + shift) % 26
```

### 🔓 Decryption Formula

```
(old_index - shift + 26) % 26
```

The `% 26` ensures the letters wrap correctly within the 26-letter alphabet.

---

## 🧩 Project Structure

```
index.html
 ├── HTML Layout
 ├── Internal CSS Styling
 └── JavaScript Logic
```

---

## 💡 How To Use

1. Enter your message in the text area.
2. Enter a shift value.
3. Click **Encrypt** to encode the message.
4. Click **Decrypt** to decode it.
5. The result appears below the buttons.

---

## ⚠️ Input Rules

* Message cannot contain numbers.
* Shift value should be a number.
* Non-alphabet characters (like spaces) are preserved.

---

## 📱 Responsive Design

The UI adjusts automatically for:

* Desktop
* Tablet
* Mobile devices

---

## 🎯 Future Improvements

* Support uppercase letters separately
* Add copy-to-clipboard button
* Add reset/clear button
* Add error message UI instead of alert
* Add animation effects

---

## 👨‍💻 Author

Built By Code Domain as a JavaScript learning project to understand:

* DOM manipulation
* Event listeners
* String handling
* Modulus operator logic
* Basic encryption concepts

---

## ⭐ If You Like This Project

Give it a star and keep building more projects!

---
