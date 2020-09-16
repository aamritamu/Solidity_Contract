# Smart Contract 

## Preliminary Steps 

1. Open the Ganache 


![](initganch.jpg)



2. Open the Remix and connect it with meta mask, make sure it is conntected with testnet network
3. Deploy the three solidity contracts (Level1 , Level 2 and Level 3) 

### Level 1 Solidity Contract


- The name of the contract is AssociateProfitSplitter.sol
- This will allows to deposite the ether into the contract and distrubute the ether among the employees i.e one, two and three.


#### Steps 
- Compile the contract
- Deploy the contract, make sure the Remix is connected to Injected Web3

![](Step1Deployment.jpg)

- Once the contract is deploy, put the amount and click on Deposit 

![](Step2Depo.jpg)


### Level 2 Solidity Contract

- The name of the contract is TieredProfitSplitter.sol
- This contract basically divides the ether amount based on the desgination level of employee. In the contract employee one, two and three receives 60%, 25% and 15% of ether amount respectively.
- The method of compilation and deployment is same as of level 1 contract 
- Once the contract is deploy, hit on deposite to distribute the ether

![](stepbdepo2.jpg)
- Confirm the distribution in the Ganache 

![](Ganach2.jpg)

### Level 3 Solidity Contract

- The name of the contract is DeferredEquityPlan.sol
- This contract determines how many the number of years a employee served in the company and based on it the number of company share is given to them. In our contract for each year spend the number of shares should given as 250 from total awarded share of 1000. 
- The process of compilation and deplyment is same

![](step3B.jpg)

- distribute will distribute the shares to the specified address and deactivate will deferred the share back to the company if the employee the firm before 4 years


