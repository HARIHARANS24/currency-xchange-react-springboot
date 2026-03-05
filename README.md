# Currency Exchange Web Application

## Overview

Currency Exchange is a full-stack web application built using **React (Frontend)** and **Spring Boot (Backend)** that allows users to convert currency values between different countries. The application provides a simple user interface where users can input an amount and select the source and target currencies to receive the converted result.

The backend exposes REST APIs implemented with Spring Boot, while the frontend consumes these APIs using React to display real-time currency conversion results.

This project demonstrates full-stack development concepts including REST API design, frontend–backend integration, and modern web application architecture.

---

# Project Objectives

The main objectives of this project are:

• Demonstrate full-stack development using React and Spring Boot  
• Build a RESTful API for currency conversion  
• Implement frontend and backend communication using HTTP requests  
• Provide a clean and responsive user interface for currency conversion  
• Understand API integration and service-based architecture  

---

# Features

• Currency conversion between different currencies  
• REST API built with Spring Boot  
• Interactive frontend built with React  
• Clean and responsive UI  
• Simple API architecture for integration  
• Scalable backend structure  

---

# Tech Stack

## Frontend

React.js  
JavaScript  
HTML5  
CSS3  
Axios (for API requests)

## Backend

Java  
Spring Boot  
Spring Web  
REST API  
Maven

## Tools and Development Environment

Git  
GitHub  
Postman  
Visual Studio Code  
IntelliJ IDEA  

---

# System Architecture

The application follows a **client–server architecture**.

React handles the user interface while Spring Boot processes business logic and currency conversion requests.

Architecture Flow:

User Interface (React)

↓

HTTP Request (REST API)

↓

Spring Boot Backend

↓

Currency Conversion Logic

↓

JSON Response

↓

React UI Update

---

# Application Workflow

1. User opens the currency converter interface.
2. User enters the amount to convert.
3. User selects source currency.
4. User selects target currency.
5. React frontend sends request to backend API.
6. Spring Boot backend processes the conversion request.
7. Backend returns conversion result as JSON.
8. React displays the converted amount on the UI.

---

# Project Directory Structure
```
Directory structure:
└── hariharans24-currency-xchange-react-springboot/
    ├── README.md
    ├── LICENSE
    ├── Backend/
    │   ├── HELP.md
    │   ├── mvnw
    │   ├── mvnw.cmd
    │   ├── pom.xml
    │   ├── src/
    │   │   ├── main/
    │   │   │   ├── java/
    │   │   │   │   └── com/
    │   │   │   │       └── example/
    │   │   │   │           └── currencyconverter/
    │   │   │   │               ├── CurrencyconverterApplication.java
    │   │   │   │               ├── controller/
    │   │   │   │               │   └── CurrencyController.java
    │   │   │   │               ├── model/
    │   │   │   │               │   └── CurrencyResponse.java
    │   │   │   │               └── service/
    │   │   │   │                   └── CurrencyService.java
    │   │   │   └── resources/
    │   │   │       └── application.properties
    │   │   └── test/
    │   │       └── java/
    │   │           └── com/
    │   │               └── example/
    │   │                   └── currencyconverter/
    │   │                       └── CurrencyconverterApplicationTests.java
    │   └── target/
    │       └── classes/
    │           ├── application.properties
    │           └── com/
    │               └── example/
    │                   └── currencyconverter/
    │                       ├── controller/
    │                       ├── model/
    │                       └── service/
    └── Frontend/
        ├── README.md
        ├── package-lock.json
        ├── package.json
        ├── postcss.config.js
        ├── tailwind.config.js
        ├── public/
        │   ├── index.html
        │   ├── manifest.json
        │   └── robots.txt
        └── src/
            ├── App.css
            ├── App.js
            ├── App.test.js
            ├── index.css
            ├── index.js
            ├── reportWebVitals.js
            ├── setupTests.js
            └── components/
                ├── css/
                │   ├── CurrencyConverter.css
                │   ├── RateChart.css
                │   └── RatesTable.css
                └── js/
                    ├── CurrencyConverter.js
                    ├── RateChart.js
                    └── RatesTable.js
```

README.md

---

# Installation Guide

## 1 Clone the Repository

git clone https://github.com/HARIHARANS24/currency-xchange-react-springboot.git

cd currency-xchange-react-springboot

---

# Backend Setup (Spring Boot)

Navigate to the backend directory

cd backend

Run the application using Maven

mvn spring-boot:run

Spring Boot will start the server on:

http://localhost:8080

Running a Spring Boot application via Maven automatically compiles and launches the project from the root directory containing the pom.xml file. :contentReference[oaicite:1]{index=1}

---

# Frontend Setup (React)

Navigate to frontend directory

cd frontend

Install dependencies

npm install

Start React development server

npm start

React application will run on:

http://localhost:3000

---

# REST API Endpoints

Example API endpoint:

GET /currency-exchange/from/{fromCurrency}/to/{toCurrency}

Example Request:

GET /currency-exchange/from/USD/to/INR

Example Response:

{
 "id":10001,
 "from":"USD",
 "to":"INR",
 "conversionRate":83.5
}

---

# Example API Call Flow

React Component

↓

Axios Request

↓

Spring Boot Controller

↓

Service Layer

↓

Response JSON

↓

UI Update

---

# Future Improvements

• Integration with real-time exchange rate APIs  
• Add authentication and user login system  
• Store previous conversions in database  
• Add graphical charts for currency trends  
• Implement Docker containerization  
• Deploy backend on cloud (AWS / Azure / GCP)  
• Improve UI design and user experience  

---

# Learning Outcomes

This project helps understand:

• React component-based architecture  
• Spring Boot REST API development  
• Frontend and backend integration  
• API request handling  
• JSON data exchange  
• Full-stack application deployment  

---

# Contributing

Contributions are welcome.

Steps to contribute:

1 Fork the repository  
2 Create a feature branch  
3 Commit your changes  
4 Push to your branch  
5 Open a pull request  

---

# Author

Hariharan S

GitHub  
https://github.com/HARIHARANS24

---

# License

This project is licensed under the MIT License.

---

# Acknowledgements

Special thanks to open source communities and developers who contribute tools and frameworks like React and Spring Boot which enable rapid development of modern web applications.
