# A thread pool written in rust

A thread pool implementation which has been tested using a simple webserver implementation.

The basic HTTP webserver listens for TCP connections on port 7878.

Start the webserver by running ```cargo run```

The 2 available endpoints are:

- / -> Returns a response immediately
- /sleep -> Returns a response after a 5 second delay.

By default, the thread pool is initialized with 4 threads.