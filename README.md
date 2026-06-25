# EV Charging Stations Web Application

## Project Overview

The **EV Charging Stations Web Application** is a simple front-end project developed using **HTML, CSS, and JavaScript**. It simulates an Electric Vehicle (EV) charging station booking system where users can log in, browse available charging stations, and register their vehicle for charging.

The project is designed as a beginner-friendly demonstration of DOM manipulation, page navigation, and JavaScript event handling without using any backend or database.

---

## Features

* User Login Interface
* Home Dashboard
* View Nearby EV Charging Stations
* Display Charging Price per kWh
* Vehicle Registration Form
* Interactive Navigation Between Pages
* Responsive and Clean User Interface
* JavaScript-Based Dynamic Content

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

---

## Project Structure

```
EV-Charging-Stations/
│
├── index.html          # Main application
├── styles.css          # External stylesheet (optional)
├── login-bg.jpg        # Login background image
├── home-bg.jpg         # Home page background
├── stations-bg.jpg     # Stations page background
└── README.md           # Project documentation
```

---

## Application Workflow

### Step 1: Login

* User enters a username.
* Clicking **Login** redirects the user to the Home page.

### Step 2: Home Page

* Displays a welcome screen.
* User clicks **View Stations** to see available EV charging stations.

### Step 3: Charging Stations

The application displays available stations such as:

* FastCharge Station
* EcoCharge Hub
* SuperCharge Plaza

Each station displays:

* Station Name
* Charging Price per kWh
* Register Button

### Step 4: Registration

After selecting a station:

* Selected station name is displayed.
* Charging price is shown.
* User enters the vehicle name.
* Clicking **Register** shows a success message.

---

## JavaScript Functions

### login()

Validates username input and navigates to the Home page.

### showHomePage()

Returns the user to the Home page.

### showStationsPage()

Displays the list of EV charging stations dynamically.

### showRegisterPage(id)

Displays the registration page for the selected charging station.

### register()

Registers the vehicle and displays a success message.

---

## Sample Charging Stations

| Station            | Price     |
| ------------------ | --------- |
| FastCharge Station | $0.30/kWh |
| EcoCharge Hub      | $0.25/kWh |
| SuperCharge Plaza  | $0.40/kWh |

---

## Future Enhancements

* User Authentication
* Backend Integration
* Database Support (MySQL/MongoDB)
* GPS-Based Nearby Station Detection
* Online Payment Gateway
* Slot Booking System
* Charging History
* QR Code Generation
* User Profile Dashboard
* Google Maps Integration

---

## Learning Outcomes

This project demonstrates:

* HTML page structure
* CSS styling and layouts
* JavaScript DOM manipulation
* Dynamic content generation
* Event handling
* Simple single-page application concepts

---

## How to Run

1. Download or clone the repository.
2. Place all background images in the project folder.
3. Open `index.html` in any modern web browser.
4. Enter a username.
5. Browse available charging stations.
6. Register your vehicle for charging.

---

## Author

**S M Mokshagna**

BCA Student

GITAM University, Bengaluru

---

## License

This project is created for educational and learning purposes. Free to use and modify.
