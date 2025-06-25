# 🌍 Travel-Smart

**Travel-Smart** is a full-stack web application designed to simplify and enhance the way users explore, review, and share travel destinations. From curated listings to real-time reviews, Travel-Smart brings travel planning to your fingertips.

---


## 📂 File Structure

```plaintext
StaySmart/
├── .git/                         # Git configuration and metadata
│   ├── ...
├── .github/                      # GitHub-specific files
│   ├── workflows/                # GitHub Actions workflows
│   │   ├── ...
│   └── ...
├── controllers/                  # Controllers for handling requests
│   ├── ...
│   └── ...
├── models/                       # Data models or schemas
│   ├── User.js
│   ├── Listing.js
│   └── ...
├── public/                       # Public static files
│   ├── assets/                   # Static assets (images, fonts, etc.)
│   │   ├── logo.png
│   │   └── ...
│   ├── index.html                # Main HTML file
│   ├── favicon.ico               # Favicon
│   └── manifest.json             # Web app manifest
├── routes/                       # Route definitions
│   ├── index.js
│   └── ...
├── utils/                        # Utility functions and helpers
│   ├── formatDate.js
│   └── ...
├── views/                        # Views for rendering templates
│   ├── Home.js
│   ├── Listings.js
│   └── ...
├── .env                          # Environment variables
├── .gitignore                    # Git ignore file
├── README.md                     # Project documentation
├── SECURITY.md                   # Security-related documentation
├── app.js                        # Main application entry point
├── cloudConfig.js                # Configuration for cloud services
├── middleware.js                 # Middleware for request processing
├── package-lock.json             # NPM lock file
├── package.json                  # NPM package configuration
├── schema.js                     # Database schema definitions
└── vercel.json                   # Vercel deployment configuration
```

---

## 🛠 Technologies Used

- **Backend**: Node.js, Express.js
- **Templating Engine**: EJS
- **Database**: MongoDB (via Mongoose)
- **Authentication**: Passport.js
- **Image Storage**: Cloudinary
- **Validation**: Joi
- **Session & Flash Messages**: express-session, connect-flash

---

## 🧩 Travel-Smart: Key Features

<details>
<summary><strong>🔐 User Authentication and Security</strong></summary>

- **Passport Integration:** Secure sign-up and login.  
- **Express Sessions:** Persistent user sessions in MongoDB Atlas.

</details>

<details>
<summary><strong>📸 Dynamic Listing Creation</strong></summary>

- **Cloudinary Image Uploads:** Supports PNG, JPG, JPEG up to 500KB.  
- **Joi Validation:** Ensures data integrity during listing creation.

</details>

<details>
<summary><strong>🗺️ Interactive Maps and Geolocation</strong></summary>

- **Mapbox Integration:** Interactive maps with zoom and full-screen features.  
- **Geocoding:** Converts text locations to coordinates.

</details>

<details>
<summary><strong>🏨 Comprehensive Listing Details</strong></summary>

- **Detailed Information:** Displays name, location, price, and user reviews.  
- **Map Integration:** Embedded Mapbox maps for each listing.

</details>

<details>
<summary><strong>🗣️ User Reviews and Community Interaction</strong></summary>

- **Review System:** Users can leave detailed reviews.  
- **Map-Enhanced Reviews:** Reviews include geolocation data.

</details>

<details>
<summary><strong>📱 Responsive Design</strong></summary>

- **Bootstrap Framework:** Consistent UI across desktops, tablets, and mobiles.

</details>

<details>
<summary><strong>📊 Scalable Data Management</strong></summary>

- **Mongoose and MongoDB:** Flexible and scalable data storage.  
- **MongoDB Atlas:** Reliable cloud-based storage.

</details>

<details>
<summary><strong>🧱 Robust Back-End Architecture</strong></summary>

- **Express.js Framework:** Efficient server-side structure.  
- **MVC Pattern:** Organized and scalable codebase.

</details>

<details>
<summary><strong>⚡ Enhanced User Experience</strong></summary>

- **Interactive Elements:** Zoomable and full-screen maps.  
- **Performance Optimization:** Quick load times with Cloudinary.

</details>

<details>
<summary><strong>✅ Comprehensive Schema Validation</strong></summary>

- **Joi Validation:** Maintains data consistency and integrity.

</details>

<details>
<summary><strong>🛡️ Secure and Efficient Middleware</strong></summary>

- **Express Middleware:** Manages request processing and authentication.

</details>

<details>
<summary><strong>☁️ Scalable Cloud Integration</strong></summary>

- **Cloudinary for Image Management:** Efficient media handling.  
- **MongoDB Atlas for Data Storage:** Reliable and scalable solutions.

</details>

## Environment Variables

```javascript
CLOUD_NAME=
CLOUD_API_KEY=
CLOUD_API_SECRET=
MAP_TOKEN=
ATLASDB_URL=
SECRET=dtrvstyjtvhdtcd
```

---
## 🤝 Contribution
Contributions are welcome! Feel free to fork the repo, create issues, or submit pull requests to enhance features or improve UI/UX.

---
## 📬 Contact

For questions, ideas, or feedback, feel free to reach out via email:  
[📧 shyamkk.work@gmail.com](mailto:shyamkk.work@gmail.com)

