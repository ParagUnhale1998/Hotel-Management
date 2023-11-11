# Hotel Management System

This Hotel Management System is a comprehensive Angular application designed for users, owners, and administrators. Utilizing a JSON server (`db.json`) for data storage, it offers seamless functionality for managing hotels, bookings, and users.

## Features

### User Module

- **Sign Up and Login:** Users can register and log in securely to access personalized features.
- **Hotel Booking:** A user-friendly interface allows users to browse and book hotels.
- **Cart Functionality:** Users can add hotels to their cart for easy booking.
- **My Hotels:** Users can view and manage their booked hotels.

### Owner Module

- **Owner Dashboard:** Owners can log in to their personalized dashboard.
- **Hotel Management:** CRUD operations for managing hotels with a beautiful interface.
- **My Bookings:** Owners can view and manage bookings for their hotels.

### Admin Module

- **Admin Dashboard:** A special route for administrators with a landing page showcasing all modules.
- **User, Owner, Hotel Lists:** Admins can view comprehensive lists of users, owners, and hotels.

## Technology Stack

- **Angular:** Utilizing Angular for building a dynamic and responsive user interface.
- **Material UI and Bootstrap:** Enhancing aesthetics and user experience.
- **JSON Server (`db.json`):** Serving as a lightweight database to store application data.

## Deployment

### Fake Backend Server

To simulate a backend server, a fake server has been set up using JSON Server and hosted on GitHub. The server data is stored in the `db.json` file.

- **GitHub Repository:** [Fake Backend Server](https://github.com/ParagUnhale1998/Hotel-Management-Data-Api.git)

### Angular Application Deployment with Firebase

This Hotel Management System is hosted using Firebase Hosting to provide a seamless experience for users, owners, and administrators.

- **Hosted Link:** [Firebase Hoisting](https://hotel-management-88cb3.web.app/user)

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ParagUnhale1998/Hotel-Managment-Project.git
   cd hotel-management
** Install Dependencies**
```npm install```

** Start the JSON Server**
```npm run server```

** Start the Angular App **
```ng serve```

# Project Structure

hotel-management-system/
|-- src/
|   |-- app/
|       |-- components/
|       |-- services/
|       |-- modules/
|       |-- ...
|-- db.json
|-- ...

Feel free to explore the codebase and contribute to enhancing this Hotel Management System. If you encounter any issues or have suggestions, please create an issue in the repository.


