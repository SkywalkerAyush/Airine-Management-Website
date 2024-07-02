# JetEase
## Airline Management Website

## Project Description
The Airline Management and Booking App is a comprehensive website that is designed to streamline flight scheduling, flight booking and user interface, the app offers features such as real-time flight status updates, secure payment processing using Razorpay API, and personalized booking options, enhancing the overall travel experience for users. The website is built using HTML, CSS, JavaScript, EJS, Express, Node.js, and MongoDB.

## Features
- **Home Page**: Overview of the airline services and features.
- **Ticket Booking**: Page to book flight tickets.
- **Payment Gateway**: Secure payment processing  integrating Razorpay Gateway.
- **Passenger Details**: Form to fill in passenger information.
- **Flight Status**: Check the current status of flights (departed, arrived, in air).
- **Admin Portal**: Create new flughts using admin password.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript, EJS
- **Backend**: Express, Node.js, Razorpay API
- **Database**: MongoDB

## Setup

### Prerequisites

- Ensure Node.js is installed on your deviece.
- Ensure MongoDB is installed and ensure it's running.
- Clone the Project in your terminal. Type:
  
  ```
  git clone https://github.com/AryanShivapuram/JetEase-Airline-Management-Website-.git
  cd JetEase-Airline-Management-Website-/
  ```
  
### Getting Flights Database

- If your MongoDB server does not run on `port 27017`, please replace the port with your own port in `db.ns` in root directory on the project.
- In the terminal, change the current directory to porject's folder if not.
  ```
  cd JetEase-Airline-Management-Website-/
  ```
- Now install the Node Packages
  ```
  npm i
  ```
- Now run the `createFlight.js` on the terminal to create database of flights for current and next month. Type:
  ```
  node createFlight.js
  ```
### Starting the server

- If all the above steps were donce correctly, you could start the project, type:
  ```
  node index.js
  ```
- Go to `http://localhost:3000/` to visit JetEase!!
- To stop the server, do `CTRL + C` on your terminal

## Usage Instructions

Home Page: Navigate to the home page to get an overview of the airline services.

Ticket Booking: Go to the booking page to select flights and book tickets.

Payment: Proceed to the payment gateway for secure payment processing.

Passenger Details: Fill in the required passenger details after booking the ticket.

Flight Status: Check the current status of flights by navigating to the flight status page.

Admin Portal: Navigate to the Admin Portal to create new flights, filing in data. the password for admin portal is 'cow'.

## Dependancies

Express and node js
ejs
mongodb
mongoose
body-parser

## Contributors
[Ayush Kumar](https://www.linkedin.com/in/ayush-kumar-235344254/)

[Aryan Shivapuram](https://www.linkedin.com/in/aryan-shivapuram-341638257/) 

[Aditya Narayan](https://www.linkedin.com/in/aditya-narayan-a02493256/)


[Ayush Mishra](https://www.linkedin.com/in/urayush-mishra/)


