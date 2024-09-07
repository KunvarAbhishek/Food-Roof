# Food-Roof - Your Ultimate Restaurant Experience

Welcome to **Food-Roof**, a dynamic web application that lets you enjoy the best of both worlds—seamless **Table Reservations**, **Online Food Ordering**, and real-time **Delivery Tracking**—all from the comfort of your home.

## Project Overview

Food-Roof is a full-featured web app designed to streamline restaurant services. Whether you want to **book a table**, **order food online**, or **track your delivery**, Food-Roof makes it effortless.

With a user-friendly design and powerful functionality, this app enhances restaurant operations and provides customers with the convenience they deserve.

## Features

- **Table Booking**: Check table availability and make reservations with just a few clicks.
- **Online Ordering**: Browse the menu and place orders from the comfort of your home.
- **Live Delivery Tracking**: Stay updated with real-time delivery tracking through integrated map services.

## Installation Instructions

Setting up Food-Roof on your local environment is simple. Follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-repository-url.git
    ```

2. **Create and Activate a Virtual Environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install the Required Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Configure API Keys**:
    - Sign up for a Twilio account and create an Authy App to get your API key. 
    - Replace the placeholder in `config.py` with your Twilio API key.
    - Also, set up a secret key for handling user sessions.

5. **Run the Application**:
    ```bash
    python run.py
    ```

6. **Access the App**:
    Visit the following address in your browser:
    ```
    http://127.0.0.1:5000/
    ```

## Technologies Used

The Food-Roof application is built with modern web technologies for both the frontend and backend:

- **Frontend**: Developed using **HTML5**, **CSS3**, and **JavaScript**.
- **Backend**: Powered by **Flask**, a lightweight Python web framework.
- **Database**: All data (user details, reservations, orders) are managed through **SQLite**.
- **Phone Verification**: Integrated using **Twilio Authy API**.
- **Real-Time Tracking**: Achieved through **Google Maps JavaScript API** and **Google Directions API**.

## App Flow

Here’s a breakdown of how the Food-Roof application works:

1. **Home Page**: Provides an overview of the restaurant's offerings and a navigation bar to explore other features.
   
2. **Registration and Login**: New users can easily sign up, verify their phone numbers, and log in to access personalized services.
   
3. **Booking a Table**: Users can check availability and make table reservations for specific times directly from the app.
   
4. **Placing an Order**: The menu displays a variety of food items with options to customize and place an order online.

5. **Delivery Tracking**: After placing an order, users can track the delivery status on an interactive map.

6. **About Us & Contact Pages**: Learn more about the restaurant or get in touch with the team for any queries.

## Screenshots

### Home Page
![Home Page](https://user-images.githubusercontent.com/92647313/143268173-ff82236a-d49e-4ed1-85df-cb132b1be61f.png)

### User Registration
![Registration Page](https://user-images.githubusercontent.com/92647313/143269562-8892a106-5d79-435d-8443-d0033de8d29d.png)

### Phone Number Verification
![Phone Verification](https://user-images.githubusercontent.com/92647313/145669345-1664b46a-d8d8-4862-ae2e-65f2638bbc14.png)

### User Login
![Login Page](https://user-images.githubusercontent.com/92647313/143269879-8703fd51-d4f1-47ef-a82d-04ab302b3d00.png)

### Services
![Services Page](https://user-images.githubusercontent.com/92647313/143269862-a9794ea5-e50d-4a6b-bfef-397fb30ac60f.png)

### Table Reservation
![Table Reservation](https://user-images.githubusercontent.com/92647313/143269836-4c35eb47-ae86-41d9-90f1-6ea1b42ce566.png)

### Menu
![Menu Page](https://user-images.githubusercontent.com/92647313/143270255-39b2aa04-6469-4fe2-a009-7361a1ee66f7.png)

### Order Cart
![Cart Page](https://user-images.githubusercontent.com/92647313/143269901-21b84d5e-81d3-4ed8-a6be-42692c0ccc58.png)

### Order Confirmation
![Order Confirmation](https://user-images.githubusercontent.com/92647313/143270441-cb669f88-6d49-4f95-8540-5e5d7d1444f9.png)

### Delivery Tracking
![Delivery Tracking](https://user-images.githubusercontent.com/92647313/143269928-a232bfc6-8307-4ae9-9aa7-f7e97575199d.png)

### About Us
![About Us](https://user-images.githubusercontent.com/92647313/143269712-70a96ef3-38d8-46f9-b361-8eb2e07a8c94.png)

### Contact Us
![Contact Page](https://user-images.githubusercontent.com/92647313/143270006-6e1ab438-d112-44a0-be1e-a55a857a7dac.png)

## Contribution Guidelines

We love collaborating with developers! If you'd like to contribute to Food-Roof, feel free to fork the repository, make your changes, and submit a pull request. We welcome all improvements and suggestions.

---

Thank you for checking out **Food-Roof**! Let us know if you have any questions or suggestions for enhancing the experience.
