# AeroChain-Airport-Lost-Baggage-Tracking-using-Blockchain-
Airport Lost Baggage Tracking using Blockchain

 ## Abstract
This project attempts to address the issue of lost luggage at airports. Mis-transportation and luggage loss have cast doubt on the current aircraft business. Adding to this, there are several issues that also exist like the difficult and time taking process of compensation. This abstract proposes a more dependable and secure method of tracking and managing missing luggage. 

Keyword: Blockchain, Aerochain, Airport Baggage.

## Proposed System
The proposed system is to make a secure and user-interactive platform for baggage management that uses blockchain technology as the base to ensure transparency, accountability, and data integrity. The system consists of two sections: Airport-Register to upload unclaimed baggage, and Baggage-Claim for the passengers.

## Sequence Diagram for Proposed System:
The flow of sequence diagrams illustrate a series of interactions between different entities like airport authority, airports, and passengers, with the contract state acting as a shared ledger to maintain the state of the system.
![image](https://github.com/Nishu2903/AeroChain---Airport-Lost-Baggage-Tracking-using-Blockchain-/assets/117971452/19a1f8ef-2efe-4750-a199-d23382852391)

Fig. 1 shows the test plan using a sequence diagram between different entities, which consists of executing the different functions in the smart contract namely “BaggageClaim” smart contract. The functions are formed by constructor(), Airportregister(), ClaimRequest(), addLuggage(), ClaimResponse(), Paymentsettle(), and Airportunregister(). The higher authority of the Airport is the AirportAuthority entity. The Airports can self-register on the Login page and proceed to add baggage and then approve and disapprove based on given hash value. Passengers can register as Customer to Portal and access the details uploaded by Airports.

## Technology 
To proceed further in the process, either of Airport or Passenger has to register their details on decentralized application which is developed and deployed with followings:
●	Ganache: Ganache is generally used as Simulator as it stimulates as a main Ethereum network, but actually it operates locally on the system, hence it serves as a Private Blockchain to deploy contracts and further testing as well.
●	Truffle: Truffle is a framework to develop smart contracts and test them using the Ethereum Virtual Machine (EVM).
●	Solidity, Web3, and ReactJS: Solidity is used to develop smart contracts. The frontend part is formed using ReactJS and using Web3 provider, these both parts are configured to connect and facilitate a fully working system.

## Main Landing Page:
![image](https://github.com/Nishu2903/AeroChain---Airport-Lost-Baggage-Tracking-using-Blockchain-/assets/117971452/3db7c465-74ff-473f-a754-7193c3319066)

## Airport Registration:
![image](https://github.com/Nishu2903/AeroChain---Airport-Lost-Baggage-Tracking-using-Blockchain-/assets/117971452/914f0457-8063-4310-8914-44d29a4067c2)
Figure 3(a) shows the Login interface where new Airports can come and unlist themselves with a total number of Unclaimed Baggages. Figure 3(b) shows the Metamask Account created for Airport Demo Registration. Figure 3(c) is the output window after successful registration of Airport and airports can unlist themselves on a decentralized application. A Airport.json file is used which contains 50 Indian Airports which are listed as options.

![image](https://github.com/Nishu2903/AeroChain---Airport-Lost-Baggage-Tracking-using-Blockchain-/assets/117971452/78229fe1-1823-4249-adfa-f76538576308)
Here the Transaction Block is created after the Airport Registration. The Airport unlists themselves with unclaimed baggage and data is taken as input into decentralized application. Gas price is used as a parameter in blockchain, this gas price is decided by miners and all nodes on blockchain validate the transaction. In the end, if the block is added in the network, the miner receives the gas fee. In Fig. 4, a Block generated for an Airport Registration while the transaction id generated is(while gas used:21000 at gas price of 2043295517): 
0x2302e10b71b93fec1d913cc94fda7f41326f40617de44a940761babb1baa1689

## Passengers Registration:
![image](https://github.com/Nishu2903/AeroChain---Airport-Lost-Baggage-Tracking-using-Blockchain-/assets/117971452/3bbfff8f-d7ea-493e-8145-e74c30f52b29)
Figure 5(a) shows the Login interface where new Passengers can come and register themselves and find the total number of Unclaimed Baggages listed by Airports. Figure 5(b) shows the Metamask Account created for Passenger Demo Registration. Figure 5(c) is the output window after successful registration of Passenger, he/she can getDetails of Unclaimed Baggage by clicking Get Details Button and proceed to Claim Section if he/she is interested in Claiming the baggage.

![image](https://github.com/Nishu2903/AeroChain---Airport-Lost-Baggage-Tracking-using-Blockchain-/assets/117971452/bf9a08a7-1959-4a86-aa92-cbbce7884fbc)
In Fig. 6, a Block generated for an Passenger Registration while the transaction id generated is: TX 0x035198836e29c2da566a8333570ffcd6f83c8aed6855d3add5e03f49fce5331d while gas used:21000 at gas price of 1795433488. 

## FlowDiagram:
![image](https://github.com/Nishu2903/AeroChain---Airport-Lost-Baggage-Tracking-using-Blockchain-/assets/117971452/aae4a7e6-8098-4caf-93ee-f42d602be8aa)


## Result 
In conclusion, the project “Aerochain” is a novel approach towards addressing the problem of lost or mishandled baggage at airports. The use of blockchain technology and the Solidity programming language has enabled us to create a secure, decentralized, and immutable system for tracking and managing baggage at airports. Through this project, we have successfully implemented a user-friendly web interface that allows passengers to request a claim for their lost baggage and track its status in real-time. The use of blockchain technology ensures that all data related to baggage handling is transparent, tamper-proof, and can be easily audited by relevant stakeholders.










