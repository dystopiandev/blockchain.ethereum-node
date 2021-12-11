ARG VERSION=v1.10.13

FROM ethereum/client-go:${VERSION}
VOLUME ["/.ethereum"]
ENTRYPOINT ["geth", "--port", "30303", "--http.port", "8545", "--ws.port", "8546", "--datadir", "/.ethereum"]