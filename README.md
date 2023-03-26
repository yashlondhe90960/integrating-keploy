# Integrating Keploy 🚀🚀


Integrated keploy in my first Golang project.
It is a simple API with Echo Golang framework.

run the API, by the command
```go
go run server.go
```
test the API by request to `http://localhost:3000/hello`  the response will be:
```json
{"message":"Hello World"}
```

![hello_world](hello_world.jpg)


## Some snippets:
File structure: <br>
![image2](img2.png)

Starting echo server: <br>
<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192257-8c58b1ff-2891-4fd2-957e-30d51e7426d9.png">

<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192361-820ea153-c5cc-4ce5-82d7-ea77abbbd197.png">

<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192385-31aa1b4a-4387-4b3f-934d-6a47705d0780.png">

Importing keploy files according to the [Documentation](https://docs.keploy.io/docs/go/integration)

<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192492-a1796b07-08e0-4b52-b8c8-b6aa6670aa5d.png">

<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192543-a42cfaff-7075-4f4d-8a73-b8a1b4afd793.png">

<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192559-cec57c1d-5c61-4512-9633-f7ac98878277.png">

<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192577-434e0dd9-c06d-4cdf-aed5-2a31ec7c9c62.png">

Running the Keploy server:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/77205923/226192619-c41b9826-a3c8-4d2f-800b-6582b924aabd.png">

For unit testing using Keploy, run cmd:

```
$env:KEPLOY_MODE="record"; go run server.go
```

