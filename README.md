# Personal Finance

A web application that helps users track their financial transactions, calculate monthly balances, and generate financial insights. Built with the MERN stack, Clerk.io for authentication, and JWT for session management.

## Features

- **User Authentication**: Secure login and registration system with Clerk.io authentication and JWT-based session management.
- **Financial Data Storage**: Store user transaction data and calculate monthly balances using MongoDB.
- **Dynamic Transaction Processing**: Automatically calculate and update balances for users as transactions are recorded.
- **Financial Insights**: Display insights into user finances, including monthly spending patterns and savings trends.

## Tech Stack

- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Clerk.io, JWT
- **State Management**: React Context API

## Setup

To get this project up and running on your local machine, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/personal-finance-app.git
cd personal-finance-app
```

### 2. Install Dependencies

For the backend:
```bash
cd backend
npm install
```

For the frontend:
```bash
cd frontend
npm install
```

### 3. Configuration

Set up the necessary environment variables:

* For the backend, create a .env file and add the following configuration:
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLERK_API_KEY=your_clerk_api_key
```

* For the frontend, configure the Clerk.io API key:
```bash
REACT_APP_CLERK_FRONTEND_API=your_clerk_frontend_api
```

### 4. Run the Application
* Start the backend server:
```bash
cd backend
npm start
```

* Start the frontend server:
```bash
cd frontend
npm start
```

Visit http://localhost:3000 in your browser to see the app in action.

## Usage

- **Sign Up / Log In**: Use Clerk.io authentication to create an account or log in.
- **Add Transactions**: Record your income and expenses to keep track of your finances.
- **View Financial Insights**: See your balance and financial trends for the current month.
- **Security**: JWT-based session management ensures that your data is securely stored and protected.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Roadmap

**Future Enhancements:**
- Add integration with third-party financial APIs for automatic transaction tracking.
- Support for multi-currency.
- Add expense categorization for detailed financial reports.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Contact

For any questions or feedback, feel free to reach out:

- Allan Emmanuel
- allanfrelens@gmail.com
