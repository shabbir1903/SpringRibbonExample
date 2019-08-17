# SpringRibbonExample
Spring Ribbon POC
1.Start Eureka Server - http://localhost:8761/
2.Start ribbon Server - http://localhost:9090/backend
3.Start ribbon client - http://localhost:8888/client/frontend

To Test Ribbon Client start muliple instance of ribbon server by changing the port number in the application properties and then run ribbon client
You will see port number is changing in the UI of backend server by hitting http://localhost:8888/client/frontend
