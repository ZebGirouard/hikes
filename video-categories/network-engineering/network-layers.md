Today we’ll be talking about the 7 layers of computer networking.

So let’s take a simple example.  If we have Computer A; it has some information that it wants to communicate to Computer B; and it wants to say something like “01100011”.  All it needs to do is send that electrical information over to Computer B, and everything is all set.

And this works really well when we have 2 computers. But when we get a lot more computers, that’s where networking layers come in.

So we can consider networking layers as layers of electrons.  Basically a computer signal is just a stream of electrical input.  It’s the same if we’re talking about inside a computer as if we’re talking about between computers.  We have “0” for off and “1” for on.  So if we want to send the information “1010111”, all we have to do is turn a switch on / off / on / off / on / on / on.

As we go outside the computer, we need to pick up a new box of information, a new set of “0”s and “1”s so that the information knows how to get to its destination.  And then, when we get to the destination, we’re going to shed these boxes as we decrease those layers.  Then the destination computer can see the information inside.

The OSI, or Open Systems Interconnection model, has 7 of these layers.  We can see what that looks like in practice on the Onions Have Layers slide.  We have a set of data.  We pack a header of “0”s and “1”s onto it.  Then we pass it up to the next layer.  Then we pack another header on it, pass it up to the next layer, etc.

We start down at the bottom, at the Physical Layer, which is just our “0”s and “1”s of data that we want to get to another computer.

If we want to talk to computers within our network, we go to the Data Link Layer (Layer 2), which has our MAC Address and local information.

Then if we want to go to the Internet, we go to the Network Layer (Layer 3), which has our IP Address and network information.

Then if we want to direct to a specific port like HTTP or HTTPS, we go to the Transport Layer (Layer 4), which has our TCP/UDP port information.

And then all the way at the top, we have our data layers, which tell our destination computer how to interpret the incoming data.