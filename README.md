# React + Vite + Docker

```
docker build -t react-image .
docker build --no-cache  -t react-image .
docker run -v ${PWD}:/app -d -p 7000:7000 --name react-container react-image
docker exec -it react-container bash
```

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
