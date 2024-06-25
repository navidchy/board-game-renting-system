# Board Game Renting System

## Overview
This project involves creating a system with an administrative interface and a game catalogue, built using Java and JavaFX. The application follows the Model-View-Controller (MVC) architecture.

## Features
### Administrative Section
- **Add and Remove Customers**: Manage customer records by adding or removing customers.
- **Add and Remove Games**: Manage the game catalogue by adding or removing games.
- **Display Customer Records**: View detailed records of customers, including their current balance and rental history.
- **Top-up Customer Accounts**: Allow customers to add funds to their accounts.
- **View Customer's Favorite Games**: Display the top 3 most rented games for a customer.

### Game Catalogue
- **Store Game Information**: Manage a list of all games, including their genres and availability.
- **Display Games**: Show games based on availability, genre, and year.
- **Handle Rentals**: Rent out and return games through the system.

## Screens and Functionalities
### Main Menu
- Access the catalogue, view customer records, top-up an account, view customers’ favorite games, and access the administration menu.

### Administration Menu
- **Add Customer**: Enter customer ID, name, and balance.
- **Add Game**: Enter game title, year, genre, and price.
- **Remove Customer and Game**: Display and remove items via tables.

### Customer Record and Favorite Games
- Display customer record and favorite games.
- Input customer ID to refresh the display.

### Catalogue Menu
- Interact with the catalogue to show all games or available games.

### Game Browsing
- Browse games by genre and year.

### Rent and Return Games
- **Rent a Game**: Input customer ID, select a game to rent.
- **Return a Game**: Input customer ID, select a game to return.

### Account Top-Up
- Top-up account by entering customer ID and top-up amount.

## Technologies Used
- **Java**: For application logic.
- **JavaFX**: For graphical user interface.
- **MVC Architecture**: For structuring the application.
- **FXML**: For defining the UI layout.

## Getting Started
### Prerequisites
Ensure you have Java installed. You can download it from [here](https://www.oracle.com/java/technologies/javase-downloads.html).

### Running the Application
To run the project, execute the JAR file:
```sh
java -jar path/to/your.jar
