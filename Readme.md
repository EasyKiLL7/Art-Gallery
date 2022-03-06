# Art-Gallery Campsite

## 💡Introducing Art-Gallery Campsite
A Node.js based end to end web application for sharing art-gallery, places or anything for users (read camping lovers) with functionalities, such as to add, rate and review different art-gallery campsite, then the others users or campers can put their reviews and concerns, so that it is a well informed, beneficial and easy to decides to prepare for camping trip for different users.


## See the application in action
[deployed on Heroku.](https://art-gallerysite.herokuapp.com/)

## ⚙️ Features
-	Login, sign-up, Admin
-	RESTful routes (Create, Read, Update, Delete) for campsites, comments, and reviews
-	Create and Update forms have both client-side and server-side validation
-	Create routes have authentication
-	Update, and Delete routes have authentication and authorization
-	[Google Mapbox APIs](https://docs.mapbox.com/api/search/geocoding/)

## ⚙️Features Description
* Authentication:
  - User login with username and password

  - Admin login admin password

* Authorization
  - User can only modify campgrounds created by them.

  - User cannot edit or delete campsite and comments created by other users

* Manage campsites posts with basic functionalities:

  - Create, update and delete posts and comments
  - Upload campsite images

  - Add Name, Image and Description to the campsites.

* Basic functionalities

  - Flash messages responding to users' interaction with the app

  - Responsive web design

## 🚀 To run this project on your system:

* Clone or download this repository

```
git clone https://github.com/EasyKiLL7/Art-Gallery
```
Then Create an .env file and add values to the following variables which contains API secrets and passwords :
```
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_KEY=
CLOUDINARY_SECRET=
MAPBOX_TOKEN=
DB_URL=
SECRET=
```
Make sure you have [Node](https://nodejs.) and  [MongoDB](https://docs.mongodb.com/manual/installation/) installed on your system
In a terminal window, initialize a MongoDB Database 
```
$ ./mongod
```
In a second terminal window, access the MongoDB Database with Mongoose
```
$ mongoose
```
install dependencies using npm: 

``` 
npm install
```
this will install all the necessary packages that you need to run the application

And then run the application with
```
$ npm start
```  
or
```
$ nodemon app.js
```
## 🛠 Technology used

### Front-end

* [ejs](http://ejs.co/)
* [Bootstrap](https://getbootstrap.com/docs/4.6/)

### Back-end

* [node](https://nodejs.org/)
* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [body-parser](https://www.npmjs.com/package/body-parser)
* [cloudinary](https://cloudinary.com/)
* [geocoder](https://github.com/wyattdanger/geocoder#geocoder)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

### Platforms
* [Google Mapbox APIs](https://docs.mapbox.com/api/search/geocoding/)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
* [Cloudinary](https://cloudinary.com/)
* [Heroku](https://www.heroku.com/)
 
## Contact

Amar Singh - [@link](https://www.linkedin.com/in/amarsingh371/) - amarsingh07171@gmail.com

Project Link: [https://github.com/EasyKiLL7/Art-Gallery](https://github.com/EasyKiLL7/Art-Gallery)
