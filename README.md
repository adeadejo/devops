# Simple Flask App

A Python Flask application that says "Hello, World!" and provides a sample data endpoint.

## Prerequisites

- Docker
- Docker Compose

## Setup and Running

1. **Clone the repository:**
2. **Navigate to the project directory:**
3. **Build and run the application with Docker Compose:**
4. **Access the application:**
- Greeting: <http://localhost:5000/>
- Sample data: <http://localhost:5000/data>

## Using the Data Parsing Script

To parse data from the application and create files:

1. **Run the script:**
2. **Check the `files/` sub-directory for the created files.**

## Testing

- Navigate to <http://localhost:5000/> to see the custom greeting.
- Navigate to <http://localhost:5000/data> to see the sample data returned by the application.
- Check the `files/` sub-directory to verify that files are created correctly with matching SHA256 sums.

## Troubleshooting

- If you encounter any issues with Docker, ensure that Docker is running and try restarting it.
- If you encounter permission issues, try running the commands with `sudo` or as an administrator.

## Repository Structure

- `app.py`: Flask application.
- `apptest.py`: Script to parse data from the Flask app.
- `Dockerfile`: Dockerfile for the Flask app.
- `docker-compose.yml`: Docker Compose file to run the Flask app and Nginx.
- `nginx.conf`: Nginx configuration for reverse proxy.
- `requirements.txt`: Python dependencies for the Flask app.
- `README.md`: Documentation for the project.

