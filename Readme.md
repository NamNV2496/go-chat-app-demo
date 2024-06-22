# A basic chat app is implemented by Golang + websocket

# Technologies

    1. websocket - "github.com/gorilla/websocket"
    2. Gin - "github.com/gin-gonic/gin"

# How to start?

    1. run server `main.exe`
    2. run FE `start templates/index.html`

# Flow

![alt text](docs/flow.png)


The latest message always is updated to show user
![alt text](docs/image.png)

Old message also was stored to display new user (maximum config from code is `MaxLengthOldMsg = 50`)
![alt text](docs/image-1.png)

Register new chat room
![alt text](docs/image-3.png)

Inbox
![alt text](docs/image5.png)

private chat room
![alt text](docs/image6.png)
