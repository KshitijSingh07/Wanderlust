# Wanderlust

Wanderlust is a full-stack travel listing web application inspired by Airbnb, where users can explore, create, edit, and manage travel accommodation listings. The platform provides an interactive and responsive interface for discovering unique stays around the world.

---

## Features

- User Authentication & Authorization
- Create, Edit, and Delete Listings
- Upload Listing Images
- Responsive UI Design
- Review and Rating System
- Interactive Listing Pages
- Secure Session Handling
- Flash Messages & Form Validation
- MongoDB Database Integration

---

## Tech Stack

### Frontend
- HTML
- CSS
- Bootstrap
- JavaScript
- EJS Templates

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- Passport.js
- Express Session

### Cloud & Utilities
- Cloudinary
- Multer
- Connect Flash

---

## Project Structure

```bash
Wanderlust/
│── models/
│── routes/
│── controllers/
│── views/
│── public/
│── utils/
│── app.js
│── package.json
│── .env
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Wanderlust.git
cd Wanderlust
```

Install dependencies:

```bash
npm install
```

Create a `.env` file and add:

```env
ATLASDB_URL=your_mongodb_url
SECRET=your_secret_key
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_secret
```

Run the server:

```bash
node app.js
```

---

## Usage

- Register/Login to your account
- Create travel accommodation listings
- Upload images for listings
- Browse listings from different locations
- Add reviews and ratings
- Edit or delete your own listings

---

## Future Improvements

- Booking System
- Payment Gateway Integration
- Wishlist Feature
- Map Integration
- Search & Filter Functionality
- Real-time Chat Support

---

## Author

**Kshitij Singh**  
B.Tech CSE, IIIT Manipur

GitHub: https://github.com/KshitijSingh07
