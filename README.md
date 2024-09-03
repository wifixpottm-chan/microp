# Online Trading Platform - Frugal Flow

## Project Overview

**Frugal Flow** is an online trading platform designed to facilitate the buying and selling of shop ownership in the form of stocks. The platform allows local businesses to raise capital by listing a portion of their ownership as stocks, creating a dynamic marketplace for traders and listing entities. It aims to enhance the online stock trading experience with an intuitive interface, robust trade management, and data-driven insights.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Database Design](#database-design)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Accounts:** Create and manage trader and listing entity accounts.
- **Stock Trading:** Buy and sell stocks seamlessly with a user-friendly interface.
- **Portfolio Management:** View and manage stock portfolios, monitor stock performance.
- **Stock Listing:** Listing entities can list stocks, set initial prices, and manage stock quantity.
- **Real-Time Data:** Integrates real-time market data feeds for up-to-date stock information.
- **Secure Transactions:** Implements robust authentication and authorization mechanisms.

## Technologies Used

- **Front End:** PyQt5
- **Back End:** Python
- **Database:** MySQL
- **Database Management System:** Relational Database Management System (RDBMS)

## Installation

1. **Clone the Repository**
    ```bash
    gh repo clone wifixpottm-chan/microp
    cd online-trading-platform
    ```

2. **Install Dependencies**
    Ensure you have Python and MySQL installed on your system. Install necessary Python packages:
    ```bash
    pip install PyQt5 mysql-connector-python
    ```

3. **Database Setup**
    - Create a MySQL database named `trading_platform`.
    - Import the SQL file `schema.sql` located in the `database` folder to set up the tables.

4. **Run the Application**
    ```bash
    python main.py
    ```

## Usage

1. **Create an Account:** Users can sign up as either traders or listing entities.
2. **Login:** Access the platform using your credentials.
3. **Trade Stocks:** Browse the stock market, select stocks, and execute trades.
4. **Manage Portfolio:** View and manage your purchased stocks and their performance.

## Database Design

The database consists of five main tables:

- **account:** Stores user account information.
- **login:** Manages user login credentials.
- **portfolio:** Keeps track of stock ownership and performance for each trader.
- **shop:** Contains information about shops listed as stocks.
- **stocks:** Manages stock details listed on the platform.

## Contributing

We welcome contributions from the community! If you would like to contribute, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
