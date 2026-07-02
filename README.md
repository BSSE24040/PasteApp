# 📁 PasteBin Clone

A modern Pastebin clone built with React, Redux Toolkit, and Tailwind CSS.  
Create, view, edit, delete, and search text/code pastes with a clean, responsive UI.

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
- Toast notifications for actions
- Clean macOS-inspired UI

---

## 🛠️ Tech Stack

- React 18
- React Router DOM
- Redux Toolkit
- Tailwind CSS
- Lucide React (Icons)
- react-hot-toast
- JavaScript (ES6+)

---

## 🚀 Installation & Setup

```bash
git clone https://github.com/BSSE24040/PasteApp
cd pastebin-clone
npm install
npm run dev
```

Then open:

http://localhost:5173

---

## 📁 Project Structure

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

---

## 🎯 Usage

Home Page (/)
- Create new paste
- Edit paste using ?pasteId=xxx

Pastes Page (/pastes)
- View all pastes
- Search by title
- Edit, delete, view, copy actions

View Paste (/pastes/:id)
- Read-only paste view

---

## 🔧 Redux Actions

- addToPastes() → Add paste
- updatePastes() → Update paste
- removeFromPastes() → Delete paste

---

## 💾 Storage

All data is stored in browser localStorage under:

pastes

---

## 🎨 UI Highlights

- macOS-style editor UI
- Smooth hover effects
- Responsive grid layout
- Modern clean design
- Toast notifications

---

## 📝 Future Improvements

- Public shareable links
- Syntax highlighting
- Expiry system for pastes
- Authentication system
- Dark/Light mode toggle
- Export as file feature

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

---

## 📄 License

This project is licensed under the MIT License.
