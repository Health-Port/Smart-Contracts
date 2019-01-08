# Health Port 

Health Port is a patient-centric healthcare information system that will bring patients a portable, interoperable, decentralized, integrated system for managing their personal electronic health records.

The smartcontract.sol contains the code for smart contract of health port.

# Health Port Smart Contracts
* `HealthPort.sol` Logic for Submitting Medication, Allergic and Procedure Documents on blockchain
* `Ownable.sol` a contract with an owner.

## Compiling & Deploying Smart Contracts on Tron Network
* Smart Contract is compiled from tronbox which is a user-friendly IDE for developing contracts.
* Once Tron Studio is launched, please copy and paste the Health Port smart contract source code into the main window.
* Select the Compile button under the Compile tab in the far right window.

* After successfully compiling the smart contract, navigate to the Run tab. 
* Click on the Settings gear icon on the upper right to edit settings for Local TVM, Test Net, and Main Net. 
* In the Test Net field, fill in grpc.shasta.trongrid.io as your HTTP input and 50051 as your port input. This configuration allows contract deployment on the Tron Shasta test network.
* Click on Deploy button and it will deploy the smart contract on the tron network.
