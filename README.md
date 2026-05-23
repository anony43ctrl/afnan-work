# Afnan Javeed – Work Portfolio

A modern, high-performance personal portfolio website built with **React 19**, **Vite**, and **Tailwind CSS 4.0**. This repository showcases the software engineering journey, full-stack projects, and machine learning research of **Afnan Javeed**.

---

# 🚀 Key Features

### Modern Tech Stack
Leverages the latest **React 19** features and **Vite 7** for lightning-fast development and optimized production builds.

### Next-Gen Styling
Built with **Tailwind CSS 4.0** and **PostCSS**, utilizing modern CSS variables and a utility-first styling paradigm.

### Dynamic Content Engine
All portfolio data *(Experience, Education, Projects, Publications)* is managed through a central **`src/App.jsx`** data object, making the website highly maintainable and scalable.

### Interactive Java-Style Hero
Features a custom-built, responsive **terminal interface** that simulates a Java development environment, reflecting Afnan's proficiency in backend engineering.

### Smooth User Experience
Includes:

- Scroll-linked animations  
- Dark / light mode persistence  
- Fully responsive layout optimized for all device sizes

---

# 🛠️ Technology Stack

| Category | Technology |
|--------|-----------|
| Framework | React 19 |
| Build Tool | Vite 7 |
| Styling | Tailwind CSS 4.0 |
| Icons | Lucide React |
| Code Quality | ESLint 9 |

---

# 📂 Project Structure

```

.
├── public/                # Static assets (favicon, global icons)
├── src/
│   ├── assets/            # Project-specific images and SVG assets
│   ├── App.jsx            # CENTRAL SOURCE OF TRUTH: Main logic and data
│   ├── main.jsx           # Application entry point
│   └── index.css          # Tailwind 4.0 directives and custom animations
├── tailwind.config.js     # Tailwind configuration (selector-based dark mode)
└── vite.config.js         # Vite configuration with React plugin

````

---

# ⚡ Getting Started

## Prerequisites

- **Node.js:** v20.19.0 or higher  
- **npm** or **yarn**

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/afnan-javeed/work-profile.git
cd work-profile
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

### 4. Build for Production

```bash
npm run build
```

---

# 📝 Customizing Content

The application dynamically renders content based on the **`portfolioData`** object located in:

```
src/App.jsx
```

You can easily update the following sections:

### Profile

* Name
* Role
* Social links
* Biography

### Experience

* **Synechron (Amex)**
* **C-DAC**
* **ITJobxs**

### Education

* **VIT**
* **GEMS OOIS**

### Publications

* IEEE research on **Graph Attention Networks (GAT)**

### Skills

* Enterprise Java
* SpringBoot
* Machine Learning
* DevOps

---

# 📄 License

This project is intended for **personal portfolio use**.

All rights reserved by the author.
