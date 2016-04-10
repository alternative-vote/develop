# develop

Check that you have the necessary dependencies installed and configured.
```bash
git -v
docker -v
docker-compose -v
docker info
```

Clone and start the repositories
```bash
git submodule init && git submodule update
git submodule foreach npm install
docker-compose up -d
```