FROM python:3.10-slim

# Set working directory in the container
WORKDIR /app

# Copy everything from your repo to the container
COPY . .

# Install Python dependencies
RUN pip install -r requirements.txt

# Run the app
CMD ["python", "app/calculator.py"]
