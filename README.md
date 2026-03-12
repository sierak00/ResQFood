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

## User Stories
### 01: User registration

User navigates to the registration page.

User selects account type (Food Provider or Food Receiver).

User enters personal details (name, email, password).

System validates the entered information.

System creates a new account.

System confirms successful registration.
---
### 02: User login

User navigates to login page.

User enters username and password.

System validates credentials.

System grants access and redirects to dashboard.

If credentials are invalid, system displays error message.
---
### 03: Create food donation

Food provider logs into the system.

Provider navigates to "Create Food Donation".

Provider enters food details (name, quantity, description).

Provider adds pickup location and time.

System validates the information.

System creates a new food donation listing.

Listing becomes visible to receivers.
---
### 04: View available food

Food receiver logs into the system.

Receiver navigates to the "Available Food" section.

System retrieves active food listings.

System displays available food donations.

Receiver selects a listing to view details.
---
### 05: Request food donation

Food receiver selects a food listing.

Receiver clicks "Request Donation".

Receiver confirms request submission.

System records the request.

System notifies the food provider.
---
### 06: Manage food posts

Provider navigates to "My Food Posts".

System displays provider's listings.

Provider selects a listing to edit or delete.

Provider updates details or removes listing.

System updates the database.
---
### 07: View donation requests

Provider logs into the system.

Provider navigates to "Donation Requests".

System retrieves requests related to provider's listings.

System displays request details.

Provider reviews the requests.
---
### 08: Approve or reject request

Provider selects a donation request.

Provider reviews receiver details.

Provider chooses approve or reject.

System updates request status.

System notifies the receiver of the decision.
---
### 09: Track request status

Receiver navigates to "My Requests".

System retrieves all submitted requests.

System displays status (Pending / Approved / Rejected).

Receiver views pickup information if approved.
---

### 10: Cancel request

Receiver selects a submitted request.

Receiver chooses cancel request.

System confirms cancellation.

System removes the request from active listings.
---
### 11: Confirm pickup

Receiver arrives at pickup location.

Provider confirms food collection.

System updates donation status to "Completed".

System records the completed donation.

### 12: Manage users (Administrator)

Administrator logs into the system.

Admin navigates to user management panel.

System displays list of registered users.

Admin can deactivate or remove suspicious accounts.

System updates the user database. 
---
### 13: Search food donations

 Food receiver navigates to the "Available Food" section.
 
 Receiver enters a keyword in the search field (e.g., bread, vegetables).

 System processes the search request.
 
 System retrieves matching food listings.
 
 System displays the filtered results to the receiver.

---

### 14: Filter food listings
Food receiver navigates to the food listings page.

 Receiver selects filter options (location, quantity, pickup time).
 
 System applies selected filters.
 
 System retrieves matching listings from the database.
 
 System displays filtered results to the receiver.

---

### 15: View donation details

 Food receiver browses available food listings.
 
 Receiver selects a specific listing.
 
 System retrieves detailed information about the donation.
 
 System displays food description, quantity, provider, pickup location, and pickup time.
 
 Receiver reviews the information.

---

### 16: Notification of new donations

 Food provider creates a new food donation post.
 
 
System saves the new listing in the database.

 System identifies receivers subscribed to notifications.
 
 System sends a notification about the new donation.
 
 Receivers receive the notification and may view the listing.

---

### 17: View donation history

 Food provider logs into the system.
 
 Provider navigates to the "Donation History" section.
 
 System retrieves past donation records.
 
 System displays completed donation listings.
 
 Provider reviews their previous donations.

---

### 18: View request history

 Food receiver logs into the system.
 
 Receiver navigates to the "My Requests" section.
 
 System retrieves all previously submitted requests.
 
 System displays request history with status information.
 
 Receiver reviews past requests.

---

### 19: Rate donation experience

 A food donation is marked as completed.
 
 System prompts both provider and receiver to leave feedback.
 
 User selects a rating score.
 
 User optionally enters written feedback.
 
 System stores the rating and feedback.

---

### 20: Report inappropriate listing
Food receiver views a food listing.
 
 Receiver selects the "Report Listing" option.
 
 Receiver selects a reason for the report.
 
 System records the report.
 
 System notifies the administrator for review.

### 21: Priority distribution for urgent requests

 Food receiver submits a food request.
 
 Receiver marks the request as urgent if the organization has immediate need.
 
 System evaluates the request priority.

System highlights urgent requests to the food provider.

Food provider reviews and may prioritize the urgent request.

---

### 22: Automatic expiration of food listings

 Food provider creates a food donation listing.

 Provider specifies pickup deadline.
 
 System stores the listing and monitors expiration time.
 
 When the pickup time passes, the system automatically marks the listing as expired.
 
 Expired listings are removed from the available food list.

---

### 23: Sustainability impact tracking

 Food donation is successfully completed.
 
 System calculates the amount of food saved from waste.
 
 System updates sustainability statistics.
 
 System records environmental impact data.
 
 Users can view statistics such as total food saved and number of donations.

---

### 24: Pickup reminder notification

 Food request is approved by the provider.
 
 System records the scheduled pickup time.
 
 System sends reminder notifications to the receiver before pickup.
 
 Receiver receives the reminder notification.
 
 Receiver prepares to collect the food.

---

### 25: Generate donation report (Administrator)

 Administrator logs into the system.
 
 Admin navigates to the reporting dashboard.
 
 System retrieves donation activity data.
 
 System generates statistics such as total donations, active users, and completed pickups.
 
 Administrator reviews or exports the report.





