# Sentiment-API Docker Image

## Overview
This Docker image provides an environment for running a sentiment analysis API built with TensorFlow and Flask. Sentiment-API uses a pre-trained model for classifying text as positive, neutral, or negative. Develop your Python code in the `src/` directory to train the model locally and execute it inside a containerized environment.

## Project Structure
- **Dockerfile**: Defines the Docker image and its environment.
- **src/**: Contains the Flask API, training scripts, and source code.
- **README.md**: This file, containing project documentation.

## Overview of the Environment
**Base Image**: Ubuntu 22.04  
**Includes**:
- Python 3.12
- TensorFlow and Keras for deep learning
- Flask for API development
- Necessary NLP libraries for text processing

## Features
- **Pre-trained Sentiment Model**: The image installs and configures a pre-trained sentiment analysis model.
- **API Server**: Run a Flask-based API to analyze text sentiment in real time.
- **Local Development**: Develop your code locally in the `src/` directory and test it within the Docker container.
- **Containerized Environment**: Ensure a consistent environment for deployment across different platforms.

## Prerequisites

### On Linux
- **Install Docker**: Follow your distribution’s instructions for installing Docker.
- **Allow Docker to Connect to X Server** (if needed for any GUI applications):  
  - Install `xhost` and allow connections:
    ```bash
    xhost +localhost
    xhost +127.0.0.1
    ```
    
## Reference
[1] TensorFlow Documentation  
[2] Flask Documentation  
[3] Docker Documentation

