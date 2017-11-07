# BIT Platform #################################################################

**Platform the Blockchain for the Internet of Things**

Alexander Ivannikov a.n.ivannikov@yandex.ru  
Iraida Sak i.a.sak@yandex.ru  
*Published 04.11.2017 / Version 0.0.0*  
*For discussion, [join our group in Telegram](https://t.me/bit-platform)!*

### Purpose ####################################################################

--------------------------------------------------------------------------------

The main purpose of the project is the creation of a new decentralized secure platform for the Internet of Things (IoT-platform), which will combine a devices Internet of Things (IoT-devices), Blockchain, cryptography and crypto-currencies.

*A IoT-devices connected to the BIT-platform of things will allow you to receive reliable data about the surrounding space and perform any actions related to the outside world. Under the IoT-devices you can understand any device that can be connected to the network. For example, robots, "smart" technology, control and automation tools, mobile devices, etc.*

For the comprehensive development of the BIT-platform  we plan to release the software for all operating systems and platforms, and also create own version of the operating system based on Linux for nodes and IoT-devices.

In the BIT platform, we plan to implement the following components:  
  - [ ] Internal fast and easy crypto currency to maintenance the work of the BIT-platform:
    - [ ] Unlimited block;
    - [ ] Adaptive time of creation block, which will depend on network parameters;
    - [ ] Adaptive transaction fee, which will depend on network utilization, including zero transaction fee for micropayments - some minimum number for a certain period of time;
    - [ ] Recalculation of the complexity after each block;
    - [ ] The introduction of a new block type is an Actual block that will be periodically generated and exclude non-actual data at the time of block formation. For synchronization with the network it will be enough to download all the blocks starting from the last Actual block. Example. Since the last Actual block, 1000 transactions have been made at the time of formation of the new Actual block at a specific address. In the new Actual block, this address and current balance will be recorded, if the address balance is 0, then this address will not be written to the new Actual block;
    - [ ] Private addresses and transactions (Zcash or other protocol);
    - [ ] Invoice for payment;
    - [ ] Transmit data in transaction:
      - [ ] A comment;
      - [ ] Arbitrary data;
      - [ ] A program (samart-contract).
    - [ ] Time of data actuality is a parameter that determines the value of data in coins over time and protects the current blockage from oversaturation with non-actual information. Information with the actuality of 0 will not be recorded in the current block;
    - [ ] Separation of types of rewards and fees into the following types:
      - [ ] Block creation;
      - [ ] Maintaining the network;
      - [ ] Data storage, including storage of the all blockchain of network (archive);
      - [ ] Computing and processing data (distributed computing).
    - [ ] Avoiding the use of the PoW (Proof of Work) algorithm.
  - [ ] Internal encrypted messenger;
  - [ ] Creation of digital assets (tokens);
  - [ ] Internal decentralized exchange;
  - [ ] Programs (smart-contracts);
  - [ ] Automatically configurable network layer (using Artificial Intelligence);
  - [ ] Creation of clusters conjugated to the main network;
  - [ ] Decentralized, secure, automated system for managing IoT-devices;
    - [ ] Connecting IoT-devices to the cluster;
    - [ ] Management of IoT-devices;
    - [ ] Processing data received from IoT-devices.
  - [ ] Connection of external crypto-currencies as separate clusters of the main network;
  - [ ] Connection of external interfaces as separate clusters of the main network;
  - [ ] Internal encrypted workflow system;
  - [ ] Torrent;
  - [ ] Decentralized database;
  - [ ] Distributed computing.

--------------------------------------------------------------------------------

*NOTE: We're still actively developing this document. Please check regularly for updates on GitHub!*

*NOTE: This document are presented in [Russian](PURPOSE_RU.md "PURPOSE_RU.md") and in [English](PURPOSE.md "PURPOSE.md") languages.*

*NOTE: This document is a translation from Russian. In the event of a conflict between the Russian version and this translation - only the Russian version of the document has legal force. The Russian version of the document can be found [here](PURPOSE_RU.md "PURPOSE_RU.md").*
