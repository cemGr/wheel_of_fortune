# wheel_of_fortune
Birthday present to troll

## Docker

Build the container and serve the page locally:

```sh
docker build -t wheel .
docker run -p 8080:80 wheel
```

Or with docker compose:

```sh
docker compose up --build
```

The page is available at http://localhost:8080 on your local network.
