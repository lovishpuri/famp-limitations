# famp-limitations
Famp is a secure p2p (peer to peer) social network, hence it has the limitations of typical p2p communication. It needs a good number of active users which might be difficult in the early stage of famp.

In a p2p network, data is exchanged directly between devices without going through a central server. It requires that your device is reachable on internet from outside. Depending on your network configuration, your public IP might not be accessible from outside. Eg. Office WiFis have a firewall that blocks all inbound traffic. Sometimes on mobile data, connection is not responsive enough for secure p2p communication, carrier might have random restrictions preventing p2p exchange.  Generally speaking, if you’re connected to home WiFi (without any special network configuration) and have a public IPv6, you should be fine.

Other peers may not be able to reach you, but you can reach other peers if they're reachable. P2P will work just fine if there are plenty of active peers that are reachable.

For efficient broadcast of posts, there must be a good number of users who are active, most of the time. Information is shared between active peers, and it gets relayed when other peers come online later. In Gossipsboard, posts are shared between peers located in an area, so there needs to be several active users in that area.

