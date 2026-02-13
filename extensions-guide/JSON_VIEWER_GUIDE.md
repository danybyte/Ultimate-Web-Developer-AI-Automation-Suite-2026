# 🌳 JSON Viewer: Making APIs Readable

## 🌟 Overview
If you've ever opened an API endpoint and seen a "wall of text" that's impossible to read, you know the pain. **JSON Viewer** automatically intercepts JSON responses and transforms them into a beautiful, formatted, and interactive tree structure directly in your browser.

---

## 🚀 Why It’s a Backend & Integration Essential

### 1. Readable Hierarchy
Instead of squinting at commas and curly braces, you get a clean, indented view. You can collapse or expand nested objects and arrays to focus on the data that matters.

### 2. Syntax Highlighting
It colors strings, numbers, booleans, and nulls differently. This makes spotting a data type error (like a string where a number should be) instantaneous.

### 3. Clickable Links
If your JSON contains URLs (like image paths or related API endpoints), JSON Viewer makes them clickable, allowing you to navigate through your API structure with ease.

---

## 🔍 Key Features at a Glance

| Feature | Why you'll love it |
| :--- | :--- |
| **Search/Filter** | Quickly find a specific key or value in a massive 5,000-line JSON file. |
| **Copy Path** | Right-click any value to copy its JSON path (e.g., `user.profile.images[0].url`)—perfect for coding! |
| **Raw vs. Parsed** | Switch back to the raw view instantly if you need to copy the entire string for testing. |
| **Themes** | Supports Dark Mode and various color schemes to match your VS Code setup. |

---

## 💡 How to Use for API Debugging

1. **The Quick Audit:** When your frontend isn't displaying data, open the API URL in a new tab. JSON Viewer will show you if the field name has changed or if the data is missing.
2. **Deep Nesting:** Use the "Collapse All" feature and expand only the specific keys you are working on to avoid "information overload."
3. **Validation:** It automatically alerts you if the JSON is "Invalid," helping you catch backend syntax errors before you even look at the logs.

---

## 🛠 Pro Tip
Combine this with **Playwriter**. Use Playwriter to trigger an API call, and then use the **JSON Viewer** to verify the payload before you tell the AI to process the data.

---

## 📥 Installation
* **Official Store:** [Download JSON Viewer](https://chromewebstore.google.com/detail/gbmdgocenclidppncbeadhbaidgoenno)

---

[⬅️ Back to main Toolkit](./README.md)