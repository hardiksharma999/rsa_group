
README file that you can use for your Node.js  Hello world application with Docker support and tag and github action Pipeline auto  trigger on main branch.

markdown
Copy code
# Node.js Hello World Application

This is a simple Node.js application packaged with Docker. It includes a Docker Compose setup to run the application alongside a SonarQube instance for continuous code quality checks.

## Requirements

# Node.js Hello World Application

This is a simple Node.js application packaged with Docker. It includes a Docker Compose setup to run the application alongside a SonarQube instance for continuous code quality checks.

## Requirements

- Docker
- Docker Compose

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/hardiksharma999/rsa_group
cd rsa_group

## Run the Application with Docker Compose
docker-compose up -d

Access the application:

Open your web browser and go to http://localhost:9000 for SonarQube result will generate and github action also setup fot this.

Running Tests
To run tests, use the following command:

bash
Copy code
node test.js
Build and Push Docker Image
The GitHub Actions workflow will automatically build and push the Docker image to Docker Hub on each push to the main branch.
