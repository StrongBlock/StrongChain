# **StrongBlock Light Paper 2022**

By David Moss, CEO | Brian Abramson, CTO | Corey Lederer, CPO | Konstantin Shkut, VP, Software Development

2/28/2022

**Abstract**

StrongBlock, the pioneering Nodes-as-a-Service (NaaS) rewards platform, intends to architect, design and build a Layer 1, EVM-compatible blockchain protocol that will be known as StrongChain. The goal of moving the NaaS platform to StrongChain is to create a community-first model that will unlock new economic layers, increase sustainability, add buoyancy to the STRONG token price, and lay the foundation for growth due to the massive success of the NaaS platform. The knowledge required to engineer a blockchain comes from the team’s many years of blockchain experience together, building the NaaS platform and the EOSIO blockchain software. This Light Paper describes: existing and upcoming features of the StrongBlock NaaS Platform; the introduction of StrongChain; how the NaaS platform fits within StrongChain; and the introduction of a new utility token, STRONGER, as the native token to power StrongChain. This Light Paper lays the foundation for a smooth and successful transition to a new token and blockchain, and a prosperous future for the StrongBlock community.

Copyright © 2022 StrongBlock®, a USPTO registered trademark of Jenison Holdings SEZC.

*Disclaimer. This StrongBlock Light Paper is for information purposes only. StrongBlock does not guarantee the accuracy of this light paper and is presented “as is.” StrongBlock does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this light paper are free from errors and omissions; and (iii) that such contents will not infringe third-party rights. StrongBlock and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this light paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will StrongBlock or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special, for the use of, reference to, or reliance on this light paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses or unrealized savings.*

