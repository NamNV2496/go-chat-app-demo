# A basic chat app is implemented by Golang + websocket

# How to start?

    1. run server `go run cmd/main.go`
    2. run FE `start templates/index.html`

# Flow

![alt text](docs/flow.png)


The latest message always is updated to show user
![alt text](docs/image.png)

Old message also was stored to display new user (maximum config from code is `MaxLengthOldMsg = 50`)
![alt text](docs/image-1.png)

Leave message
![alt text](docs/image-2.png)

Register new chat room
![alt text](docs/image-3.png)

Multiple real-time chatting
![alt text](docs/image4.png)
