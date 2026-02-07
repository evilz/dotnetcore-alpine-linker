# dotnetcore-alpine-linker
Test of Docker image using the .NET linker on Alpine.

## Build and run locally

```bash
# build

dotnet build

# run

dotnet run
```

Expected output:

```
Hello World!
```

## Build the Docker image

```bash
docker build -t dotnetcore-alpine-linker .
```

Run it:

```bash
docker run --rm dotnetcore-alpine-linker
```


