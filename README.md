# Ethereum Node

- [Ethereum Node](#ethereum-node)
  - [geth](#geth)
    - [Configure](#configure)
    - [Build](#build)
    - [Start](#start)
    - [Stop](#stop)
    - [View logs](#view-logs)

## geth
### Configure
Alter data directory, ports, extra arguments and other options in `.env`. Sample is provided as `.env.example`.

### Build
```bash
docker-compose build geth
```

### Start
```bash
docker-compose up -d geth
```

### Stop
```bash
docker-compose stop geth # stop
docker-compose kill geth # kill
docker-compose rm geth # remove container
```

### View logs
```bash
docker-compose logs geth
```