This demo illustrates how to invoke ordinary (twoway) operations, as
well as how to make oneway, datagram, secure, and batched invocations.

To run the demo, first start the server:

      python Server.py

In a separate window, start the client:

      python Client.py

To test timeouts you can use 'T' to set an invocation timeout on the client
proxy and 'P' to set a delayed response in the server to cause a timeout.
