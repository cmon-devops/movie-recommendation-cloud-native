FROM python:3.9

WORKDIR /app

COPY requirements.txt ./  # Make sure requirements.txt is in the same directory as the Dockerfile

RUN pip install -r requirements.txt

COPY . .  # Copy the rest of your application files

# Run the Flask app
CMD ["python", "main.py"]
