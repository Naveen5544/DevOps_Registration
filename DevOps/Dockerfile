# Use the official Python image
FROM python:3.11-slim

# Set the working directory in the container
WORKDIR /app

# Copy the requirements file and install dependencies
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy the project files to the container
COPY . .

# Expose port 5000 for Flask
EXPOSE 8000

# Run the Flask app using App.py
CMD ["python", "App.py"]
