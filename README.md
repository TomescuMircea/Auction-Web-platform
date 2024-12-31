# Auction Web Platform

## Overview

This project is an Auction Web Platform created as part of our second-semester coursework in the second year at Alexandru Ioan Cuza University, Faculty of Computer Science, developed in collaboration with my colleague **Cotos Ștefan**. The platform allows users to create auctions for various items, place bids in real-time, and interact with other users. It features an **Admin page** where administrators can manage and control the auction process.

The platform is built using the **Spring Framework** for the backend, with **vanilla HTML, CSS, and JavaScript** for the frontend. The system follows the **MVC (Model-View-Controller)** architecture, ensuring a clean separation of concerns. The platform also incorporates **security features**, such as user authentication, and supports **real-time bidding** with the help of **WebSockets**.

### Key Features:
- **Auction Creation**: Users can create auctions for various items.
- **Bidding**: Users can place bids on active auctions in real-time.
- **Admin Page**: Admins have full control over the platform, including managing auctions, users, and bids.
- **Real-Time Bidding**: WebSocket integration for live bid updates.
- **Security**: Login and authentication layers are implemented for secure user access.
- **Responsive Frontend**: Built using vanilla HTML, CSS, and JavaScript, ensuring a smooth user experience.

## Technologies Used
- **Backend**: Spring Framework (Spring Boot, Spring MVC, Spring Security)
- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Real-Time Features**: WebSocket
- **Deployment**: Hosted on Heroku
- **Database**: MySql using JPA

## Features and Functionality

### User Features:
- **Register and Login**: Users can register an account and log in to start bidding.
- **Auction Listings**: Browse ongoing auctions with details about each item.
- **Place Bids**: Users can place bids on items in real-time.
  
### Admin Features:
- **Dashboard**: Admins have access to a management dashboard to view and manage all users, auctions, and bids.
- **User Management**: Admins can add/remove users.
- **Auction Management**: Admins can manage auction listings and their status (active, closed, etc.).
- **Bid Monitoring**: Admins can monitor all live bids.

### Real-Time Bidding:
- The system uses **WebSockets** to allow users to see real-time bidding updates. As soon as a new bid is placed, all users participating in the auction will see the updated bid amount instantly.

## Security

- **Authentication**: The platform uses Spring Security for user authentication.
- **Role-based Access Control**: Users and admins have different levels of access to the platform.
  
## Deployment

The application was hosted on **Heroku** at the time of final presentation.
