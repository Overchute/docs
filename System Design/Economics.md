# Overchute Economics

### Cash flow
- __Fixed costs (overheads):__ Development, maintenance, support, administration
- __Variable costs (direct):__ IC canister compute
- __Revenue:__ A share of the overshoot of each successful sale. The size of this share is the key economic parameter in the system. It can be adjusted to maintain a reserve fund from which expenses are covered, and profits distributed.

### Market dynamics
Overchute is an intermediary, or multi-sided platform. These platforms can profit from the value they add only if there is a competitive 'moat' deriving from:
- __Trust__, where transactions are enabled because parties who don't trust each other each trust the platform. For Overchute, track-record and brand-recognition can give some advantage, but this competitive moat is limited because of the tamperproof execution guarantees of the blockchain network. If a competitor starts up, users just need to inspect their open-source smart-contract code to be willing to switch.
- __Secret sauce__, where the platform has some proprietary abilities that can't easily be copied. For Overchute, the code needs to be open-source to be trusted, so anyone can fork it, and this moat doesn't apply.
- __Network effects__, where the increasing presence of others on the platform increases its utility in a re-inforcing cycle. For Overchute, the current design has all communication happening outside the dApp, so there's no friction to switch to a competitor - just point to a different crowdsale URL.

Because of the absence of a strong natural moat, Overchute will only be able to make a sustained profit if its __tokenomics__ give users a stake in the success of the platform.

### Token design principles
- The native token must not add friction for users, so it isn't required for crowdsales, which use the XTC stablecoin.
- The value of the token should arise from the profitability of the platform, not from speculative ponzi/pyramid scheme dynamics.
- The primary goal of the native token is give users a stake in the success of the platform, aligning interests to incentivise continued and expanding use of the platform, and sustainable profit.

### Token functionality
- Tokens can be freely traded on exchanges.
- Token ownership confers the right to a share in the profit of the platform, which can be distributed by:
    - Method 1 (_not preferred_): Transferring XTC profits to the accounts of token-holders as dividends.
    - Method 2 (_preferred_): Using XTC profits to buy back tokens on the open market and burn them. This distributes the value proportionally to token holders via deflation.
- Token ownership also confers the right to a say in platform governance (when the SNS functionality becomes available), including:
    - the direction of development of the dApp
    - allocation of funds from the reserve to pay for development, maintenance, support and administration
    - setting economic parameters, especially the platform fee

Note: Assuming the SNS functions like the NNS, voting power will depend on staking in neurons, with inflation-funded voting rewards.

### Token rewards
- __Funding source:__ For successful crowdsales, 10% of the contributed amount goes to the platform (limited by the amount of overshoot available). This is quite a large amount, but it can't be reduced because it acts as a barrier that prevents 'shilling' by the creator, which is when the creator inflates the offer price while adding a corresponding contribution themselves, to gain an unfair share of the overshoot. So I propose we rename the 'platform share' as the 'reward share', and use it to fund the tokenomics incentives, as follows:
    - The reward share on contributions up to 2X the offer price goes to the platform, for covering expenses and distributing profit to token holders.
    - The reward share on contributions above 2X the offer price goes to the creator as a token incentive, as follows:
        - The funds are used to purchase tokens on the open market from existing token-holders.
        - These purchased tokens are staked in a neuron with dissolve delay of 1 year and awarded to the creator.
- __Incentive effects:__
    - Because the token reward only kicks in on contributions exceeding 2X the offer price, this design strengthens the incentive for creators to keep the offer price low.
    - For the creator's next crowdsale, they are likely to choose Overchute again, because they now have a stake in the profit of the platform. Subsequenct crowdsales may result in more token reward again, creating a re-inforcing cycle.
    - It is not necessary to give a token reward to contributors (over and above their share of the overshoot) because they will contribute on whichever platform the creator sets up the crowdsale. It is the creators who choose between Overchute and competitors.

### Initial token distribution

| Founders | 49% | |
| Investors | 0% | Asssuming we get the Dfinity Foundation Developer Grant, we can fund our hours and pay sundry expenses without raising capital |
| Partners | 20% | Organisations like Creative Commons and Open Source Initiative, or providers of features like Credit Card integration |
| Overchute Foundation Endowment | 20% | Can be gradually sold to fund development and operations until the dApp is profitable, and then to promote |
| Airdrop recipients | 10% | We can use this to build a community and kickstart awareness and adoption |
| Creators | 0% | This will grow as tokens are purchased from existing holder to reward creators |

| Token-holder group | Initial allocation | Comment |
| ------ | ------ | ------ | 
| Dropbox | [plugins/dropbox/README.md][PlDb] |  |
| GitHub | [plugins/github/README.md][PlGh] |  |
| Google Drive | [plugins/googledrive/README.md][PlGd] |  |
| OneDrive | [plugins/onedrive/README.md][PlOd] |  |
| Medium | [plugins/medium/README.md][PlMe] |  |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |  |


### Token-holder options
- Hold tokens for a sustained profit-share
- Sell tokens on the open market, with price influenced by:
    - Fundamental value deriving from steady profits
    - Forced buying for creator token rewards
    - The value of having a say in dApp governance
