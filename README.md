docker build -t whisper-api-img .
docker run -p 8000:8000 whisper-api-img

Go to localhost:8000