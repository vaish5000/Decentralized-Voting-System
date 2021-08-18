# Decentralized-Voting-System
A Decentralized E-Voting System Developed using Ganache and Metamask 
## About
This is a Blockchain-based project, made by me [[Pilla Vaishno Mohan](https://www.linkedin.com/in/pilla-vaishno-mohan-b61a29212)]. This project is entirely based on Ethereum Blockchain with Web3Js to link it with HTML. Blockchain Technology is yet very hard to be hacked [ Until You have committed mistakes in Protocols or Coding Part ] that is what allows implementation of Blockchain in the Voting System. Once Blockchain is introduced in the Voting System, no one can put question on it's integrity. Thus, an inititative, of switching our voting system on Blockchain must be done by Governmen.
In this project we have used Etherem Blockchain to demonstrate the voting procedure.
## Procedure
1.	Start your Ganache application and click “QUICKSTART” this will provide us 10 free accounts with 100 Ethereum each.
2.	Configure the "truffle-config.js" file so that it runs on the same port as that of ganache.
3.	Then we have to compile the transaction and migrate it to the chain by using the following command on terminal at our project directory.
truffle migrate --reset
4.	After the Ganache has started running and transaction is initiated, we can now run the main application. For this, we have to go to our project directory and type the following NPM server command in our terminal:
	npm run dev 
5.	After doing this the server will get started on our machine and we can switch over to our browser.
6.	On the Browser, we can see the home screen window.
7.	Now, we have to configure the Metamask. For this create a new network named “Ganache Local” and configure it to the currently running ganache application. This will help us to configure the dummy accounts for our application.
8.	Once this is done we have to import one of the accounts from ganache to the metamask by using the import account option.
9.	Now we just have to connect the current account to the site, and we can head to the cast vote page.
10.	Now we can select the candidate whom we want to elect and cast our vote
11.	We will be then shown a confirmation window from the metamask. We have to click on Confirm and then we will be redirected to the results page.
12.	The results page will show that the vote we casted is added and the current votes of the candidates along with highest voted candidate. 
## Screenshots
1-Home Screen:
<br>![image](https://user-images.githubusercontent.com/86741118/124347965-dd8e4300-dc04-11eb-93c9-d043c2d428be.png)
<br>2-Importing Account From Ganache:
<br>![image](https://user-images.githubusercontent.com/86741118/124348044-660ce380-dc05-11eb-829f-618a1cf92e60.png)
<br>![image](https://user-images.githubusercontent.com/86741118/124347996-19290d00-dc05-11eb-861d-808297893a54.png)
<br>![image](https://user-images.githubusercontent.com/86741118/124348036-5ab9b800-dc05-11eb-8618-43f302c127b1.png)
<br>3-Casting Vote:
<br>![image](https://user-images.githubusercontent.com/86741118/124348010-352cae80-dc05-11eb-987e-8d0d4ce9b19b.png)
<br>![image](https://user-images.githubusercontent.com/86741118/124348102-a9675200-dc05-11eb-8b3e-8d99cd7bf84e.png)
<br>4-Results Page:
<br>![image](https://user-images.githubusercontent.com/86741118/124348028-4bd30580-dc05-11eb-9c34-303b253f8f39.png)
