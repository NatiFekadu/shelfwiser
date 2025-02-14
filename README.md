# Shelfwiser Library Management Application

Shelfwiser is a comprehensive library management application built using the Frappe framework. It helps libraries manage their books, members, and transactions efficiently.

<!-- ## Features

- **Book Management**: Add, update, and delete book records.
- **Member Management**: Register new members and manage existing ones.
- **Transaction Management**: Issue and return books, track due dates, and manage fines. -->
<!-- - **Reports**: Generate various reports for books, members, and transactions. -->

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Natifekadu/shelfwiser.git
    ```
2. Navigate to the project directory:
    ```bash
    cd shelfwiser
    ```
3. Install the required dependencies:
    ```bash
    bench init
    ```
4. Set up the Frappe site:
    ```bash
    bench new-site shelfwiser.local
    ```
5. Install the Shelfwiser app:
    ```bash
    bench get-app shelfwiser
    bench --site shelfwiser.local install-app shelfwiser
    ```
6. Start the Frappe development server:
    ```bash
    bench start
    ```

## Usage

1. Open your web browser and navigate to `http://library.localhost:8000/`.
2. Log in with your credentials.
3. Use the dashboard to manage books, members, and transactions.

## Contributing

We welcome contributions to Shelfwiser! Please fork the repository and submit pull requests.

## License

Shelfwiser is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or support, please contact us at Natifekadu808@gmail.com