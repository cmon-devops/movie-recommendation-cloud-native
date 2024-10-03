# Use an official Python runtime as a parent image
FROM python:3.9

# Set the working directory
WORKDIR /app

COPY /app/requirements.txt .  # Adjust this path accordingly

# Install the dependencies
RUN pip install -r requirements.txt

# Copy the rest of the application code
COPY . .

# Run the Flask app
CMD ["python", "main.py"]
