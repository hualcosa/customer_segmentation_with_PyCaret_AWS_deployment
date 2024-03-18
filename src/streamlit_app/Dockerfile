FROM python:3.11.5-slim

# Set the working directory to /app
WORKDIR /app

RUN apt-get update && apt-get install -y --no-install-recommends \
    libgomp1 \
    && rm -rf /var/lib/apt/lists/*

# copying local files to the container
COPY . .

# Install the Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Exposing the necessary ports
EXPOSE 8501

# Command to run when the container starts (as an example, running a Streamlit app)
CMD ["streamlit", "run", "app.py"]