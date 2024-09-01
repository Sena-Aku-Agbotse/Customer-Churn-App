# Customer-Churn-Prediction-App
Customer Churn Prediction App
# Churn Management App


## Overview
This app is built with Streamlit to help businesses understand and predict when customers might leave, using machine learning. It is easy to deploy and scale using Docker.

## Key Features
- **Interactive Dashboards:** View customer data through interactive charts and graphs.
- **Predictive Analytics:** Predict which customers might leave using pre-trained models and past data.
- **Secure Login:** Only authorized users can access the app.
- **Data Upload:** Users can upload their customer data in CSV format for analysis.
- **Theme Options:** Switch between dark and light themes.
- **Docker Support:** Easy to deploy with Docker and Docker Compose.

## How to Install

### Requirements
- Docker
- Docker Compose

### Clone the Project
To get the project on your computer, use this command:
```bash
git clone https://github.com/yourusername/churn-management-app.git
cd churn-management-app
```

### Run with Docker Compose
To build and run the app, use these commands:
```bash
docker-compose build
docker-compose up
```

## Settings
You can change settings in the `Dockerfile` or `.streamlit/config.toml` for app themes. For Docker settings, edit the `docker-compose.yml` and `.env` files

## Docker Compose Details
- **Dockerfile:** Defines how the Docker container is set up.
- **docker-compose.yml:** Configures the different parts of the app, such as databases and backend services.

## License
This project is licensed under the MIT License.

## Contact
If you need help, contact [contact@email.com](mailto:agbotse81@gmail.com).
