
# Online Movie Ticket Booking System

## Demo
https://book-me-show-wps3.vercel.app/

## Overview

This project is a full-stack web application for an online movie ticket booking system. Users can view available movies, select their preferred seats from an interactive seat map, make payments, and receive a ticket and slip upon successful booking. The system is built using React.js for the frontend, Node.js and Express.js for the backend, and MongoDB for the database.

## Features

- **Movie Listings**: View a list of available movies.
- **Interactive Seat Selection**: Select seats from a dynamic seat chart.
- **User Authentication**: Sign up and log in to book tickets.
- **Payment Gateway**: Complete the booking by making a payment.
- **Booking Confirmation**: Receive a ticket and slip after successful payment.
- **Admin Panel**: Manage movies, schedules, and bookings.

## Technologies Used

- **Frontend**: React.js, CSS, HTML
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Gateway**: [Specify the payment gateway used, e.g., Stripe, PayPal]
- **Other Tools**: Axios (for HTTP requests), Mongoose (for MongoDB object modeling)

## Installation

### Prerequisites

- Node.js
- npm
- MongoDB

### Steps

1. **Clone the repository**
   \`\`\`bash
   git clone https://github.com/your-username/online-movie-ticket-booking-system.git
   cd online-movie-ticket-booking-system
   \`\`\`

2. **Install frontend dependencies**
   \`\`\`bash
   cd client
   npm install
   \`\`\`

3. **Install backend dependencies**
   \`\`\`bash
   cd ../server
   npm install
   \`\`\`

4. **Set up MongoDB**
   - Ensure MongoDB is running on your machine or use a cloud-based MongoDB service.
   - Create a \`.env\` file in the \`server\` directory and add your MongoDB URI:
     \`\`\`plaintext
     MONGODB_URI=mongodb://localhost:27017/your-database-name
     \`\`\`

5. **Run the application**
   - Start the backend server:
     \`\`\`bash
     cd server
     npm start
     \`\`\`
   - Start the frontend development server:
     \`\`\`bash
     cd ../client
     npm start
     \`\`\`

6. **Access the application**
   - Open your browser and navigate to \`http://localhost:3000\`

## Usage

1. **Sign Up / Log In**
   - Create an account or log in to your existing account.

2. **Browse Movies**
   - View the list of available movies.

3. **Select Seats**
   - Click on a movie to view its seating chart and select your seats.

4. **Make Payment**
   - Proceed to payment and complete the transaction.

5. **Receive Ticket**
   - After successful payment, receive your ticket and booking slip.

## Contributing

1. Fork the repository.
2. Create a new branch: \`git checkout -b feature-branch-name\`
3. Make your changes and commit them: \`git commit -m 'Add some feature'\`
4. Push to the branch: \`git push origin feature-branch-name\`
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Payment Gateway used]

## Contact

For any inquiries, please contact Anuj Pandey at [anujpandey0513@gmail.com].
