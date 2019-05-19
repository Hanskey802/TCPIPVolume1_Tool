# TCPIPVolume1_Tool
It is a wonderful Tool. Very useful for TCP experiment. How to use according to TCPIP volume 1.

Once, I used this tool to test in Netfilter_TCPIPChecksum

Installation:  tar -xzvf sock-0.3.2.tar.gz   && ./configure && make && make install

Server: sock -s <port> e.g. sock -s 30000

Client: sock <ServerIP> 30000

More options please sock --help

NOTE:
Checked in VM in Virtualbox. The checksum of TCP and IP are correct.
Sometimes, maybe you need to shutdown tso, gso, gro.
