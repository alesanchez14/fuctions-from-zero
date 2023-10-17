# fuctions-from-zero
live trainning
[![Python application test with Github Actions](https://github.com/alesanchez14/fuctions-from-zero/actions/workflows/main.yml/badge.svg)](https://github.com/alesanchez14/fuctions-from-zero/actions/workflows/main.yml)

### To call Microservice 

something like this
```bash
curl -X 'POST' \
  'https://glorious-parakeet-9gvgjvwv455hprv6-8080.app.github.dev/wiki' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Microsoft"
}'
```

### Build container

`docker build .`
`docker image ls`

### Run container

something like this

`docker run -p 127.0.0.1:8080:8080 a81ce4f35866`

### Invoke POST request

run `invoke.sh`

## References

* [Watch Walkthrough on YouTube](https://youtu.be/KOAdCqpQSI4)
