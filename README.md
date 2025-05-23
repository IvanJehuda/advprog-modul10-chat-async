#  Module 10 Reflection
Ivan Jehuda Angi - 2306152222 - Advance Programming A

## 2.1 Original Code of Broadcast Chat

![Screenshot](screenshot/screenshot1.png)

In my setup, the server runs in the top left terminal, while the clients are displayed in the top right and bottom terminals. To start either the server or a client, I use the command `cargo run --bin (server/client)`. Specifically, I launched the server using `cargo run --bin server` in the right terminal, and started the clients using `cargo run --bin client` in the left and middle terminals. When a client connects, the server logs the new connection and is aware of all active clients. If I type a message in one client, it is sent to the server, which then broadcasts it to every connected client. As a result, all clients receive the message, even though it was entered on just one of them.

---