# Social Media Application

## Overview

This project is a backend development for a social media application where users can create posts, view a feed of posts, like and comment on posts, and manage user registration and authentication. The application is built using Java 17 and Spring Boot version 3.3.4.

## Features

### Core Features

1. **API Integration**
   - Implemented JWT (JSON Web Token) authentication for secure user access.
   - Efficient handling of API requests to ensure performance and security for mobile application usage.

2. **Data Storage**
   - Fetched weather data is stored in a relational database ( PostgreSQL).

3. **REST API Development**
   - Developed a RESTful API to allow the mobile application to fetch new feeds and stories from the database.

4. **API Endpoints**
   - Create a new post.
   - View a feed of posts.
   - Like a post.
   - Comment on a post.
   - Register and authenticate users.


## Technologies Used

- **Java 17**
- **Spring Boot 3.3.4**
- **JWT for authentication**
- **PostgreSQL for data storage**

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/social-media-app.git
   cd social-media-app
   ```

2. **Set up the database:**
   - Create a PostgreSQL database and configure your application properties for database connection.

3. **Build the project:**
   ```bash
   ./mvnw clean install
   ```

4. **Run the application:**
   ```bash
   ./mvnw spring-boot:run
   ```

## Postman Collection

A Postman collection for testing the API endpoints is included in this repository. Import the collection into Postman to test the various API functionalities.

## Submission Guidelines

Upload the code assignment on GitLab, Github, or any GIT repository and provide access to the following emails:
- abdulhak.maatouk@beno.com
- rana.aljarrah@beno.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.