Run graphhopper container:

first build: `docker build -t graphhopper:master .`

then run without  docker composer: `docker run -d --name graphhopper -v ./data:/data -p 8989:8989 graphhopper:master`