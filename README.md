# 🏠 Airbnb Clone  

link-https://bookmyroom-one.vercel.app

A full-stack Airbnb clone that allows users to book vacation rentals, list properties, and explore unique stays around the world.  

## 🚀 Features  

### User Features  
- User authentication (Sign up, Login, Logout)  
- Search and filter listings by location, price, and amenities  
- Book and manage reservations  
- Review and rate properties  
- Responsive design for mobile and desktop  

### Host Features  
- List new properties with images, pricing, and availability  
- Manage property details and booking requests  
- View and respond to guest reviews  

### Admin Features  
- Manage users, listings, and reservations  
- Monitor platform activity and analytics  

## 🛠️ Tech Stack  

### Frontend  
- **React / Next.js** – For a fast and responsive user interface  
- **Tailwind CSS** – For modern, responsive styling  

### Backend  
- **Node.js / Express** – RESTful API for managing data  
- **MongoDB / PostgreSQL** – Database for storing user, listing, and reservation information  

### Authentication  
- **JWT (JSON Web Tokens)** – Secure user authentication and session management  

### Deployment  
- **Docker** – Containerized application for easy deployment  
- **Vercel / AWS** – Cloud hosting for frontend and backend  

## 📦 Installation  

1. **Clone the repository:**  
```bash
git clone https://github.com/yourusername/airbnb-clone.git
cd airbnb-clone
```

2. **Set up environment variables:**  
Create a `.env` file in the root directory and add:  
```bash
DATABASE_URL=your_database_url
JWT_SECRET=your_secret_key
CLOUDINARY_URL=your_cloudinary_url
```

3. **Install dependencies:**  
```bash
# For the backend
cd server && npm install

# For the frontend
cd client && npm install
```

4. **Run the development servers:**  
```bash
# Start backend
cd server && npm run dev

# Start frontend
cd client && npm run dev
```

## 📊 Database Schema  
- **User**: id, name, email, password, avatar, isHost  
- **Listing**: id, title, description, location, price, amenities, hostId  
- **Reservation**: id, userId, listingId, checkIn, checkOut, totalPrice  
- **Review**: id, userId, listingId, rating, comment  

## ✅ Future Improvements  
- Payment integration (Stripe)  
- Advanced search with map view  
- Chat system between hosts and guests  
- Wishlist feature  

## 🤝 Contributing  
Contributions are welcome!  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature-name`)  
5. Open a Pull Request  

## 📄 License  
This project is licensed under the **MIT License**.  

## 📧 Contact  
For any questions, reach out via:  
- **Email:** panwarhp2351@gmail.com  
- **GitHub:** [yashpanwar-hub](https://github.com/yashpanwar-hub)  
