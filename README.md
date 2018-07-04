# Genesys-Framework

## Common Terms

### Automatic Call Distributor (ACD)
Phone System that:
  - Answers incoming calls
  - Gets Information and instructions from database
  - Determines the best way to handle the call
  - Sends the call to the proper agent

### Automatic Number Identification (ANI)
System that utilized by telephone company to:
  - Identify the directory number (DN) of a calling subscriber
  - Through subscribers can block Caller ID
  - Usually impossible to block
  - ANI data is transmitted in-band using multi-frequency signaling
  
### Contact Center
Centralized place in a variety of media are sent and received
Softwave, hardware and human infrastructure are maintained at the contact center to manage customer interactions

### Directory Numbers (DNs)
Contact points where an interaction is handled. Genesys refers to several types of contact points as DNs
  - Routing Points
  - ACD Queue
  - Extension/ACD Position
 
### Dialed Number Identification Service (DNIS)
Identifies the phone number the caller dialed to reach the answering telephone system
Maybe a number translation, depending on the dialing plan

### Interactive Voice Response (IVR)
A hardware or software system that uses responses from a touch tone telephone to prompt, gather and store data
it is sometimes referred to as a Voice Response Unit (VRU)

### Private Automatic Branch Exchange (PABX)
Telephone switch inside a private business

### Public Switched Telephone Network (PSTN)
The public telephone network to which telephones, ACDs and PBXs are connected, aka the network cloud

### Telephony Server (T-Server)
  - Know what activity is taking place on the switch
  - Able to coordinate with the telephone system in the contact center
  - Finds out about the activities by message from the switch via the CTI link and translating them into a standard format and distributing these translated messages to client program likes the Agent Desktop
  
### Screen Pop
  - T-Server relates information to an agent's service application through the notification from CTI system

### Trunk
A physical link (wire, optical line and so forth) between telephone exchanges (switches)
  
![alt text](https://github.com/tommycmt/Genesys-Framework/blob/master/figure/framework.png "Framework")
