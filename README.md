## Fish Contract

It is Ethereum ERC20 token contract with some modification.

Person can buy and sell tokens using `buy` and `sell` methods respectively. Every day buy price gets increased automatically. Rate of buy price growth is between _20%_ and _100%_ a month, which corresponds to daily increase of _0,61%_ and _2,33%_ respectively. 

Sell price is also adjusted automatically and is always _90%_ of buy price at any given moment.

After waiting just for two weeks person can take out more than what he/she put there initially. If you continue waiting your tokens would worth more of course.

This contract does not contain `selfdistruct` method so it is immortal.

There is also a referral program embedded, rules are following:

1. New user gets additionally 4% of tokens on his first purchase if he sets referral via `referral` method.
2. Referral gets additionally 4% of tokens on every subsequent purchase of every referred user
3. Referral of referral gets additionally 2% of tokens on every subsequent purchase of every referred user
4. Referral of referral of referral gets additionally 1% of tokens on every subsequent purchase of every referred user
5. A bounty award of maximum of 100 tokens can be assigned to proactive users as a reward for promotion, help in translation or any other good things.

A contract owner can only modify:

* _Daily growth rate_ - and set it to be between _20%_ and _100%_ a month.

Initial price of token is _0.1 ETH_ and token resolution is 3 decimals (1000 unitary tokens equals 1 unit token and it is initial price is 0.1 ETH).

SO, here it comes:

Contract address is: `0x80c1a36dcbdca742f59f09fda16c43e6ad877c2b`
You can check that the code is actually the contract at Etherscan: https://etherscan.io/address/0x80c1a36dcbdca742f59f09fda16c43e6ad877c2b#readContract

For the first birds, my address is `0xb8f7c360b194620da49a8af736fddf4e17177bea`. Feed it to `referral` method and you will get your landing discount. 

Why do I do that? I am curious how this will get evolved over time. It is really spectacular to see the growth charts ;) and I want this contract to overcome any existing or coming coin offering in the history :p

