# log_timestamps

Logs Interactions with Timestamps

Description:
This project is a Solidity smart contract that logs user interactions with messages and timestamps. Each interaction is stored on the blockchain, allowing users to keep track of logged events securely.

Smart Contract Address:
0x1D16B3BCFA89a7D1525eA0844A0FE0d436deE952

Features:
Users can log interactions with a message.
Each log entry includes the sender's address, message, and timestamp.
Logs are stored on-chain and can be retrieved anytime.

Usage:
Deploy the smart contract.
Call logInteraction(string memory _message) to record a message.
Retrieve logs using getLogsCount() and getLog(uint256 index).

License:
This project is open-source and available under the MIT License.

