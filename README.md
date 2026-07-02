# 📁 PasteBin Clone

A modern PasteBin clone built with **React**, **Redux Toolkit**, and **Tailwind CSS**. This application allows users to create, edit, view, delete, search, and copy text/code snippets with a clean, responsive user interface.

---

## ✨ Features

- Create new pastes with title and content
- Edit existing pastes
- View individual pastes
- Delete pastes permanently
- Copy paste content to clipboard
- Search pastes by title
- Persistent storage using `localStorage`
- Responsive design for all devices
- Toast notifications for user actions
- Clean and modern UI

---

## 🛠️ Tech Stack

- React 18
- React Router DOM
- Redux Toolkit
- Tailwind CSS
- Lucide React
- react-hot-toast
- JavaScript (ES6+)

---

## 🚀 Installation & Setup

Clone the repository:

```bash
git clone https://github.com/BSSE24040/PasteApp.git
```

Navigate to the project directory:

```bash
cd PasteApp
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## 📁 Project Structure

```text
src/
├── components/
│   ├── Home.jsx
│   ├── Paste.jsx
│   ├── ViewPaste.jsx
│   └── Navbar.jsx
├── redux/
│   ├── pasteSlice.js
│   └── store.js
├── utils/
│   └── formatDate.js
├── data/
│   └── Navbar.js
├── App.jsx
├── main.jsx
└── index.css
```

---

## 🎯 Usage

### Home (`/`)
- Create a new paste
- Edit an existing paste using `?pasteId=<id>`

### Pastes (`/pastes`)
- View all saved pastes
- Search pastes by title
- View, edit, copy, or delete pastes

### View Paste (`/pastes/:id`)
- Read-only view of a selected paste

---

## 🔧 Redux Actions

| Action | Description |
|--------|-------------|
| `addToPastes()` | Add a new paste |
| `updatePastes()` | Update an existing paste |
| `removeFromPastes()` | Delete a paste |

---

## 💾 Storage

All paste data is stored locally in the browser using **localStorage** under the key:

```text
pastes
```

---

## 🎨 UI Highlights

- Responsive design
- Modern interface
- Smooth hover animations
- Clean layout
- Toast notifications
- Clipboard copy functionality

---

## 📝 Future Improvements

- Public shareable links
- Syntax highlighting
- Paste expiration
- User authentication
- Dark/Light mode
- Export paste as file

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Muhammad Mahad Ashfaq**

GitHub: https://github.com/BSSE24040
