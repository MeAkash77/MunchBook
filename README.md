<h1 align="center"> 🍽️ MunchBook - Decentralized Crowdfunding Platform</h1>

<p align="center">

**MunchBook** is a full-stack restaurant dining tracker and food review app tailored for food-loving families and groups. Track every delicious moment—from restaurant visits and dish reviews to smart meal recommendations and analytics that help shape your next culinary adventure.


![Next.js](https://img.shields.io/badge/Next.js-14-blue?style=flat-square&logo=nextdotjs)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=flat-square&logo=mongodb)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-UI-blue?style=flat-square&logo=tailwindcss)
![Recharts](https://img.shields.io/badge/Recharts-Analytics-orange?style=flat-square&logo=chartdotjs)
![License](https://img.shields.io/github/license/yourusername/munchbook?style=flat-square)


## ✨ Features

### 📍 Restaurant Visit Tracking
- Log visits with date, restaurant, and location
- Add reviews and individual dish ratings
- Quick logging from previous restaurants

### 📊 Advanced Analytics Dashboard
- Cuisines breakdown, visit frequency (day/month)
- Bar & pie charts via MongoDB aggregation
- Trends in ratings, top dishes, and places

### 🔍 Smart Recommendation Engine
- Suggestions based on:
  - Past ratings & reviews
  - Cuisine variety & gaps
  - Time-based and seasonal trends

### 📅 Visit History
- Complete chronological log of visits
- Filter by cuisine, rating, or restaurant

### 👥 Multi-Group Support
- Create and manage groups (e.g., Family, Friends)
- Track shared dining experiences

### 🌐 Fully Responsive Design
- Optimized for desktop & mobile
- Seamless adaptive navigation

---

## ⚙️ Tech Stack

| Layer      | Technology                              |
|------------|------------------------------------------|
| 🖼️ Frontend | **Next.js 14**, **Tailwind CSS**, **ShadCN UI** |
| 🧠 Backend  | **Next.js API Routes (Server Actions)** |
| 🗄️ Database | **MongoDB + Mongoose**                 |
| 🔐 Auth     | **Custom Token-based Authentication**   |
| 📊 Charts   | **Recharts**                            |
| 🚀 Hosting  | **Vercel**                              |

---

## 🧠 Key Technical Highlights

### ⚡ MongoDB Aggregations
- Top dishes by frequency & rating
- Least visited cuisines
- Weekly & monthly trends
- Group-based historical insights

### 💡 Smart Real-time Suggestions
- Dynamic avoidance of repetitive cuisines
- Diversity-based meal guidance

### 🔩 Scalable Data Model
- Normalized schemas for:
  - Restaurants
  - Food Items
  - Visits
  - Groups & Users


MunchBook
=========

![Project Poster](https://i.ibb.co/67LCGfs9/Munch-Book.png)

[Live Demo →](https://munch-book.vercel.app/)

* * * * *
<p align="center">
    <a href="https://nextjs.org/">
        <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
    </a>
    <a href="https://www.mongodb.com/">
        <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    </a>
    <a href="https://tailwindcss.com/">
        <img src="https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
    </a>
    <a href="https://ui.shadcn.dev/">
        <img src="https://img.shields.io/badge/shadcn%2Fui-000?logo=shadcnui&logoColor=fff&style=for-the-badge" alt="ShadCN UI" />
    </a>
    <a href="https://vercel.com/">
        <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
    </a>
    <a href="https://vercel.com/">
        <img src="https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge" alt="Vercel" />
    </a>
</p>

* * * * *

Overview
--------

**MunchBook** is a full-stack restaurant dining tracking and food review application tailored for food-loving groups and families. It enables users to document and analyze their culinary experiences by logging detailed restaurant visits, reviewing individual dishes, and leveraging smart analytics and suggestion engines to guide future food adventures.

Whether you're planning your next meal out or simply want to remember what you ordered last time, MunchBook turns your dining habits into meaningful insights.

* * * * *

Features
--------

### 📍 Restaurant Visit Tracking

-   Log each visit with date, restaurant name, and location

-   Add reviews and ratings for the restaurant and individual food items

-   Select from previously visited restaurants for quick logging

### 📊 Advanced Analytics Dashboard

-   Visual breakdown of cuisines, visit frequency by day/month

-   Bar and pie charts powered by complex MongoDB aggregation queries

-   Insights into most-visited restaurants, frequently ordered dishes, and rating trends

### 🔍 Smart Recommendation Engine

-   Suggests restaurants and dishes based on:

    -   Past ratings and reviews

    -   Cuisine types you haven't had in a while

    -   Seasonal and time-based trends

    -   Variety and diversity of food experiences

### 📅 Visit History

-   Detailed chronological history of all visits

-   Easily search and filter by restaurant, cuisine, or rating

### 🔀 Multi-Group Support

-   Create and manage groups (e.g., Family, Friends)

-   Track food journeys across different groups

### 🌐 Fully Responsive Design

-   Optimized for both desktop and mobile

-   Adaptive navigation menu for seamless mobile experience

* * * * *

Tech Stack
----------

-   **Frontend**: Next.js 14, Tailwind CSS, ShadCN UI

-   **Backend**: Next.js API Routes (Server Actions)

-   **Database**: MongoDB with Mongoose

-   **Authentication**: Custom token-based authentication

-   **Deployment**: Vercel

-   **Data Visualization**: Recharts

-   **Design System**: Accessible, dark-mode compatible UI using ShadCN

* * * * *

Key Technical Highlights
------------------------

### Complex MongoDB Aggregations

Used MongoDB's powerful aggregation pipeline to generate insights such as:

-   Most ordered items by rating frequency

-   Least visited cuisines

-   Weekly and monthly visit frequency trends

-   Personalized recommendations based on group behavior and historical data

### Real-time Suggestions

The recommendation engine dynamically analyzes user patterns to:

-   Avoid repetitive cuisines

-   Suggest under-explored categories

-   Prioritize high-rated experiences

### Scalable Data Model

Built around normalized schemas for:

-   Restaurants

-   Items

-   Visits (linked by ObjectIds)

-   Groups and Users

### Clean UX with State Isolation

-   Separated concerns between visit logs and analytics

-   Smooth navigation without re-renders

* * * * *

Screenshots
-----------

*Include screenshots here for:*

-   Dashboard

![Dashboard](https://i.ibb.co/jCcvYxm/screencapture-munchbook-vercel-app-dashboard-2025-06-21-12-58-24.png)

-   Visit History Page

![History](https://i.ibb.co/bMM3NgzV/screencapture-munchbook-vercel-app-history-2025-06-21-13-07-40.png)

-   Analytics Page

![Analytics](https://i.ibb.co/RGHPFXQ9/screencapture-munchbook-vercel-app-analytics-2025-06-21-13-07-03.png)

-   Suggestions Output

![Suggestions](https://i.ibb.co/s9XT2bB0/Screenshot-2025-06-21-130833.png)


* * * * *

How to Run Locally
------------------

```
git clone https://github.com/MeAkash77/MunchBook.git
cd munchbook
npm install

# Add your .env file with MongoDB URI
npm run dev

```

* * * * *

License
-------

This project is licensed under the MIT License.

* * * * *

Contact
-------

Built with passion by [Vandit Shah](https://vandit-shah.me). You can connect with me via [LinkedIn](https://linkedin.com/in/shah-vandit) or email at <shahvandit8@gmail.com>.

* * * * *

**MunchBook**: A smarter way to track, review, and relive your food memories.
