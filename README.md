# CS571 Workshop 05
This workshop involves developing a login based mobile application supported by a Node backend server. Use `Mongoose` Schema to design your DB according to the following details. 
  
**Your backend server must have 3 routes:**
* `Sign up` - Public (collect email, password, phone number, location object contains coords, city, zip code ..etc)
* `Login` - Public (by email) - Will always add a log (fail, success) - trigger an SMS when new location is detected.
* `Logs` - Private (display a list of how many times the user have logged in, timestamp, and from which location) - The log contains both failed and succeeded attempts.
  
**Your front end application has the following screens:**
* `Sign up` - Public
* `Login` - Public
* `Logs` - Private
  
**Notes:**
* Your mobile app should send an SMS to the user phone number once they login from a new city.  
* The app will persist the user state and is expected not to require users to login every time they use the application.
* The deadline to submit your work is Monday 9 PM CST.
