# Use official Python image (feel free to chose the version you deem appropriate)
FROM python:3.10-alpine

# Set the working directory
WORKDIR /app

# Copy requirements and install dependencies
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy the source code
COPY ./src .

# Expose port
EXPOSE 8000

# Start the application 
CMD TODO