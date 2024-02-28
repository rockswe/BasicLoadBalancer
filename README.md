<html>
  <head>
  </head>
  <body>
    <h1>Basic Load Balancer</h1>
    <h3>How does it work?</h3>
    <p>So, there is a simple TCP server that listens on a specific address ('localhost:8080') and distributes incoming connections among a set of backend servers ('localhost:5001', 'localhost:5002', 'localhost:5003'). It includes basic setup for network communication, error handling, and connection acceptance.</p>
    <h3>Load Balancing Algorithm?</h3>
    <p>The program uses round-robin load balancing algorithm to select a backend server for each incoming connection, as indicated by the ```html
'chooseBackend'
      ```
function call.</p>
    <h3>Purpose?</h3>
    <p>The purpose of this server is to act as a load balancer or proxy, distributing client requests evenly across multiple backend servers to manage load and ensure high availability.</p>
  </body>
</html>
