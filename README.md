# React-project---alobha-technology
#  Responsive Multi-Page Landing UI (React)

This project is a **responsive multi-page landing website** built using **React (with Vite)**. It demonstrates modern frontend practices like **routing, component reusability, responsive layouts, and clean UI design**.  
It’s perfect for beginners learning how to structure a React project with **React Router v6**, **CSS Modules**, and **Framer Motion** for subtle animations.


#  Project Overview
The landing UI includes:
- A **Home Page** with a Hero section, Feature highlights, and Footer  
- An **About Page** describing the site or organization  
- A **Contact Page** with a working form (Name, Email, Message) and basic validation  
- A **Reusable Component System** (Navbar, Footer, Card, FormField, etc.)  
- Fully **Responsive Design** for mobile, tablet, and desktop  
- Optional **Dark/Light Mode Toggle**  



##  Tech Stack
- **React (Vite)**
- **React Router v6**
- **CSS Modules / Styled Components**
- **Framer Motion** (for optional animations)
- **Functional Components + React Hooks**


##  Setup and Installation Guide

Follow the steps below to set up and run this project locally 

### 1️ Prerequisites
Make sure you have the following installed:
- **Node.js (v16 or above)**
- **npm** (comes with Node)
- **Git** (optional, if cloning from GitHub)



### 2️ Clone or Create the Project
If you’re starting fresh:

bash

npm create vite@latest my-landing
Then choose:

yaml
Copy code
✔ Framework: React
✔ Variant: JavaScript
3️ Install Dependencies
Install all required packages:

bash
npm install
Now install additional dependencies:

bash
npm install react-router-dom framer-motion

4️ Project Structure
After setup,  project folder should look like this:

pgsql
Copy code
my-landing/
├── index.html
├── package.json
├── vite.config.js
├── /public
├── /src
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   └── /components
│       ├── Navbar.jsx
│       ├── Footer.jsx
│       ├── Card.jsx
│       ├── Home.jsx
│       ├── About.jsx
│       ├── Contact.jsx
│       └── components.module.css
5️ Running the Project
To start the local development server:

bash
npm run dev
Once the server starts, open your browser and visit:
 http://localhost:5173/

This will launch the landing page with navigation and all responsive layouts working.

