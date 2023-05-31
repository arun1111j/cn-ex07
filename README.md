# IMPLEMENTATION OF TRACEROUTE COMMAND
# EXP NO:7
# DATE:19-04-2023
# AIM :
## To write the python program for simulating Traceroute command
# ALGORITHM :
## 1. Start the program.
## 2. Get the frame size from the user.
## 3. To create the frame based on the user request.
## 4. To send frames to server from the client side.
## 5. If your frames reach the server, it will send ACK signal to client
otherwise it will sendNACK signal to client.
## 6. Stop the program

# CLIENT PROGRAM :
# PROGRAM :
```PYTHON 3 
from scapy.all import *
target = ["www.google.com"]
result, unans = traceroute(target, maxttl=32)
print(result, unans)
```
# OUTPUT :
![image](https://github.com/arun1111j/cn-ex07/assets/128461833/a3c35f4e-debd-41a5-bfb8-4feebbad3355)

# RESULT :
## Thus, the python program for simulating Traceroute command was successfully executed.
