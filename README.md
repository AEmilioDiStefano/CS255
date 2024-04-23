The client for this project was a company called DriverPass.  DriverPass wants to create a web-based 
application which allows driving students to set up in-car training sessions and schedule their driving 
tests at their local DMV.  We began by conducting an interview with the client company owner Liam, their 
IT Officer Ian, our project lead Jennifer, and former system analyst Sam.  During the interview, Liam 
expressed that DriverPass would like to help driving students pass their driving testsby allowing users 
to choose from different DriverPass Packages to meet their individual needs.  Package One includes six 
hours in a car with a trainer.  Package Two includes eight hours in a car with a trainer and an 
in-person lesson explaining the DMV rules and policies. Package Three includes twelve hours in a car with 
a trainer, an in-person lesson explaining the DMV rules and policies, and access to an online class with 
all the content and material including practice tests based on material covered in the class. 
Administrators who will be using the system include DriverPass IT officer Ian who will be performing 
system maintenance as needed, and DriverPass' secretary who schedules appointments. 

I believe that I captured all of the functionality described by Liam in the DriverPass interview in a way 
which leverages object oriented programming principles such as encapsulation and polymorphism, for example. 
As can be observed in my UML class diagram depicted in my system design document, I designed the system with 
four types of client-side users: ‘NewUser,’ ‘PackageOneUser,’ ‘PackageTwoUser,’ and ‘PackageThreeUser.’  
Since Package Three includes everything included in Package Two and Package Two includes everything in 
Package One, I made the ‘PackageOneUser’ class a parent class of the ‘PackageTwoUser’ class, and I made 
the ‘PackageTwoUser’ class a parent class of the ‘PackageOneUser’ class.  This means that users who have 
purchased Package Three will have access to all of the functionalities to which users who have purchased 
Package Two have access, and that users who have purchased Package Two will have access to all of the 
functionalities to which users who have purchased Package One have access.  This will also make it so that 
the process of making changes to the functionalities included with each package will only need to be edited 
once within one of the three classes associated with users who have purchased DriverPass packages, making 
the DriverPass system efficient and simple to modify in the future as needed. 

One change which could be made to my system design document would be the inclusion of a brief description 
above my UML use case diagram, my UML activity diagrams, and my UML sequence diagram as I did above my UML 
class diagram.  Though these descriptions were not included in the prompt, they could help less technically 
inclined individuals to better understand the models and the dataflows depicted within them.  

I interpreted the users' needs by carefully reviewing the DriverPass initial interview transcript and 
designing the system based on the functionalities specified by the client, and then modeling the system 
based on those requirements and on relevant object-oriented development principles which could be used to 
make the system as effective, efficient, and functional as possible.  It is of the utmost importance to 
carefully consider and address the needs of the client and those of the system’s users (the client’s 
customers) in order for the system to most effectively solve the problems which it is meant to solve.  
With these considerations in mind, my approach to designing software involves translating the needs and 
requirements of the client into a robust and efficient object oriented system for the client to provide 
to their users.  I always consider different aspects and concepts of object-oriented development which 
can be used to make the most effective, precise, and scalable system possible according to the needs of 
the client.  
