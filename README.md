# Mvc-WebSite

[Site Name]

Login Page:
UI
Input fields 
Username / Email 
Password
Button
Login
Register
Features
Email should be validated in JS
On click of Login button 
Call Ajax
Check if user is registered from database
Return with Response (Should contain Success / Failure)
Handle response in Ajax
If Success move to Home page
If Admin - Show “Manage Users” functionality, and hide it if other User
If Failure - Show error and ask them to register first

Registration Page:
UI
Input fields 
Firstname
Lastname
Username
Email
Mobile
Password
Confirm Password
Button
Register
Image upload
Avatar
Features
Validation on - Email, Mobile, Password & Confirm Password
On click of Register button
Call Ajax
Check if user is already registered from database
Add user into db if not registered and return with success response, else return with failure response
Handle response in Ajax
If Success move to Login page
If Failure - Show error 

Home Page:
Welcome to [Site Name]... - More details will be added


[Database]
Tables:
Table name: Users
Columns: 
Id(Primary Key), FirstName, LastName, UserName, Email, Mobile, Password, CreatedDate, LastLoginDate, Status, Avatar
Table name: UserUpdateHistory
Columns:
Id, UpdatedBy, UpdatedFor, UpdatedFieldName, PreviousValue, NewValue, UpdatedDateTime
