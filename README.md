Let us not forget our roots, Bitcion v0.1.0. Pure code as close to Satoshi as you can get.
We have this pinned to our organization to remind everyone where we came from, so that we
can better see where we are going.

Announcement
-----
Announcing the first release of Bitcoin, a new electronic cash
system that uses a peer-to-peer network to prevent double-spending.
It's completely decentralized with no server or central authority.

See bitcoin.org for screenshots.

Download link:
http://downloads.sourceforge.net/bitcoin/bitcoin-0.1.0.rar

Windows only for now. Open source C++ code is included.

- Unpack the files into a directory
- Run BITCOIN.EXE
- It automatically connects to other nodes

If you can keep a node running that accepts incoming connections,
you'll really be helping the network a lot. Port 8333 on your
firewall needs to be open to receive incoming connections.

The software is still alpha and experimental. There's no guarantee
the system's state won't have to be restarted at some point if it
becomes necessary, although I've done everything I can to build in
extensibility and versioning.

You can get coins by getting someone to send you some, or turn on
Options->Generate Coins to run a node and generate blocks. I made
the proof-of-work difficulty ridiculously easy to start with, so
for a little while in the beginning a typical PC will be able to
generate coins in just a few hours. It'll get a lot harder when
competition makes the automatic adjustment drive up the difficulty.
Generated coins must wait 120 blocks to mature before they can be
spent.

There are two ways to send money. If the recipient is online, you
can enter their IP address and it will connect, get a new public
key and send the transaction with comments. If the recipient is
not online, it is possible to send to their Bitcoin address, which
is a hash of their public key that they give you. They'll receive
the transaction the next time they connect and get the block it's
in. This method has the disadvantage that no comment information
is sent, and a bit of privacy may be los