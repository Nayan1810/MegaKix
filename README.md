# MegaKix eCommerce Platform

![MegaKix Logo](app/gui/resources/logo.png)

MegaKix is an eCommerce platform developed in Python 3 using PyQt and MySQL. It aims to provide a user-friendly and secure marketplace for sneakers and shoes, catering to both buyers and sellers. The platform offers a GUI-based interface, a sign-up/login system for buyers and sellers, real-time updates on order activities, an admin panel for platform management, and a formidable MySQL database system for data storage.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Features

- GUI-based interface for a user-friendly experience.
- Secure sign-up and login system for both buyers and sellers.
- Real-time updates for order and purchase activities.
- Admin panel for managing products, users, and orders.
- Password hashing for enhanced security.
- Formidable MySQL database system for robust data storage.

## Installation

To run the MegaKix eCommerce platform on your local machine, follow these steps:

1. Clone the repository to your local machine using:

   ```git clone https://github.com/your-username/MegaKix.git```

2. Install the required Python packages listed in `requirements.txt`. It is recommended to create a virtual environment first:

   ```cd MegaKix
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   pip install -r requirements.txt```

3. Set up the MySQL database by running the `schema.sql` script in the `database` directory.

4. Update the database connection details in `database/database.py` with your MySQL credentials.

## Usage

1. Activate the virtual environment (if you haven't already):

   ```source venv/bin/activate  # On Windows, use: venv\Scripts\activate```


2. Run the MegaKix application:

   ```python app/main.py```

3. The GUI application will launch, allowing you to access the platform as a buyer, seller, or administrator.

## Testing

You can run unit tests for the database interactions and GUI components using the following commands:

`python -m unittest tests.test_database
python -m unittest tests.test_gui`


## Contributing

Contributions to MegaKix are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

1. Fork the repository and create your branch: `git checkout -b feature/my-feature`.
2. Commit your changes: `git commit -m "Add my feature"`.
3. Push to the branch: `git push origin feature/my-feature`.
4. Open a pull request.

Please ensure that your code follows the project's coding standards and passes the tests before submitting a pull request.

## License

This project is licensed under the [MIT License]

---
Developed by Team LB for MegaKix eCommerce Platform.
