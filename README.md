# Food Rush – Swiggy Clone

Food Rush is a fully functional food ordering web application inspired by Swiggy.  
It replicates core food delivery features including restaurant browsing, dynamic menu rendering, and centralized cart management using Redux.

This project demonstrates scalable frontend architecture, state-driven UI updates, and modular component structuring using modern development practices.

---

## Live Demo

🔗 **Live Application:** https://foodrushhh.netlify.app/  
🔗 **GitHub Repository:** https://github.com/Equationeer/FoodRush  

---

## Key Features

- Dynamic restaurant listing with efficient data rendering  
- Real-time menu display with structured component architecture  
- Centralized cart management with add/remove item functionality  
- Global state management using Redux Toolkit  
- Search and filtering capability for improved user experience  
- Optimized loading states using shimmer UI  
- Fully responsive layout across devices  
- Production-optimized build using Parcel bundler  

---
## Project Architecture

The application follows a modular and scalable architecture designed for maintainability and extensibility.

- Centralized state management using a Redux store  
- Slice-based state segregation for predictable state updates  
- Component-driven development with reusable UI modules  
- Clear separation of concerns between UI, business logic, and data handling  
- Structured and maintainable folder hierarchy  

## Project Structure

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
## Tech Stack

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

## Getting Started

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

### Professional Tip (Optional Improvement)

For cleaner commands, you can add scripts in your `package.json`:

```json
"scripts": {
  "start": "parcel src/index.html",
  "build": "parcel build src/index.html"
}
npm start

