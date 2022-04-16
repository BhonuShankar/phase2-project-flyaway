# Flyaway Ticket Booking App in JAVA - Servlet&JSP

## Table of contents
* [General info](#general-info)
* [Using the application](#using-the-application)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)


## General info
A small flight booking demo project in <b>JAVA</b> 

## Using the application
Home displays the application name (FlyAway) and two options - User Login and Admin Login Access
![Screenshot (523)](https://user-images.githubusercontent.com/101262568/163674789-cf62a45a-daa9-4c72-8bc3-b708127e54b4.png)

<br><br>
<b>Book Flights</b>  - <br>
The user enters flight details (From, To, Departure date and No. of Travellers). 
A query is sent to the remote database to fetch related flights and displayed to user.
The User enters other details and proceeds to book the flight.
<br><br>
<b>Admin</b>  - <br>
Admin dashboard is accessed with a preset username and password.
Admin can see all entries in database table.
Admin can change his password after Login.
Admin can add new flights.

## Technologies
<b>Frontend</b> - JSP, HTML, CSS <br>
<b>Backend</b> - JAVA Servlets <br>
<b>Database</b> - MySQL <br>


## Setup
To run in your localhost - Clone into local and run project on tomcat server. If any issue check artifact is build properly.
<br><br>

## Features
A search form in the homepage to allow entry of travel details, like the date of travel, source, destination, and the number of persons.
Based on the travel details entered, it will show the available flights with their ticket prices.
Once a person selects a flight to book, they will be taken to a register page where they must fill in their personal details. In the next page, they are shown the flight details of the flight that they are booking, and the payment is done via a dummy payment gateway. On completion of the payment, they are shown a confirmation page with the details of the booking. 
● An admin login page where the admin can change the password after login, if he wishes
● A master list of places for source and destination
● A master list of airlines
● A list of flights where each flight has a source, destination, airline, and ticket price


