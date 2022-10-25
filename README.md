docker build . -t rat
docker run -d --name rat -p 2222:2222 rat