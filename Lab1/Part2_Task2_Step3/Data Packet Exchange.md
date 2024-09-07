### TCP Three-Way Handshake

1. **SYN (Synchronization):**
   - The client (`192.168.8.59`) initiates the connection by sending a SYN packet to the server (`52.206.115.246`). This packet requests synchronization and starts the process of establishing a connection.

2. **SYN-ACK (Synchronization-Acknowledgment):**
   - The server responds to the client with a SYN-ACK packet. This packet acknowledges the client's SYN request and sends its own SYN request to the client.

3. **ACK (Acknowledgment):**
   - The client sends an ACK packet back to the server, acknowledging the server's SYN-ACK packet. This completes the three-way handshake, and a reliable TCP connection is established.

### Summary
This three-way handshake is the initial exchange of data packets required to establish a TCP connection. It ensures that both the client and server are ready to communicate, and it sets up the parameters for the data transfer that will follow.

<img width="857" alt="image" src="https://github.com/user-attachments/assets/206108ce-4dbc-4faf-9990-f6506a65a05e">

