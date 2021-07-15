# gRPC (Google Remote Procedure Call) Java

[This code's has been inspired from from the grpc.io site.](https://grpc.io/docs/languages/java/quickstart/)

## Run

### Message

#### Message Execution

From the `examples` directory:

Configure the project:

```bash
./gradlew installDist
```

Run the server:

```bash
./build/install/examples/bin/hello-world-server
```

From another terminal window, run the client:

```bash
./build/install/examples/bin/hello-world-client
```
