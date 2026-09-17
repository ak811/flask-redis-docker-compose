# Flask + Redis with Docker Compose

This project demonstrates how to containerize a Python Flask web application, connect it to a Redis cache, and orchestrate services using Docker Compose.

---

## Setup & Run

1. **Clone the repo / download files**

   Make sure the following files are present in the project folder:
   - `app.py`
   - `requirements.txt`
   - `Dockerfile`
   - `compose.yaml`

2. **Build and start the containers**
   ```bash
   docker compose up --build

## Results

After running the containers, you should see the Flask app output.  
Here’s a sample result screenshot:

![Docker](docker.png)
