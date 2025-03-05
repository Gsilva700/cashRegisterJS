Cash Register App 💰


The Cash Register App is a web application that calculates the change to be returned to a customer based on the price of an item, the cash provided, and the cash available in the cash drawer. It handles various scenarios, such as insufficient funds or exact change, and displays appropriate messages to the user.

This project was built as part of the freeCodeCamp curriculum and simulates a real-world cash register system.

Features ✨


Dynamic Change Calculation:

Calculates the change to be returned based on the available cash in the drawer.

Status Messages:

Status: OPEN: If the cash drawer has enough funds to return the exact change.

Status: CLOSED: If the cash drawer has exactly the amount of change due.

Status: INSUFFICIENT_FUNDS: If the cash drawer does not have enough funds to return the exact change.

Currency Handling:

Supports standard US currency denominations (e.g., pennies, nickels, dimes, quarters, dollars, etc.).

User-Friendly Interface:

Simple and intuitive design for easy use.

How It Works 🛠️


Input:

Enter the price of the item and the cash provided by the customer.

Calculation:

The app calculates the change due and checks if the cash drawer has enough funds to return the exact change.

Output:

Displays the status (OPEN, CLOSED, or INSUFFICIENT_FUNDS) and the breakdown of the change to be returned.

User Stories Implemented ✅


The app has an input field for the cash provided by the customer.	✔️
The app displays the change due in a structured format.	✔️
The app handles scenarios where the customer provides insufficient cash.	✔️
The app handles scenarios where the cash drawer has insufficient funds.	✔️
The app handles scenarios where the customer provides exact cash.	✔️
The app supports standard US currency denominations.	✔️

Technologies Used 💻

HTML: For structuring the app.

CSS: For styling the app.

JavaScript: For handling the logic and calculations.

Setup Instructions 🚀

Clone the Repository:

bash
Copy
git clone https://github.com/Gsilva700/cash-register-app.git
cd cash-register-app
Open the App:

Open the index.html file in your browser.

Use the App:

Enter the price of the item and the cash provided by the customer.

Click the "Purchase" button to see the change due.

Example Usage 📋
Scenario 1: Exact Change
Price: 19.50

Cash: 20.00

Cash Drawer:

json


[
  ["PENNY", 1.01],
  ["NICKEL", 2.05],
  ["DIME", 3.1],
  ["QUARTER", 4.25],
  ["ONE", 90],
  ["FIVE", 55],
  ["TEN", 20],
  ["TWENTY", 60],
  ["ONE HUNDRED", 100]
]
Output:


Status: OPEN QUARTER: $0.5
Scenario 2: Insufficient Funds
Price: 19.50

Cash: 20.00

Cash Drawer:

json

[
  ["PENNY", 0.01],
  ["NICKEL", 0],
  ["DIME", 0],
  ["QUARTER", 0],
  ["ONE", 0],
  ["FIVE", 0],
  ["TEN", 0],
  ["TWENTY", 0],
  ["ONE HUNDRED", 0]
]
Output:


Status: INSUFFICIENT_FUNDS


Code Structure 🗂️

cash-register-app/
├── index.html          # Main HTML file
├── styles.css          # CSS for styling
├── script.js           # JavaScript for logic
├── README.md           # Project documentation
└── screenshot.png      # Screenshot of the app (optional)




Credits 🙌
Built by Gabriel de Macedo Silva.

Inspired by freeCodeCamp.

 
Contributions are welcome! 🤝

