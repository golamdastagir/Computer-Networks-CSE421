# Lab 3 — Socket Programming

## Overview

This lab demonstrates TCP client-server communication using Python sockets, including message processing, multithreading, and server-side calculations.

## Tasks

### Task 1 — Client/Server Communication

* Establishes TCP connection between client and server
* Client sends its hostname and IP address
* Server receives and acknowledges the message
* Uses `"End"` for disconnection

**Example:**

```text
Client: Hostname: DESKTOP-PC, IP: 192.168.1.10
Server: Message received successfully
```

### Task 2 — Vowel Processing

* Client sends a word to the server
* Server counts vowels and returns a response

**Example:**

```text
Client: education
Server: Too many vowels
```

### Task 3 — Multithreaded TCP

* Uses `threading.Thread`
* Creates a thread for each client
* Allows multiple clients to connect simultaneously
* Performs vowel processing like Task 2

**Example:**

```text
Client 1: apple
Client 2: sky

Server:
Client 1 → Too many vowels
Client 2 → Not enough vowels
```

### Task 4 — Work Hours & Payment

* Client sends hours worked
* Server calculates the payment

**Calculation:**

```text
Hours ≤ 40  →  200 × Hours
Hours > 40  →  8000 + 300 × (Hours - 40)
```

**Example:**

```text
Hours Worked: 45
Server: Will receive money: 9500
```

## Technical Concepts

* TCP sockets using Python `socket`
* Length-prefixed messages using a 16-byte header
* Multithreading using `threading.Thread`
* Graceful disconnection using `"End"`

## Project Structure

```text
Lab-3/
├── Task-1/
│   ├── client.py
│   └── server.py
├── Task-2/
│   ├── client.py
│   └── server.py
├── Task-3/
│   ├── client1.py
│   ├── client2.py
│   ├── client3.py
│   └── server.py
└── Task-4/
    ├── client.py
    └── server.py
```

## Tools

• Python • TCP/IP • Socket Programming • Multithreading • GitHub
