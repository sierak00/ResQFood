# ResQFood 🍽️

## Project Overview

ResQFood is a Java-based application designed to help reduce food waste by connecting food providers with people or organizations that need food. Many restaurants, bakeries, and supermarkets throw away perfectly good food at the end of the day. At the same time, many individuals and charities struggle to access meals.

The purpose of this project is to create a simple platform where businesses can post surplus food and charities or individuals can request and collect it instead of letting it go to waste.


---

## Objectives

The main objectives of the ResQFood application are:

* Reduce food waste from restaurants and food businesses
* Help people in need access free food
* Provide an easy system for businesses to donate surplus food
* Improve coordination between food providers and receivers

---

## Features

The application includes several core features that allow users to interact with the system.

### User Registration

Users can create an account in the system as either a **Food Provider** or a **Food Receiver**.

### Login System

Registered users can log into the system securely using their credentials.

### Post Surplus Food

Food providers can add food listings that include:

* Food name
* Quantity
* Description
* Pickup time
* Location

### Browse Available Food

Receivers can browse all available food listings posted by providers.

### Request Food

Users can request food donations through the system.

### Manage Listings

Providers can update or remove their food posts when the food is no longer available.

---

## Technologies Used

This project was developed using the following technologies:

* **Java**
* **Object-Oriented Programming (OOP)**
* **Java Collections**
* **Basic File Handling / Data Storage**

The application follows object-oriented design principles such as encapsulation, modularity, and separation of responsibilities.

---

4.1.2 User Scenarios Extended
US_01: User registration

User navigates to the registration page.

User selects account type (Food Provider or Food Receiver).

User enters personal details (name, email, password).

System validates the entered information.

System creates a new account.

System confirms successful registration.

US_02: User login

User navigates to login page.

User enters username and password.

System validates credentials.

System grants access and redirects to dashboard.

If credentials are invalid, system displays error message.

US_03: Create food donation

Food provider logs into the system.

Provider navigates to "Create Food Donation".

Provider enters food details (name, quantity, description).

Provider adds pickup location and time.

System validates the information.

System creates a new food donation listing.

Listing becomes visible to receivers.

US_04: View available food

Food receiver logs into the system.

Receiver navigates to the "Available Food" section.

System retrieves active food listings.

System displays available food donations.

Receiver selects a listing to view details.

US_05: Request food donation

Food receiver selects a food listing.

Receiver clicks "Request Donation".

Receiver confirms request submission.

System records the request.

System notifies the food provider.

US_06: Manage food posts

Provider navigates to "My Food Posts".

System displays provider's listings.

Provider selects a listing to edit or delete.

Provider updates details or removes listing.

System updates the database.

US_07: View donation requests

Provider logs into the system.

Provider navigates to "Donation Requests".

System retrieves requests related to provider's listings.

System displays request details.

Provider reviews the requests.

US_08: Approve or reject request

Provider selects a donation request.

Provider reviews receiver details.

Provider chooses approve or reject.

System updates request status.

System notifies the receiver of the decision.

US_09: Track request status

Receiver navigates to "My Requests".

System retrieves all submitted requests.

System displays status (Pending / Approved / Rejected).

Receiver views pickup information if approved.

US_10: Cancel request

Receiver selects a submitted request.

Receiver chooses cancel request.

System confirms cancellation.

System removes the request from active listings.

US_11: Confirm pickup

Receiver arrives at pickup location.

Provider confirms food collection.

System updates donation status to "Completed".

System records the completed donation.

US_12: Manage users (Administrator)

Administrator logs into the system.

Admin navigates to user management panel.

System displays list of registered users.

Admin can deactivate or remove suspicious accounts.

System updates the user database. 




