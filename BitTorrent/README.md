# BitTorrent-type P2P file sharing

## Group 43
* Mohammed Haroon Rasheed Kalilur Rahman - 6751 2967
* Siddharth Yellur Sathiesh - 1361 7920
* Ariz Ahmad - 7111 2167

## Description of Source Files
* ConfigFile.java - has config file parameters
* Logs.java - logs all the actions
* NeighbourPeerNode.java - maintains the bitfields for all the neighboring peers
* PeerCommonUtil.java - splits the file into chunks, read and write the file chunks, creates log and peer directories, and combines the chunks into a single file.
* PeerConstants.java - has all the message type and other constants
* ReadFiles.java - reads the Common.cfg and PeerInfo.cfg 
* RemotePeerInfo.java 
* StartRemotePeers.java - start remote peers
* peerProcess.java - main java file where connection establishment, choke and unchoke, and file exchange takes place
 
## Instructions for Execution
* javac *.java
* java StartRemotePeers
* pkill -u <username>

## URL for Video file
https://drive.google.com/file/d/1xkK57HADvaKx6T_-d7-0sgmFlu-CKdG0/view?usp=sharing
 