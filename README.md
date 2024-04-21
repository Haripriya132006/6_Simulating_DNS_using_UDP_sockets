# 6_Simulating_DNS_using_UDP_sockets
## AIM: 
The aim of simulating DNS using UDP sockets is to create a basic DNS server that can receive DNS queries over UDP and respond with the appropriate IP address for a given domain. In this simulation, we're simplifying DNS functionality, focusing on basic domain-to-IP mapping and handling simple queries.
## ALGORITHM 
1.Initialize DNS Server:
<BR>
Create a UDP socket to handle communication.
Bind the socket to a specific IP address and port to listen for incoming DNS queries.
<BR>
2.Define DNS Server Configuration:
<BR>
Set the DNS server IP address and port.
Prepare a mapping of domain names to corresponding IP addresses.
<BR>
3.Listen for DNS Queries:
<BR>
Enter a loop to continuously listen for incoming UDP messages.
Receive DNS Query:
When a DNS query is received, extract the domain name from the received data.
<BR>
4.Check Domain-to-IP Mapping:
Check if the received domain name exists in the predefined mapping.
If it does, retrieve the corresponding IP address.
If it doesn't, prepare an error response.
<BR>
5.Send DNS Response:
<BR>
If the domain is found, send the IP address back to the client.
If the domain is not found, send an error response.
<BR>
6.Handle Multiple Requests:
<BR>
The server remains in the listening state to handle multiple DNS queries.
Close the Server:
Optionally, include a mechanism to gracefully close the server when needed.
<BR>
## PROGRAM
## Server
![Screenshot 2024-04-21 174625](https://github.com/Haripriya132006/6_Simulating_DNS_using_UDP_sockets/assets/144870747/255fc62c-f455-439c-9500-4f5d5175182f)

## client
![Screenshot 2024-04-21 174620](https://github.com/Haripriya132006/6_Simulating_DNS_using_UDP_sockets/assets/144870747/c4aae166-f435-4447-b93e-7d44862b31b3)

## OUPUT
## server
![Screenshot 2024-04-21 174436](https://github.com/Haripriya132006/6_Simulating_DNS_using_UDP_sockets/assets/144870747/1bf6774e-3912-422c-90f8-8d1b808a33ae)

## client
![Screenshot 2024-04-21 174429](https://github.com/Haripriya132006/6_Simulating_DNS_using_UDP_sockets/assets/144870747/538a9190-e1ae-4780-8bca-2b87f6ece668)

## RESULT
Thus the Experiment implemented sucessfully
