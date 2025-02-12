# NextNest

NextNest is a JavaFX-based desktop application designed to help users find to-lets, homes for rent, homes for sale, and sell properties. It provides an interactive interface for buyers and sellers, including features like image and video uploads, 360-degree views, and a messaging system for direct communication.

## Features
- **Property Listings**: Browse available properties with images and descriptions.
- **Search & Filter**: Find properties based on location, price, and preferences.
- **Post Creation**: Users can add property details, upload images, and create listings.
- **Live Chat**: Real-time messaging between users and property owners.
- **Review & Complaints**: A section for users to share their experiences.
- **Modern UI**: JavaFX-based design with Scene Builder.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nextnest.git
   ```
2. Open the project in an IDE (IntelliJ IDEA or Eclipse) with JavaFX support.
3. Set up the database:
   - MySQL is required.
   - Database name: `nextnest`
   - Tables: `users`, `post_info`
   - Update `DatabaseUtil.java` with your MySQL credentials.
4. Run the application from the main JavaFX class.

## Technologies Used
- **JavaFX** for UI
- **Scene Builder** for designing FXML layouts
- **MySQL** for database management
- **JDBC** for database connectivity

## Contributors
- **Md. Injabin Alam** (Project Lead & Developer)

## License
This project is open-source under the MIT License.

---
Feel free to contribute and improve the project!
