# Empire-LupinOne-Writeup
A writeup of my methodology for attempting the Vulnhub Machine Empire: LupinOne


1. The Attack Phase 1:  Information Gathering
 
The  first  part  is  focused  on  gathering  the  network  information  for  allthe  machines  involved.   This  includes  confirming  the  IP  address  of  the  machine  used  for carrying out the attacks, as well as finding the IP addresses of the target machine on the network.  After collecting those,  the next step for each of the target machine is to collect more information regarding each one such as OS versions, Open ports, and so on.

   *  IP addresses / Live hosts Discovery

To locate the IP address of the Machine that will be carrying out the tests, in this case, amachine running Kali OS, the commandif configis used, as shown in the figure below:

![nmap-fping](https://user-images.githubusercontent.com/58232821/143317977-ba560e38-3a9d-4007-b388-8f8003ee6d8e.png)
