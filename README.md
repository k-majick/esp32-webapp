## Run Virtual Environment
pip install -r requirements.txt
pip install "fastapi[standard]"
source .venv/bin/activate

## Run in Docker

# Fullstack
docker-compose up

# Backend
docker-compose up -d backend