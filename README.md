# CS571 Workshop 05
This workshop involves developing a login based mobile application supported by a Node backend server. Design your DB according to the following details. 
Your backend server must have 3 routes:
* `Sign up` - Public (collect email, password, phone number, location)
* `Login` - Public (by email)
* `Logs` - Private (display a list of how many times the user have logged in and from which location)
Your front end application has the following screens:
* `Sign up` - Public
* `Login` - Public
* `Logs` - Private
Your mobile app should send an SMS to the user phone number once they login from a new location.
THe app will not persist the user state and is expected to require users to login every time they use the application.
