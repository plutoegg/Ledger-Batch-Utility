Batch utility to send multiple eth confirmations using Ledger. 

Follow install instructions from main readme

cp ethConfig.json.example ethConfig.json

Update ethConfig.json and fill in infura url (used for broadcasting)

Update ethConfig.json and specify the fil to read the tx list from (or use the default Ledger-Eth-1)

Update ethConfig.json and enter the startingNonce (or pass it in at command line)


Usage: 
`node confirm.js <optional starting nonce>`

Program will cycle through the Ledger-Eth-1 file line by line and create /prompt user to review and broadcast the confirm transaction id. 
