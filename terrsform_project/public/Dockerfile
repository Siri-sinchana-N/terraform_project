# Use the Python 3.9  base image
FROM python:3.9

# Set the working directory inside the container
WORKDIR /apps

# Copy all files from the current directory to the container's working directory
COPY . .

# Install the required Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the application on port 3000
EXPOSE 3000

# Command to run the application
CMD ["python", "server/server.py"]
