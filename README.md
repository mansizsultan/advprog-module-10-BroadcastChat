| NAME               | ID         | ADVPROG CLASS |
| ------------------ | ---------- | ------------- |
| Sultan Ibnu Mansiz | 2306275840 | B             |

# Module 10: Asynchronous Programming - Broadcast Chat

## Original Code
![img](images/img1.png)
Clients and the server communicate via WebSocket, enabling real-time interaction. When a client sends a message, the server relays it to all connected clients, creating a broadcast effect where the message from one client is received by every other connected client. This mechanism facilitates efficient and simultaneous data distribution across multiple participants.

## Modifying the Websocket Port
![img](images/img2.png)
For proper functionality, both ports in `client.rs` and `server.rs` must be configured accordingly. Any discrepancy between the two will prevent the client from establishing a connection with the server.
