# Build your own Redis
This repository follows [Write your own miniature Redis with Python](https://charlesleifer.com/blog/building-a-simple-redis-server-with-python/) by charles leifer.

<img width="700" alt="Screen Shot 2021-10-21 at 12 25 38" src="https://user-images.githubusercontent.com/33516104/138209904-96a330b6-ece1-4707-b717-95193f1f8616.png">

## Summary
This database has both server and client applications. The server handles all the incoming requests and converts the command into actual data operations. The client handles user inputs and delivers the response from the server side.

ProtocolHandler has main two function, handle_request() and write_response(). handle_request() is for serializing data according to the redis protocol which is stated in here [Redis Protocol specification](https://redis.io/topics/protocol). 
On the other hand, write_response() is for printing the output from any operations from the database. It accepts string, integer, array, and dictionary as much as the real Redis.


## Gif animation
![redis](https://user-images.githubusercontent.com/33516104/138208058-aae2231e-a715-461d-9937-9b2966fa2d34.gif)
