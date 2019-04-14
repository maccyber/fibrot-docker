# fibrot-docker

## Usage
Pass either *encrypt* or *decrypt* along with the message to `fibrot`. For instance:


### Encrypt

```console
$ fibrot encrypt "Hello World"
$ docker run --rm macyber/fibrot fibrot encrypt "Hello World"
```

    Hfmnr Bwegl

### Decrypt

```console
$ fibrot decrypt "Gppfedm Pmchw Knexc"
$ docker run --rm macyber/fibrot fibrot decrypt "Gppfedm Pmchw Knexc"
```

    Goodbye Cruel World

