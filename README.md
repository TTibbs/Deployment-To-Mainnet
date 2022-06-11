# Deploying Flattened Contracts To Mainnet

A detailed description of how to deploy your already flattened smart contracts to the ethereum mainnet using remix.ethereum.org and to verify them on etherscan.

This is a step by step guide of how I deploy contracts on remix to ensure it goes smoothly after testing it in the JavaScript virtual machine and flattening them.

# Step one: 
After testing your code out in the JavaScriptVM check to make sure you do not have auto compile ticked here

<img width="680" alt="Step1" src="https://user-images.githubusercontent.com/104795657/173172238-e56bece1-6d87-47a9-a50c-236abe263e10.png">

# Step 2: 
Copy all of your code from your flattened smart contract and have it ready to paste in step 4.
Do this quickly by pressing Ctrl A to select all, Ctrl C to copy and Ctrl V to paste in step 4

# Step 3: 
Opening a new workspace in remix.

<img width="680" alt="Step3" src="https://user-images.githubusercontent.com/104795657/173172243-2c94e055-6367-4cff-bc1a-175169f99970.png">

# Step 4: 
Going to the contracts folder and selecting ballot.sol and deleting everything in it and then pasting your code to replace it.

<img width="680" alt="Step4" src="https://user-images.githubusercontent.com/104795657/173172338-fc2dd780-6b10-4f8c-b277-95f54c0f1401.png">

# Step 5: 
Renaming the ballot.sol file to the name of your contract and head over to the compiler tab.

<img width="274" alt="Step5" src="https://user-images.githubusercontent.com/104795657/173172818-1d382044-1f39-47d2-956c-12eb6da21486.png">

# Step 6: 
Making sure you have the right compiler version selected, choose 0.8.7.

<img width="274" alt="Step6" src="https://user-images.githubusercontent.com/104795657/173172824-19d779ad-e32f-4e9f-9b7a-88f269595a01.png">

# Step 7:
Making sure you have the right contract selected here and click auto compile.

<img width="257" alt="Step7" src="https://user-images.githubusercontent.com/104795657/173172934-cda9ae15-9f55-4e3b-a0ae-b55aae3c20bf.png"> <img width="455" alt="Step7 1" src="https://user-images.githubusercontent.com/104795657/173173368-fd83f22f-b8fc-4be5-8ce9-56e205c40ce0.png">

# You should see the green tick indicating there are no errors with the code.

<img width="450" alt="Step7 2" src="https://user-images.githubusercontent.com/104795657/173173370-bf7a04bb-be51-4285-b6a6-a9721e25a6b2.png">

# Step 8:
Going to the deployment tab and again make sure you have the right contract selected.

<img width="450" alt="Step8" src="https://user-images.githubusercontent.com/104795657/173173143-8d39256e-7620-4a9d-ad7d-dd46c81722bb.png"> <img width="225" alt="Step8 1" src="https://user-images.githubusercontent.com/104795657/173173187-57efe109-c807-4b93-a5e2-1a1fc5ce9985.png">

# Step 9:
Confirming that your metamask wallet in your browser is connected to the ethereum mainnet.

<img width="258" alt="Step9" src="https://user-images.githubusercontent.com/104795657/173173492-43a4eb84-8be2-4db4-8de2-74bb0f28a62e.png">

# Step 10:
Confirm again inside remix that your wallet is connected to the ethereum mainnet.

<img width="375" alt="Step10" src="https://user-images.githubusercontent.com/104795657/173173658-93f9b9a3-b822-40f8-85ee-2937925857f9.png">

# Step 11:
Deploying the contract, when you deploy the contract you will be prompted by metamask to pay a gas fee. This cost varies with the contract you use for deployment and the price of gas at the time also.

<img width="246" alt="Step11" src="https://user-images.githubusercontent.com/104795657/173173783-7cbc01b7-eac1-424c-be3b-8a9cccd7904c.png">

# You will then see your deployed contract below here

<img width="450" alt="Step11 5" src="https://user-images.githubusercontent.com/104795657/173174363-91e3e37c-e5a1-480d-a6dd-08063cf38594.png">

# Step 12:
Verifying the contract on etherscan, copy your contract address from here and head over to etherscan.io, I will be using the rinkeby testnet in this guide.

<img width="450" alt="Step12" src="https://user-images.githubusercontent.com/104795657/173174419-c6490486-651d-4551-ba02-4c151d4ae356.png">

# Paste your contract address into here 

<img width="700" alt="Step12 5" src="https://user-images.githubusercontent.com/104795657/173174661-9fdccd19-a165-434d-84e9-7d99c5aeb305.png">

# Step 13:
Click on the contract and then click on "verify and publish if you are the owner of this contract", go back into remix and copy every line of code again.
Choose solidity single file
Choose 0.8.7 compiler
Choose the same license identifier used in the contract on line 1
Paste the code into the top field here 
If there is an error message in the field below remove it and leave it EMPTY
Verify your contract
