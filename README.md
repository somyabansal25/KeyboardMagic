# ⌨️ Keycode Info App

A simple JavaScript project that listens for keyboard events and displays the **key pressed**, its **keycode**, and the **event code** in a table.

---

## 📌 Features
- Detects any key pressed on the keyboard.
- Displays:
  - **Key** → actual character or name of the key (e.g., "a", "Enter", "Space").
  - **KeyCode** → numerical keycode (legacy but useful).
  - **Code** → physical key location identifier (e.g., "KeyA", "ArrowLeft").
- Updates dynamically as you press different keys.
- Clean and minimal UI with table format.

---

## 🚀 How to Use
1. Open the project in your browser.
2. Press any key on your keyboard.
3. A table will appear showing the `key`, `keyCode`, and `code` of the pressed key.

---

## 🛠️ Tech Stack
- **HTML** – basic structure  
- **CSS** – styling (optional if added)  
- **JavaScript** – event handling with `keydown`  

---

## 📂 Project Structure
├── index.html # Layout with a div (id="insert")
├── style.css # Styling for table (optional)
├── script.js # Key event handling logic
└── README.md # Project details

