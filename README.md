# Muhisina Chatbot

A simple chatbot application that connects to a WebSocket server to provide financial advice on managing salary and saving money. The chatbot is built using **HTML, TailwindCSS, and JavaScript**.

---

## 🚀 Features
- **Real-time chat** powered by WebSocket.
- **User-friendly interface** with TailwindCSS.
- **Dynamic message display** with auto-scroll.
- **Reconnects automatically** if the WebSocket connection closes.
- **Enter key support** for sending messages.
- **Predefined system prompt** for financial advice.

---

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS (TailwindCSS), JavaScript
- **WebSocket API** for real-time messaging
- **Crypto API** for generating unique chat IDs

---
![Chatbot Screenshot](screenshot.png)

## 📂 Project Structure
```
📦 chatbot-project
├── 📄 index.html  # Main HTML file
├── 📄 style.css   # Custom styling (optional)
├── 📄 README.md   # Project documentation
```

---

## ⚙️ How It Works
1. The user enters a message and clicks the **"Ask Advisor"** button.
2. The message is sent to the WebSocket server (`wss://backend.buildpicoapps.com/api/chatbot/chat`).
3. The chatbot processes the message and responds based on the **financial advisor system prompt**.
4. Messages from the user appear on the right, while responses from the chatbot appear on the left.
5. If the WebSocket connection is lost, the chatbot **automatically reconnects**.

---

## 🎮 How to Run the Project
1. Clone this repository:
   ```sh
   git clone https://github.com/muhisina123/chatbot-project.git
   ```
2. Open the **index.html** file in a web browser.

---

## 💡 Usage
- Type a message in the input field and press **Enter** or click **"Ask Advisor"**.
- The chatbot will respond with financial advice.
- If the connection drops, it will **automatically attempt to reconnect**.

---

## 🔧 Future Enhancements
- Add support for **user authentication**.
- Store conversation history in **localStorage**.
- Improve the **UI/UX** with animations.
- Deploy a backend for a **custom chatbot API**.

---

## 📜 License
This project is open-source and free to use.

---

### ✨ Author
Developed by **Muhisina** 🚀

