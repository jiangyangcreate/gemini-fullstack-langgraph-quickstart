
**1. Build the Docker Image:**


   ```bash
   docker build -t gemini-fullstack-langgraph -f Dockerfile .
   ```
**2. Run the Production Server:**

   Windows
   ```bash
   $env:LANGSMITH_API_KEY="ls*****"; docker-compose up -d
   ```

   Linux
   ```bash
   LANGSMITH_API_KEY="ls*****"; docker-compose up -d
   ```

Open your browser and navigate to `http://localhost:8123/app/` to see the application. 
The API will be available at `http://localhost:8123`.
