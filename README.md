# https-redirect

A super lightweight https redirect server written in rust! (<1MiB Docker image!)

## Usage
### Docker
```sh
docker run -d \
    -p 8080:8080 \
    --name https-redirect \
    matthewhartstonge/https-redirect:latest
```

### Binary
```sh
./https-redirect
```
