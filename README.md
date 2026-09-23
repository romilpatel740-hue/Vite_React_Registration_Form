# React Form Validation (Assignment 4)

A responsive React application featuring a user registration form with real-time field validation, password strength criteria checking, dynamic feedback, and clean UI components.

## 🚀 Features

- **Real-Time Input Validation:**
  - **Full Name:** Restricts numbers and special characters.
  - **Email Address:** Validates proper email formatting.
  - **Phone Number:** Validates valid phone number entry.
  - **Password:** Live criteria checking (character length, uppercase, lowercase, numbers, and special characters).
  - **Confirm Password:** Live matching against password entry.
- **Toggle Password Visibility:** Show/hide password text using eye icon toggles.
- **Form Controls:** Terms of Service checkbox verification and a dynamic Form Reset button.
- **Dashboard Layout:** Sidebar navigation, top header bar, storage usage indicator, and footer links.

## 🛠️ Tech Stack

- **Frontend:** React (Vite / CRA)
- **Styling:** CSS3 / Tailwind CSS (or standard CSS modules)
- **Icons:** Lucide React / FontAwesome (or native HTML icons)

## 📁 Project Structure

```text
src/
├── components/
│   ├── Sidebar.jsx
│   ├── Header.jsx
│   ├── RegistrationForm.jsx
│   └── Footer.jsx
├── App.jsx
├── index.css
└── main.jsx
