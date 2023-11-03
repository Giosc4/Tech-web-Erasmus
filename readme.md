# Project Readme

This project is a full-fledged eCommerce website with administrative functionalities built using Node.js and Express.

## Setup

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine. You can download and install Node.js from the official website [here](https://nodejs.org/). npm (Node Package Manager) is included in the Node.js installation.
- PostgreSQL database is installed and configured. You can download and install PostgreSQL from the official website [here](https://www.postgresql.org/download/).

### Installation Steps

1. **Clone the repository:**

    ```
    git clone https://github.com/your-username/your-repo.git
    ```
    
2. **Navigate to the repository folder:**

    ```
    cd your-repo
    ```

3. **Install dependencies:**

    ```
    npm install
    ```


4. **Run the server:**

    ```
    node src/server.js
    ```

### Accessing the Website

Once the server is running, you can open the website by visiting `http://localhost:3000` in your browser.

### Admin Panel

To access the admin panel, visit `http://localhost:3000/admin`. 

## API Endpoints

- GET `/search_products` - Search for products based on a query string
- GET `/search_product` - Search for a single product
- GET `/fetch_products` - Fetch all products
- POST `/authenticate` - Handle user login
- POST `/paymentForm` - Handle payment form submission
- GET `/getPaymentFormData` - Get payment form data
- PUT `/updatePaymentStatus/:id` - Update the payment status of a form
- POST `/adminAdd` - Add a new product (admin only)
- PUT `/adminEdit/:id` - Edit an existing product (admin only)
- DELETE `/delete/:id` - Delete a product (admin only)
- POST `/logout` - Handle user logout

## Authors

This project is developed and maintained by:

- Yacine Chettab
- Giovanni Maria Savoca

## Contact

If you have any questions or would like to contribute, feel free to reach out to us.

## Contributing

If you wish to contribute to this project, please fork the repository and make a pull request.

## License

This project is open source under the MIT license.