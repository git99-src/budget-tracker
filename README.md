# budget-tracker


#Link to application:  
https://mysterious-basin-13178.herokuapp.com/

Link to GitHub repository:  
https://github.com/git99-src/budget-tracker  


## Description 
The budget tracker application allows the user to track withdrawals and deposits online. The user will be able enter the name for the transaction and the amount. If the user loses connectivity to the internet - they can continue to enter transactions which will be synched to the original database when the connection is restored. A chart is displayed to show the history of the user's balance over time.  

## Table of Contents 
  * [Installation](#installation)
  * [Usage](#usage)
  * [Development](#development)
  * [License](#license)
  * [Contributing](#contributing)
  * [Env](#env)

## Installation

If you are interested in installing and using the project, you can do so by forking the GitHub repository and cloning it to your machine.  

To use the app, simply follow the provided Heroku link. In addition to running this via the link, this web application can also be installed as a PWA onto the PC desktop or mobile device.  After navigating to the URL:

* Windows PC:

  * 1. Press the "+" in the address bar.

  * 2. Select Install.

* iOs:

  * 1. Tap the Share button in Safari.

  * 2. Tap the icon labeled Add to Home Screen.

  * 3. Tap Add in the upper-right corner.

  * 4. Name the application icon (or use default provided), then tap Add in the upper-right corner.

  
* Android:

  * 1. Tap the menu button in the upper right corner of Chrome.

  * 2. Tap the icon labeled Add to Home Screen.

  * 3. Name the application icon (or use default provided), then tap Add in the upper-right corner.


 ## Usage

The user is presented with the application screen which displays the current total balance.  There is a field to enter the name of the transaction and a field to enter the transaction amount.  Once the user enters values into these fields - they can press the Add Funds button (if the transaction will add to the balance) or the Subtract Funds button (if the transaction will remove funds from the balance).  

Once the transaction has been completed, the new balance will be displayed.  In addition, the total balance chart will update to reflect the new balance.

To use the app, simply follow the provided Heroku link at the link above. 

## Development 

The program used to write the application is VS Code. It was developed using MongoDb and Mongoose to create and design the schema. The app uses the following programming languages:    

* Back End:
   * Node.js
   * Mongoose
   * Express


* Front End: 
   * HTML
   * CSS
   * JavaScript/JQuery  

The app also uses various npm packages to run: 
* express
* mongoose
* morgan
* compression
* lite-server

The app is deployed on Heroku and uses MongoDB as a database on Heroku.  

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) MIT License  

## Contributing
Please fork the repository in Github with permission.  

## Env
Requires a ".env" file created in root.
--
**MONGODB_URI** = locationofdatabase
 
--
---