
## Features

### Responsive design

![homepage](images/homepage.jpg)

### Index page of campgrounds with a ClusterMap

![campground index page](images/index-page.jpg)

### Campground details and its reviews

![campground details](images/campground-details.jpg)

### Making new campground and editing previous posts (authentication required)

![create and edit campgrounds](images/create-and-edit.jpg)

## Implementation

### Languages

- JavaScript
- EJS
- CSS

### Tools

- Node.js
- Express
- Bootstrap v5.0
- MongoDB
- NPM tools:
  - Mongoose
  - Passport.js: handle authentication
  - Joi: schema description & data validation
  - helmet: helps secure the app by setting various HTTP headers
  - express-mongo-sanitize: prevent MongoDB Operator Injection

### Services

- [Cloudinary](https://cloudinary.com/): store the images that users upload
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas): store the data of campground, reviews and users
- [Mapbox](https://www.mapbox.com/): provide interactive maps to mark the locations of campgrounds