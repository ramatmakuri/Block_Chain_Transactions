# Block_Chain_Transactions

In this assignment, we will generate a digital wallet, access Ethereum account balances, and sign & send transactions via a personal Ethereum blockchain called Ganache.

In this application,  we will assume the perspective of a Fintech Professional Finder customer and perform the following tasks:

1. Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

<img width="732" alt="Screen Shot 2022-05-14 at 2 08 28 PM" src="https://user-images.githubusercontent.com/96159292/168448216-e4c6d445-1b8c-402a-ab43-1f7c5b4c11f4.png">


<img width="688" alt="Screen Shot 2022-05-14 at 1 59 14 PM" src="https://user-images.githubusercontent.com/96159292/168447984-0f054114-4632-452e-8d38-7753c4b586fd.png">

2. Fetch and display the account balance associated with your Ethereum account address.

<img width="634" alt="Screen Shot 2022-05-14 at 2 09 30 PM" src="https://user-images.githubusercontent.com/96159292/168448233-2bdd6731-7526-4c25-baec-b18022e6a4d6.png">


<img width="553" alt="Screen Shot 2022-05-14 at 2 01 20 PM" src="https://user-images.githubusercontent.com/96159292/168448009-213d988c-af8f-4658-8586-609f240dc13f.png">


3. Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

<img width="757" alt="Screen Shot 2022-05-14 at 2 11 13 PM" src="https://user-images.githubusercontent.com/96159292/168448293-9cf27345-2fb1-487a-b701-77a1136d1f23.png">

<img width="724" alt="Screen Shot 2022-05-14 at 2 12 42 PM" src="https://user-images.githubusercontent.com/96159292/168448327-a802e164-74b1-4db7-9df5-5db7872e8759.png">


4. Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

<img width="786" alt="Screen Shot 2022-05-14 at 2 13 25 PM" src="https://user-images.githubusercontent.com/96159292/168448347-50ca26ac-b6d5-4b9e-908b-b2af41f16099.png">

<img width="658" alt="Screen Shot 2022-05-14 at 2 14 39 PM" src="https://user-images.githubusercontent.com/96159292/168448388-461ba7a6-6dad-4987-8ace-b80f9394aa2e.png">


5. Review the transaction hash code associated with the validated blockchain transaction.

<img width="655" alt="Screen Shot 2022-05-14 at 2 15 56 PM" src="https://user-images.githubusercontent.com/96159292/168448404-4edaf03b-7dca-45ae-be42-116354ad68a1.png">


6. Once the transaction’s hash code is received, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. 

  a. Transaction execution in Streamlit
  
<img width="302" alt="TransactionExecution" src="https://user-images.githubusercontent.com/96159292/168451694-bf7d49b4-14d0-4fb9-83e2-0c9be960197a.png">


  b. Sender Balance 
  
 <img width="1440" alt="SenderBalancAfterTransaction" src="https://user-images.githubusercontent.com/96159292/168451700-5e45ecbb-fcdb-4cd5-9db0-1afb5843cbe2.png">

  
  Balance before the Transaction: ETH 96.37
  
  Wages:                         ETH ( 1.00)  
  
  Balance after the Transaction: ETH 95.37
  
  c. Transaction Screenshot
  
  <img width="1440" alt="Transaction Screen Shot " src="https://user-images.githubusercontent.com/96159292/168451706-a81d767a-5ba9-46e9-b8ea-45dc042d1ab7.png">

  
  d. Receiver Balance
  
  <img width="1440" alt="Screen Shot FinTech Professional Balance" src="https://user-images.githubusercontent.com/96159292/168451723-2884fd4c-d870-42bb-b353-430c6c0aadff.png">

  Balance before the Transaction: ETH 100.00
  
  Wages:                         ETH  1.00  
  
  Balance after the Transaction: ETH 101.00
 
Data source: Input in Streamlit application

File Structure: Primary functions are in crypto_wallet.py file, the file to be run in streamlist (which calls the funcions referrred to before, as needed) is in fintech_finder.py file. 

Packages Used This project leverages python 3.7

Installation Guide: The application requires the below programs to be installed
Streamlit, dataclasses, typing, web3

Contributors: Brought to you by Ram Atmakuri (ram.atmakuri@outlook.com)

License [MIT] (https://choosealicense.com/licenses/mit/)
