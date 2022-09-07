## Course content

### 1.1. [Blockchain introduction 1.0](https://docs.google.com/presentation/d/1FDmZtSe_2LRUNE8xLC6Faq4FyMkkcztv2i2-D7ObXf4/edit?usp=drivesdk)  
### 1.2. [Blockchain introduction 2.0](https://docs.google.com/presentation/d/1sIp5l0bbJpZmGHoRkm5v8PCaS8w_ThIon8eR274l05E/edit)

<details>
  &ensp;
   <summary>Home assignment</summary>

   [Check-up](https://docs.google.com/forms/d/1sXvd1W-VLOkeLZj0Z_RsR67o9fXg7WiH_ZYEQmFv7_4/edit)

Now it’s time to test what you’ve picked up so far and check the necessary background skills. The test consists of 15 questions and will &ensp;&ensp;&ensp; take about 20 min to complete. You will see the results immediately. Good luck! 😊
  
 </details>

### 2. [EVM & Smart Contracts](https://docs.google.com/presentation/d/1pwsLzASm_uBsxeyybC_aSvbIVgi93YiAm1eamsIHKKQ/edit#slide=id.gc6f919934_0_0)

<details>
  &ensp;
  <summary>Home assignment</summary>

- Install VSCode, hardhat, npm
- Configure github actions
- Add a functionality to see all the donors from the Donations contract (from the coding session)

</details>
  
### 3. [ERC20 tokens](https://docs.google.com/presentation/d/1WA71SiQlbRFMF2WsVy0KAbucKoUIZEIIJ1hzaXjS9Ys/edit#slide=id.gc6f919934_0_0)

  <details>
  <summary>Home assignment</summary>
&ensp;
  
1. Write and unit test your own ERC20 token with mint/burn features for contract creator. Do **not** use any libraries. The contract should conform to the [ERC-20 standard](https://eips.ethereum.org/EIPS/eip-20), which means it should include all the functions and &ensp;&ensp;&ensp;events described in the standard, keeping their names.  
2. Write tests.  
3. Write deploy script.  
4. Deploy on testnet.  
5. Write tasks for mint, transfer, transferFrom, approve.  
6. Verify the contract.  
  
#### &ensp;&ensp;&ensp;Tips  
- [How to interact](https://docs.ethers.io/v5/api/contract/) with a deployed contract using ethers.js.
- How to deal with [environment variables](https://dev.to/asjadanis/parsing-env-with-typescript-3jjm) in TypeScript.
- [Deploying](https://dev.to/yakult/series/16254) ERC-20 with hardhat.
- Hardhat [tutorial](https://hardhat.org/tutorial) and [documentation](https://hardhat.org/getting-started).

 </details>


### 4. [Liquidity Pools and Staking](https://docs.google.com/presentation/d/1jXJK6HKrlLZEA90fJc0SWuTk41v1IA1uVKxzmx8_QZE/edit#slide=id.gc6f919934_0_0)

  <details>
  <summary>Home assignment</summary>
&ensp;

&ensp;&ensp;&ensp;1. Write and test WETH contract.  
&ensp;&ensp;&ensp;2. Create a Uniswap Liquidity Pool with token pair WETH-[token from first task]  
&ensp;&ensp;&ensp;3. Write a staking contract, which will accept LP tokens and starts to assign reward tokens [token from first task] after a certain &ensp;&ensp;&ensp;period of time (e.g., 10 min). The amount of reward tokens depend on the amount of LP tokens staked: for example, a reward can be 20% of &ensp;&ensp;&ensp;staked amount. Staked LP tokens should be frozen (unavailable for withdrawal) for a certain period of time (e.g., 10 min). 
    
&ensp;&ensp;&ensp;        stake(): transfers LP tokes from the user to the contract. 
&ensp;&ensp;&ensp;        claim(): withdraws reward tokens available to the user from the contract 
&ensp;&ensp;&ensp;         unstake(): withdraws LP tokens available for withdrawal.
&ensp;&ensp;&ensp;    A few functions with restricted access should change staking parameters (freezing time, % of reward, ect.)
    
&ensp;&ensp;&ensp;4. Write tests.  
&ensp;&ensp;&ensp;5. Write deploy script.  
&ensp;&ensp;&ensp;6. Deploy on testnet.  
&ensp;&ensp;&ensp;7. Write tasks for stake, unstake, claim.  
&ensp;&ensp;&ensp;8. Verify the contract.  

#### &ensp;&ensp;&ensp;Tips

&ensp;&ensp;&ensp;For testing purposes to simulate that some time has passed use  
    
      ```jsx
      ethers.provider.send("evm_increaseTime", [1500])
      ```
 </details>
 
### 5. [EVM & Smart Contracts](https://docs.google.com/presentation/d/1pwsLzASm_uBsxeyybC_aSvbIVgi93YiAm1eamsIHKKQ/edit#slide=id.gc6f919934_0_0)

#### &ensp;&ensp;&ensp;Home assignment

- Install VSCode, hardhat, npm
- Configure github actions
- Add a functionality to see all the donors from the Donations contract (from the coding session)
