# What is it

rhim stands for _this host is mine_ and is a tool to reserve a host
if a group of people are using some hosts

# How it works
There is a server and a client.
Server is installed as a web REST application. Perhaps gRPc.


## Server 

- lists the machines
- allows to
  - add new machines
  - tag machines
  - change description of a machine
  - change owner of a machine
  - ask who is an owner of a machine

## Client

- can ask server 
  - for a list of machines
  - for all machines of a tag
  - edit machine
    - change description
    - change owner
  - add machine
  

This has two parts. A server that is running on a machine
