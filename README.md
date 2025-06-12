## EV Charging Station Finder and Slot Booking System
**EV Charging Station Finder and Slot Booking System** is a web-based application designed to help electric vehicle (EV) owners easily find nearby charging stations and book slots in advance . This system is aimed at improving the EV charging experience, ensuring convenience, accessibility, and reliability for users while promoting the adoption of electric vehicles by reducing charging anxiety.

As the adoption of electric vehicles continues to rise, the need for a streamlined and efficient way to locate, reserve, and pay for charging slots becomes critical. This application addresses that need by offering a simple yet powerful solution.

## Features
- **Charging Station Locator:** Find nearby EV charging stations using geolocation services.
- **Slot Booking:** View available slots and reserve a time for charging your EV.
- **Real-time Updates:** Live status of charging slots and availability.
- **User Profiles:** Create accounts to manage bookings and transaction history.
- **Station Management:** Admin panel for charging station operators to manage bookings and monitor station performance.

## Installation
**Prerequisites**
- Node.js (for backend)
- MongoDB (for database)
- HTML, CSS, JavaScript (for frontend)

**Steps to Install**
1. Clone the Repository:
```bash
git clone https://github.com/kalyansai15/EV-WebApp.git
cd EV-WebApp
```
2. Install Backend Dependencies:

Navigate to the backend/ folder and run:
```bash
npm install
```

3. Install Frontend Dependencies:

Since the frontend uses HTML, CSS, and JavaScript, there are no specific package dependencies. You can simply open the frontend/ folder and start working with the files.

4. Configure Database:

Set up your MongoDB instance and configure the connection string in the backend/config/db.js file.

5. Start the Application:

For the backend:
```bash
cd backend
node server.js
```

6. Visit http://localhost:3000 in your browser to access the application.

## Tech Stack
- Frontend: HTML5, CSS3, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Geolocation: Google Maps API

## Folder Structure
```
EV-WebApp/
│
├── backend/
│   └──server.js/            # Backend logic and API 
│   
├── frontend/                # HTML, CSS, and JavaScript frontend code
│   ├── Login.html           # Login page with HTML, CSS, and JavaScript
│   ├── User.html            # User page with HTML, CSS, and JavaScript
│   ├── Admin.html           # Admin page with HTML, CSS, and JavaScript
│
└── README.md                 # This file
```

## Screenshots
***Login page***
![image](https://github.com/user-attachments/assets/3a821b29-d347-4628-a708-522aafe01cbe)


***User Page***
![image](https://github.com/user-attachments/assets/4bf3c3ce-80d3-4627-a287-e302be97b22f)


![image](https://github.com/user-attachments/assets/9a918fd7-14b0-4144-b148-2338344a7c03)

![image](https://github.com/user-attachments/assets/43769c5a-fff8-4544-ba10-fedd9a79d4ca)


***Admin Page***
![image](https://github.com/user-attachments/assets/526920e5-2938-40f6-b0a5-d9d5b59d2e84)

![image](https://github.com/user-attachments/assets/c4b4857b-1ded-486a-93bf-ff14ab7185bf)


## Contributing
We welcome contributions from the community! If you'd like to improve or add features to this project, feel free to fork the repository, make your changes, and submit a pull request. Please ensure that your code adheres to the project's coding standards and is well-documented.

## Acknowledgments
** Google Maps API for geolocation and station search.

** HTML, CSS, and JavaScript for building the user interface.

** Node.js and Express.js for building the backend server.

** MongoDB for storing data.
