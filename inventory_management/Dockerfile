# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the requirements file
COPY requirements.txt .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the current directory contents into the container at /app
COPY app/ /app/

# Set environment variables (if needed)
ENV DATABASE_URL="postgresql://library_db_b8kh_user:UR4gum8FTpuYr7xGARal3HPXH24C7UMf@dpg-crb64hbtq21c73cfqjn0-a.oregon-postgres.render.com/library_db_b8kh"

# Expose the port that the app will run on
EXPOSE 8001

# Command to run the FastAPI application using Uvicorn
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8001"]
