# SERVICE-MESH

## Requirements
A `datadog.env` file located in the `datadog` directory of the project with your datadog api key set with a variable named `DD_API_KEY`

For example, in `./datadog/datadog.env`:
```
DD_API_KEY=01234567890123456789012345678901
```

## How to Use
1. `docker-compose build`
2. `docker-compose up -d`
3. Hit `http://localhost:8000/stats` and `http://localhost:8000/service/1`

