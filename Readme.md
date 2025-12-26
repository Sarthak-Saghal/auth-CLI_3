
# React Authintication
A **modern React authentication system featuring secure login, signup, and password recovery flows with smooth routing and polished UI interactions**.
# 💎 Neon Diamond Login UI

A **futuristic neon-themed authentication UI** featuring **animated diamond layers, glowing effects, and glassmorphism styling**.  



---

### 📦 Dependencies Installation (Required)

Before running the project, install the following dependencies:

### ▶ React Router DOM  
Used for client-side routing and navigation.

```bash
npm install react-router-dom


```
### Framer Motion
``` bash
npm install framer-motion
```
### React Icons

```bash
npm install react-icons
```


## ✨ Overview

This project showcases a **high-impact login interface** built for modern products that want to stand out.  
The UI uses **layered diamond shapes**, neon glow effects, and smooth **Framer Motion animations** to create a subtle 3D illusion and premium feel.

---

## 🎨 Visual Highlights

- Layered neon diamond background
- Subtle 3D illusion using transforms
- Glassmorphism login card
- Glow effects for primary actions
- Dark theme with high contrast
- Smooth animated transitions

---

## 🚀 Features

- Login screen UI
- Social login icons
- Animated diamond layers
- Neon glow & glassmorphism effects
- Fully responsive design
- Clean and production-ready structure
- Easy to customize colors, motion, and layout

---

## 🛠 Tech Stack

- **React**
- **Tailwind CSS**
- **Framer Motion**
- **React Icons**
- **CSS Glow Effects**
- **Vite / CRA**

---



---
## 🔗 Application Routing Structure

The application routes are defined in `App.jsx` as follows:


```jsx

import { Routes, Route, Navigate } from "react-router-dom";
import Login from "./pages/Login";
import Signup from "./pages/Signup";
import ForgotPassword from "./pages/ForgotPassword";
import Logout from "./pages/Logout";

export default function App() {
  return (
    <Routes>
      <Route path="/" element={<Navigate to="/login" replace />} />
      <Route path="/login" element={<Login />} />
      <Route path="/signup" element={<Signup />} />
      <Route path="/forgot-password" element={<ForgotPassword />} />
      <Route path="/logout" element={<Logout />} />
    </Routes>
  );
  
}
```
