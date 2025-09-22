# Base image
FROM python:3.7

# Set working directory
WORKDIR /app

# Copy Python app into container
COPY python-app/app.py ./app.py

# Install dependencies
RUN pip install flask

# Command to run the app
CMD ["python", "app.py"]
