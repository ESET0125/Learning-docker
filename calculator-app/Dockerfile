# 1. Base image (OS + Python)
FROM python:3.12-slim

# 2. Set working directory inside image
WORKDIR /app

# 3. Copy application files into image
COPY app.py .
COPY requirements.txt .

# 4. Install dependencies (if any)
RUN pip install --no-cache-dir -r requirements.txt

# 5. Command to run when container starts
CMD ["python", "app.py"]

