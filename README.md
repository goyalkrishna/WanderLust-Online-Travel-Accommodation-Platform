<div align="center">


  <h1>WanderLust 🌍</h1>
  
  <p>
    <b>A full-stack Online Travel Accommodation Platform built with Node.js, Express, and MongoDB.</b>
  </p>
  <p>
    WanderLust is a feature-rich web application that allows users to discover, list, and book unique accommodations around the world. It provides a secure, intuitive, and responsive interface for both hosts and travelers, crafted with a robust MVC architecture.
  </p>

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js Badge">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js Badge">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB Badge">
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap Badge">
    <img src="https://img.shields.io/badge/EJS-7E479C?style=for-the-badge" alt="EJS Badge">
</p>

</div>

---


### ✨ Key Features

* **Full CRUD Functionality**: Users can **C**reate, **R**ead, **U**pdate, and **D**elete property listings and reviews.
* **Interactive Booking System**: A secure booking workflow with integrated availability tracking.
* **Secure Authentication & Authorization**: Features robust user registration and login using Passport.js, with protected routes and session management.
* **Community-Driven Reviews & Ratings**: Users can post reviews and ratings for properties, fostering a trusted community.
* **Dynamic Search & Filtering**: Easily discover stays based on location, price, and other preferences.
* **Responsive & Modern UI**: A mobile-first design built with Bootstrap ensures a seamless experience on any device.
* **Cloud Image Storage**: Utilizes Cloudinary for efficient and scalable image uploads and storage.

---

### 🛠️ Tech Stack & Architecture

WanderLust is built on the **MVC (Model-View-Controller)** architectural pattern to ensure a modular, scalable, and maintainable codebase.

* **Frontend**: EJS, Bootstrap, JavaScript
* **Backend**: Node.js, Express.js
* **Database**: MongoDB with Mongoose ODM
* **Authentication**: Passport.js (Local Strategy)
* **File Storage**: Multer & Cloudinary
* **Deployment**: Render

---

### 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

#### Prerequisites

Make sure you have Node.js and MongoDB installed on your machine.
* **Node.js**: `https://nodejs.org/`
* **MongoDB**: `https://www.mongodb.com/try/download/community`

#### Installation

1.  **Clone the repository:**
    ```sh
    git clone [YOUR_GITHUB_LINK]
    cd WanderLust
    ```
2.  **Install NPM packages:**
    ```sh
    npm install
    ```
3.  **Set up environment variables:**
    Create a `.env` file in the root directory and add the following variables. You'll need to create a free Cloudinary account and a MongoDB Atlas cluster to get these keys.
    ```env
    MONGO_URL=<your_mongodb_connection_string>
    CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
    CLOUDINARY_API_KEY=<your_cloudinary_api_key>
    CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
    SESSION_SECRET=<a_strong_secret_string>
    ```

4.  **Run the application:**
    ```sh
    npm start
    ```
    The application should now be running on `http://localhost:8080`.

---

### 📈 Roadmap: Future Enhancements

Here are some features I plan to add to enhance the platform:

* **💳 Payment Gateway Integration**: Incorporate Stripe or Razorpay for seamless and secure online transactions.
* **🗺️ Map-Based Search**: Implement Mapbox or Google Maps API to allow users to search for properties visually on a map.
* **📊 Host Dashboard**: Create an analytics dashboard for hosts to track bookings, earnings, and property performance.
* **💬 Real-Time Chat**: Add a messaging feature for direct communication between hosts and guests.

---

