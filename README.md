# mc-server

## Server requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) or [OrbStack](https://orbstack.dev) (Mac)
- [playit.gg](https://playit.gg) tunnel for exposing the server

### Running the server

```sh
# clone the repository
git clone ...

# cd into the server
cd mc-server

# start the server on port 25565 with docker compose
docker compose up
```

### Exposing the server

You can expose the server by creating a [playit.gg](https://playit.gg) tunnel that points to `127.0.0.1:25565`. 
Make sure that the tunnel type is set to TCP. 

You can then share the domain with your friends to allow them to connect.

## Client requirements

- Minecraft 1.21.1 with Fabric Loader 0.16.5
- Mods downloaded from [`mods.txt`](./mods.txt) under the "Client sided mods" section, and placed into the `mods` folder in `.minecraft`
