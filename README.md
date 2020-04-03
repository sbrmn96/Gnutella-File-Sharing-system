# Gnutella-File-Sharing-system
Multiple Peer to Peer Communication indicating the Gnutella system


ADVANCED OPERATING SYSTEMS
CS 550

Programming Assignment – 2

Manual Document
By

Subramanya Prasad Kantharaj (A20450692)
Shilpa Benarji (A20445736)



PROCEDURE:
• Download the PA2.zip file and extract the folder that is present.
• The folder Assignment consists of all the java source files and the class files.
• Check the Configuration file Config.txt that represents which peers are neighbouring to each other and how the topology works.
• The programming is done using the Java language and the version is jdk 13.0.2
• This was run and tested on Windows 10 and Linux Environment
This indicates the peer connections to the other available peers.
• Run the file PeerMin.java by using the command
“java PeerMain”
• The folder where the file is stored is indicated in the picture.
There shows a list of options when the PeerMain.java file is run

1) Register Peer
• This is an option that is used for the registering the particular peer to the Gnutella network.
• Once the Peer is set up, the files are linked and the operations can be accessed between them.
• Different command terminals are opened to access the other peers.
• Commands related to the files can be sent and received across these terminals.
• When the Peer P1 is registered, the files are also registered and the output is seen as this:
• Similarly, other peers will be registered by using the Register Peer option.
• Once the registration of the peers is complete, the next operation is locating the files and downloading them.
2) Lookup and Download Files
• There might be a file xyz present in Peer 6 that is essential for Peer7.
• These Peers have to be on the same network for the operation to take place.
• The peers can contact each other to search for the file and then download it.
• In this program, search and download are included in the same option.
• This helps to locate where the file is present and if the file is present, download will be completed.
• The operation takes place in this way:
• The filename along with the path is being entered for the lookup and download.
• The file to download is ten.txt, which is present in the Peer P6.
• The content present in the ten.txt is printed on the terminal screen of Peer P7, which asked for the download.
• The content of ten.txt “hello world” is printed on the terminal screen as the download of file takes place completely.
Close
• The close operation helps to exit from the Gnutella network.
LOG
• The operations that are performed on these files are saved in a file named Peerlog.txt. The flow goes like this:
REFERENCES:
1. www.wikipedia.com
2. www.computerhowstuffworks.com
3. www.sciencedirect.com
4. www.researchgate.net
