# Use an official Python image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy dependencies file
COPY requirements.txt . 

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the backend code
COPY . .

# Expose the correct port
EXPOSE 3001

# Start the backend
CMD ["python", "main.py"]  # Update this if your backend entrypoint is different
