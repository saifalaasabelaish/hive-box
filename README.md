# Hive Box Application

The Hive Box Application is a scalable solution designed to assist beekeepers with their daily chores. This project leverages Docker to simplify the deployment and management of the application.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Running the Application](#running-the-application)
- [Docker Commands](#docker-commands)
- [Contributing](#contributing)
- [License](#license)

## Features

- Easy to set up using Docker
- Scalable RESTful API

## Technologies Used

- Python 3.9
- Flask
- Docker
- Docker Compose

## Getting Started

To get started with the Hive Box Application, follow the instructions below:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saifalaasabelaish/hive-box.git
   cd hive-box
   ```

2. **Build and run the Docker containers:**
   ```bash
   docker-compose up --build
   ```

3. **Access the application:**
   - Open your web browser and navigate to `http://localhost:5000`

## Docker Commands

- To build the Docker image:
  ```bash
  docker-compose build
  ```

- To run the Docker containers in detached mode:
  ```bash
  docker-compose up -d
  ```

- To stop the running containers:
  ```bash
  docker-compose down
  ```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or enhancements.

1. Fork the repository.
2. Create your feature branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License 
