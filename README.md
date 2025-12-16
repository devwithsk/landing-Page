# 🎙️ AI Voice – Modern Landing Page

AI Voice is a modern, fully responsive landing page built using **Tailwind CSS**.  
It showcases an AI-based voice generation product with a clean UI, dark/light theme support, animations, and a scalable design system using CSS variables.

---

## 🚀 Live Preview
> https://aivoice-landingpage.netlify.app/

---

## 📸 Screenshots
> <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a63f92c2-b1dc-46d5-ba7e-2d7eb00c3b23" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/30b28782-ab63-4109-aa6b-472c46ffcae4" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f69a6edf-7388-427e-843b-4f547965b79d" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/98e8c19e-4eaf-42ac-beba-7e69d07a4bc1" />










---

## ✨ Features

- 🌗 **Auto Dark / Light Mode**
  - Detects user's system theme automatically
  - Manual toggle support

- 🎨 **Theme System using CSS Variables**
  - Centralized color management
  - Easy future rebranding
  - No hard-coded colors

- 📱 **Fully Responsive Design**
  - Mobile-first approach
  - Optimized for desktop, tablet & mobile

- 🧩 **Modern UI Sections**
  - Navbar
  - Hero Section with floating animation
  - Features Grid
  - Pricing Cards
  - Contact Form
  - Footer

- ✨ **Smooth Animations**
  - Hover effects
  - Floating hero image
  - Fade-in section animations

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS (CDN)**
- **CSS Variables**
- **JavaScript (Vanilla)**
- No frameworks, no libraries – lightweight & fast ⚡

---

## 🧠 Key Concepts Used

- Tailwind Flexbox & Grid
- Responsive utilities (`sm`, `md`, `lg`)
- CSS Custom Properties (Variables)
- `prefers-color-scheme` for system theme detection
- Utility-first design approach
- Clean and scalable UI architecture

---

## 🌙 Dark Mode Logic

The website automatically detects the user's system theme using:

```js
window.matchMedia('(prefers-color-scheme: dark)').matches

