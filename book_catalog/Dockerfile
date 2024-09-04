# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Set the working directory in the container to /app
WORKDIR /app

# Copy the requirements file to the container at /app
COPY requirements.txt .

# Install the dependencies specified in the requirements.txt file
RUN pip install --no-cache-dir -r requirements.txt

# Copy the contents of the book_catalog/app directory to /app in the container
COPY app/ /app/

# Set environment variables (if needed)
ENV DATABASE_URL="postgresql://library_db_b8kh_user:UR4gum8FTpuYr7xGARal3HPXH24C7UMf@dpg-crb64hbtq21c73cfqjn0-a.oregon-postgres.render.com/library_db_b8kh"

# Expose the port that the app will run on
EXPOSE 8000

# Command to run the FastAPI application using Uvicorn
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]
