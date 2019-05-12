Create tokens and host a crowdsale


/////////DEPLOYING CROWDSALE//////////////
1. Copy and paste both files in Remix - Solidity IDE.

2. Create or use an existing MyEtherWallet address and paste it under balances in the Mint Token file (this is where your new minted tokens will be sent to)

3. Under Remix, go to Mint Token file and deploy 'Chad Coin' contract

4. Then go to CrowdSale contract and deploy it with arguments of 
   'address to send ether funds raised'
   'fund raising goal in ether'
   'crowdsale duration in minutes'
   'token amount per ether'
   'Chad Coin contract address'
   
5. Go to MyEtherWallet.com and click the 'Contracts' tab. Copy address of 'Chad' Coin' contract and paste it under Contract address. Extract ABI from 'Chad Coin' contract and paste it under ABI/JSON Interface. Click access, and choose 'transfer' function. Copy address
of 'Crowdsale' Contract with X amount of tokens you wish to send. Generate transaction

At this point, sent coins should be under CrowdSale contract and ready for distribution


///////INTERACTING WITH CROWDSALE////////////////////
1. Under Remix - Solidity IDE, go to 'Crowdsale' Contract and choose desired address to use
2. Select amount of ether you want trade for 'Chad Coin' and click (fallback) function
