# Use a Python base image
FROM python:3.9

# Set working directory in the container
WORKDIR /app

# Copy requirements file to the container
COPY requirements.txt .

# Install project dependencies
RUN pip install -r requirements.txt

# Copy project files to the container
COPY . .

# Command to run the Python script for energy management
CMD ["python", "scripts/energy_management.py"]
