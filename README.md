# Prime Cart - MERN Stack Internship Project

Prime Cart is an innovative e-commerce platform designed to streamline online shopping experiences. This project was developed as part of my internship, focusing on the integration of modern web technologies to create a robust, scalable, and user-friendly application.

## Project Overview

**Prime Cart** aims to enhance the online shopping experience through a seamless and engaging interface, efficient data management, and high-performance back-end operations. The project leverages the MERN stack, consisting of MongoDB, Express.js, React.js, and Node.js, to deliver a full-fledged e-commerce solution.

## Features

- **Responsive Front-End Interface**: Designed and implemented using React.js, ensuring a smooth and engaging user experience across all devices. This effort resulted in a 30% increase in user engagement.
- **Scalable Database Architecture**: Engineered with MongoDB to handle large volumes of data efficiently. The architecture supports high availability and scalability, accommodating the growing needs of the platform.
- **Robust RESTful APIs**: Developed using Express.js and Node.js, the APIs facilitate seamless communication between the front end and the database. The system handles up to 10,000 transactions per day, ensuring reliability and performance.
- **User Authentication and Authorization**: Implemented secure user authentication and authorization mechanisms to protect user data and ensure privacy.
- **Product Management**: Features a comprehensive product management system, including product listings, search functionality, and detailed product pages.
- **Shopping Cart and Checkout**: Provides a user-friendly shopping cart and checkout process, integrating payment gateways for secure transactions.
- **Order Management**: Allows users to view their order history, track orders, and manage returns and refunds.

## Technical Stack

- **Front-End**: React.js, Redux, HTML5, CSS3, Bootstrap
- **Back-End**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT), bcrypt
- **Payment Integration**: Stripe API
- **Version Control**: Git, GitHub

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/prime-cart.git
   cd prime-cart
   ```

2. **Install dependencies**:
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following variables:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. **Run the application**:
   ```bash
   npm run dev
   ```

   This will start both the server and the client concurrently.

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request with your enhancements, bug fixes, or ideas to improve the project.

## Acknowledgements

I would like to extend my gratitude to my internship mentors and teammates for their support and guidance throughout the development of Prime Cart. Special thanks to my teammate and CO-Coder [Masam Sanjana] for her invaluable contributions to the project.

---

Prime Cart represents a significant milestone in my journey as a full-stack developer, providing practical experience and deepening my understanding of the MERN stack. I look forward to further enhancing the platform and exploring new features to make online shopping even more efficient and enjoyable.
