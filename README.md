Contents
1.	Project Description	2
2.	Software Requirements	3
3.	Database Design	3
4.	Screenshots	4



















1. Project Description
Car Rental application rents a car for short period of time. In this application, an online member can login to the portal and update the personal details which are necessary for the application to approve the rentals. To ensure the security to the costumers, the passwords are hashed and stored in the database using MD5 algorithm. If the user forgets the password, new password can be created upon clicking forgot password on the sign in page, but Phone number is mandatory. Once the profile is complete, the subscriber can view wide range of cars and can request the car of their choice. Users are also provided sections to give feedback. Upon requesting, the admin/owner through the admin portal approves or rejects the requests based on the availability of the vehicles. The users can check the status of the approval in their respective profile under my bookings. Admin has a separate portal to maintain the service requests of the costumers. Admin has all privileges to delete the details of the user if found malicious to the website.
Users Privileges:
* Car Booking
* View Car booking history
* Update His/Her profile
* Update his/her password
* Logout 
Admin Privileges:
* Admin can create vehicle brands
* Manage Vehicle Brands(Edit, Delete)
* Post Vehicle
* Manage vehicle(Edit,Delete)
* Manage Booking(Admin can confirm and Cancel Booking)
* Manage  Contact us Query
* Admin Can see the details of registered users
* admin can also update the page content
* Admin can update the contact us details
* Manage Subscribers
* Admin Dashboard(Admin can view the count of reg users, total booking, total subscribers, total queries etc)
* Change Password(admin can change own password)
* logout
2. Software Requirements
Programming language – PHP
Database – MySQL
User Interface Design - HTML, AJAX,JQUERY,JAVASCRIPT
Web Browser – Chrome
XAMPP Server
3. Database Design
The database component used for the project was relational. MySQL is used with 9 tables for different data storage of the functionalities. Example of the few tables defined are:
* Admin info (Id, Username, Password, UpdationDate)
* Booking details (Id, userEmail, vehicleId, FromDate, ToDate, message, status, PostingDate)
* Brand info (Id, BrandName, CreationDate, UpdationDate)
* Contact Us (Id, Address, EmailId, ContactNo) 

A more detailed view of the structure is shown below.
Fig 1: Database structure

4. Screenshots

Fig 2: Sign in Form


Fig 3: Registration Form includes form validation, Password strength


Fig 4: Product listing and search feature


Fig 5: Booking status (cart)


Fig 6: Admin Panel to add, delete, update & remove vehicles or users requests

