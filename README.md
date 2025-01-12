﻿# TFlights - Flexible Flight Search Web Application

TFlights is a modern web application designed to help long-distance and budget travelers find flexible flight options. The platform features an interactive user interface, real-time suggestions, and seamless integration with external APIs to deliver up-to-date flight data.

![Landing Page Screenshot](screenshot1.png)
![Flight Search Screenshot](screenshot2.png)

---

# Features

- **Auto-Suggestion for Airports**  
  Users can search airports by name with real-time auto-suggestion functionality, powered by a JSON-based airport database.
  
- **Dynamic Flight Search**  
  Leverages a flight search API to retrieve and display flights with details such as airline name, departure time, and prices.

- **Flexible Date Selection**  
  Integrated with Flatpickr to allow easy single-date or range-based flight searches.

- **Modern UI/UX**  
  Built with Bootstrap and custom CSS for a responsive, elegant design.

---

# Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Date Picker**: Flatpickr
- **API Integration**: Booking.com Flights API
- **Data**: JSON-based airport data
- **Version Control**: Git/GitHub

---
# Project Structure

├── assets/ │ ├── images/ # Image files (logos, icons, etc.) │ └── styles.css # Custom CSS for styling ├── scripts/ │ ├── script.js # Core frontend JavaScript │ ├── api_handling.js # Handles API interactions │ └── countryData.json # JSON file with airport data ├── index.html # Main HTML file └── README.md # Documentation

##  How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/tflights.git
   cd tflights

## Install Dependencies: 
This project is static, so no dependencies are required. Just open the HTML file in a browser.

## API Key Setup:
Obtain an API key from Booking.com Flights API.
Replace YOUR_API_KEY in the showFlightsTable function inside script.js with your API key.

## Run Locally:
Open index.html in your preferred browser

#  Usage Instructions
Enter departure and destination airports using the auto-suggestion input fields.
Select departure date using the date picker.
Choose the cabin class and the number of passengers from the dropdown menus.
Click Update to fetch and display flight options

#  Contact
Email: hello@travisthio.com

# License 
This project is licensed under the MIT License. See the LICENSE file for details.

#  Acknowledgments
Flatpickr for the date picker
Bootstrap for UI components
Booking.com Flights API for flight data

# Website Link
https://thiozhaosheng.github.io/TFlights/
