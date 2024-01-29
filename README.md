# Product Management System

This C++ program implements a simple product management system using a linked list data structure. The program allows users to insert, remove, and consult the price of products in the list. Product information is stored in a file, and the program reads and writes data to/from this file.

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [Usage](#usage)
- [File Format](#file-format)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/product-management-system.git
    ```

2. Compile the program:

    ```bash
    g++ main.cpp -o product_management
    ```

3. Run the program:

    ```bash
    ./product_management
    ```

## Features

1. **Insert Product**: Users can add new products to the list.

2. **Remove Product**: Products can be removed from the list based on their code.

3. **Consult Price**: Users can check the price of a product by entering its code.

4. **File Persistence**: Product information is stored in a file (`list.txt`) and is read/written by the program.

## Usage

The program presents a menu with options to perform various operations. Follow the on-screen instructions to interact with the system.

- **Insert Product (Option 1)**: Enter the code, name, and price of the new product.

- **Remove Product (Option 2)**: Enter the code of the product to be removed.

- **Consult Price (Option 3)**: Enter the code of the product to check its price.

- **Exit (Option 4)**: Save the current product list to the file and exit the program.

## File Format

The product information is stored in a text file (`list.txt`). Each line in the file represents a product with the format:

*code* *name* *price*

Example:

101 Laptop 1200.50

102 Smartphone 699.99

## Contributing

Feel free to contribute to this project by submitting pull requests. If you find any issues or have suggestions, please open an issue.

## License

This project is licensed under the [MIT License](LICENSE).
