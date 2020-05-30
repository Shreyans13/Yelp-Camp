# Web App: Yelp-Camp-Udemy
YelpCamp is a Node.js web application with RESTful routing project from the Udemy course - [The Web Developer Bootcamp](https://www.udemy.com/course/the-web-developer-bootcamp/) by [Colt Steele](https://www.udemy.com/user/coltsteele/)

  ## From the creater
  >This course is also unique in the way that it is structured and presented. Many online courses are just a long series of "watch as I code" videos.  
  >This course is different. I've incorporated everything I learned in my years of teaching to make this course not only more effective but more engaging.

## To see the demo
To see the page in action, go to Yelp Camp
1. Username: User
2. Password: user12345

## Features of this project
  1. Authentication:<br>
    * User signup with username, password<br> 
    * User login with username and password <br>
    * Admin login with admin username and password <br> 

  2. Authorization:<br>
    * One cannot create new posts or view user profile without being authenticated<br>
    * One cannot edit or delete existing posts and comments created by other users<br>
    * Admin can manage all posts and comments<br>
    * Admin can generate invitation code for user to sign up<br>

  3. Functionalities of campground posts and comments:<br>
    * Create, view, edit and delete posts and comments<br>
    * Upload campground photos from url

  4. Flash messages responding to users’ interaction with the app
  5. Responsive web design

## Built with
  ### Front End
  1. Bootstrap 4
  2. Font Awaesome
  ### Back End
  1. body-parser
  2. connect-flash
  3. ejs
  4. express
  5. express-session
  6. method-override
  7. mongoose
  8. passport
  9. passport-local
  10. passport-local-mongoose
