# Self Hosted DMS Server With Chibisafe

### Chibisafe

Chibisafe is a file uploader service written in typescript that just works. It's easy to use, easy to deploy, free and open source.

## How to start this system

**prerequisite:** Docker

#### Build Log Server

```sh {"id":"01J3YMEVP2HMH0HE6M1XQSJEK2"}
docker compose build
```

#### Create Log Container

```sh {"id":"01J3YMEVP2HMH0HE6M1YYZ7BH2"}
docker compose create
```

#### Start Log Server

```sh {"id":"01J3YMEVP2HMH0HE6M1ZTXXZBS"}
docker compose start
```

## Run your DMS Server

### Chibisafe Dashboard

You can find Chibisafe Dashboard at http://localhost:24424

username: **admin**

password: **admin**