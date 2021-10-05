## Prerequisite

* Ruby 2.7

```bash
ruby details.rb 9080
```

## How to run with Docker

```bash
# Build Docker Image for details service
docker build -t image_details .

# Run details service on port 8081
docker run -d --name details -p 8081:8081 image_details
```

* Test with path `/details/1` and `/health`

## License

MIT License
