# Use official Python base image
FROM python:3.11-slim

# Set working directory
WORKDIR /app

# Copy code and install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

# Expose port
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]
