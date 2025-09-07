# 🏠 ALX Listing App

The **ALX Listing App** is a modern web application scaffolded as part of the **ALX Intermediate Frontend Program**.  
It serves as the foundation for building an **Airbnb clone** with a scalable, production-ready setup using **Next.js, TypeScript, TailwindCSS, and ESLint**.  

This milestone (Milestone 1) focuses on **scaffolding and initial setup** for a property listing page, ensuring code quality, reusability, and scalability.

---

## 🎯 Project Goals

- Scaffold a **Next.js project** with production-ready configurations.  
- Integrate **TypeScript** for type safety and maintainability.  
- Configure **TailwindCSS** for responsive, accessible, and modern UI development.  
- Implement **ESLint** to enforce code quality and consistency.  
- Establish a **scalable folder structure** for real-world applications.  
- Create **reusable UI components** (Card & Button).  
- Manage assets under a centralized `public/assets` folder.  

---

## 📂 Project Structure

```

alx-listing-app/
├── components/          # Reusable UI components
│   └── common/          # Core components shared across the app
│       ├── Button.tsx   # Reusable button component
│       └── Card.tsx     # Reusable card component
│
├── constants/           # Centralized constants (API URLs, UI text, etc.)
│   └── index.ts
│
├── interfaces/          # TypeScript interfaces for type safety
│   └── index.ts
│
├── pages/               # Next.js Pages Router
│   └── index.tsx        # Home / Listing page
│
├── public/              # Public assets accessible in the app
│   └── assets/          # Images, SVGs, placeholders
│
├── styles/              # Global styling
│   └── globals.css
│
├── README.md            # Project documentation
├── tailwind.config.js   # TailwindCSS configuration
├── tsconfig.json        # TypeScript configuration
└── package.json         # Dependencies and scripts


---

## 🧩 Components

- **Card Component (`components/common/Card.tsx`)**  
  Displays property details (image, title, description) in a reusable format.

- **Button Component (`components/common/Button.tsx`)**  
  A styled button for actions like "Book Now" or "View Details".

---

## ⚡ Tech Stack

- **[Next.js 13+ (Pages Router)](https://nextjs.org/)** – React framework for SSR & SSG.  
- **[TypeScript](https://www.typescriptlang.org/)** – Type safety and maintainability.  
- **[TailwindCSS](https://tailwindcss.com/)** – Utility-first CSS for responsive design.  
- **[ESLint](https://eslint.org/)** – Code linting and best practices enforcement.  



## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/alx-listing-app.git
cd alx-listing-app
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Development Server

```bash
npm run dev
```

### 4. Open in Browser

Visit [http://localhost:3000](http://localhost:3000) to see the app running.

---

## 🖼️ Assets

All assets (images, icons, SVGs) are located in the `public/assets/` folder.
Example usage:

```tsx
<img src="/assets/placeholder.jpg" alt="Property" />
```

---

## ✅ Milestone 1 Deliverables

* [x] Scaffolded **Next.js + TypeScript + TailwindCSS + ESLint** project.
* [x] Established clean **folder structure**.
* [x] Created **Card** and **Button** reusable components.
* [x] Defined **TypeScript interfaces** for props.
* [x] Organized assets under **public/assets/**.
* [x] Added **README.md** with setup and documentation.

---

## 👨‍💻 Author

Developed by **Biniyam Beyene**
As part of the **ALX Intermediate Frontend – Milestone 1: Scaffolding and Initial Setup for Listing Page**
