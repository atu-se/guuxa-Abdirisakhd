# Student README

## Questions

1. The client and server have different sized buffers. Why does it still work?

- because they don't know what buffer size the other have.

2. What happens if the buffer size on the client is changed to a value smaller than the initial `message_length`?

- it breaks the message into small

3. What happens if you run the client when the server is not running?

- the client will show **ConnectionRefusedError**.

4. What happens if you run the server while the server is already running?

- it'll output _**OSError**: Address already in use._

5. What changes did you make to finish this assignment?

-

6. What resources did you use to complete this assignemnt? Make a Markdown list of web links below.

- [Real Python tutorial](https://realpython.com/python-sockets/#multi-connection-client-and-server)
-
