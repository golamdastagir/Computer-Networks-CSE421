# Socket Programming

A collection of Python-based client-server programming exercises using **TCP sockets**.

The exercises explore basic client-server communication, message processing, multithreaded servers, and server-side computation.

## Tasks

### Task 1 — Client Information

Implemented a basic client-server application where the server provides the connected client's:

* IP address
* Device name

### Task 2 — Message Processing

Implemented a client-server application where the server receives a message from the client and counts the number of vowels.

The server responds based on the number of vowels detected:

* No vowels → `Not enough vowels`
* At least two vowels → `Enough vowels I guess`
* More than two vowels → `Too many vowels`

### Task 3 — Multithreaded Client-Server

Extended the previous client-server application by implementing a **multithreaded server** capable of handling multiple clients simultaneously.

The server processes messages from multiple connected clients and returns the appropriate response based on vowel count.

### Task 4 — Salary Calculation

Implemented a client-server application where the client sends the number of hours worked and the server calculates the corresponding salary.

The salary rules are:

* Up to 40 hours → **Tk 200/hour**
* More than 40 hours → **Tk 8,000 + Tk 300 for each additional hour**

The calculated salary is returned to the client.

## Networking Concepts

* Client-server architecture
* TCP sockets
* IP addresses and ports
* Socket connection and data exchange
* Server-side request processing
* Multithreaded network applications
* Concurrent client handling

## Technologies

* Python
* TCP/IP
* Python Socket API

## Files

```text
3-socket-programming/
├── Task1/
│   ├── client.py
│   └── server.py
├── Task2/
│   ├── client.py
│   └── server.py
├── Task3/
│   ├── client1.py
│   ├── client2.py
│   ├── client3.py
│   └── server.py
└── Task4/
    ├── client.py
    └── server.py
```
