# DevOps Template

A simple Flask app with Docker, CI/CD (GitHub Actions), and VS Code setup.

## 🛠️ How to use

1. Clone:
   ```
   git clone https://github.com/yourusername/devops-template.git
   cd devops-template
   ```

2. Build & run locally:
   ```
   docker build -t devops-template .
   docker run -p 5000:5000 devops-template
   ```

3. Push to GitHub:
   ```
   git remote add origin https://github.com/yourusername/devops-template.git
   git push -u origin main
   ```

4. Add DockerHub secrets in GitHub repo settings:
   - DOCKERHUB_USERNAME
   - DOCKERHUB_TOKEN

Every push to `main` will build and push a Docker image to DockerHub.
#   d e v o p s - t e m p l a t e  
 