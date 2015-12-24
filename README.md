# Docker TensorFlow

## Feature

- `ONBUILD` support
- Python 3

## Usage

```Dockerfile
FROM uetchy/tensorflow:0.6.0-onbuild
```

```yaml
app:
  build: .
```

```console
$ docker-compose build
```
