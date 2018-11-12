Run graphhopper container:

first build: `docker build -t tgraphhopper:latest .`

then run without  docker composer: `docker run --name tgraphhopper -v ./data:/data -p 8989:8989 tgraphhopper:latest`