Token Data Converter (TDC)

Summary: The goal of the Token Data Converter (TDC) is to easily take the token contents of a connected wallet and convert it into a usable spreadsheet format. 

User Workflow: 
1. A user navigates to our custom URL (tokendataconverter.com). 
2. They click the connect wallet button and follow the prompts until the wallet is fully connected. 
3. The website displays some high level summary info on tokens (# of ERC 721s, ERC 20s, ERC 1155) to user. 
4. User clicks "convert spreadsheet" button. 
5. When conversion is complete a download xls/csv link appears for user to download locally. 

Pseudocode:
1. Front end displays all relevant information to users and changes given the stage user is at.
2. The connect wallet button needs to work as a dapp that connects a metamask wallet to the smart contract.
3. The smart contract has to scan the wallet and extract all token data into a structured format.
4. The smart contract data needs to summarize key data and present to user on the front end.
5. Once user submits a conversion request, the smart contract has to generate a spreadsheet file and correctly format data into rows and columns
