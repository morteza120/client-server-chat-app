# Client-server chat application with C

This is a **single-threaded** chat application that uses sockets for communication.

## Build
Build the program to `build/` subfolder.
```bash
make
```
## Usage

server-side:
```bash
make server-run  #default port is 7070
```
client-side:
```bash
make client-run  u=your-name #default address is 127.0.0.1:7070
```
client commands:
| command| Description |
| ----------- | ----------- |
| create [groupID] | create the group|
| join [groupID] | join to the group|
| leave [groupID] | leave the group|
| send [groupID] [message] | send the message to the group|
| quit | close connection and exit from application|

## License
[MIT](https://choosealicense.com/licenses/mit/)
