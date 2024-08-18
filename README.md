# OSPF-configuration

# Configuring OSPF (Open Shortest Path First) on a Cisco Router
 


![image](https://github.com/user-attachments/assets/8526c1dd-10bd-4114-8e4e-72c2939931f1)














## To configure a router with IP addresses on two interfaces—one connected to a switch (SW1) and another connected to a second router (R2)—follow these steps:

 ![image](https://github.com/user-attachments/assets/ae352dab-4a58-4d62-831b-6a3dc6c3e32a)
![image](https://github.com/user-attachments/assets/e8c6be67-00eb-45c7-aeff-414f211b62ed)




 

## To configure a router with IP addresses on two interfaces—one connected to a switch (SW2) and another connected to a second router (R1)—follow these steps:

 ![image](https://github.com/user-attachments/assets/d8cfd3a2-ce50-4f5b-9b6b-f4c89f509dbf)

![image](https://github.com/user-attachments/assets/8cf56d77-e305-4962-ba7b-31f8d0757722)

 

## To configure a router with IP addresses on two interfaces—one connected to a switch (SW1) and another connected to a second router (R2)—follow these steps:
![image](https://github.com/user-attachments/assets/3a311594-702e-4678-9343-20d937fee93d)

 

## Now I am attempting to ping PC4 to check if it is reachable.
![image](https://github.com/user-attachments/assets/400b1c0e-cf93-49d7-8301-2adc09671891)





 
It is unreachable because the devices are on different subnets, and no routing protocol has been configured. I am now setting up the OSPF protocol to enable communication between PC4 and PC5.






## Now I am configuring and enabling OSPF to allow communication between both subnets.


## First, access global configuration mode on your router. Then, activate OSPF routing by entering OSPF configuration mode and assigning a locally significant process ID. Next, define the networks that will participate in OSPF by specifying them with wildcard masks, and assign each network to a specific OSPF area. Finally, configure a unique router ID for this OSPF instance to identify the router within the OSPF domain.

![image](https://github.com/user-attachments/assets/43379c7d-ba02-4fc1-9435-6246855a3750)









 
## To check for OSPF neighbors on your router, use the command:
 
![image](https://github.com/user-attachments/assets/df34cfcd-8fda-4d73-adf1-b0fe296fc420)




## Now I will configure OSPF on Router R2 to establish communication across the entire network.

![image](https://github.com/user-attachments/assets/64beb9d4-93f2-4cf7-8587-a70d38272ae0)




 

## To check for OSPF neighbors on your router, use the command:

 
![image](https://github.com/user-attachments/assets/afae42de-e2dc-4660-9d96-fd9cef46a297)





## Ping PC5 from PC4 to verify if they can reach each other.


![image](https://github.com/user-attachments/assets/12dca4e2-c4b2-4a77-ba1f-0787663ddd34)




 









## Go to the other subnet and ping from PC4 to PC5 to check if they can reach each other.

 ![image](https://github.com/user-attachments/assets/a807ef6a-c3f3-471c-8539-727b1db67b38)


# The project, which involved configuring OSPF, was completed successfully.







