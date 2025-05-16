a. It depends on message size and count. The publisher sends one message at a time. Total data is the sum of all message sizes.

b. Same URL means same server. Both use same login and port.They can share queues to communicate.

![alt text](image.png)

![alt text](image-1.png)
This screenshot shows a Publisher-Subscriber pattern in Rust to send and process user-created events  using message queues.