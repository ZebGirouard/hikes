Today, we’ll be talking about network maps.

So we can see a very simple network map with Computer A and Computer B.  Already with such a small map, we may see a small problem.  What happens if Computer A and Computer B want to talk at the same time?  And to make matters worse, many networks have hundreds of these computers that want to talk at the same time.  That’s where network maps come in, to help manage that traffic.

Network maps are usually divided into 2 types.

Layer 2 maps can show all of our local connections.  They map out Switches for our Ethernet cable connections and Access Points for our Wireless connections.  And the way they manage traffic/destinations is by MAC address.

Layer 3 maps can show all of our global connections, out to the Internet.  They map out Routers and all their connections.  And the way they manage traffic/destinations is by IP address.

In the hardware, that looks like the Crossover slide.  We have 8 wires in a typical Ethernet cable, and the input wire from one computer is mapped to the output from the other computer.  This way, 2 computers can talk at the same time because they use different wires for their input and their output.

An actual Layer 2 map might look like the one in the Layer 2 slide.  We have 6 blue Switches and a few computers plugged into each of the Switches.  So each of these Switches has something like 32 ports where you can plug in an Ethernet cable.  And when information is sent out, a computer says, “I’d like to talk to this computer,” and the Switch says, “OK, I know that computer is connected to that port,” and it sends the information out that port.

If we want to get out of the network, we use Routers.  Routers are usually represented in a map as circles with arrows.  Each Router, connecting to the next Router, will use an IP address to get to its destination.  And once we get to the right Router (the right network), then we dump the information back to Layer 2.

In the Complex Case slide, we have three Layer 2 diagrams in beige.  So we route to the proper network which might be a company or city.  Then we go to the right Switch.  And finally we get to the right computer.