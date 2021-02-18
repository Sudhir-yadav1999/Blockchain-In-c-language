# Blockchain-In-c-language(hash -sha256 implemented)

Minors project -1 

Problem statement

The main aim of our project is to eradicate one of the basic issue of our society that is the need of a middle man.
That is, our aim is to build a reliable, trust-worthy and robust network for peer to peer connection.
This connection runs on the idea of mutual trust and dependency.
So, in-order to implement this idea we use the concept of “BLOCKCHAIN” and our project will depict it’s requirement in the field of defence procurement. 
The main aim of removing the  broker/middleman is that it hampers the profit margins of suppliers thereby making it more reliable and free of corruption as there is no third party interruption. 
In order to implement the such a trustworthy network we have decided to use the concept of block-chain as the block-chain not only keeps the transaction encrypted but also transparent among the present entities. It also helps in maintaining proper logs of all the transactions, so that we could verify the subject in future

PURPOSE

The project is about making transaction between two parties easier and transparent. It also reduces the need of an inter mediator thereby reducing the chances of corruption by making one to one connection among the individuals involved. The main idea is to create a Block-Chain so that involved parties can store the data in the Block-Chain after being approved by the involved participants.
Key highlights of our project:

DESIGN AND METHODOLOGY


 Socket Programming for establishing connection between multiple nodes.
Socket programming ensures the connectivity among the nodes can converse for the deal making process.

	Linked list is used to demonstrate the blockchain.
Linked list depict the blockchain, stores the information about the transaction and act as an ledger.  

	Hashing through SHA256.

	Files management through file handling.


 EXECUTION (STEP BY STEP)
 
 In this project, working of block chain through a millitary purchase between countries (ex: India and USA )
 where we have designed 6 nodes in general,
 out of these 6 nodes we have assigned 3 nodes to Indian sides namely
 (Indian Army, Indian Ministry of Defence, Indian Ministry of Finance) and remaining 3 nodes to the side of USA ( which includes manufacturer ( Boeing), US Defence Ministry, US Finance Ministry) 
 
 STEP 1) Start a server using command
 gcc -Wall -g3 -fsanitize=address -pthread server.c  -I/usr/local/ssl/include -L/usr/local/ssl/lib -lssl -lcrypto -o server
./server 4444
 
 STEP 2) Start a client using command
 telnet localhost 4444
 ./client 4444
 
 STEP 3)Create 6 nodes
 -INDIA
        1)INDIAN AIRFORCE
        2)INDAIN MINISTRY OF FINANCE
        3)INDIAN DEFENCE
 -USA
        1)US FINACNE MINISTRY
        2)US DEFENCE MINISTRY
        3)US MANUFACTURER
  STEP 3) TRANSFER OF CHATS (ie hello send by one node is broadcasted to another nodes also)
  
  STEP 4)Transfer files into blockchain the file name include:-
        prop.txt -INDIAN AIRFORCE
        approval.docx-US DEFENCE MINISTRY
        money_tra.pdf-INDIAN MINISTRY OF FINANCE
        pay_req.html-US FINANCE MINISTRY
        
  STEP 5)File transferred by one node must be approved by another node in concent of y or n.
  
  STEP 6)Start blockchain and push file into blockchain
 TO start blockchain use keyword
 -"SEND"
  STEP 7)Push file into blockchain by node who has last send concent for approval

BLOCKCHAIN WILL BE WORKING AND YOU CAN DISPLAY HASH VALUE ALSO 

NOTE : The output of the code is saved in output.docx file have a look to see the flow of execution 
          

CONCLUSION AND FUTURE SCOPE
This project is robust and flexible enough to ensure quick, encrypted and decentralized transaction between any two parties involving multiple nodes on each side.
We demonstrated the concept of BlockChain through an idea of defence procurement that takes place between 2 nations. 
However, this project can be further elaborated by adding features like Pocket which would further enable the user to transfer money without the inclusion of any third party.
Further, the project can also be scaled up to have multiple trading partners simultaneously so that multiple clients can trade together in an encrypted environment.
