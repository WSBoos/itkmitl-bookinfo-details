## How to run with Docker

```bash
cd itkmitl-bookinfo-details/src

# Build Docker Image for details service
docker build -t image .

# Run details service on port 8081
docker run -d --name details -p 8081:8081 image 
```

* Test with path `/details/1` and `/health`

## Prerequisite

* Ruby 2.7

```bash
ruby details.rb 9080
```
