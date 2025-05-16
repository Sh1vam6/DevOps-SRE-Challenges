# Use official Python image
FROM python:3.9-slim

# Set working directory
WORKDIR /app

COPY requirements.txt /app
# Copy files
COPY app.py /app

# Install Flask
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000
EXPOSE 5000

# Run Flask app
CMD ["python", "app.py"]