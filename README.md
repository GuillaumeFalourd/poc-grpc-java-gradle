# gRPC (Google Remote Procedure Call) Java

[This code's has been inspired from from the grpc.io site.](https://grpc.io/docs/languages/java/quickstart/)

## Run

### Message

#### Message Execution

From the `hello-world` directory:

Configure the project:

```bash
./gradlew installDist
```

Run the server:

```bash
./build/install/hello-world/bin/hello-world-server
```

From another terminal window, run the client:

```bash
./build/install/hello-world/bin/hello-world-client
```
