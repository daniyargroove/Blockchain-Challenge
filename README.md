# Blockchain-Challenge
![alt=""](Images/application-image.png)

In this assignment, being in a role of a fintech engineer at one of the world's largest banks, I was tasked with leading the development of a blockchain-based ledger system for the decentralized finance team. This system allows partner banks to conduct financial transactions securely and efficiently while ensuring the integrity of the ledger's data.

## Step 1: Create a Record Data Class
To start, I created a new Python data class named Record with a formalized data structure for financial transaction records. The Record class includes attributes for the sender, receiver, and amount of each transaction.

## Step 2: Modify the Existing Block Data Class
Next, I modified the existing Block data class to store Record data. I renamed the data attribute to record and set its data type to Record.

## Step 3: Add Relevant User Inputs to the Streamlit Interface
I updated the Streamlit interface to include input areas for capturing sender, receiver, and amount for each transaction. I removed the input_data variable and added input fields for sender address, receiver address, and transaction amount.

## Step 4: Test the PyChain Ledger by Storing Records
Finally, I tested the PyChain ledger by running the Streamlit application and storing multiple blocks in the ledger. I verified the block contents and hashes in the Streamlit dropdown menu. Additionally, I tested the blockchain validation process through the web interface to ensure the integrity of the blockchain.

## The screenshot of the Streamlit application page, which details a blockchain that consists of multiple blocks.

![Screenshot No 1](https://github.com/daniyargroove/Blockchain-Challenge/assets/143307322/b8738c47-f693-4e37-aeba-ca36bf8d752b)

## The screenshot of the Streamlit application page, which should indicate the validity of the blockchain.

![Screenshot No  2](https://github.com/daniyargroove/Blockchain-Challenge/assets/143307322/a6ff5f77-67af-434a-b9bd-d7eb542852fd)


This streamlined ledger system provides a secure and transparent platform for conducting financial transactions, ensuring data integrity across multiple partner banks.
