# roadmap

plans to get to where we are going

greetings, this is a work in progress, commits are not copy safe nor final. 

This doc is an attempt to classify the COCO eth token, and identify ways to increase utility of the eth token in particular. 

---

Background

The COCO meme, originally presented by Kero is becoming well known among many PEPE artists. The meme itself has grown into having several offshoots, most with the intention of bringing COCO to various technologies which could benefit from the additional ecosystem a vibrant art space can bring. The original author was looking for a product similar to rare pepes with an open and free trading environment, and offered this on the XCP protocol, a stack which uses bitcoin transactions as a consensus layer for the assets within. Thus, rarecoco.wtf was the first born child of the meme. Stamps, another bitcoin tech that embeds the graphic directly on the bitcoin blockchain have been created as well. These assets are showing signs of growth and strength at the time of this writing.

During the initial deployment, a anonymous party decided to kind of persuade Kero to support a eth speculation token, which at the time many people showed interest in a token on ETH. Typically these tokens of memes are deployed in an anonymous fashion which persuades the community to promote what they believe in and thus we have the meme economy. Recently, another token PEPE on eth, after having a much higher level of success saw their anonymous deployer remove some assets and vanquish themselves from any responsibility to the token. Further, the original deployer of the anonymous COCO token has also taken actions to cause scrutiny, they removed the social accounts. This doesnt mean they have removed themselves entirely, they are probably just busy.

The first thing that must be approached here is how to deal with the Anonymous Deployer.

Solution 1: Reissue the token. This would mean taking a snapshot at a particular point in time and reissuing via airdrop a new version of the token where the community is 100% in control. Issuing a new v2 pool (someone has to fund it) and take on the responsibility of exchange listings and marketing ourselves.

Solution 2: Accept that the 28T (out of 420T) tokens the anonymous deployer holds is a counterparty and start a process to recover or vanquish those tokens, on failure, accept that the tokens held by the anonymous deployer are an acceptable risk for the token holder community. (The data from this occurring with PEPE shows that the price moved less than 1% after their anon's sold)

---

Either of these solutions requires creating a DAO to make community decisions. 

The DAO will be a smart contract that issues tokens for a say in the voting process of community decisions like these. A vote will have a weight based on the amount of tokens a voter has. The weight will be limited to never exceed more than 25% of the vote. It will contain a blacklist to provide a manual means to ensure a particular person cannot use multiple accounts to manipulate the vote. The votes will be held between block A and block B and votes after block B will not be counted. The cost of a vote will be limited to the transaction fees. 

---

Adding utility

Regardless of the direction chosen above, the main purpose of this document is about utility of the eth token, which is predominately expected to be used in speculation. Additional use cases can increase the value of the overall product / or token and there are a couple which could be discussed:

1: AI rendered NFT's
There is a set of AI rendered images already and more can be easily generated. These are a contribution by the author @snowkidind in order to provide some alternate versions of the COCO meme to the masses. These AI images can be issued as NFT's at which point, the minting process can add utility to the token. How?

NFT contract receives COCO and burns 100% of the deposited coco.
NFT Contract receives ETH, buys COCO and burns 100% of the coco, leaving the eth in the pool.

During this process we can target a burn amount to bring the supply into a more rational supply and also increase the value of the underlying asset. 

2. Burn Token for Governance tokens
A burn incentive would be some sort of token issued in return for a user burning COCO. It could be a separate set of NFTs, it could be governance tokens to allow a user to vote on decisions such as the one above.

--- 

What if: Token reissue

Should the decision to reissue the token occur, further improvements to the smart contract can be made to increase the security of the token as well as increase the value:

1. Ban sandwich bots - create a function to remove MEV bots from front running user purchases and sells.
2. Make the token deflationary - on any Transactions, burn a percentage of the token automatically. (see WHACKD token for example)
3. Add defi rewards for staking and or locking liquidity pool tokens - upon locking LP tokens the LP tokens can earn a percentage of a special reserve of coins and / or governance tokens. (this practice may or may not be subject to securities laws / liabilities)






