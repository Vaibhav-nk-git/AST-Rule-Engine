

# Rule Engine

## Introduction
The **Rule Engine** is a web application designed to help users create and manage rules easily. By providing a straightforward input form, users can define rules, which are then parsed into an Abstract Syntax Tree (AST) for advanced processing. The application leverages Flask for backend development, ensuring a seamless user experience.

## Technology Stack
- **Frontend**: HTML, CSS
- **Backend**: Flask (Python)
- **Database**: SQLite
- **Containerization**: Docker

## Key Features
- **Intuitive Interface**: Effortlessly enter rules through a user-friendly form.
- **AST Visualization**: Dynamically display the generated Abstract Syntax Tree.
- **Error Handling**: Robust mechanisms for managing invalid rule inputs.

## Getting Started

### Prerequisites
Before you begin, make sure you have the following installed on your machine:
- **Docker**: Refer to the [Docker Installation Guide](https://docs.docker.com/get-docker/) for setup.
- **Docker Compose**: Typically included with Docker. If not, follow the [installation instructions here](https://docs.docker.com/compose/install/).

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vaibhav_nk/rule-engine.git
   cd rule-engine
   ```

2. **Build and Run the Application**:
   Execute the following command to build the Docker containers:
   ```bash
   docker-compose up --build
   ```

3. **Access the Application**:
   Open your web browser and navigate to [http://localhost:5000](http://localhost:5000).

### Local Development Without Docker
If you prefer to run the application without Docker, you can do so by following these steps:
1. Install the necessary Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the application:
   ```bash
   python app.py
   ```
3. Navigate to [http://localhost:5000](http://localhost:5000) in your browser.

## Design Choices
- **Flask**: Selected for its simplicity and flexibility, making it an excellent choice for rapid web application development.
- **SQLite**: Chosen for its lightweight nature, making setup quick and easy.
- **Docker**: Used for containerization, ensuring a consistent development environment across various machines.

