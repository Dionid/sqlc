# Installing sqlc

sqlc is distributed as a single binary with zero dependencies.

## macOS

```
brew install sqlc
```

## Ubuntu

```
sudo snap install sqlc
```

## go install 

### Go >= 1.17:

```
go install github.com/Dionid/sqlc/cmd/sqlc@latest
```

### Go < 1.17:

```
go get github.com/Dionid/sqlc/cmd/sqlc
```

## Docker

```
docker pull sqlc/sqlc
```

Run `sqlc` using `docker run`:

```
docker run --rm -v $(pwd):/src -w /src sqlc/sqlc generate
```

Run `sqlc` using `docker run` in the Command Prompt on Windows (`cmd`):

```
docker run --rm -v "%cd%:/src" -w /src sqlc/sqlc generate
```

## Downloads

Get pre-built binaries for *v1.21.0*:

- [Linux](https://downloads.sqlc.dev/sqlc_1.21.0_linux_amd64.tar.gz)
- [macOS](https://downloads.sqlc.dev/sqlc_1.21.0_darwin_amd64.zip)
- [Windows](https://downloads.sqlc.dev/sqlc_1.21.0_windows_amd64.zip)

See [downloads.sqlc.dev](https://downloads.sqlc.dev/) for older versions.
