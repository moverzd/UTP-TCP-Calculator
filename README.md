# UDP/TCP Calculator
- Ability to work with two or variable operands
- Parenthesis precedence
- Zero Division, Overflow, Incorrect expression handled
- UTP/TCP supported
- Multithreading for clients
- Tests covered via Python3
- Static testing via cppcheck

# How to compile
```bash
g++ CalcServer.cpp -o server && g++ CalcClient.cpp -o client -std=c++14

Starting the server via UDP protocol
./server -u -a ip -p port

Starting the server via TCP protocol
./client -u -a ip -p port

Starting the client via UDP protocol
./server -a ip -p port

Starting the client via TCP protocol
./client -a ip -p port

```
