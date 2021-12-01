# Software-Engineering 
# Flight Booking System for Airlines (Java Web Application) 


A fully responsive web-based Flight Booking System for Airlines based on the Model View Controller (MVC) Architecture made using Java Servlets, Java Server Pages (JSPs). Moreover authentication and authorization for users is implemented using Tomcat Roles. The web-application is also secured against SQL Injection and Cross-Site Scripting attacks.
# Technologies Used
Frontend: HTML, CSS, JavaScript, Jquery, Bootstrap, Java Server Pages (JSPs), AJAX (for a Flight Search Widget)

Backend: Java Servlets, Java Models, Microsoft Access (Database)

Webservices: SOAP Web Services (to get price and number of seats)

Security Features: SQL Injection, Cross-Site Scripting (XSS), Tomcat Roles

# Roles
Following roles are implemented:

 Airline Admin

 Airline Manager

 Customer

# Workflow (Functionalities)
This is for just one airline who wants to sell seats to their customers via internet.

Following are the steps of work flow:

1, Airline Admin will set the prices of the seats. There should be three types of seats:
  
    First Class
  
    Business
  
    Economy
    

2, The Airline Admin should be able to create and update the features of each type of seat.

3, The Airline Admin should be able to set the total number of seats for each flight.

4, Airline Manager should see a list of seats which the Admin has added or edited when he/she logs in.

5, Airline Manager then needs to approve the new price or updates.

6, When the price and update is approved by the manager only then it should be available for the customer to buy.

7, The Customer should be able to buy seats based on availability.

8, When a customer buys a ticket the system should be able to calculate how many seats are left. If all seats are bought the application should not let the customers buy more seats.

9, The Customer should be able to select the following, to select a seat:

    origin and destination cities
    
    dates of travel
    
    number of people traveling

10, When the customer selects the seat and confirms the booking flight Itinerary should be shown to the customer.

11, When the customer approves the itinerary the customer should be taken to a payment page where the total price should be shown. When the customer presses the pay button consider the transaction done and mark the seat sold.

12, Once the seat is sold, send out an email to the customer with the flight itinerary.

Home page
![home](https://user-images.githubusercontent.com/90812251/144147773-f8c146b0-7ff4-4268-819e-c9502e663922.PNG)![hmp222](https://user-images.githubusercontent.com/90812251/144147934-7211cf8d-afef-42a9-b755-32f282e15c9f.PNG)


Login pages
![login1](https://user-images.githubusercontent.com/90812251/144147836-058f632d-2df5-450a-b979-6ca7ae7d423e.PNG)
![login2](https://user-images.githubusercontent.com/90812251/144147840-9d7b8c61-bb39-42b0-b7fd-89f8aa2e4bfa.PNG)

changing features
![changeseat](https://user-images.githubusercontent.com/90812251/144147977-612422dc-517e-4e58-ac71-ddcca1abb99a.PNG)
![setseats](https://user-images.githubusercontent.com/90812251/144148324-0cc62b17-9d5d-414f-ba65-7c837d9ef4fe.PNG)


booking flight

![booking](https://user-images.githubusercontent.com/90812251/144148038-853d6891-87da-49fe-afd9-ba51fff495c4.PNG)
![search flights](https://user-images.githubusercontent.com/90812251/144148138-dde63f61-c10a-4906-a927-acf95373585a.PNG)
