Today we’ll be talking about network addresses.

So let’s say I want to send some information to another computer.  I can think of it the same way as I’d send a letter to one of my friends.  I need to know where it’s going.  If I want to send it within my own town (network), all I need to know is the local address (MAC address).

But if I want it to go further than that (the Internet), then I’m going to need the external address (IP address) and the port.

So putting those together, an address is a local (MAC) address, a network (IP) address, and a (TCP/UDP) port.

A MAC address is at the Data Link Layer, also known as the Local Layer, or Layer 2.  It is a physical address assigned by the manufacturer.  So every device that Apple, Dell, or Asus makes has one of these numbers assigned to it in the factory.  It’s a hexadecimal (16) number, meaning that digits go from “0” to “f” (0,1,2,3,4,5,6,7,8,9,a,b,c,d,e,f--16 digits).  And we can see how a MAC address might look in the MAC Address slide, as well as its binary representation.

Next, we’ll talk about the IP address, which is at the Network Layer (going to the Internet), also known as Layer 3.  It is a network address which is usually assigned by an administrator.  It is 4 octets, or 4 sets of 8 binary digits.  So each octet has a value between 0 and 255 (2^8).  And we can see how an IP address might look in the IP Address slide, as well as its binary representation.

Last, we’ll talk about the TCP or UDP port, which is at the Transport Layer, also known as Layer 4.  This port tells the destination endpoint how it is going to interpret the data that is incoming.  It is a number between 0 and 65,535 (2^16).  And we can see how a couple of common TCP ports might look in the TCP/UDP Port slide.