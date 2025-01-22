# fastapi-demo-3
- docker --version
- sudo apt update
- sudo apt install docker.io
- sudo systemctl status docker
- sudo systemctl start docker
- sudo systemctl restart docker



# Solutions to Fix Permission Denied Error
- sudo usermod -aG docker $USER
- groups $USER
- sudo chmod 666 /var/run/docker.sock
- docker-compose up -d
- docker images
- docker ps
- docker restart core-api-container  # (core-api-container) --> container_name

