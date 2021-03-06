# Awesome Cryptoeconomics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources for Cryptoeconomics research

Looking for contributors. Submit a pull request if you have something to add :)

_Please check the [contribution guidelines](contributing.md) for info on formatting and writing pull requests._

<!-- MarkdownTOC depth=5 -->

## Table of Contents

- [Cryptoeconomics](#cryptoeconomics)
  - [Articles](#articles)
    - [Introductory](#introductory)
    - [Game Theory](#game-theory)
    - [Mechanism Design](#mechanism-design)
    - [Cryptographic Primitives](#cryptographic-primitives)
    - [Consensus Mechanisms](#consensus-mechanisms)
    - [Network Effects](#network-effects)
    - [Governance](#governance)
    - [Cryptoeconomic Security](#cryptoeconomic-security)
    - [Token Engineering](#token-engineering)
    - [Cryptoeconomic Primitives](#cryptoeconomic-primitives)
    - [Tokenomics](#tokenomics)
    - [Stablecoins](#stablecoins)
    - [State Channels](#state-channels)
    - [Empirical Cryptoeconomics](#empirical-cryptoeconomics)
  - [Videos](#videos)
    - [Consensus Protocols](#consensus-protocols)
    - [Cryptoeconomics](#cryptoeconomics)
    - [State Channels](#state-channels)
    - [Cryptoeconomic Security](#cryptoeconomic-security)
    - [Cryptography](#cryptography)
    - [Additional](#additional)
  - [Podcasts](#podcasts)
  - [Whitepapers](#whitepapers)
  - [Books](#books)
  - [Other Resources](#other-resources)
  - [Blockchain Hacks and Post-mortems](#hacks)
    - [The DAO](#the-dao)
    - [Parity MultiSig](#parity-multisig)
    - [Bancor](#bancor)
    - [King of Ether](#king-of-ether)
    - [Roulette](#roulette)
- [Additional Information](#additional-information-and-related-topics)
  - [Behavioural Economics](#behavioural-economics)
  - [Related Awesome Lists](#related-lists)
- [Licence](#license)

<!-- /MarkdownTOC -->

## Articles

### Introductory

“Cryptoeconomics is the application of incentive mechanism design to information security problems.”

1.  :ballot_box_with_check: [Cryptoeconomics for dummies](https://medium.com/@j32804/cryptoeconomics-for-dummies-part-0-7172efa81507)
    - "The purpose of a system is what it does" - [POSIWID](https://en.wikipedia.org/wiki/The_purpose_of_a_system_is_what_it_does)
    - RELATED FIELD: [Systems Theory](https://en.wikipedia.org/wiki/Systems_theory)
    - RELATED FIELD: [Cybernetics](https://en.wikipedia.org/wiki/Cybernetics)
1.  :ballot_box_with_check: [Cryptoeconomics 101](https://thecontrol.co/cryptoeconomics-101-e5c883e9a8ff)
    - "Cryptoeconomics is the study of economic interaction in adversarial environments." (Where those environments are decentralised or distributed.)
1.  :ballot_box_with_check: [Making Sense of Cryptoeconomics](https://medium.com/@jjmstark/making-sense-of-cryptoeconomics-c6455776669) by Josh Stark
    - "Cryptoeconomics is the use of incentives and cryptography to design new kinds of systems, applications, and networks."
    - "Understanding the mechanism design of a project holding an ICO is an essential tool in determining that token’s utility and likely value."
1.  :ballot_box_with_check: [What is Cryptoeconomics](https://blockgeeks.com/guides/what-is-cryptoeconomics/) - A guide by BlockGeeks
    - PoS negates _P + epsilon_ attack. Bribes (_epsilon_) no longer outweigh punishments.
1.  :ballot_box_with_check: [Paving the Future of Blockchain Technology](https://hackernoon.com/cryptoeconomics-paving-the-future-of-blockchain-technology-13b04dab971)
    - "Using cryptography, the blockchain concept allows us to definitively prove what transactions actually happened in the past. Through game theory and economics incorporated into the design of blockchain protocols, the system incentivizes stability and this common good to hold into the _future_."
    - PoS is resistant to the P + epsilon attack because the attacker will have to credibly show an enormous budget to subsidize the participants’ security deposits.
1.  :ballot_box_with_check: [Vivek Singh's Cryptoeconomics in context](https://hackernoon.com/cryptoeconomics-in-context-6435ad6839be)
1.  [The Blockchain Economy: A beginner’s guide to institutional cryptoeconomics](https://medium.com/@cryptoeconomics/the-blockchain-economy-a-beginners-guide-to-institutional-cryptoeconomics-64bf2f2beec4) by RMIT Blockchain Innovation Hub
1.  :ballot_box_with_check: [Cryptoeconomics is Hard Part 1](https://blog.coinfund.io/cryptoeconomics-is-hard-ad401b2428b9), [Part 2](https://blog.coinfund.io/cryptoeconomics-is-hard-part-2-4d522cb3d3a4) and [Part 3](https://blog.coinfund.io/cryptoeconomics-is-hard-market-cap-4833c378a3e0) by Aleksandr Bulkin
1.  :ballot_box_with_check: [How to create a cryptoeconomic protocol from scratch](http://mattgoldenberg.net/2016/10/26/vlad-zamfir-how-to-create-a-crypto-economic-protocol-from-scratch/) by Vlad Zamfir
1.  :ballot_box_with_check: [Behavioural Crypto-Economics](https://medium.com/berlin-innovation-ventures/behavioral-crypto-economics-6d8befbf2175): The challenge and promise of Blockchain Incentive Design by Elab Verbin
    - [Congnitive deliberation costs](https://en.wikipedia.org/wiki/Choice_architecture#Reducing_choice_overload)
    - [Overchoice](https://en.wikipedia.org/wiki/Overchoice) - "The tyranny of choice..."

![Labels](field_labels.png)

### Game Theory

"Game Theory is a set of tools used to help analyse situations where an individual's best course of action depends on what others do or are expected to do. Game Theory allows us to undersand how people act in situations where they are interconnected."

"Game theory generally refers to the study of mathematical models that describe the behavior of logical decision-makers (who want to maximise their payoff). A game refers to a situation involving a set of players who each have a set of possible choices, in which the outcome for any individual player depends partially on the choices made by other players."

1.  :ballot_box_with_check: [Introduction to Game Theory](https://towardsdatascience.com/introduction-to-game-theory-part-1-1a812d898e84) Part one of a series by Devin Soni
    - [Payoff matrix (Normal-form game)](https://en.wikipedia.org/wiki/Normal-form_game) - A payoff matrix is a visual representation of the possible outcomes of a strategic decision.
    - Wikipedia: [Prisoner's Dilemma](https://en.wikipedia.org/wiki/Prisoner%27s_dilemma)
    - Wikipedia: [Ultimatum Game](https://en.wikipedia.org/wiki/Ultimatum_game)
1.  :ballot_box_with_check: [Schelling Point](http://wisdomofcrowds.blogspot.com.es/2010/02/chapter-five-part-iii.html) Introduction to the concept of Schelling Point
    - Wikipedia: [Focal Point](<https://en.wikipedia.org/wiki/Focal_point_(game_theory)>)
1.  :ballot_box_with_check: [Nash Equilibria and Schelling Points](http://lesswrong.com/lw/dc7/nash_equilibria_and_schelling_points/)
    - "A Nash Equilibrium is a set of choices in which no player has anything to gain by changing only their own choice. They are often applied to games in which both players move simultaneously and where decision trees are less useful."
1.  :ballot_box_with_check: [Mechanism design (deck)](https://www.slideshare.net/stathisgrigoropoulos/mechanism-design-theory-examples-and-complexity-final) Mechanism design theory examples and complexity
1.  [Standford's Algorithmic Game Theory lecture series](https://theory.stanford.edu/~tim/f13/f13.html)
1.  :ballot_box_with_check: [Cryptocurrency Game Theory](https://blockgeeks.com/guides/cryptocurrency-game-theory/) What is Cryptocurrency Game Theory: A Basic introduction
1.  :ballot_box_with_check: [Correlated Equilibria](https://www.quantamagazine.org/in-game-theory-no-clear-path-to-equilibrium-20170718/) In Game Theory, No Clear Path to Equilibrium
1.  :ballot_box_with_check: Wikipedia: [Assurance Contract](https://en.wikipedia.org/wiki/Assurance_contract)
1.  :ballot_box_with_check: Wikipedia: [Vickrey Auction](https://en.wikipedia.org/wiki/Vickrey_auction)
    - Bids are secret and the winner of the auction (defined as the player with the highest bid) only pays the second highest amount that was bid.
1.  :ballot_box_with_check: Wikipedia: [All-Pay Auction](https://en.wikipedia.org/wiki/All-pay_auction)
    - An auction in which every bidder must pay regardless of whether they win the prize.

### Mechanism Design

"Mechanism Design is often referred to as “reverse game theory” – Game theory is about choosing the best moves in a given game, whereas mechanism design is about creating a game, given the moves you desire."

"Cryptography is the part of your mechanism that ensures the integrity of past moves, and economics is the part of your mechanism that ensures you’ll take the proper future moves."

"Mechanism design is a field of economics dedicated to the study of mechanisms to (dis)/incentivize actions."

"Creating tokens without studying mechanism design is like building new cryptosystems without reading any crypto papers... "

1.  :ballot_box_with_check: [A Crash Course in Mechanism Design for Cryptoeconomic Applications](https://medium.com/blockchannel/a-crash-course-in-mechanism-design-for-cryptoeconomic-applications-a9f06ab6a976)
1.  :ballot_box_with_check: [Mechanism Theory](https://web.stanford.edu/~jacksonm/mechtheo.pdf) paper by Matthew O. Jackson
1.  "It's naive to tackle distribute systems and incentive mechanism design separately" - [Link](https://pbs.twimg.com/media/DhWUzHLVQAIDz8P.jpg)

### Cryptographic Primitives

1.  :ballot_box_with_check: [Cryptographic Primitives](https://en.wikipedia.org/wiki/Cryptographic_primitive) as described in Wikipedia
1.  [A Graduate Course in Applied Cryptography](http://toc.cryptobook.us/) by Dan Boneh and Victor Shoup
1.  :ballot_box_with_check: [Ethereum: Signing and Validating](https://medium.com/@angellopozo/ethereum-signing-and-validating-13a2d7cb0ee3)
1.  :ballot_box_with_check: [Merkling in Ethereum](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/) by Vitalik Buterin
1.  :ballot_box_with_check: [Bitcoin's Academic Pedigree](https://queue.acm.org/detail.cfm?id=3136559) by Arvind Narayanan and Jeremy Clark
1.  :ballot_box_with_check: [Commitment Scheme](https://en.wikipedia.org/wiki/Commitment_scheme)
    - "...allows one to commit to a chosen value (or chosen statement) while keeping it hidden to others, with the ability to reveal the committed value later"

### Consensus Mechanisms

#### PoW - Proof of Work

1.  :ballot_box_with_check: [PoW and Blockchains](https://www.zurich.ibm.com/dccl/papers/eyal_dccl_slides.pdf) presentation by Prof. Ittay Eyal (IC3)
    - PoW provides Sybil protection
1.  :ballot_box_with_check: [The PoW concept](http://nakamotoinstitute.org/mempool/the-proof-of-work-concept/) article by the Nakamoto Institute
    - [Handicap Principle](https://en.wikipedia.org/wiki/Handicap_principle) - "The central idea is that sexually selected traits function like conspicuous consumption, signalling the ability to afford to squander a resource. Receivers know that the signal indicates quality because inferior quality signallers cannot afford to produce such wastefully extravagant signals."
1.  :ballot_box_with_check: [Vulnerability: Proof of Work vs. Proof of Stake](https://medium.com/@robertgreenfieldiv/vulnerability-proof-of-work-vs-proof-of-stake-f0c44807d18c)
    - PoW has objective consensus protocol. PoS is weakly subjective.

#### PoS - Proof of Stake

1.  [Strengths and Weaknesses of PoS](https://blog.ethereum.org/2014/07/05/stake/) Vitalik Buterin's article on the strengths and weaknesses of staking contrasting to PoW algorithms
1.  [PoS Design Philosophy](https://medium.com/@VitalikButerin/a-proof-of-stake-design-philosophy-506585978d51) A Proof of Stake Design Philosophy by Vitalik Buterin
1.  [Ethereum PoS FAQ](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ)
1.  [The evolution of PoS](https://cointelegraph.com/news/the-history-and-evolution-of-proof-of-stake) Article on the evolution of PoS by Coin Telegraph
1.  [Weak Subjectivity in PoS](https://blog.ethereum.org/2014/11/25/proof-stake-learned-love-weak-subjectivity/) Weak Subjectivity in PoS by Vitalik Buterin
1.  [The History of Casper - Chapter 1](https://medium.com/@Vlad_Zamfir/the-history-of-casper-part-1-59233819c9a9) Vlad Zamfir's series on the history of Casper, [Chapter 2](https://medium.com/@Vlad_Zamfir/the-history-of-casper-chapter-2-8e09b9d3b780), [Chapter 3](https://medium.com/@Vlad_Zamfir/the-history-of-casper-chapter-3-70fefb1182fc), [Chapter 4](https://medium.com/@Vlad_Zamfir/the-history-of-casper-chapter-4-3855638b5f0e),
    [Chapter 5](https://medium.com/@Vlad_Zamfir/the-history-of-casper-chapter-5-8652959cef58)
1.  [On Stake and Consensus](https://download.wpsoftware.net/bitcoin/pos.pdf)
1.  [Critic on the PoS Philosophy](https://medium.com/@tuurdemeester/critique-of-buterins-a-proof-of-stake-design-philosophy-49fc9ebb36c6) by Tuur Demeester
1.  [Extended Summary on Casper](https://medium.com/@jonchoi/ethereum-casper-101-7a851a4f1eb0) by Jon Choi
1.  [The Economics of the PoS consensus algorithm](https://medium.com/@gertrammeloo/the-economics-of-the-proof-of-stake-consensus-algorithm-e28adf63e9db)
1.  [Casper vs Tendermint](https://blog.cosmos.network/consensus-compare-casper-vs-tendermint-6df154ad56ae)
1.  [Minimal Slashing condition in Ethereum](https://medium.com/@VitalikButerin/minimal-slashing-conditions-20f0b500fc6c)

#### DPoS - Delegated Proof of Stake

1.  [DPoS Introduction](https://bitshares.org/technology/delegated-proof-of-stake-consensus/) Introduction to DPoS by Bitshares
1.  [DPoS vs PoW](http://bytemaster.github.io/bitshares/2015/01/04/Delegated-Proof-of-Stake-vs-Proof-of-Work/) Article by Daniel Larimer from Bitshares
1.  [Tendermint BFT vs. EOS dPoS](https://blog.cosmos.network/consensus-compare-tendermint-bft-vs-eos-dpos-46c5bca7204b) by Tendermint
1.  [Seeking Consensus on Consensus](https://steemit.com/eos/@iang/seeking-consensus-on-consensus-dpos-or-delegated-proof-of-stake-and-the-two-generals-problem) Delegated Proof of Stake and the Two Generals' Problem

#### dBFT - Delegated Byzantine Fault Tolerance

1.  [Byzantine Fault Tolerance in Distributed Systems](http://sce.uhcl.edu/goodwin/Ceng5334/downLoads/byzantine.pdf) by Prof. Kenneth Goodwin
1.  [dBFT vs PoW and PoS](https://www.econotimes.com/Blockchain-project-Antshares-explains-reasons-for-choosing-dBFT-over-PoW-and-PoS-659275) Antshare's (now NEO) views on consensus
1.  [Intro to Ethermint BFT](https://blog.cosmos.network/a-beginners-guide-to-ethermint-38ee15f8a6f4)

### Network Effects

1.  :ballot_box_with_check: [A Note on Metcalfe's Law, Externalities and Ecosystem Splits](http://vitalik.ca/general/2017/07/27/metcalfe.html) by Vitalik Buterin
    - Wikipedia: [Metcalfe's Law](https://en.wikipedia.org/wiki/Metcalfe%27s_law)
    - Not N<sup>2</sup> except at low numbers. More like N\*log(N).
1.  :ballot_box_with_check: [How I learned to stop worrying and love ETC](http://pdaian.com/blog/stop-worrying-love-etc/)
1.  :ballot_box_with_check: [Continuous Token Models: Towards a Million Networks of Value](https://media.consensys.net/exploring-continuous-token-models-towards-a-million-networks-of-value-fff153175776) by Simon de la Rouviere
    - "Continuous Token Models take a different approach to quantifying interest in networks of value."
    - "The idea is that instead of pre-selling tokens during a launch phase, the tokens are minted as needed through various means. The tokens are then dispensed for services rendered in the network."
    - "However, if you add a global namespace, users can start using this system WITHOUT the permission of Truffle. Users would then be able to immediately start congregating around common focal (schelling) points in the same way people organise around hashtags..."
    - See meme markets.
1.  :ballot_box_with_check: [Crypto Tokens: A breakthrough in open network design](https://medium.com/@cdixon/crypto-tokens-a-breakthrough-in-open-network-design-e600975be2ef) by Chris Dixon
    - "Token networks remove this friction by aligning network participants to work together toward a common goal— the growth of the network and the appreciation of the token."
1.  :ballot_box_with_check: [Bitcoin Network Effects](http://blog.eladgil.com/2017/12/bitcoin-network-effects_11.html)
    - [reflexive assets](https://macro-ops.com/understanding-george-soross-theory-of-reflexivity-in-markets/) - "perfect information does not exist"
1.  :ballot_box_with_check: [Keepers — Workers that Maintain Blockchain Networks](https://medium.com/@rzurrer/keepers-workers-that-maintain-blockchain-networks-a40182615b66)
1.  :ballot_box_with_check: [Smart-Contract Network Effect Fallacy](https://multicoin.capital/2017/08/28/smart-contract-network-effect-fallacy/)
1.  :ballot_box_with_check: [On The Network Effects of Stores of Value](https://multicoin.capital/2018/05/09/on-the-network-effects-of-stores-of-value/)
1.  :ballot_box_with_check: [Power laws and Network Effects: Why BitcoinCash is not a free lunch](https://cryptofundamental.com/power-laws-and-network-effects-why-bitcoincash-is-not-a-free-lunch-5adb579972aa)

### Governance

1.  [The Consensus Series, Part I: The Basics of Collectivity](https://blog.coinfund.io/the-consensus-series-part-i-the-basics-of-collectivity-a11d76ff4d5d) and [Addendum](https://buzzrobot.com/consensus-series-addendum-1-what-do-the-robots-want-729349014aee) by Aleksandr Bulkin
1.  [Governance and Network Effects](https://blog.aragon.one/thoughts-on-governance-and-network-effects-f40fda3e3f98)
1.  [Notes on Blockchain Governance](https://vitalik.ca/general/2017/12/17/voting.html) by Vitalik Buterin
1.  [Against On-Chain Governance](https://medium.com/@Vlad_Zamfir/against-on-chain-governance-a4ceacd040ca) by Vlad Zamfir

### Cryptoeconomic Security

1.  [Intro to Cryptoeconomic security](https://blockchainatberkeley.blog/understanding-crypto-economic-security-through-game-theory-526e810c7736) Basic intro to cryptoeconomic security
1.  [Anti-fragile Cryptoeconomic systems](https://thecontrol.co/antifragile-cryptoeconomic-systems-f66d72b54128) Anti-fragile cryptoeconomic Systems
    through game theory
1.  [Triangle of harm](http://vitalik.ca/general/2017/07/16/triangle_of_harm.html) by Vitalik Buterin
1.  [On Inflation, Transaction Fees and Cryptocurrency Monetary Policy](https://blog.ethereum.org/2016/07/27/inflation-transaction-fees-cryptocurrency-monetary-policy/) Vitalik Buterin's article on the role of cryptoeconomics in blockchain security
1.  [Settlement Finality](https://blog.ethereum.org/2016/05/09/on-settlement-finality/) Vitalik Buterin's article on the elusive topic of economic finality
1.  [Bancor is flawed](http://hackingdistributed.com/2017/06/19/bancor-is-flawed/) Bancor's review by Hacking Distributed
1.  [To sink front-runners, send submarines](http://hackingdistributed.com/2017/08/28/submarine-sends/) Bancor's front-running woes by Hacking Distributed
1.  [Bitcoin's security model](https://www.coindesk.com/bitcoins-security-model-deep-dive/) by Jameson Lopp

#### Attacks

1.  [General article on how attacks work in PoW - Part 1](https://medium.com/@chrshmmmr/an-introduction-to-understanding-attacks-and-dishonesty-on-proof-of-work-blockchains-9e7f547ed4c8) and [Part 2](https://medium.com/@chrshmmmr/a-guide-to-dishonesty-on-pow-blockchains-when-does-double-spending-pays-off-4f1994074b52)
1.  [Long range attacks](https://blog.ethereum.org/2014/05/15/long-range-attacks-the-serious-problem-with-adaptive-proof-of-work/)
1.  [Censorship attacks](https://blog.ethereum.org/2015/06/06/the-problem-of-censorship/)
1.  [P + epsilon attack](https://blog.ethereum.org/2015/01/28/p-epsilon-attack/)
1.  [Coordination problems](http://vitalik.ca/general/2017/05/08/coordination_problems.html)
1.  [The Miners dilemma](http://hackingdistributed.com/2014/12/03/the-miners-dilemma/)
1.  [Dealing with failure in cryptocurrency](https://medium.com/@Vlad_Zamfir/dealing-with-failure-in-cryptocurrency-463475da83e5) Vlad Zamfir's article on dealing with failure in cryptocurrency
1.  [Model of an internal PoW attacker](https://medium.com/@Vlad_Zamfir/simple-model-of-an-internal-pow-attacker-1a713cf00672) Vlad Zamfir's article on PoW attackers
1.  [Cryptoeconomics and X-Risk researchers should listen to each other more](https://medium.com/@VitalikButerin/why-cryptoeconomics-and-x-risk-researchers-should-listen-to-each-other-more-a2db72b3e86b) Vitalik Buterin's article on how cryptoeconomics and existential risk researchers could apply blockchain technology in global coordination challenges
    [Part 2](https://medium.com/@chrshmmmr/a-guide-to-dishonesty-on-pow-blockchains-when-does-double-spending-pays-off-4f1994074b52)
1.  [Presentation on most common attacks in Bitcoin](http://www.cs.columbia.edu/~fernando/classes/cryptopuc2016-01/AnalyzingBitcoinSecurity.pdf)
1.  [51% Attack](https://en.bitcoin.it/wiki/Majority_attack) Bitcoin.it Wiki explanation
1.  [Selfish Mining](https://bitcoinmagazine.com/articles/selfish-mining-a-25-attack-against-the-bitcoin-network-1383578440/) a 25% attack against Bitcoin
1.  [Sybil attack](https://en.wikipedia.org/wiki/Sybil_attack) as described in Wikipedia
1.  [Nothing at Stake and Long-range attacks in PoS](https://blog.goldmint.io/nothing-at-stake-and-longrange-attack-in-pos-4ec486f1fc89)
1.  [$5 wrench Attack](https://xkcd.com/538/) XKCD comic on the cheapest attack on cryptography

### Token Engineering

![Labels](token_engineering.png)

1.  Wiki: [Token Engineering](http://tokenengineering.net/)
    - "Creating tokenized ecosystems is hard. How do we figure out what we want? How do we manifest that intent with block rewards and other crypto building blocks? How do we simulate and validate the design? How do we anticipate attacks and respond to them? How do we update the protocols? Given that these systems are wildly powerful, how can we better take responsibility for their design & deployment?"
1.  [Towards a Hierarchy of Token Building Blocks](https://blog.oceanprotocol.com/towards-a-hierarchy-of-token-building-blocks-6c8dd7b42341)
1.  [History Is Rhyming: Fitness Functions & Comparing Blockchain Tokens To The Web](https://hackernoon.com/history-is-rhyming-fitness-functions-comparing-blockchain-tokens-to-the-web-3c117239f4c) by Simon de la Rouviere
1.  [Introducing Curation Markets: Trade Popularity of Memes & Information ](https://medium.com/@simondlr/introducing-curation-markets-trade-popularity-of-memes-information-with-code-70bf6fed9881) by Simon de la Rouviere
1.  [TE Series Part I: Can Blockchains Go Rogue?](https://blog.oceanprotocol.com/can-blockchains-go-rogue-5134300ce790) by Trent McConaghy
1.  [TE Series Part II: Towards a Practice of Token Engineering](https://blog.oceanprotocol.com/towards-a-practice-of-token-engineering-b02feeeff7ca), with presentation deck [here](https://www.slideshare.net/TrentMcConaghy/towards-a-practice-of-token-engineering) by Trent McConaghy
1.  [Token Engineering Case Studies](https://blog.oceanprotocol.com/token-engineering-case-studies-b44267e68f4) Analysis of Bitcoin, Design of Ocean Protocol by Trent McConaghy

### Cryptoeconomic Primitives

1.  :ballot_box_with_check: [The Emergence of Cryptoeconomic Primitives](https://medium.com/@jacobscott/the-emergence-of-cryptoeconomic-primitives-14ef3300cc10) by Jacob Horne
    - "Protocol based incentives systems that are uniquely enabled by tokens. Also referred to as “tokenized economic games”."
1.  :ballot_box_with_check: [Rewriting the Story of Human Collaboration - Or, an Introduction to Token Bonding & Curation Markets](https://blog.goodaudience.com/rewriting-the-story-of-human-collaboration-c33a8a4cd5b8)
    - Token Curated Registries (i.e. TCRs)
    - Token-Ranked Lists (i.e. TRLs)
    - Curation Markets (i.e bonding curves)
    - Prediction Markets
    - Stablecoins
    - Geospatial Markets

#### Token Curated Registries

Code: https://github.com/skmgoldin/tcr

1.  :ballot_box_with_check: [Token Curated Registries 1.0](https://medium.com/@ilovebagels/token-curated-registries-1-0-61a232f8dac7) by Mike Goldin
    - "Token-curated registries are decentrally-curated lists with intrinsic economic incentives for token holders to curate the list’s contents judiciously."
    - "Token holders have a tactical incentive to challenge and reject every candidate to their registry in the interest of increasing their holdings, but this is at odds with their strategic interest of increasing the value of their holdings. An empty list is of no interest to consumers, so candidates would not bother applying to it. Candidates drive fundamental demand for a registry’s intrinsic token, and so by behaving tactically rather than strategically, token holders go against their own interests and incur a potentially severe financial loss. Generally, it is in the interest of economically rational token holders to behave strategically and curate a high-quality list."
    - [Mike’s Cryptosystems Manifesto](https://docs.google.com/document/d/1TcceAsBlAoFLWSQWYyhjmTsZCp0XqRhNdGMb6JbASxc/edit)
      - "A token must work as a necessary element of a self-sustaining system which is a public utility."
1.  :ballot_box_with_check: [Token Curated Registries 1.1, 2.0 TCRs, new theory, and dev updates](https://medium.com/@ilovebagels/token-curated-registries-1-1-2-0-tcrs-new-theory-and-dev-updates-34c9f079f33d) by Mike Goldin
    - [A Closer Look at TCR 1.1 and the µ Equation]()
1.  [City Walls & Bo-Taoshi: Exploring the Power of Token-Curated Registries](https://medium.com/@simondlr/city-walls-bo-taoshi-exploring-the-power-of-token-curated-registries-588f208c17d5)
    - TCRs == binary, Curation Markets (i.e. Bonding Curves) == continuous
1.  [Token Curated Registry (TCR) Design Patterns](https://medium.com/coinmonks/token-curated-registry-tcr-design-patterns-4de6d18efa15)
1.  [Graded Token-Curated Decisions with Up-/Downvoting — Designing Cryptoeconomic Ranking and Reputation Systems](https://medium.com/@sebastian.gajek/graded-token-curated-decisions-with-up-downvoting-designing-cryptoeconomic-ranking-and-2ce7c000bb51)
1.  [Token Curated Registries in Development
    ](https://medium.com/@brandonarvanaghi/explaining-the-genesis-block-in-ethereum-92f7d6b90c2f)
1.  [Subjective vs. Objective TCRs](https://medium.com/coinmonks/subjective-vs-objective-tcrs-a21f5d848553)
1.  [Incentive alignment in Token Curated Registries](https://medium.com/paratii/incentive-alignment-in-token-curated-registries-4d6e41652a9b)
1.  :ballot_box_with_check: [Learnings from MetaX on Launching The First Token-Curated Registry (TCR)](https://medium.com/metax-publication/learnings-from-metax-on-launching-the-first-token-curated-registry-c30140d5052c)
1.  :ballot_box_with_check: [Investable Token Curated Registries](https://decentralize.today/investable-token-curated-registries-1e395f1b3471)
1.  :ballot_box_with_check: [Sponsored Burning for TCR](https://medium.com/@avsa/sponsored-burning-for-tcr-c0ab08eef9d4)
1.  :ballot_box_with_check: [When Can Token Curated Registries Actually Work?](https://medium.com/wireline/when-can-token-curated-registries-actually-work-%C2%B9-2ad908653aaf)
1.  :ballot_box_with_check: :rage3: [Curate This: Token Curated Registries That Don’t Work.](https://blog.coinfund.io/curate-this-token-curated-registries-that-dont-work-d76370b77150)

###### Projects

- Civil
- FOAM
- adChain
- District0x

#### Token-Ranked Lists

1.  :ballot_box_with_check: [Introducing Token-Ranked Lists (TRLs)](https://medium.com/@marcziade/introducing-token-ranked-lists-trls-3394ec2e360b)

#### Curation Markets (Curved Bonding Contracts or Token Bonding Curves)

1.  :ballot_box_with_check: [Token Bonding Curves Explained](https://medium.com/@justingoro/token-bonding-curves-explained-7a9332198e0e)
1.  :ballot_box_with_check: [Can We Save The Utility Token?](https://medium.com/collabs-io/can-we-save-the-utility-token-55ef639370cf)
    - Utility Tokens exhibit the "velocity problem":
      - [The Blockchain Token Velocity problem](https://www.coindesk.com/blockchain-token-velocity-problem/)
      - [The False Dichotomy of Utility and Store of Value](https://medium.com/@QwQiao/the-false-dichotomy-of-utility-and-store-of-value-27fe12bf3bdb)
1.  [Continuous Token-Curated Registries: The Infinity of Lists](https://medium.com/@simondlr/continuous-token-curated-registries-the-infinity-of-lists-69024c9eb70d) by Simon de la Rouviere
1.  [Tokens 2.0: Curved Token Bonding in Curation Markets](https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5) by Simon de la Rouviere
1.  [Solving Price Discovery Of Non-Rivalrous Goods (with Curved Bonding)](https://medium.com/@simondlr/solving-price-discovery-of-non-rivalrous-goods-with-curved-bonding-27b2186d55d5) by Simon de la Rouviere
1.  [How to Make Bonding Curves for Continuous Token Models](https://hackernoon.com/how-to-make-bonding-curves-for-continuous-token-models-3784653f8b17)
1.  [Bonding curve simulation using Incentivai](https://medium.com/incentivai/bonding-curve-simulation-using-incentivai-2b2bfe0c6400)
1.  [_Dynamic_ Token Bonding Curves](https://tokeneconomy.co/dynamic-token-bonding-curves-41d36e43befa)
    - "What if we had bonding curves that used the shared funds in a bonding contract, but the curve were based on the individual token holder’s ‘activity’ (i.e. their portion of the total token supply)?"
1.  [On Bonding Curves as Funding Mechanisms](https://medium.com/thoughtchains/on-bonding-curves-as-funding-mechanisms-a0812b22cc3d)
1.  [Futarchy with Bonding Curve Tokens](https://ethresear.ch/t/futarchy-with-bonding-curve-tokens/3449)
1.  GitHub: [curve-bonded-tokens](https://github.com/tarrencev/curve-bonded-tokens)

###### Projects

- Bancor

#### Curated Governance

1.  :ballot_box_with_check: [Curated Governance with Stake Machines](https://medium.com/@DimitriDeJonghe/curated-governance-with-stake-machines-8ae290a709b4)

#### Curated Reputation

1.  :ballot_box_with_check: [Claims Curated Registries: Thoughts on reputation development](https://medium.com/@EntrpoicNonsense/claims-curated-registries-thoughts-on-reputation-development-6d368c81516) - [See TCRs]

#### Other

1.  [Hashtag Markets: Mashing together Reddit, Schelling Points, Tokenisation & Autonomous Organisations](https://media.consensys.net/hashtag-markets-mashing-together-reddit-schelling-points-tokenisation-autonomous-organisations-ceec3cd3baf0) by Simon de la Rouviere
1.  [Token curated playlists #1: thoughts on staking and consumer applications](https://medium.com/paratii/token-curated-playlists-1-thoughts-on-staking-and-consumer-applications-2a50bc837a94) by Felipe Gaúcho Pereira
1.  [Re-Fungible Token (RFT)](https://medium.com/@billyrennekamp/re-fungible-token-rft-297003592769) by Billy Rennekamp

#### Tools

1.  :ballot_box_with_check: [Incentivai](http://incentivai.co/)
    - "... is a tool for testing mechanism design of smart contract economies. It is done prior to deployment onto blockchain via simulation using AI agents."

### Tokenomics

1.  [Token sales models](http://vitalik.ca/general/2017/06/09/sales.html) Token sales models by Vitalik Buterin
1.  [Traditional Asset Tokenization](https://hackernoon.com/traditional-asset-tokenization-b8a59585a7e0) by Stephen McKeon
1.  [A business guide to Tokenomics](https://medium.com/@wmougayar/tokenomics-a-business-guide-to-token-usage-utility-and-value-b19242053416) by William Mougayar
1.  [Cryptoasset Valuations](https://medium.com/@cburniske/cryptoasset-valuations-ac83479ffca7) by Chris Burniske
1.  [Justified Token Value](https://www.frontierfoundry.co/blog/justified-token-value-part-1) by Adrian Jonklaas
1.  [Understanding Token Velocity](https://multicoin.capital/2017/12/08/understanding-token-velocity/)
1.  [On Value, Velocity and Monetary Theory](https://medium.com/blockchannel/on-value-velocity-and-monetary-theory-a-new-approach-to-cryptoasset-valuations-32c9b22e3b6f)
    - "The velocity of money is the rate at which money is exchanged from one transaction to another. It also refers to how much a unit of currency is used in a given period of time."
1.  [The Token Classification Framework](http://www.untitled-inc.com/the-token-classification-framework-a-multi-dimensional-tool-for-understanding-and-classifying-crypto-tokens/) a multi-dimensional tool for understanding and classifying crypto tokens
1.  [MV = PQ isn't right for crypto](https://medium.com/@AustereCapital/mv-p-que-love-and-circularity-in-the-time-of-crypto-1626c8ac297f) a case made by Austere Capital
1.  [The Blockchain Token Velocity Problem](https://www.coindesk.com/blockchain-token-velocity-problem/)
    - "Most utility tokens don't provide a compelling reason for token holders to hold the token for more than a few seconds."
1.  [The quantitative theory of money for tokens](https://blog.coinfund.io/the-quantity-theory-of-money-for-tokens-dbfbc5472423) a rebuttal of the MV = PQ theory by Warren Weber
1.  [NVT - network value to transactions ratio](https://coinmetrics.io/mtv-ratio-part-ii/) a market to transaction value proposal by Coinmetrics

### Stablecoins

1.  [Ethereum Madrid's Cryptoeconomics 101](http://slides.com/ethereummadrid/cryptoeconomics101-stablecoin#/) presentation on Stablecoins by Sandra Becker of Ethereum Madrid
1.  [An Overview of stablecoins](https://multicoin.capital/2018/01/17/an-overview-of-stablecoins/)
1.  [Stablecoins: A Holy Grail in digital cryptocurrencies](https://thecontrol.co/stablecoins-a-holy-grail-in-digital-currency-b64f3371e111)
1.  [Volatility and Mass Adoption: 2 reasons we would benefit from a stablecoin](https://medium.com/topl-blog/dangerous-volatility-and-why-we-need-a-stable-cryptocurrency-6d66dcd605f8)
1.  [The search for a stable cryptocurrency](https://blog.ethereum.org/2014/11/11/search-stable-cryptocurrency/)
1.  [An Experiment with Sai, a simple stablecoin](https://blog.makerdao.com/2017/06/05/introducing-sai/) by MakedDAO
1.  :ballot_box_with_check: [Maker for Dummies: A Plain English Explanation of the Dai Stablecoin](https://medium.com/cryptolinks/maker-for-dummies-a-plain-english-explanation-of-the-dai-stablecoin-e4481d79b90)
1.  [Designing a price stable currency](https://hackernoon.com/stablecoins-designing-a-price-stable-cryptocurrency-6bf24e2689e5) by Haseeb Qureshi
1.  [A skeptic view of stablecoins](https://medium.com/@odtorson/that-thing-about-stable-coins-2231bc0a339b)

### State Channels

1.  [Compact and very well explained definition](http://www.jeffcoleman.ca/state-channels/)
1.  [Overview on the Raiden Network](https://hackernoon.com/raiden-network-developer-preview-dad83ec3fc23)
1.  [Generalised State Channels on Ethereum](https://medium.com/l4-media/generalized-state-channels-on-ethereum-de0357f5fb44)
1.  [Introducing multi-party state-channels](https://medium.com/@kentaiwasaki/velcron-enabling-multi-party-state-channels-11141e82b2a3)
1.  [A state-channels adventure with Counterfactual Rick](https://medium.com/spankchain/a-state-channels-adventure-with-counterfactual-rick-part-1-ce68e16252ea) by SpankChain (SFW!)

### Empirical Cryptoeconomics

1.  [How manipulation-resistant are Prediction Markets?](https://blog.gnosis.pm/how-manipulation-resistant-are-prediction-markets-710e14033d62) How manipulation-resistant are Prediction Markets? Our Undertaking in Empirical Cryptoeconomics by Gnosis
1.  [Empirical Cryptoeconomics](https://www.reddit.com/r/ethereum/comments/453sid/empirical_cryptoeconomics/) Vitalik Buterin's post on empirical cryptoeconomics
1.  [Testing mechanism design with AI agents](http://incentivai.co/) Tool for Smart Contract testing with [concept paper](http://incentivai.co/incentivai_concept_paper_10032018.pdf) and [intro](https://medium.com/incentivai/introducing-incentivai-41ce8ba87152)

## Videos

### Consensus Protocols

1.  [Consensus](https://www.youtube.com/watch?v=fw3WkySh_Ho&t=3606s) Consensus Algorithm - Andreas Antonopoulos
1.  [Intro to Casper](https://www.youtube.com/watch?v=MyDocEQfBGA) Karl Floersch presenting Ethereum's Casper PoS
1.  [PoS roundtable](https://www.youtube.com/watch?v=1tdxPzQt4ZI) PoS roundtable with Joseph Poon, Vitalik Buterin, Vlad Zamfir, Dominic Williams, Zack Hess at Cryptoeconomicon 2015
1.  [PoW roundtable](https://www.youtube.com/watch?v=sADoZx7Ar4A) PoW roundtable with Tim Swanson, Vitalik Buterin and Peter Todd at Cryptoeconomicon 2015
1.  [Proof of Stake - Technion Cyber and Computer Security Summer School](https://www.youtube.com/watch?v=NRwA-uHkQlU) and [presentation deck](http://vitalik.ca/files/technion2.pdf)
1.  [CESC2017 - Casper Proof of Stake](https://www.youtube.com/watch?v=ycF0WFHY5kc&list=PLSONl1AVlZNVDkdLkn3b_VxY96ENwcm99&index=14)
1.  [Hangout - Ethereum PoS: Casper FFG In Depth](https://www.youtube.com/watch?v=uQ3IqLDf-oo) and the
    [presentation](https://docs.google.com/presentation/d/1fqnjL-2TqXjhHx8k7HRX7eUYnDK83adnlCLLH8Bk054/edit#slide=id.g2758035b7d_0_0)
1.  [Hangout - Ethereum PoS: Casper & Smart Contract Consensus Overview](https://www.youtube.com/watch?v=MyDocEQfBGA) and the [presentation deck](https://docs.google.com/presentation/d/1MTb9myfNIQzjMs6QdW2NrtmtzeCexEAiLUpLJZJRKoU/edit#slide=id.g35f391192_00)

### Cryptoeconomics

1.  [Game Theory in Bitcoin](https://www.youtube.com/watch?v=_VANRj3WpdY) Game Theory approach behind the motivation for Bitcoin mining
1.  [CESC2017 - Cryptoeconomics in Casper](https://youtu.be/5ScY7ruD_eg)
1.  [What is Cryptoeconomics](https://www.youtube.com/watch?v=9lw3s7iGUXQ) Vlad Zamfir introducing Cryptoeconomics
1.  [Introduction to Cryptoeconomics](https://www.youtube.com/watch?v=pKqdjaH1dRo) Vitalik Buterin introducing Cryptoeconomics. The corresponding presentation deck is [available here](https://edcon.io/ppt/one/Vitalik%20Buterin_Introduction%20to%20Cryptoeconomics_EDCON.pdf)
1.  [Hard problems in Cryptoeconomics](https://www.youtube.com/watch?v=p5qwbOkCZSc&t=2316s) Vitalik Buterin discussing hard problems with cryptoeconomics
1.  [The Cryptoeconomic way](https://www.youtube.com/watch?v=ZH9nMKIHfAE) Vitalik Buterin discussing cryptoeconomics.
1.  [Cryptoeconomic Protocols In the Context of Wider Society](https://www.youtube.com/watch?v=S47iWiKKvLA) Vitalik Buterin discussing cryptoeconomics. The corresponding presentation deck is [available here](https://www.slideshare.net/ethereum/vitalik-buterin-cryptoeconomic-protocols-in-the-context-of-wider-society)
1.  [The current state of Cryptoeconomics](https://www.youtube.com/watch?v=u6VSPD5TrP4) The current state of Cryptoeconomics by Vlad Zamfir
1.  [Programmable Incentives](https://youtu.be/Yo9o5nDTAAQ?t=5h4m44s) by Karl Floersch at Devcon 3
1.  [Hard problems in cryptoeconomics](https://www.youtube.com/watch?v=p5qwbOkCZSc) by Vitalik Buterin
1.  [Cryptoeconomic Primitives](https://www.youtube.com/watch?v=Mxt-SdfXEKw&t=1598s)
1.  [Global Scale Research Networks and Cryptoeconomics](https://www.youtube.com/watch?v=G9Bp56y3X8U)
1.  [Towards a Practice of Token Engineering](https://www.youtube.com/watch?v=Zf-WlBl1dAA) by Trent McConaghy
1.  [Cryptoeconomic Theory](https://medium.com/@viktorwrites/cryptoeconomic-theory-table-of-contents-311fcf30bc2b) an on-going series by Viktor Makarskyy with [part 1](https://medium.com/blockchannel/cryptoeconomic-theory-basics-of-social-order-2be4c1be89c1), [part 2](https://medium.com/blockchannel/cryptoeconomic-theory-markets-vs-planning-85a76bb2c038), [part 3](https://medium.com/blockchannel/cryptoeconomic-theory-pareto-efficiency-89d34664f9d) and [part 4](https://medium.com/blockchannel/cryptoeconomic-theory-game-theory-basics-fb3a49aab1a8)

### State Channels

1.  [The Raiden Network, a technical introduction](https://www.youtube.com/watch?v=aMs0wAFIu7I)
1.  [Short introduction to the The Raiden Network](https://www.youtube.com/watch?v=JuVP4iDVkoQ) by Lefteris Karapetsas
1.  [State Channels explained in detail](https://www.youtube.com/watch?v=MEL50CVOcH4) by Ameen Soleimani

### Cryptoeconomic Security

1.  [The costs of hacking Bitcoin](https://www.youtube.com/watch?v=qxGqozl6kj4) Sybil attacks explained
1.  [Game theory and Network Attacks- How to destroy Bitcoin](https://www.youtube.com/watch?v=TZcfQtBXthc) by by Max Fang 03/2017
1.  [Game theory and Network Attacks- How to destroy Bitcoin](https://youtu.be/Y_dBl-iLeMc) by Nadir Akhtar and Aparna Krishnan 11/2017
1.  [51% Attacks: Pools and Game Theory](https://www.youtube.com/watch?v=LN6Yhm0TMAM)
1.  [Nothing at stake](https://www.youtube.com/watch?v=pzIl3vmEytY) Introducing the nothing at stake attack
1.  [Security Considerations of the Casper Protocol](https://www.youtube.com/watch?v=bPQfWTizYpg) Vlad Zamfir at Standford's Blockchain Protocol Analysis and Security Engineering 2017

### Cryptography

1.  [Cryptography for Cryptocurrency](https://www.youtube.com/watch?v=Fyqtl7eGQZY)
1.  [Bitcoin - Cryptographic hash functions](https://www.youtube.com/watch?v=0WiTaBI82Mc)
1.  [Hashed based signatures](https://blog.cryptographyengineering.com/2018/04/07/hash-based-signatures-an-illustrated-primer/) An illustrated primer

### Additional

1.  [BBC Documentary](https://www.youtube.com/watch?v=y97Ywl7RtUw) Adam Curtis' "Fuck you buddy" BBC documentary

## Podcasts

1.  [Q&A on Casper](https://etherreview.info/the-ether-review-2-vlad-zamfir-28f95afc8a3c) Vlad Zamfir answering questions regarding Ethereum's Casper PoS
1.  [PoW attacks](https://letstalkbitcoin.com/blog/post/epicenter-bitcoin-68-kamikaze-attack-block-halving-and-the-perils-of-proof-of-work) Podcast from 2015 on PoW attacks
1.  [Cryptoeconomics, Stablecoins, Casper](https://softwareengineeringdaily.com/2017/10/28/cryptoeconomics-with-vlad-zamfir/) with Vlad Zamfir, and corresponding transcript is available [here](https://softwareengineeringdaily.com/wp-content/uploads/2017/10/SED449-Vlad-Zamfir.pdf)
1.  [Fintech Podcast - Episode 151](https://www.youtube.com/watch?v=CZr6vOwi2Jw) Cryptoeconomics as explained by Dr Chris Berg
1.  [Cryptoeconomic Primitives](https://soundcloud.com/rhys-lindmark/25-trent-mcconaghy-ocean-protocol-cryptoeconomic-primitives-humanitys-future-plan) by Trent McConaghy

## Whitepapers

1.  [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)
1.  [Ethereum Whitepaper](https://github.com/ethereum/wiki/wiki/White-Paper)
1.  [Blockchain Consensus Protocols in the Wild](https://arxiv.org/pdf/1707.01873.pdf)
1.  [dBFT Whitepaper](https://allquantor.at/blockchainbib/pdf/vukolic2015quest.pdf) The Quest for Scalable Blockchain Fabric: Proof-of-Work vs. BFT Replication by IBM Research
1.  [Federated Byzantine Agreements](https://www.stellar.org/papers/stellar-consensus-protocol.pdf) by Stellar Development Foundation's David Mazieres
1.  [Research Paper on PoS vs. Pow](http://bitfury.com/content/5-white-papers-research/pos-vs-pow-1.0.2.pdf) by Bitfury
1.  [Demystifying Incentives in the Consensus Computer](https://eprint.iacr.org/2015/702.pdf)
1.  [Game Theory approach behind Bitcoin mining](http://ledger.pitt.edu/ojs/index.php/ledger/article/view/96/67)
1.  [Research Paper on the security model in PoW](https://eprint.iacr.org/2016/555.pdf) by ETH Zurich and others
1.  [A Note on Limits on Incentive Compatibility and Griefing Factors](http://vitalik.ca/files/extortion_griefing_bounds.pdf)
1.  [Research Paper on eclipse attacks](https://eprint.iacr.org/2015/263.pdf) on the Bitcoin Network
1.  [Research Paper on eclipse attacks](http://www.cs.bu.edu/~goldbe/projects/eclipseEth.pdf) on the Ethereum Network
1.  [Research paper on hashrate-based double spend attack](https://arxiv.org/pdf/1402.2009v1.pdf)
1.  [Satoshi Risk Tables](https://arxiv.org/pdf/1702.04421.pdf)
1.  [MakerDAO Purple Paper](http://stablecoin.technology/purple.pdf)
1.  [Sweetbridge Liquidity Protocol](https://blog.sweetbridge.com/sweetbridge-liquidity-protocol-mathematical-specifications-whitepaper-884df39ae854)
1.  [Bancor Protocol](https://about.bancor.network/static/bancor_protocol_whitepaper_en.pdf)
1.  [Maker Dai Stablecoin](https://medium.com/@MakerDAO/introducing-the-new-whitepaper-for-the-dai-stablecoin-system-e7c6caabcfc4)
1.  [Curation Markets](https://docs.google.com/document/d/1VNkBjjGhcZUV9CyC0ccWYbqeOoVKT2maqX0rK3yXB20) by Simon de la Rouviere
1.  [The Economics of BitCoin Price Formation](https://arxiv.org/ftp/arxiv/papers/1405/1405.4498.pdf) This paper analyses the relationship between BitCoin price and supply-demand fundamentals of Bitcoin
1.  [A Cost of Production Model for Bitcoin](http://www.economicpolicyresearch.org/econ/2015/NSSR_WP_052015.pdf)
1.  [The Bitcoin Backbone Protocol Analysis and Applications](https://eprint.iacr.org/2014/765)
1.  [Cryptocurrencies without PoW](https://arxiv.org/pdf/1406.5694.pdf)
1.  [Some Simple Economics of the Blockchain](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2874598)

## Books

1. [Game Theory - A Graphic Guide](https://www.amazon.co.uk/Introducing-Game-Theory-Graphic-Guide-ebook/dp/B01J4P6L90/ref=sr_1_1?ie=UTF8&qid=1552306185&sr=8-1&keywords=game+theory+a+graphic+guide)
## Other Resources

1.  [Casper PoS Discourse](http://ethereumresearch.trydiscourse.com/c/casper) Ethereum Foundation's Discourse channel on Casper
1.  [Evolution of Trust](http://ncase.me/trust/) Fun interactive game by Nicky Case showing the evolution of group trust over time
1.  [Formal verification on Casper](https://medium.com/@pirapira/formal-methods-on-some-pos-stuff-e309775c2ab8) Formal verification on Casper
1.  [Ethresear.ch Casper research topic](https://ethresear.ch/c/casper)
1.  [CECS - CryptoEconomics Security Conference](https://cesc.io)
1.  [Reddit subgroup](https://www.reddit.com/r/cryptoeconomics/)
1.  [Telegram Group](https://t.me/cryptoeconomics)
1.  [RIAT - Institute for Future Cryptoeconomics](https://riat.at/Cryptoeconomics/) a research group from Austria
1.  [Cryptoeconomics Asia](https://cryptoeconomics.asia) is an independent research firm
1.  [Cryptoeconomics at RMIT University](http://cryptoeconomics.com.au) a research group of economists in Australia
1.  [Research Institute for Cryptoeconomics](https://www.wu.ac.at/en/cryptoeconomics/) Vienna University of Economics and Business
1.  [MIT Cryptoeconomics Lab](https://ce.mit.edu) MIT's first cryptoeconomics lab

## Blockchain Hacks and Post-mortems

### The DAO

1.  [The DAO can turn into a naturally arising Ponzi](http://hackingdistributed.com/2016/06/13/the-dao-can-turn-into-a-naturally-arising-ponzi/) prescient article by Hacking Distributed
1.  [Analysis of the DAO Exploit](http://hackingdistributed.com/2016/06/18/analysis-of-the-dao-exploit/) by Hacking Distributed
1.  [Thoughts on the DAO hack](http://hackingdistributed.com/2016/06/17/thoughts-on-the-dao-hack/) by Hacking Distributed

### Parity MultiSig

1.  [Parity's Post-mortem](https://blog.ethcore.io/the-multi-sig-hack-a-postmortem/)
1.  [Deep dive into the Parity hack](http://hackingdistributed.com/2017/07/22/deep-dive-parity-bug/)

### King of Ether

1.  [King of Ether Post-mortem](http://www.kingoftheether.com/postmortem.html)

# Additional information and related topics

## Behavioural Economics

1.  [BE Ted Talk](https://www.ted.com/talks/dan_ariely_on_our_buggy_moral_code) Prof. Dan Ariely's Ted Talk on Behavioural Economics

### Related Ideas

1.  Wikipedia: [Groupthink](https://en.wikipedia.org/wiki/Groupthink)
1.  [Sunk Cost Fallacy](https://youarenotsosmart.com/2011/03/25/the-sunk-cost-fallacy/)

## Related Lists

1.  [Awesome Economics](https://github.com/antontarasenko/awesome-economics)
1.  [Awesome Cryptography](https://github.com/sobolevn/awesome-cryptography)
1.  [Awesome DeFi](https://github.com/RichHorrocks/awesome-decentralized-finance)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Joaquim Pedro Antunes](https://github.com/jpantunes) has waived all copyright and related or neighbouring rights to this work.
