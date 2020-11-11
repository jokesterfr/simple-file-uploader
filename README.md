# Simple file uploader

This project aims at providing a simple file uploader protected by a basic authentication mechanism. It eases file sharing with your friends and family without using any Dropbox or Google, AWS, Azure Cloud...

## Run as a Docker image

Via docker-compose:

```sh
cp .env.dist .env
docker-compose up -d
```

Via docker:

```sh
docker run -d -p 8080:8080 jokesterfr/simple-file-uploader
```

If you want to rebuild the image:

```sh
docker build .
```

## Run from the sources

```sh
yarn
yarn start
```

## Licence

MIT Licence, see [./LICENCE]()