# **Table of Contents**
[Introduction](#intro) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[StrongBlock 2021 Recap (graph)](#2021recap) <br><br>
[Why supporting blockchains is important](#support) <br><br>
[The slow march to true decentralization](#slowmarch)<br><br>
[Problems: High Gas Cost and Sustainability](#highgas)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[High Gas Cost](#gascost)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Sustainability](#sustain)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Sustainability Experiments](#susexp)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ETH 2.0 Pool](#eth2pool)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Tapering](#tapering)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Validator rewards](#valreward)<br><br>
[Solution: STRONGER and StrongChain](#strongerandchain)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[How StrongChain Democratizes Validation](#howstdv)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[How StrongChain brings value back to the community](#howvalue)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[StrongChain Community-First Tokenomics](#community1)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[STRONGER Facts and Definitions](#factsdefs)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[STRONGER Tokenomics - Initial Proposed Model (chart)](#strongermod)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Phases for Distribution and Transition](#distrophase)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Phase 1: Easy Defi DApp with rewards (completed)](#easydefi)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Phase 2: Transition to STRONGER](#transitiontos)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Phase 3: Launch StrongChain and migrate DApp](#launchchain)<br><br>
[StrongBlock 2022 Roadmap (graph)](#2022map)<br>

[The future of STRONG](#futurestrong)	<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Team and Shareholder sales of STRONG](#teamsales)<br><br>
[CONCLUSION](#conclude)<br>

---

# <a name="intro">Introduction</a><br>

When StrongBlock launched its pioneering Nodes-as-a-Service (NaaS) rewards platform on December 3, 2020, it was the sole NaaS reward DApp in the DeFi marketplace, and an outlier. Today, the StrongBlock NaaS DApp is consistently one of the most-used DApps on the Ethereum blockchain. The NaaS Dapp has removed the barrier of entry to recurring passive rewards for non-technical people, and gained recognition that rewarding nodes is important.

Even more significant, the StrongBlock NaaS DApp has now spawned an entire “Infrastructure DeFi” category. To show how the StrongBlock NaaS DApp reached this point, here is a recap of the platform’s 2021 success.



## <a name="2021recap">StrongBlock 2021 Recap (graph)</a>

![](https://static.strongblock.io/lp/n-2021-recap-timeline.png)

With more daily DApp transactions on the Ethereum mainnet than most Layer 1 and Layer 2 blockchains, it was inevitable that StrongBlock would launch its own blockchain. This was further enforced through StrongBlock’s research and participation on multiple Layer 1 and Layer 2 blockchains. Our conclusion from this research is that there is still a significant gap in scalability, performance and, most important, community participation in validation and rewards for all blockchains. We also recognized that blockchain itself is still in its very early stages, and that none of the alternatives to Ethereum are truly established. This creates a significant opportunity for a purpose-built alternative.


# <a name="support">Why supporting blockchains is important</a>

Blockchains need miners and nodes. Miners are rewarded, nodes are not. Miners can prove that a block was mined, and can automatically claim rewards via a blockchain’s system smart contract. Nodes have a harder - if not impossible - time proving they were specifically used to facilitate a blockchain transaction, or that they have provided access; such proof can also be spoofed. Therefore, nodes are typically not compensated.

With limited resources, and no financial incentive, most nodes run out-of-date software, maintain incomplete blockchain histories, and are intermittently off-line.

Yet nodes are crucial to the resilience of a blockchain. Not rewarding them is not an option.


# <a name="slowmarch">The slow march to true decentralization</a>

Despite the proliferation of Layer 1 and Layer 2 blockchains, decentralization remains an elusive goal. Decentralization - the transfer of control and decision-making from a centralized entity to a distributed network - is easy to talk about, but difficult to achieve. Instead, well-meaning blockchains claim they will become decentralized, but instead quickly become oligarchies. 

Is it really time for a blockchain revolution, or is blockchain just another technology evolution? What is to be done?

Instead of trying to “boil the ocean” and force the move to decentralization, StrongBlock’s approach has been to start with the community that has gathered around the NaaS DApp, then build out from there. We believe this is the only way true decentralization can be achieved. From inception, the StrongBlock had taken steps toward that goal, building the NaaS DApp with multiple variable components. These components will be the basis for community control and decision-making when the DApp is eventually handed over to the community when it resides on its own blockchain. The community can then continue to decide, build and adapt from there. We will continue with that community-first philosophy as we build out a blockchain.


# <a name="highgas">Problems: High Gas Cost and Sustainability</a>

## <a name="gascost">High Gas Cost</a>

According to Etherscan, the StrongBlock NaaS DApp consistently ranks in the Top 10 - and is often in the Top 3 “Gas Guzzlers” - on the Ethereum blockchain. This does not mean individual transactions are costly; it simply means that, collectively, the NaaS DApp is one of the most-used DApps on Ethereum - an important distinction. Due to sustained high DApp usage, it has become imperative to implement measures to reduce gas consumption by the NaaS DApp, to lessen both its cost to the community and its environmental impact. These measures may require migration to the Service 2 Smart Contract, but - more important - migration to a new blockchain, where overall gas costs will be lower, and validator fees can be shared by the community.


## <a name="sustain">Sustainability</a>

The initial supply of 10,000,000 STRONG, minted in August, 2020, included no capabilities to burn or to further mint. This was the accepted standard in DeFi at the time. When the initial launch of the BYON version of rewarded nodes had a shaky start, the protocol voluntarily burned 94.7% of the supply, reducing its token footprint to sustain the project. 

With the subsequent explosive growth of the StrongBlock NaaS DApp, the inability to mint new STRONG in the original contract limits the growth of the NaaS DApp. Further, planned features that will dramatically lower community gas costs will, in turn, require a significantly larger supply of STRONG for sustainability than is currently possible.


### <a name="susexp">Sustainability Experiments</a>

#### <a name="eth2pool">ETH 2.0 Pool</a>

As an experiment to see if non-STRONG rewards could be offered, StrongBlock launched and is maintaining up to 32 ETH 2.0 nodes to back the ETH rewards for the ETH 2.0 pool. The pool allows STRONG to be staked for a share of Ethereum 2.0 ETH rewards when they become available. Rewards weight is based on the quantity of STRONG staked and the amount of time it is staked, divided by all STRONG staked. Each staking event is considered a separate entry, even from the same wallet. When rewards become available, an epoch will be created and ETH will be deposited. If a staker unstakes STRONG before an epoch has been created, they receive no rewards. When they unstake to claim rewards, their timer is set back to zero.

While there has been considerable interest in the ETH 2.0 pool, the Ethereum community is moving at a slow pace, with postponement of the cutover to Proof of Stake. ETH rewards are still on the far horizon. 

Our conclusion is that the ETH 2.0 pool, while helpful, is a viable but less significant factor to offer non-native rewards in the StrongBlock platform.


#### <a name="tapering">Tapering</a>

Another experiment, released in the Service 2 Smart Contract, introduced a flexible, tapered rewards model that allows for different implementations for each protocol. Currently, the tapering model has only been deployed for Polygon nodes.

In the Polygon tapered model, rewards are initially higher than current ETH 1.0 node rewards. They then gradually taper to reach the ETH 1.0 rewards rate, intersecting at breakeven. After breakeven, the tapering model converts to a steady, sustainable stream of passive income that tapers gradually over several years, to a maximum number of tokens.

The Service 2 Smart Contract also enables most of the features in the 2022 Roadmap. Features such as Sizable and Entangled Nodes will only be available in Service 2 - and subsequently on StrongChain - due to smart contract size limitations of the Service 1 Smart Contract.

Our conclusion is that variations of the tapered model could be a component of long term sustainability for the community, when judiciously communicated and applied.


#### <a name="valreward">Validator rewards</a>

In April, 2021, StrongBlock created a Validator on the Sentinel blockchain to support their DVPN application. Millions of DVPN tokens were delegated to the Validator, and it is consistently in the Top 10 of Validators on the Sentinel blockchain. Despite this, the project itself has failed to thrive, and the value of DVPN tokens dramatically and rapidly decreased, producing scant and unpredictable rewards.

Our conclusion is that participating as a Validator on any blockchain - except our own community-first chain - requires excessive capital and considerable risk, with minimal return. Validators outside of a community-first chain are therefore not a viable component of long term sustainability for the community.



# <a name="strongerandchain">Solution: STRONGER and StrongChain</a>

Given the specific set of problems created by the success of the NaaS DApp, StrongBlock - the pioneering Nodes-as-a-Service (NaaS) rewards platform - intends to architect, design, build, test and launch a Layer 1, EVM-compatible blockchain protocol that will be known as StrongChain. Details on this chain will be addressed in a separate document.

StrongChain solves two immediate problems for the StrongBlock community: high gas costs and rewards sustainability. Starting with that strong entry point, a new economic layer can then be opened up, which the community can fully participate in and benefit from.

StrongChain will be a place where the community can benefit from the chain itself and experience true equity in the chain. By democratizing validation, value will accrue to the community, instead of benefitting the miners on another chain.

StrongChain creates an economy that will run on resources provided by the community, who are also the consumers of those resources. In this way, the ecosystem can now pay for itself, while the community can influence its development and benefit from its growth.

We have concluded that launching StrongChain will move the community closer to sustainability than any other action. With StrongChain, it will be much easier to expand into short and long term features. If the NaaS DApp remained on Ethereum, or even moved to someone else’s Layer 1, this growth would not be possible. It’s one of the main ways the community can collectively support lowering the dependencies of new people coming into the platform.

Based on our deep experience across multiple blockchains, there is no need for StrongBlock to try and reinvent or compete with other blockchains. That’s why we will start with a focus on the community, solving sustainability and adding governance, and grow from there, just as the NaaS DApp started with a handful of nodes. The community has expressed support for growth, to allow for new sustainable ideas to emerge while hosting a thriving Infrastructure DeFi ecosystem.


## <a name="howstdv">How StrongChain Democratizes Validation</a>

The current validator model for most blockchains is:

- Users stake tokens with validator nodes > validator node receives reward > validator node distributes reward to stakers
- Unless you’re a large token holder, or a large amount of tokens are delegated to you, you don’t make enough to pay your hosting bill

Currently, validators stake their tokens to become a validator. Every chain has a floor count  - except Solana, which looks like it's an infinite growth validators list, since the minimum entrance fee is essentially just the cost of paying for your validator init data storage on-chain. 

Users on a chain can delegate their tokens to one or more Validators (with different lockups and unlock penalties) to essentially "vote" for the Validators of their choosing. The amount of staked tokens is the Yield Farm play that allows greater proportion when the rewards distribution kicks in; some are monthly epochs, some are quarterly, and some are per unit whether block or transactions. Validators always take the lion's share, but the users that have delegated play their Yield Farm off of the overall portion allotted to rewarding delegated tokens/votes. Generic Validator calculations put most of the chains where it's reasonable to compete for rewards around the 10% APY level.

For users that have delegated, the percentage allotted for them out of the total rewards (typically a low proportional amount) becomes it's own mini-game of fighting for scraps between the other users’ delegated positions. Most of the chains that have better APY usually have an unstaking period that's basically just a lockup period (on DVPN, for example, it’s currently around 3 weeks, changeable through a community vote).


## <a name="howvalue">How StrongChain brings value back to the community</a>

For StrongChain, the goal isn't so much disruption as it's about bringing value back to the community, in all forms. Currently, the StrongBlock NaaS DApp rewards RPC nodes because no native blockchains are rewarding them. There's no tangible returns for blockchains to do so unless rewards are already baked in, particularly since RPC nodes can be spammed horizontally to game the system. RPCs are still somewhat critical to any blockchain, because they are the onramp for transactions to a chain's Validators to process. There are considerable cases where RPC nodes - specifically Infura - have had downtime and affected most of the Ethereum mainnet.

Yet blockchain philosophy is that a user or client can - and usually will - launch its own local RPC as part of its package. For example, when the Ethereum Foundation created Grid client. Most retail users usually have some complaint or challenge to this path compared to something that's easy to use like MetaMask. That is why StrongBlock still keeps the RPC NaaS posture for our chain, which is still the StrongBlock "compound nodes” incentivization.


Launching StrongChain allows the community to also tap into the Validator and Delegation reward systems, keeping in mind inflation and deflation related issues for the increase in rewards posture. When we were concerned about the limited STRONG supply becoming stretched by adding Polygon nodes, the conclusion was that the platform currently gives away a set reward against Geth and Polygon/Matic nodes already, which is no different than being a user and just creating more Geth nodes. Adding in a solid Validator and Delegation model for rewarding gives the community more ways to participate, with the goal of keeping a low volatility balance on rewards inflation and price.


We see purpose-built blockchain as a crucial innovation -  a new path - for DeFi products in general, which will allow for disruption. While a complicated task for most, creating a chain is actually fairly trivial for the StrongBlock team, keeping things stock and leveraging our engineers who already have considerable experience building blockchains cleanly.

We’re therefore creating StrongChain as a dedicated, purpose-built blockchain that exists initially as:

- A tool to return value back to the community;
- The means to support all of the ecosystem that the community relies on for value that is currently in play;
- An architecture that allows it to be the launchpad for future feature sets that are logical expansions and growth paths.
- The path to long-term liquidity and sustainability.

We believe StrongChain presents an amazing blockchain use-case, while meeting our philosophical and technical goals of democratizing blockchain participation, and laying the foundation for community governance.

StrongChain nodes will support StrongChain. StrongBlock will continue to add and support new protocols going forward.


## <a name="community1">Strongchain Community-First Tokenomics</a>

### <a name="factsdefs">STRONGER Facts and Definitions</a>

STRONGER will be an ERC-20 token at first mint. When the StrongChain launches, STRONGER will convert to a native token with ERC-20 liquidity, and Ethereum and other L1 and L2 bridges for seamless liquidity and interoperability.

StrongChain will be a community-owned chain. The majority of STRONGER tokens have been set aside for the community, with no additional team and shareholder tokens. The following is the **INITIAL PROPOSED** StrongChain token structure, which is subject to change prior to launch. A separate Medium post describing allocation will be published prior to conversion.


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**STRONGER:** A utility token for StrongChain<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Name:** Stronger<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Symbol:** STRONGER <br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**TYPE:** ERC-20 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Decimals:** 18<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Original Supply:** 10,000,000<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**STRONGER Contract Address:** TBD<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Protocol Smart Contracts:** OpenZeppelin<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Mint possible:** Yes, in contract<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Burn possible:** Yes, in contract<br>

### <a name="strongermod">STRONGER Tokenomics - Initial Proposed Model (chart)</a>

![](https://static.strongblock.io/lp/gg-lighpaper-feb-2022-allocation.png)

### <a name="distrophase">Phases for Distribution and Transition</a>

The evolution of the StrongBlock NaaS protocol to StrongChain will take place in three phases:

#### <a name="easydefi">Phase 1: Easy Defi DApp with rewards (Completed)</a>

- Top 5 most-used DApps on the Ethereum Mainnet based on gas
- More daily transactions than most blockchains
- Pioneered new category “Infrastructure DeFi”
- Service 2 Smart Contract with tapering model


#### <a name="transitiontos">Phase 2: Transition to STRONGER</a>

&nbsp;&nbsp;&nbsp;&nbsp;Issue a new mint/burn token - STRONGER<br>
&nbsp;&nbsp;&nbsp;&nbsp;Transition the NaaS DApp and the StrongBlock community to STRONGER<br>
&nbsp;&nbsp;&nbsp;&nbsp;Having STRONG will make you STRONGER<br>
&nbsp;&nbsp;&nbsp;&nbsp;All current STRONG holders will be awarded STRONGER<br>
- Nodes will have the highest STRONGER award percentage
- Pool holders will receive the next highest STRONGER award percentage
- Anyone holding STRONG in a wallet will receive a STRONGER  award

&nbsp;&nbsp;&nbsp;&nbsp;Metal NFT’s <br>
- All Metal NFTs will retain their boost value
- Metal NFT holders will receive a STRONGER award
- Metal NFTs will also be a component of StrongChain

&nbsp;&nbsp;&nbsp;&nbsp;Design, Build and Test an EVM-compatible Layer 1 StrongChain<br>
&nbsp;&nbsp;&nbsp;&nbsp;A document with detailed allocation, award data and timing will be published prior to the start of the transition.<br>


#### <a name="launchchain">Phase 3: Launch StrongChain and migrate DApp</a>

- Launch StrongChain with STRONGER
- Migrate NaaS DApp
- Open up new economic layers
- Percentage of fees directly to community validators and stakers
- Expand and host  “Infrastructure DeFi” 
- Marketplaces for nodes, NFT’s, more
- A document with detailed information will be published prior to launch.


# <a name="2022map">StrongBlock 2022 Roadmap (graph)</a>

![](https://static.strongblock.io/lp/nn-2022-roadmap-timeline.png)

# <a name="futurestrong">The future of STRONG</a>

Since its minting of 10,000,000 tokens in August, 2020, STRONG has been doing double duty as both a utility and a governance token. 

The introduction of STRONGER creates an opportunity for STRONG to be used for scarce rewards that will be harder to achieve. There is also the potential for STRONG to be a governance component for StrongChain, used in dual token validation, and other models - though this will require community deliberation. STRONG and STRONGER will continue to co-exist; STRONG will simply become much harder to earn, and therefore much more valuable.


## <a name="teamsales">Team and Shareholder STRONG</a>

After the November, 2020 token burn, 198,520 STRONG tokens were allocated to Team and shareholders, as follows:

101,735.81 Strong Block: Team

96,784.62000000531590216 Strong Block: Shareholders

As a major vote of confidence in STRONGER and StrongChain, StrongBlock Team and Shareholders have agreed to directly transfer 100,000 STRONG from Strong Block: Team and Strong Block: Shareholders wallets (addresses referenced above, (50,000 STRONG each) to the Strong Block: Community wallet. This transfer will occur prior to the start of the STRONG to STRONGER transition period. This transfer will significantly increase sustainability during the transition.



# <a name="conclude">CONCLUSION</a>

The transition to STRONGER as the rewards token for the StrongBlock NaaS DApp will represent a major step in the move to a community-first StrongChain. Once launched, StrongChain - with the native STRONGER token - will enable community participation in all economic layers, reduce the dependencies on new node runners entering the project, and provide multi-year sustainability for the community.

We are deeply grateful for the opportunity to provide the community with a clear path toward growth and sustainability. We are passionately committed to rapidly and securely engineering StrongChain, as well as executing the intermediate steps necessary to achieve these goals. We thank the StrongBlock community for your unwavering support of the team while we facilitate this amazing journey with you.


