 What is the purpose of using sessions?



Sessions provide a way to persist data across requests, so we use 
sessions to allow a server to store information about a client that 
can be used for a variety of purposes. One of these is to persist 
authentication information so that there is no need to re-enter 
credentials on every new request that the client makes to the server.

 What does bcrypt do to help us store passwords in a secure manner?


bcrypt uses cryptographic hashing incorporating a salt to help us store 
passwords in a secure manner.

 What does bcrypt do to slow down attackers?


To slow down attackers, bcrypt uses an algorithm with accumulative 
hashing rounds, meaning that it hashes the information multiple times 
(rounds).

 What are the three parts of the JSON Web Token?


The three parts of the JSON Web Token are the Header, the Payload, and 
the Verify Signature.