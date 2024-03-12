# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
CLIENT:
![Screenshot 2024-03-12 183939](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/4cab5f0a-93da-4d95-9b77-b945f6aa3218)

SERVER:
![Screenshot 2024-03-12 183846](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/25771a65-2aae-496b-a2dc-0681f191f02f)


## OUPUT - ARP
CLIENT:
![Screenshot 2024-03-12 183309](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/4473185e-dd3d-4427-8b3f-d4ee54c109e3)
SERVER:
![Screenshot 2024-03-12 183228](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/fc731b39-2a18-4614-b59c-dbea5319f7e2)




## PROGRAM - RARP
CLIENT:
![Screenshot 2024-03-12 184412](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/55353d85-1926-4c1e-9543-ffacae5692da)

SERVER:
![Screenshot 2024-03-12 184601](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/e3607988-40b8-4c91-a178-bd8a76007638)


## OUPUT -RARP
CLIENT:
![Screenshot 2024-03-12 185144](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/ad8f98dc-61ca-4c4e-9fb2-df54775c16b9)
SERVER:

![Screenshot 2024-03-12 185131](https://github.com/jayaseelan2006/2c.ARP_RARP_PROTOCOLS/assets/151389443/b2e156b9-c0c0-4a2c-b9f9-7c87b93245e1)



## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
