-------------------------------------------------------------------------Project Version and Address-----------------------------------------------------------------------
FarmerRole Contract Addres: 0x5e661e3dda2db47fbe7dd32a5a6b2fd8dda76294
DistributorRole Contract Addres: 0x0f1b7ba1e15e3d49cd0e85de07a1292d1dfb439a
RetailerRole Contract Addres: 0xbe880b2929563dc45fc5fd94ffec1e14897baf09
ConsumerRole Contract Addres: 0x1820a3b172043f804d9bd52a3e3f7773e0cd1c4d
SupplyChain Contract Addres: 0x201f8a83024f9afb26212865a271e86bc8947fe6
web3 version number  : 0.20.6
Truffle version number : Truffle v4.1.14 (core: 4.1.14)
Solidity version number : Solidity v0.4.24 (solc-js)
node version number : v11.12.0
Libraries added:
Web3 : to connect to infura for etherium blockchain access
Truffle-Contrat - to load contract
web3-utils - to get wei conversion
truffle-hdwallet-provider - to authenticate ransactions using wallet


-------------------------------------------------------------------------Rinkeby Migration Details--------------------------------------------------------------------
Running migration: 1_initial_migration.js
  Replacing Migrations...
  ... 0x62f038b32f8e53adf5eadee8f65a41ac475ad5cba3936583f36efe8f014d95af
  Migrations: 0xddfd0f4cfaf15eec8d932f9250c4a1382a73afca
Saving successful migration to network...
  ... 0xb3efc43f328f1d19d9bea35359a5e389144959251573a57e744002045e3bc1d3
Saving artifacts...
Running migration: 2_deploy_contracts.js
  Replacing FarmerRole...
  ... 0x3598ed6ea34ab55b9e166947dfa5f2b88f87bdbd6bec2b71285e1d9cbf2722c4
  FarmerRole: 0x5e661e3dda2db47fbe7dd32a5a6b2fd8dda76294
  Replacing DistributorRole...
  ... 0x7aa712cbc1e9b1c8f6dc69ec6ef9bbab6d4ebb6ff8890f627d90660dec83fcbc
  DistributorRole: 0x0f1b7ba1e15e3d49cd0e85de07a1292d1dfb439a
  Replacing RetailerRole...
  ... 0xc60f5d83695765a10616f489083590b2fd0a85b7fc20366093308b778893a721
  RetailerRole: 0xbe880b2929563dc45fc5fd94ffec1e14897baf09
  Replacing ConsumerRole...
  ... 0x56127bc5bf75c9f795dc89d5a3e894a292f8595bf2310b45517739290b5ebe4d
  ConsumerRole: 0x1820a3b172043f804d9bd52a3e3f7773e0cd1c4d
  Replacing SupplyChain...
  ... 0x927ce6b9081dede583ee32d0622dfca141574ed57d9c48e3f83fcd7a85fc450f
  SupplyChain: 0x201f8a83024f9afb26212865a271e86bc8947fe6
Saving successful migration to network...
  ... 0x45d50e4da7a03cbcb694915f959b46661c8b0ffc788f4e19a4f8897247246de5
Saving artifacts...




----------------------------------------------------------------------------------Project Details---------------------------------------------------------------------------
# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

