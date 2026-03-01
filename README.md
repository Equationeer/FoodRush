# Food Rush – Swiggy Clone

Food Rush is a fully functional food ordering web application inspired by Swiggy.  
It replicates core food delivery features including restaurant browsing, dynamic menu rendering, and centralized cart management using Redux.

This project demonstrates scalable frontend architecture, state-driven UI updates, and modular component structuring using modern development practices.

---

## 🌐 Live Demo

🔗 **Live Application:** https://YOUR_NETLIFY_LINK  
🔗 **GitHub Repository:** https://github.com/Equationeer/FoodRush  

---

## 🚀 Features

- 🏬 Restaurant listing page
- 📄 Dynamic restaurant menu rendering
- 🛒 Add to Cart / Remove from Cart functionality
- 🔄 Global state management using Redux Toolkit
- 🔍 Search functionality
- ⚡ Loading shimmer effect
- 📱 Fully responsive UI
- 📦 Optimized bundling with Parcel

---

## 🏗️ Project Architecture

The project follows a modular and scalable folder structure:

-Centralized state using Redux store
-Slice-based state logic separation
-Reusable UI components
-Separation of UI, business logic, and data
-Clean folder hierarchy

## 📂 Project Structure

```text
src/
│
├── Components/        → UI components
│   ├── Header.js
│   ├── Home.js
│   ├── RestaurantMenu.js
│   ├── Checkout.js
│   ├── Shimmer.js
│   └── ...
│
├── Stored/            → Redux state management
│   ├── CartSlice.js
│   └── stores.js
│
├── Utils/             → Static data & utilities
│   ├── DineData.js
│   ├── FoodData.js
│   └── Grocery.js
│
├── App.js
├── index.css
└── index.html
```
## 🛠️ Tech Stack

| Category            | Technology Used        |
|---------------------|------------------------|
| Frontend Framework  | React                  |
| Programming Language| JavaScript (ES6+)      |
| Markup Language     | HTML5                  |
| Styling             | CSS3                   |
| State Management    | Redux Toolkit          |
| Build Tool          | Parcel                 |
| Deployment          | Netlify                |
| Version Control     | Git & GitHub           |

## ⚙️ Getting Started

Follow these steps to run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Equationeer/FoodRush.git
cd FoodRush
```
### 2️⃣ Install Dependencies

```bash
npm install
```
### 3️⃣ Start Development Server

```bash
npx parcel src/index.html
```

---

### 🔥 Professional Tip (Optional Improvement)

For cleaner commands, you can add scripts in your `package.json`:

```json
"scripts": {
  "start": "parcel src/index.html",
  "build": "parcel build src/index.html"
}
npm start

