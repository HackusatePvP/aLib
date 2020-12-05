# API
This doc explains all the api usages.

## Chat
It is recommended you use aLib PlayerChatEvent. This event makes chatting a lot easier by using and Channels
and by using custom format placeholders. 

## Filtering
Chat comes with a pre-filter check, this check only permits very offensive words. 

## Staff
aLib comes with its own staff utilities with a Staff API as well.

## Server

### Server State
Server states are used to define the servers own personal status. The preset values are RUNNING, STARTING, RESTARTING, 
and MAINTENANCE.

### aSpigot
aSpigot takes into account staff players when getting onLinePlayers and other values.

### StaffApi
The api is pretty much self explanatory 

##Server
###States
aLib comes with predefining server states such as STARTING, RUNNING, and STOPPING.
When a server is not in state other than RUNNING, they will be disconnected for the state reason.

