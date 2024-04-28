The CineFlix{ Distributed Movie Ticket Booking System (DMTBS) }is a distributed system
that allows users to book and cancel tickets for movies in three different theatre
locations (Atwater, Outremont, Verdun). The system has two types of users:
admins and customers. Admins are responsible for creating movie slots with
specific movie types and booking capacities, while customers can book and
cancel tickets for the available movies. The system is designed to identify the
user's server by looking at the ID prefix and perform the operation on that server.
The system uses WEB-SERVICES between clients and servers and UDP packets
for communication between servers.
The goal of this project is to create a software failure tolerant or highly available
distributed movie ticket booking system. The system should be designed in such
a way that it can continue to function even if one or more servers fail or
experience other issues.
To achieve this goal, the system will need to have redundancy built into its design.
This can be accomplished by replicating data across multiple servers and using
load balancing techniques to distribute traffic evenly across the servers. In
addition, the system will need to be able to detect and recover from failures
quickly, in order to minimize downtime and prevent data loss.
The project also aims to ensure that the system provides a seamless experience
for users, with high availability and reliability. This means that customers should
be able to book and cancel tickets without experiencing any delays or errors, and
administrators should be able to add, delete, and list movie slots without any
issues. The system should also maintain accurate records of all transactions and
be able to provide detailed logs and reports for auditing purposes.
Overall, the main goal of this project is to create a distributed movie ticket
booking system that is highly available, reliable, and capable of withstanding
software failures or other issues.


For a full understanding of design and flow read here : [(https://github.com/Shivam-Mishra1417/-CineFlix-DMTBS-DistributedMovieTicketBookingSystem/blob/main/DSD_Project_Design.pdf)]
