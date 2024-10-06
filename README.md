# Money Tracker App

A simple Money Tracker App that allows users to track their income and expenses. This app provides the ability to add categories, amounts, and additional information, and maintains a dynamic total balance that updates as users add income or expenses.

## Features

- Track income and expenses with relevant details like category, amount, information, and date.
- Add, delete, and display all transactions in a table format.
- Real-time calculation of total balance (income minus expenses).
- Stores data using MongoDB.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (using Mongoose)
- **Other**: Bootstrap for styling

## Prerequisites

Make sure you have the following installed on your system:

- Node.js (v14+)
- MongoDB (v4+)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/money-tracker-app.git
2. Navigate to the project directory:

Change into the project directory with the following command:

cd money-tracker-app
3. Install the required dependencies:

Make sure you have Node.js installed. Run the following command to install all the necessary packages defined in package.json:
npm install
4. Set up MongoDB:

Ensure that you have MongoDB running on your local machine. If you're using MongoDB Atlas, make sure to connect your application to your cluster. Update your connection string in the app.js file as needed.

5. Start the server:

Launch the server using Node.js by executing:

node app.js
6. Open your browser:

Navigate to the following URL in your web browser to access the application:

http://localhost:3000
##Project Structure
money-tracker-app/
│
├── public/                 # Frontend code
│   ├── index.html          # Main HTML file
│   ├── style.css           # CSS file for styling
│   └── script.js           # JavaScript file for frontend functionality
│
├── app.js                  # Main Node.js file for the backend
├── package.json            # Contains dependencies and project metadata

└── README.md               # Project documentation

##Usage
Add a Transaction
To add a transaction, fill in the form fields with the following details:

Category: Choose between "Income" or "Expense."
Amount: Enter the amount of the transaction.
Info: Provide additional information about the transaction.
Date: Select the date of the transaction.
Click the "Add" button to save the transaction. The transaction will be added to the list, and the total balance will be updated.

View Transactions
All the added transactions will be displayed in a table format below the form. Each transaction entry will show the category, amount, information, and date.

Delete a Transaction
If you wish to remove a transaction, click the "Delete" button next to the transaction. The transaction will be removed from the list, and the total balance will be adjusted accordingly.

![Screenshot 2024-10-06 115331](https://github.com/user-attachments/assets/c59db5a4-16c0-4829-a285-d15e8cac93cd)

##Contributing
Contributions to the project are welcome! If you have any improvements, bug fixes, or new features you'd like to suggest, please feel free to:

Fork the repository.
Create a new branch for your feature or bugfix.
Make your changes and commit them.
Push to your fork and open a pull request.
