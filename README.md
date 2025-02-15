Overview

PostPerson is an open-source API testing tool inspired by Postman, designed to help developers test, debug, and document their APIs seamlessly. It provides an intuitive UI for sending HTTP requests, inspecting responses, and automating API workflows. Built with a modern tech stack, PostPerson aims to be a lightweight yet powerful alternative to existing API testing tools.

Working On Features

User-Friendly Interface: Simplified and modern UI for managing API requests.

Multiple HTTP Methods: Supports GET, POST, PUT, DELETE, PATCH, and more.

Request History & Collections: Save and organize frequently used requests.

Authentication Support: Supports API keys, OAuth, JWT, and basic authentication.

Custom Headers & Query Params: Easily configure headers and parameters for requests.

Environment Variables: Store and switch between different environments effortlessly.

Automated Testing: Write and run test scripts using JavaScript.

Response Viewer: Inspect and format JSON, XML, and other response formats.

WebSocket & GraphQL Support: Test real-time APIs with WebSockets and GraphQL.

CI/CD Integration: Automate API testing with integration for CI/CD pipelines.

Dark Mode: Stylish dark mode for a comfortable user experience.

Tech Stack

Backend:

Spring Boot – High-performance RESTful API framework.

PostgreSQL – Scalable and efficient database.

JWT Authentication – Secure authentication implementation.

Spring Security – Role-based access control.

Frontend:

React – Modern and dynamic UI framework.

Redux – State management for seamless user interactions.

Tailwind CSS – Beautiful and responsive UI design.

Deployment & DevOps:

Docker – Containerized deployment.

AWS/Heroku – Cloud hosting solutions.

CI/CD with GitHub Actions – Automated testing and deployment.

Installation & Setup

Prerequisites

Ensure you have the following installed:

Java 17+

Node.js & npm

PostgreSQL

Docker (optional for containerized deployment)

Backend Setup

Clone the repository:

git clone https://github.com/yourusername/PostPerson.git

Navigate to the backend folder:

cd backend

Configure environment variables:

DATABASE_URL=your_postgresql_url
JWT_SECRET=your_secret_key

Build and run the application:

mvn spring-boot:run

Frontend Setup

Navigate to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the development server:

npm start

Contributing

We welcome contributions! To contribute:

Fork the repository.

Create a new branch.

Make your changes and commit them.

Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact & Support

For any questions or suggestions, feel free to open an issue or reach out to the maintainers.

Happy coding! 🚀

