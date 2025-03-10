1. Clone the repository:
2. Open app.py
3. Create a virtual network  `python -m venv venv`
4. Install all dependencies using `pip install -r requirements.txt`
5. To run the server type `./run.sh`
6. Open http://localhost:5000 and display the webpage

## Technology Stack

- **Flask** - Flask is a lightweight web framework written in Python. It is used for creating the web application and handling routing.
- **HTML** - HTML (Hypertext Markup Language) is the standard markup language for creating the structure and content of web pages. It is used for defining the user interface of the application.
- **JavaScript** - JavaScript is a programming language that enables interactivity and dynamic functionality in web pages. It is used in the Payment APP for handling user actions, interacting with the Ethereum blockchain using web3.js, and manipulating the DOM (Document Object Model).
- **web3.js** - web3.js is a JavaScript library that provides an interface for interacting with the Ethereum blockchain. It is used in the Payment APP for connecting to MetaMask, retrieving wallet balance, and sending transactions.
- **CSS** - CSS (Cascading Style Sheets) is a stylesheet language used for describing the presentation and styling of a document written in HTML. It is used in the Payment APP for styling the user interface elements.

- **MetaMask**- MetaMask is a browser extension that allows users to manage Ethereum wallets and interact with Ethereum-based applications. It is used in the Payment APP to connect the user's wallet and facilitate transactions.

- **lottie-player.js**- lottie-player.js is a JavaScript library for rendering animations using Lottie files. It is used in the Payment APP for displaying animations in the transaction details popup.


## File Structure
The relevant files and their descriptions in the project are as follows:

- **app.py**: The main Flask application file that handles routing and serves the web pages.
- **templates/index.html**: The HTML file containing the user interface and JavaScript code for the Payment APP.
- **static/images/QR.png**: The QR code image file that can be scanned to access the application using a mobile Ethereum wallet.

## Usage

The Payment APP provides the following functionalities:

- ***Connect Wallet***: Allows users to connect their wallets with MetaMask.

- ***Get Balance of Wallet***: Retrieves and displays the balance of the connected wallet.

- ***Transfer Funds***: Enables users to transfer funds to another Ethereum address. Users need to enter the recipient's address and the transfer amount. Upon successful transfer, a transaction details popup will be displayed with the transaction amount and ID.

- ***QR Code***: Displays a QR code that can be scanned to access the application using a mobile Ethereum wallet.#   S t a r t u p s t r u d s  
 