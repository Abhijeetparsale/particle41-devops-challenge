# Particle41 DevOps Challenge

## Deployment Steps
- Clone the repo: `git clone https://github.com/YOUR_USERNAME/particle41-devops-challenge.git`
- Build Docker image: `docker build -t flask-app .`
- Run the container: `docker run -d -p 5000:5000 flask-app`
- Visit `http://YOUR_EC2_PUBLIC_IP:5000`
