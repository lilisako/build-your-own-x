# Build your own Redis
This repository follows [Write your own miniature Redis with Python](https://charlesleifer.com/blog/building-a-simple-redis-server-with-python/) by charles leifer.

## Summary
This database has both server and client applications. The server handles all the incoming requests and converts the command into actual data operations. The client handles user inputs and delivers the response from the server side.

ProtocolHandler has main two function, handle_request() and write_response(). handle_request() is for serializing data according to the redis protocol which is stated in here [Redis Protocol specification](https://redis.io/topics/protocol). 
On the other hand, write_response() is for printing the output from any operations from the database.