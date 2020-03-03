# Docker image

Running the image

```
cd path/to/Dockerfile
docker build -t ship_image .
docker run -d --name ship -p 80:80 ship_image
```

Open browser and go to `http://localhost/` 


