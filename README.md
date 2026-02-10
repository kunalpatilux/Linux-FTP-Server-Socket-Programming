 Concurrent FTP Server implemented using Linux Socket Programming and TCP.
 

 # Project Overview
This project implements a Concurrent FTP Server using Linux Socket Programming and TCP/IP.  
The server supports multiple clients simultaneously using process-based concurrency (`fork()`).

 1) Features
- Client–Server architecture
- TCP based reliable communication
- Concurrent client handling using `fork()`
- File download support
- Chunk-based file transfer
- Proper error handling
- Efficient socket and file descriptor management


2) Technologies Used
- C Programming
- Linux System Programming
- TCP/IP Protocol
- Socket Programming
- Process Management (`fork()`)

 # Working Flow
A) Server Side
1. Create socket using `socket()`
2. Bind IP and port using `bind()`
3. Listen for clients using `listen()`
4. Accept client using `accept()`
5. Create child process using `fork()`
6. Transfer file using `read()` and `send()`

B) Client Side
1. Create socket
2. Connect to server using `connect()`
3. Request file
4. Receive file data


#  File Transfer Logic
- Files are transferred in chunks
- Prevents memory overflow
- Supports large file sizes
- Ensures smooth data transfer

 # Error Handling
- File not found
- Client disconnection
- Socket errors
- End-of-file detection

# Learning Outcomes
- Deep understanding of client–server architecture
- Hands-on experience with Linux sockets
- Clear concept of concurrency using `fork()`
- Practical TCP/IP communication

 Author: Kunal Dhanraj Patil  
  

