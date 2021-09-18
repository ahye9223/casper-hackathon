# Casper introduction

# Step 1
* Installed Rust and CMake, since I didn't have them before
* Installed the Rust Casper crates
* Created a sample Casper project
* Since Casper uses WASM in its runtime, I changed the target build platform to wasm32
* Compiled the smart contract and ran the tests

Compiling the contract
![](https://i.imgur.com/wNBuEq9.png)

Running the tests
![](https://i.imgur.com/5krjiP8.png)

Deploying the contract
![](https://i.imgur.com/FVEPKcN.png)



# Step 2
I chose the "Key-Value Storage Tutorial".
* Clone the repository from https://github.com/casper-ecosystem/kv-storage-contract
* Read the explanation
* Run the tests successfully in a local environment using the Casper's cargo crate
* Deployed the contract to the testnet


Tests running successfully
![](https://i.imgur.com/Wy7tN2b.png)

Deployed smart contract
![](https://i.imgur.com/7Ktd5xF.png)


# Step 3
* Read the concepts about multi-signatures
* Clone repository
* Added the wasm32 target
* Compiled the contract
* Set up local test network
* I chose scenario 1, signing with a single key

Code
![](https://i.imgur.com/tkdREUb.png)

Result
![](https://i.imgur.com/7mKYNPZ.png)
![](https://i.imgur.com/CB19LkP.png)

# Step 4
Sending a transaction
![](https://i.imgur.com/rGZ3Wll.png)

# Step 5
* Opened the validators page on the testnet explorer and chose a validator

Delegate
![](https://i.imgur.com/sJpFa2H.png)

Undelegate
![](https://i.imgur.com/f2y6L9B.png)


# Conclusion
I greatly enjoyed this project. The docs are mostly well written and there are lots of tools available for interacting with the network.
