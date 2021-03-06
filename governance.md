# FlamIncome Governance

> FlamIncome is launched in September of 2020 and its peak TVL reached more than 0.7 billion dollars.
> Governance of Flamincome is managed by a [multi-sig wallet](https://etherscan.io/address/0x9832a79C563d31ether403409C41f92C51b824435cdB0) at first, and it is replaced by a fully decentrilized DAO in October of 2020.

Governance of FlamIncome is based on [Aragon](https://aragon.org).

`FLAG` is the governance token of FlamIncome.

# FlamIncome Governance Token

> **All the governance mechanism can be changed by the governance mechanism itself**

The symbol of FlamIncome Governance Token is `FLAG` and its total supply in the first year is `1048576`.

Since the second year, `FLAG` inflation rate will be `100%` per year, which means, total suply is `2097152` in the second year, total supply is `4194304` in the third year ...

`50%` of the inflated tokens (including the initial supply in the first year) will be distributed to the liquidity provider between `nXXX` tokens (i.e. `nUSDT`) and original `XXX` (i.e. `USDT`) tokens. Initially `50%` of staking rewards tokens will be distributed to `USDT-nUSDT` pairs, `25%` to `WBTC-nWBTC` pairs and `25%` to `WETH-nWETH` pairs.  

The other `50%` of the inflated tokens (including the initial supply in the first year) will be distributed to users who participate in the governance (voters).

The high inflation rate is for continuously incentive the new contributors, in another word, if one hold `1` `FLAG`, the only way to keep its token weight (anti-inflation) is to provide liquidity continuously or vote in the DAO.

## Staking Rewards
Stake LP(liquidity provider) tokens to mint FLAG. 
Currently we support `3` LP tokens from Uniswap(`USDT-nUSDT`, `WBTC-nWBTC`, `WETH-nWETH`)  to stake and get FLAG. The rewards will be calculated by year for our FLAG distribution strategy. FLAG will be allocated to who has staked proportional to the total time and the ratio of individual LP tokens to totalsupply.

## Voting Rewards
This is an Incentive plan to encourage everyone to participate in the governance of community.
Voting rewards are calculated based on the equation below:
```
gapi = startDatei - startDatei-1 
rewardsi = stake/(yeai+nayi) * gapi/oneYear * totalSupply
rewards = ∑rewardsi
```

Where `i` is the vote on the ith governance proposal, and `gapi` is the interval between the start time of this vote and the start time of the previous proposal vote.

`vote` represents the total number of votes cast by the user on proposal `i`. `yeai+nayi` is the sum of those who voted yes and no. `oneYear` says the total time for governance vote awards is oneYear. `totalSupply` is the total number of governance votes awarded, namely 524,288.

This allows the user to calculate the number of tokens that can be awarded in a proposal vote.

If the user participates in more than one vote, the `rewards` can be equal to the sum of the reward for each vote.

The community's first vote will be on the inflation of token allocation to the Flamincome project team. When voting one can choose YES/NO to decide whether to increase the team FLAG by `6.25%` every time.

# FlamIncome Improvement Proposal

There are strong proposals and weak proposals in FlamIncome.

Strong proposals will executed once it is allowed by the DAO.

Weak proposals don't make any actual changes, but it is the opinion of the community on some principles.

## Strong Proposal

To propose a strong proposal, like minting `FLAG` tokens to distribute to someone, or propose a new strategy. These kind of proposals will be regarded as strong proposal, which will be executed immediately once approved by voting, therefore no one can stop an approved strong proposal, including the Flamincome team.

## Weak Proposal

To propose a weak proposal, like expressing someone's opinions and views in the community, which will not result in any execution on smart contract, thus weak proposals don't make any actual changes.

