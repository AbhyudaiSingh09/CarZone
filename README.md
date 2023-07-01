# CarZone
# CarZone

CarZone is a web application that allows users to buy and sell cars online. It provides a platform for car dealerships and individual sellers to list their cars for sale, and for potential buyers to browse and search for cars based on their preferences.

This repository contains the source code for the CarZone web application. The application is built using the following technologies:

- Front-end:
  - HTML
  - CSS
  - JavaScript
  - Bootstrap (CSS framework)
  - React (JavaScript library)

- Back-end:
  - Node.js
  - Express (web framework)
  - MongoDB (database)
  - Mongoose (ODM)

## Features

CarZone offers the following features:

- User registration and authentication: Users can create an account and log in to the application. Authentication is implemented using JSON Web Tokens (JWT).

- Car listing: Sellers can create listings for their cars, providing details such as make, model, year, price, mileage, and description. They can also upload multiple images of the car.

- Car search and filtering: Buyers can search for cars based on various criteria, such as make, model, year, price range, and mileage. The search results can be filtered and sorted based on different parameters.

- Car details: Users can view detailed information about a car, including the seller's contact information and location.

- User profiles: Each user has a profile page where they can view and manage their listings, as well as update their personal information.

- Messaging: Users can communicate with each other through a messaging system to discuss car details, negotiate prices, and arrange test drives.

## Getting Started

To run the CarZone web application locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/Axs7941/CarZone.git
   ```

2. Install the dependencies for the server:

   ```
   cd CarZone/server
   npm install
   ```

3. Set up the environment variables:

   - Create a `.env` file in the `server` directory.
   - Define the following environment variables in the `.env` file:
     - `JWT_SECRET`: Secret key used for JWT authentication.
     - `MONGODB_URI`: MongoDB connection URL.

4. Start the server:

   ```
   npm start
   ```

5. Install the dependencies for the client:

   ```
   cd ../client
   npm install
   ```

6. Start the client:

   ```
   npm start
   ```

7. Open a web browser and navigate to `http://localhost:3000` to access the CarZone application.

## Contributing

Contributions to CarZone are welcome! If you find a bug or have a suggestion for improvement, please open an issue in the GitHub repository. If you would like to contribute code, you can fork the repository and create a pull request with your changes.

When contributing to this project, please follow the existing coding style and conventions. Ensure that your code is well-tested and documented.

## License

CarZone is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code for personal or commercial purposes.

## Acknowledgments

CarZone was developed as a project for educational purposes. It is not affiliated with any real car dealership or company.

Special thanks to the contributors of the open-source libraries and frameworks used in this project.

## Contact

If you have any questions or inquiries, please contact the project maintainer at carzone@example.com.
