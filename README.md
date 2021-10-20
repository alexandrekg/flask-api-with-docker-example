# This project shows that I learned how to Dockerize a Flask API

## Technologies
- Python
- Docker
- Flask


## Local run

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
python -m app.index
```


## Docker run
```sh
docker build your-image-name .
docker run -p 5000:5000 your-image-name
```