# Use a specific Python version
FROM python:3.8.6-slim

# Set work directory
RUN mkdir /app
WORKDIR /app

# Install dependencies
COPY requirements.txt .
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

# Copy application code
COPY recommendation_objects/ recommendation_objects/
COPY agents/ agents/
COPY agent_controller.py agent_controller.py
COPY main.py main.py

# Clean up any caches or pyc files
RUN find . -name "__pycache__" -exec rm -r {} +

# COPY test_input.json test_input.json

# Set the default command to run the application
ENTRYPOINT [ "python", "main.py" ]