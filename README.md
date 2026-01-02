# Flask Hello World App

A simple Flask application that returns "Hello, World!" when accessed.

## Running Locally

1. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

2. Run the application:

   ```
   python app.py
   ```

3. Visit `http://localhost:5000` in your browser.

## Running with Docker

1. Build the image:

   ```
   docker build -t flask-hello-world .
   ```

2. Run the container:

   ```
   docker run -p 5000:5000 flask-hello-world
   ```

3. Visit `http://localhost:5000` in your browser.
