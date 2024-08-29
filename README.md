## Fastify.js Boilerplate

**Overview**

Welcome to the Fastify.js Boilerplate! This project provides a solid foundation to jumpstart your backend development journey. It offers a structured approach for request processing, pre-configured technologies, and handy utilities, eliminating unnecessary setup time. Get started quickly by cloning the repository, installing dependencies, and you're ready to build!

**Features**

- **Clear Request Processing Flow:**

  - `primaryRoutes.js`: Serves as the entry point for incoming requests.
  - `primaryHandlers.js`: Handles business logic and directs requests to relevant services.
  - `primaryServices.js`: Takes care of core processing, interacting with databases, APIs, or other services.
  - This structured method allows for:
    - Pre-processing: Modify requests before processing in `primaryServices.js`.
    - Post-processing: Alter responses before sending them back to the client.

- **Pre-configured Technologies:**

  - Sequelize ORM (Object Relational Mapper) for interacting with PostgreSQL databases.
  - TypeORM (another popular ORM) for PostgreSQL support (optional).
  - Socket.io for real-time communication.
  - RabbitMQ for message queuing.
  - OpenAI for accessing OpenAI functionalities.
  - Gmail API integration (optional).

- **Useful Utilities:**
  - Entity Existence Check: Easily verify if entities exist in your database using Sequelize.
  - RabbitMQ Publisher and Consumer Functions: Simplify message queuing throughout your project.
  - Password Encryption & Comparison: Securely encrypt passwords and verify against stored versions.
  - OpenAI Gateways: Pre-built functionalities for using OpenAI services.
  - Customizable QUEUE Class: Tailor this class to meet your specific queue management needs.
  - Connectivity Ensuring Methods: Maintain stable connections with your external services.

**Getting Started**

1. **Clone the repository:**
   ```bash
   git clone (https://github.com/TahaAkber/Backend-Boiler-Plate.git)
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Run Docker containers (optional):**
   ```bash
   docker-compose up -d
   ```
4. **Start development server:**
   ```bash
   npm start
   ```

**Usage**

- Define API endpoints in `primaryRoutes.js`.
- Implement business logic in `primaryHandlers.js`.
- Manage core processing within `primaryServices.js`.
- Feel free to customize and expand the boilerplate to fit your project's requirements.

**Contributing**

We welcome contributions! Please fork this repository and submit a pull request for any improvements or additional features.

**License**

This project is licensed under the MIT License.
