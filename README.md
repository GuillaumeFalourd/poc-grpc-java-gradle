# gRPC (Google Remote Procedure Call) Java with GRADLE

[This code's has been inspired from from the grpc.io site.](https://grpc.io/docs/languages/java/quickstart/)

## Run

### Hello World

#### Hello World Execution

From the `root` directory:

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

## Usage

![gradlew installDist](https://user-images.githubusercontent.com/22433243/128194922-170ae699-9fb1-4f94-8f67-b254ba5e7050.png)

![hello-world-server](https://user-images.githubusercontent.com/22433243/128194973-7b4035f0-2f51-4ad2-8a67-2035f7286eb0.png)

![hello-world-client](https://user-images.githubusercontent.com/22433243/128195020-217deeab-4bc7-4051-81aa-4fe76867aff1.png)
