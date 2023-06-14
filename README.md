# Sport Ease - Turf Booking Management System

Sport Ease is a comprehensive turf booking management system designed to simplify the process of booking and managing turf facilities. This project utilizes the Spring Boot framework for the backend, MySQL as the database management system, and React.js for the frontend development.

## Features

- User Registration and Authentication: Allows users to create an account and authenticate themselves for accessing the system.
- Turf Listing: Provides a list of available turf facilities, their details, and booking status.
- Turf Booking: Enables users to book turf slots based on availability.
- Booking Management: Allows users to view and manage their bookings, including cancellation and rescheduling.
- Admin Dashboard: Provides administrators with privileged access to manage turfs, bookings, and user accounts.
- Payment Integration: Supports secure payment processing for booking confirmations.

## Technologies Used

- Spring Boot: A Java-based framework used for developing the backend of the application.
- MySQL: A popular relational database management system used for storing and managing data.
- React.js: A JavaScript library used for building the user interface and frontend components.
- HTML/CSS: Standard web technologies used for structuring and styling the application.
- Git: Version control system used for tracking changes and collaborating on the project.
- GitHub: Hosting platform for the Git repository and project management.

## Setup Instructions

1. **Clone the repository:** Start by cloning the repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/sport-ease.git
   ```

2. **Backend Setup:**
   - Navigate to the `backend` directory.
   - Configure the MySQL database connection details in `src/main/resources/application.properties`.
   - Build and run the backend server using your preferred IDE or the following command:

     ```
     ./mvnw spring-boot:run
     ```

3. **Frontend Setup:**
   - Navigate to the `frontend` directory.
   - Install the required dependencies by running the following command:

     ```
     npm install
     ```

   - Configure the backend server URL in `src/config.js`.
   - Start the development server using the following command:

     ```
     npm start
     ```

4. **Accessing the Application:**
   - Open your web browser and visit `http://localhost:3000` to access the Sport Ease application.

## Contributing

Contributions to Sport Ease are welcome! If you find any bugs or have suggestions for new features, please open an issue on the GitHub repository. If you'd like to contribute code, you can fork the repository, make your changes, and submit a pull request.

Before contributing, please read the [contribution guidelines](CONTRIBUTING.md) for detailed information on the development process, coding standards, and more.


We hope you find Sport Ease useful and enjoy using it as a turf booking management system. Happy coding!
