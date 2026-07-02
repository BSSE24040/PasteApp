# PasteBin Clone

A modern Pastebin clone built with React, Redux, and Tailwind CSS. Create, view, edit, delete, and search code/text pastes with a clean and responsive interface.

---

## ✨ Features

- Create new pastes with title and content
- Edit existing pastes easily
- View individual pastes in a dedicated page
- Delete pastes permanently
- Copy paste content to clipboard
- Search pastes by title
- Persistent storage using localStorage
- Responsive design for all devices
- Toast notifications for user actions
- Clean, macOS-inspired UI design

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

git clone <your-repo-url>
cd pastebin-clone
npm install
npm run dev

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
- Clean modern design
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

Pull requests are welcome. For major changes, please open an issue first.

---

## 📄 License

This project is open source under the MIT License.
