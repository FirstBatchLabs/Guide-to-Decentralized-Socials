# Essential Guide to Decentralized Social on Chains & Rollups

# Introduction

To date, the inspiration and motivation behind the scaling of L1/L2 chains have largely been rooted in DeFi’s desire to improve the speed and efficiency of transactions on Ethereum. As the ecosystem grows, we move away from a winner-takes-all narrative and closer to a reality where Dapps build out across multiple specialized blockchains, each tailored to a particular category of applications. While DeFi inspired the first wave of L1/L2 scaling and development, we see a great opportunity for Social Apps to move the ball further with a fresh set of challenges and the promise of bringing the next billion users to web3.

Web3 socials offer users key benefits over traditional web2 networks. The first is decentralization. Web3 socials are built on networks that are not controlled by any single entity or organization, which allows for greater user control and privacy and makes it much more difficult for governments or other organizations to censor or shut down the platform. The second is Data Ownership. In a Web3 social, users own their own data and also have the ability to monetize it through various token economies that incentivize users to contribute to the network. 

In web2 social networks, the platform is incentivized to maximize revenue and user engagement, but often at the expense of the user and their privacy. In web3 social networks, the platform and the user are incentivized to act in the best interest of the network, leading to a more positive user experience. Finally, decentralized social networks are can interact with other decentralized apps and services, creating a more open and interconnected ecosystem.

As web3 expands, users will continue to have experiences in both web2 and web3 social ecosystems. However, the one area where web3 socials are not yet able to compete with web2 is Personalization. Web3 socials have improved technical functionalities, but lack the depth of data and users necessary to provide the same level of personalization that web2 can. The reality is that web2 socials have an enormous head start in the data economy of personalization that web3 socials will spend an eternity trying to catch up with if they are not able to improve UX interoperability. The future of social apps lies in this opportunity to meet users where they are and marry the benefits of decentralized networks with the data economies of web2 in the form of decentralized personalization. 

In this research, we will examine the progress made so far in Social App development across several L1/L2 chains and how each one addresses the unique needs of Social Apps. To build and scale great social apps, chains should have robust storage and indexing capabilities, immutability, Sybil and censorship resistance, and a high degree of privacy and security for user data. With the promise of an interweb/ multi-chain future for users, interoperable data and ID management are a must. While we still have a long way to go, we will analyze what’s working so far and what are the potential elements necessary to build and scale a great social ecosystem in web3.

# How to Build Social Stacks

In order to build a decentralized social media platform, there are many components that need to come together in order to create a complete experience for the end users. 

- Most fundamentally, there needs to be a **storage** solution to store the data related to users, content, and everything else in the app.
- Then there are **indexing** tools for managing and querying the data;
    - **graphs** which bring the underlying relationship between the users, topics, and other content to the app while detecting their positions accordingly;
    - **gating** tools to control who can access certain parts of the platform;
    - **********************************direct messaging********************************** tools that add private communication capabilities to the app;
    - **personalization** tools for optimizing users’ experience based on their interests;
    - and finally, **search** tools that allow users to easily find content.

## Storage

Using a decentralized storage solution is important for decentralized social platforms because using centralized services will give the service power over the app. While storing data on general-purpose chains is usually too costly and slow for a well-functioning social app with a large user base, decentralized storage solutions differ by their payment models, consensus algorithms and many other features, the table below gives a good overview of the four major players:

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled.png)

## Social Graphs

Social graphs represent the users’ relationship with each other by using data such as follower/friend/connection status, interactions, and shared communities. These graphs capture a crucial part of the users’ identities by positioning them on the graph. Two of the major decentralized social graph providers are [Lens Protocol](http://lens.xyz) and [CyberConnect](http://cyberconnect.me). 

Lens offers a non-custodial social media experience by letting users own their IDs (lens handles) and content. Currently, there are 14 social media apps that are built with Lens and many more tools for events, music, DAOs, etc. Their most popular app, Phaver has announced that they have [over 100k active users](https://cointelegraph.com/press-releases/phaver-the-largest-app-on-lens-protocol-hits-100k-active-users). 

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%201.png)

CyberConnnect also provides a decentralized social graph and self-sovereign identity solutions where every user owns their [ccProfile](https://cyberconnect.me/mint) as an NFT. The most popular apps in the Cyberconnect ecosystem are Link3 and Galxe, former is a web3 event platform and the latter is one of the major decentralized identity and verifiable credential protocols.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%202.png)

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%203.png)

## Indexing

Indexing is crucial for decentralized applications because the on-chain data is not meaningful by itself and just represents a list of transactions and balances, yet bringing off-chain and possibly private data only adds to this problem. Indexing solutions such as [The Graph](https://thegraph.com/en/), Covalent, Goldsky, Transpose, and Zettablock help solve these problems.

## Direct Messaging

Direct messaging is important for providing users the direct interaction that they got used to in web2, but the obvious challenge is the transparency of the on-chain interactions - you can store a public comment directly on-chain but direct messages need to be encrypted in some way. [XMPT](https://xmtp.org/) is a protocol that allows building direct messaging capabilities in your app with their SDK. [Dialect](https://www.dialect.to/) and [Status](https://status.im/) are decentralized messaging applications that enable wallet-to-wallet communication, while [Ghost](https://ghost.message) is building an app that focuses on anonymous messaging in group chats.

## Personalization

Personalization is one of the most important aspects of a social app and it creates the difference between a boring feed and an entertaining one. In web2 applications, personalization methods are advanced but the experience is limited to platforms and the user data is often used without the users’ consent. FirstBatch is working on making personalization privacy-preserving and interoperable.

## Search

Search functionality is at the heart of content-driven apps and we mostly take it for granted, but in web3 applications, it’s not rare to come across social apps that have poor search experiences (or no search bar at all). Sepana is tackling this problem, currently, they have an in-app search option for [Diamond](https://cloutavista.com/), [Lens](https://lens.sepana.io/), and [Mirror](https://askmirror.xyz/).

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%204.png)

## Gating

Token-Gating is a method that is used for only allowing people who have certain tokens in their wallet to specific parts of an app, such as communities or event registration pages. One of Lit Protocol’s most important offerings is decentralized access control which covers many gating options including token gating.

## Social Media Platforms

Currently, there are a number of live decentralized social apps that use one or more tools mentioned above. 

- **Lenster**: Decentralized social web app built with Lens, it has avsimple UI with popular, for you, trending, and interesting tabs.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%205.png)

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%206.png)

- **Phaver:** Share to earn app built with Lens. Right now it can be accessed via whitelisting. Phaver gives users 5 tokens every day that can be used to stake on posts to gain more tokens when they get more popular.
- **************Desofy:************** Mobile social media app built with DeSo
- ******************Diamond:****************** Twitter-like social web app built with DeSo.
    
    ![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%207.png)
    
- ********Yup******** is a text/image focused social media platform that aggregates posts from Lens and Farcaster

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%208.png)

- ********Galxe:******** Infrastructure for community members to curate and contribute digital credentials to Galxe data network.
- ****************gm.xyz:**************** Community-based social app similar to Reddit with reputation systems, monetization, and token-gating features.
- **********Orbis:********** Set of social data models combined with a decentralized infrastructure. SDK and flexible modules allow devs to build composable, social experiences.
- **********Link3:********** Provides a wallet address-based persona composed of verifiable credentials that allow users to connect with events, social communities, investment opportunities, airdrops, or DAO communities in the CyberConnect ecosystem.
    
    ![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%209.png)
    
- ****************Connect3:**************** Built on top of NEAR protocol, Connect3 provides users with a Social profile with identity management, content showcasing, and social interactions.

# Ethereum L1

While Ethereum has the largest developer community and user base across any chain. There are a few setbacks that make it hard for building social apps on the Ethereum L1, with high gas fees being the most major one. Because social apps have a high volume of data transfers, it’s important to be able to transfer data fast and in a cheap way. No one wants to wait for a “like” to be processed for 10 mins. One solution for that is keeping most of the data off-chain, such as likes and reposts while keeping more important actions posted on-chain. Farcaster is an example of this, having a ****************************sufficiently decentralized**************************** network they keep the high-frequency interaction data off-chain and only keep what is necessary on-chain. Another solution is making use of L2s to be able to keep more of these data on-chain while still keeping the platform fast and cheap.

The chart below shows the portion of social projects in ETHGlobal hackathon submissions. Being one of the most popular verticals among the participants, social applications have vast potential. 

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2010.png)

## CyberConnect

CyberConnect is a social graph protocol that aims to create an interoperable ecosystem of social apps. The main idea is for users to be able to use, or at least be able to move, the same ID and profiles across different platforms by connecting all of the relevant data of the ecosystem dapps in a public database.

<aside>

**Total Users:** 1.49 Million

**Total Connections:** 22.22 Million

**API Calls:** 204 Million

([Sep 2022 Data](https://mirror.xyz/cyberlab.eth/kScgXyJhnhZJLat5HO9yxJH4pOKjO5YaMHf844Zr4Kk))

</aside>

### Link3

Link3 is the flagship app of the CyberConnect ecosystem. It is mostly used for creating and sharing web3 events, doing raffles/giveaways, and analytics. 

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2011.png)

There is also a profiles feature that allows users to display their social links, web3 profiles, professional experiences, and more. The aim of this is to make Link3 a go-to platform for exploring web3 profiles without juggling between wallet explorers like Etherscan and web2 platforms like Twitter or LinkedIn.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2012.png)

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2013.png)

## Attic

Attic is a web3 social built for NFT communities. There is no additional ID or community creation needed, as every NFT automatically has a community and every wallet is an ID for the platform. Still, the community features and the user profiles can be customized to make each of them unique.

Attic is still in the beta phase and is only open to Early Access NFT holders.

## Metalink

Metalink is an NFT-focused community interactions platform that works similarly to Discord. It has announcement boards, push notifications, a portfolio tracker, and more. By pulling Discord announcements from top collections and sending notifications for floor price changes, Metalink aims to create a one-stop solution for NFT collectors. 

<img src="Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2014.png" width="300">

<img src="Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2015.png" width="300">

<img src="Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2016.png" width="300">

## Monaco

MonacoNFT is a social platform similar to Twitter with additional sections such as NFT show and drama comics.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2017.png)

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2018.png)

## Intuition

- Ethereum has the most active user base among all chains which makes the adoption easier for social apps, they can just use their Ethereum wallet.
- High gas fees make it costly to put social interactions on chain because socials have too many interactions.
- Transaction speed is not fast enough for having social interactions on chain.

# Ethereum L2s (Arbitrum, Starkware, ZKsync, Optimism)

## Optimism & Arbitrum

With their advanced scalability solutions that combine the hassle-free environment some Ethereum alternatives have with the Ethereum security, L2s like Optimism and Arbitrum have been strong financially relative to the overall market. This also translates to actual usage, contract interactions and app ecosystems in both of the chains have been optimistic (no pun intended).

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2019.png)

The lower cost and higher scalability of L2s over Ethereum create an advantage for areas where frequent interactions are needed, such as gaming or socials.

While the NFT, DeFi, and other finance/investment-related sub-verticals are rich in the number of dapps, that is not the case for the social dapps. At the moment they don’t even have social as a category on their ecosystem pages.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2020.png)

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2021.png)

### gm.xyz

[gm.xyz](http://gm.xyz) is a decentralized social network supporting optimism that is similar to Reddit. It allows logging in with a wallet and builds an experience around communities, available through its web app and mobile app. By their decentralized approach, gm.xyz wants to:

1. Make the community/DAO creation and management tools easier to access and use.
2. Let content creators earn from their content online and give minimal amounts to the platform (around 1%-2%) as opposed to current socials that take up to 100% (such as Facebook or Reddit).
3. Take the power away from the social media giants and make it decentralized.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2022.png)

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2023.png)

## Intuition (Ethereum L2s)

- With EVM compatibility and the ease of bridging, L2 solutions have the advantage of the large developer community of EVM and easier access to the user base of Ethereum.
- They are superior to Ethereum in terms of speed and scalability.
- Rollups have Ethereum’s security.
- There are not many social apps built on L2s other than a few projects that migrated from Ethereum to Optimism or Arbitrum.

# Polygon

Polygon’s main mission is to scale the Ethereum ecosystem and is already home to some of the top social platforms and protocols in web3 such as Lens, Galaxe, and Yup. Polygon uses a network of sidechains and rollups to secure transactions on Ethereum, which allows it to be competitive on gas fees. This can be especially beneficial for dApps that need to process a large number of transactions like social dApps.  Overall, Polygon's fast transaction speeds, low fees, compatibility with Ethereum, and strong security make it an attractive platform for building decentralized applications.

Polygon ID is a decentralized, self-sovereign identity solution allowing fully private and verifiable on-chain verification using ZK-cryptography. Polygon ID addresses KYC requirements, while simultaneously allowing users to retain total privacy. Specific use cases include a decentralized credit score, DAO voting rights, and exclusive gaming guild access. 

Polygon uses a proof-of-stake consensus algorithm, which makes it secure and efficient. It also has a strong team of security experts working to ensure the safety and security of the network. Polygon’s current security strategy is focused on investments in ZK technology. This year alone, Polygon has [committed $1 billion](https://blog.polygon.technology/the-polygon-thesis-strategic-focus-on-zk-technology-as-the-next-major-chapter-for-polygon-1b-treasury-allocation/) and [raised $450 million](https://blog.polygon.technology/polygon-raises-450000000-from-sequoia-capital-india-softbank-galaxy-tiger-republic-capital/?utm_source=Twitter-Main&utm_medium=Tweet&utm_campaign=Polygon-Investment) to focus on multiple ZK-related scaling efforts resulting in astonishing output and rich opportunities for Dev collaboration. 

Zero-knowledge technology can help to scale Ethereum by allowing for more efficient and secure validation of transactions. In a traditional blockchain, all nodes in the network validate all transactions, which can be resource-intensive and slow down the network. With zero-knowledge technology, only a small number of nodes called "verifiers" are responsible for validating transactions, and they do so using zero-knowledge proofs. These proofs allow the verifiers to confirm the validity of a transaction without needing to know the specific details of the transaction. This can significantly improve the efficiency and scalability of the Ethereum network.

On July 7, 2022, Reddit launched an NFT avatar marketplace on Polygon. Users don’t need to have a crypto wallet to buy them - a credit or debit card works and they can use Reddit’s wallet product to store them. The social network said it is releasing 90 designs with the total amount of NFTs going for sale in this early-access phase being “tens of thousands.” The company noted that if you purchase one of its limited-edition NFTs, you will have licensing rights to use it on and off Reddit as an avatar.

Active addresses on Polygon increased for the second consecutive quarter and set an all-time high of nearly 6 million active addresses. New addresses spiked 180% QoQ primarily due to the launch of the Reddit NFT marketplace. Total unique addresses surpassed 170 million and are on track to surpass 200 million by the end of the year.

Source: [State of polygon report](https://messari.io/report/state-of-polygon-q3-2022?referrer=asset:polygon)

Reddit has joined a long list of companies that are experimenting with NFTs. After launching NFT support on Instagram, Facebook has recently ported [some of those features over to the blue app](https://techcrunch.com/2022/06/30/facebook-testing-nfts-select-creators-us/). After launching its [own digital art collection in May,](https://techcrunch.com/2022/05/23/ebay-launches-collection-nfts/) eBay acquired [NFT marketplace KnownOrigin in June](https://techcrunch.com/2022/06/22/ebay-acquires-nft-marketplace-knownorigin/). In May, Spotify started testing a feature that allowed some artists to [promote digital collectibles on their profiles](https://techcrunch.com/2022/05/16/spotify-new-feature-artists-promote-nfts/), and link-in-bio startup Linktree rolled out new features for creators like [unlockable links for specific NFT collection holders](https://techcrunch.com/2022/05/17/linktree-nfts/). 

Source: [Tech Crunch](https://techcrunch.com/2022/07/07/reddit-is-launching-a-new-nft-avatar-marketplace/)

Lens protocol dominates the Polygon social ecosystem with 100k+ profiles minted. The purpose of the Lens Protocol is to empower users to own the links between themselves and their community, forming a fully composable, decentralized social graph. This is achieved by allowing users to create profiles and interact with each other via these profiles. "Profile" refers specifically to Lens profiles, which can be used across the multitude of social apps built on top of the protocol. The top of Lens front end is Lenster, which is a browser-based social with features similar to Twitter. 

![Screen Shot 2023-01-06 at 09.20.22.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_09.20.22.png)

Intuition: 
- User migration due to bear market conditions and the aftermath of FTX collapse is a reoccurring pain point for all verticals of the web3 ecosystem.
- In December 2022, Lens Profile Addresses had the largest monthly percentage drop since launching at -76%.
- Given the current market conditions of web3 and the global markets at large, we can expect this sentiment to persist well into 2023.

![Screen Shot 2023-01-06 at 09.34.59.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_09.34.59.png)

![Screen Shot 2023-01-04 at 17.05.05.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-04_at_17.05.05.png)

- Despite downward trends in new user acquisition, we see steady increases in Dev and Active User activity coupled with significant investments into Polygon’s ZK infrastructure as promising predictors of long-term adoption and success than short-term reactions to down-market conditions.
- The composability of Lens profiles, emphasis on security and efficiency with ZK rollups, and its institutional relationship to DeFi protocol AAVE are promising web3 native features that are flexible and easily adaptable to future development and market changes.

# BNB Chain (Binance)

![Screen Shot 2023-01-06 at 10.40.41.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_10.40.41.png)

On the surface, the architectural design of BNB’s Smart chain seems to offer flexible features for developers of social applications. The main purpose of the BNB Sidechain is to allow any project developer to deploy their blockchain with customized specifications and validator sets. It will also enable them to be connected to the BNB Smart Chain infrastructure. 

The validator set can run with fewer validators than BNB Chain, depending on the BNB Sidechain deployer and their desired level of security. The social application owners or community stakeholders can run these validators and developers and teams can create blockchains with their own business rules and economies. This modular design and flexibility are beneficial attributes for the growth of social applications that often have dynamic and diverse functionalities such as voting and governance, financial primitives, gaming, and more. 

However, this validator set is determined daily by Binance Chain, a network managed by just 11 validators. BSC's active validator set resets daily based on each validator's voting power (staked BNB + any delegations). All BNB staking and delegation take place on Binance Chain through a staking module. Binance Chain validators manage this module, and in turn all BSC validator accounts. Left unchanged, the centralized nature of Binance Chain block validation does not seem to offer a high degree of censorship resistance. 

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2024.png)

![Screen Shot 2023-01-06 at 11.01.27.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_11.01.27.png)

![Screen Shot 2023-01-06 at 11.01.07.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_11.01.07.png)

Example Social: Hooked Social 

Hooked Protocol is a Web3 Gamified Social Learning Platform and the number one social dApp on BNB Chain. Hook looks to drive engagement by focusing on Learn & Earn products and eventually build onboarding infrastructures and dApps to help more businesses to on-ramp onto web3, forming an ecosystem of community-owned economics.

Aside from Learn & Earn mechanisms, the main features of Hooked include a free-to-use app plus incentives, a ready-to-use in-app wallet, SBT to build Web3 identity, and the opportunity to turn in-game Gold into real-life currency. 

Hooked Protocol launched its first pilot dApp, Wild Cash, in October 2022 which was met with impressively high user engagement. Within one week of launch, Wild Cash locked in over 200k active users. Wild Cash is a gamified learning experience where users can:

- Enter the Training Camp where they “quiz to earn”. Users answer questions about crypto, blockchains, DeFi, NFTs, legal regulations, and more to win the native token Gold.
- Enter daily quizzes and compete against other players to earn bigger prizes.
- Log in every 24 hours and get rewarded for doing it regularly.
- Refer friends and create your own teams to earn Gold.
- “Mine” Gold by literally tapping a button to move an animated avatar and their pickaxe. This is a metaphor for mining BTC and (kind of) shows how Proof-of-Work functions.
- Watch ads to win Gold.
- Bet & Win. This feature shows that blockchain technology can be used for gambling.
- Stake, earn a yield on, and withdraw Gold tokens.
- “Mint” NFTs within the game. For this, users can spend Gold to get an upgraded pickaxe or mining cart. Both of these items help players earn more Gold.

![Screen Shot 2023-01-06 at 11.27.32.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_11.27.32.png)

![Screen Shot 2023-01-06 at 12.00.48.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_12.00.48.png)

![Screen Shot 2023-01-06 at 12.00.09.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_12.00.09.png)

Intuition: 

- BNB Chain benefits from the wealth of users on Binance and has huge network effects.
- BNB’s narrative and focus on onboarding web2 users through rewards, education, and gamification seems to have positive traction with users.
- The modular design of BNB Side Chains can be beneficial for the dynamic needs of social apps, but the centralized nature of its validator set is concerning censorship resistance and independence from Binance.
- Binance is also often a target for regulatory compliance and may impact total network usage + BNB price in 2023 onward
- Hooked protocol mainly incentivizes users with financial rewards, whose valuation is closely bound to market sentiments.
- While financial primitives seem to dominate the web3 space, users may begin to eschew such rewards as artificial and inauthentic.
- Tools and strategies for building communities of new users in web3 that do not involve financial primitives might be a better vehicle for sustained long-term growth.
- Finally, Hooked Protocol’s In-app wallet is not interoperable, and users will need to manage multiple wallets to have interactions outside of the BNB chain ecosystem.

# DeSo

DeSo is a custom-built layer-1 blockchain to scale decentralized social applications. It is also the underlying blockchain for applications such as Bitclout and Diamond. Every person that joins the DeSo network gets a portable DeSo identity and benefits from a portable social graph, which allows users to bring their profile, followers, content, and funds with them across DeSo ecosystem apps.  DeSo stores all of its data on a public blockchain, which means that anyone can run a node that exposes their own curated feed in a permissionless way. Social tokens, social NFTs, and social tipping are products also offered by DeSo. 

Diamond, a decentralized Twitter alternative, has blogging functionality and several money-native features creators can use to build, scale and monetize their audience such as social tokens and social tipping. Diamond has also integrated the DeSo wallet, which supports both a one-click Google login and a one-click MetaMask login, making it easy to bring on board users within Ethereum and mainstream users. Users can also deposit USDC from MetaMask onto DeSo apps and receive a DeSo-native stablecoin called DesoDollar. Once onboarded with USDC, all stablecoin transactions become virtually gasless, costing less than one ten-thousandth of a cent.

Intuition:
- DeSo ticks many boxes and has a clear vision for disrupting web2 socials. -The portability of a user’s social graph, Metamask ID, and USDC across DeSo social apps is a promising infrastructure for adoptability.
- Having all app activity on one chain with a composable identity is beneficial for dev teams looking to build on DeSo as the data is publicly available, and easy to label and index.
- However, the performance of DeSo interoperability beyond ETH users will be something to monitor.
- Given their development thesis, we can also not expect much interoperability or cooperation with web2 platforms.
- The narrative of DeSo is a winner takes all social chain, outperforming all other chains and claiming the lion’s share of social development in web3.
- Whether or not this is feasible will depend on developer activity, of which there is not currently publicly available data.

# Solana

Dev activity is one metric to analyze growth, and Solana hackathons have shown consistent growth through the Bear Market. Solana’s network usage has also remained relatively stable. Despite this activity, Solana does not yet have a proliferation of social apps with the exception of Orbis.

Orbis Protocol is a set of decentralized social data models, SDK, and flexible modules that can be used to build fully composable, social experiences. Orbis content is stored on the decentralized data network Ceramic. In Orbis, the user’s decentralized identity (profile) is the only entity able to create, update or delete content from their social graph. 

![Screen Shot 2023-01-06 at 13.27.18.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_13.27.18.png)

![Screen Shot 2023-01-06 at 14.45.07.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_14.45.07.png)

![Screen Shot 2023-01-06 at 14.46.57.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_14.46.57.png)

![Screen Shot 2023-01-06 at 14.47.38.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_14.47.38.png)

However, Solana Mobile Stack (SMS) stands to capitalize on some of the frustrations of web2 app developers. Marketplace fees on Web2 app stores range from 10–30%. Considering these app stores are economies worth hundreds of billions of dollars, that’s billions in value siphoned away from devs towards Apple or Google. Solana potentially offering a 0% take rate decentralized app store is a considerable business advantage that could incentivize developers to at least give the SMS a try.

For consumers, initial UX improvements on Solana Saga include native, secure private key storage, native support for Solana Pay, the decentralized app store, and more. These early UX improvements may be catered to a crypto-native audience, but we could see future improvements targeted toward a wider range of users. 

![Screen Shot 2023-01-06 at 14.50.08.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-06_at_14.50.08.png)

Intuition: Solana is shrouded in mystery and its believers often point to three key factors that will determine its success: 

- Heavy investment from web3 whales and institutional investors
- Consistent growth in its developer community/hackathons 
- Mass adoption of SMS (Solana Mobile Stack)

Whether or not these features will translate into mass adoption and social app development is yet to be seen. 

# Arweave

Arweave is different from the other chains on this list because it’s not an L1 blockchain. Arweave is built on blockweave technology, which is a fully decentralized network similar to a blockchain. By paying a one-time fee up-front, you get permanent storage on Arweave, which is much more scalable and cost-efficient than storing data on a blockchain. Here are Arweave data storage fees for reference:

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2025.png)

Arweave is also called a ********Layer 0******** because it’s able to store L1 on-chain data efficiently. A major example of that is Solana. With a much higher number of blocks produced than many of the other L1s combined, Solana needed a better way of storing transaction data. This is where Arweave comes into play: only transactions in the last two days are stored on the Solana nodes, and the rest is stored in Arweave. This shows the scalability and storage cost efficiency of Arweave in action (both are crucial for social applications) and also means that the transaction data of any social platform built on Solana is actually stored on Arweave.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2026.png)

Being a data-storage-focused network, Arweave is a great storage option for social platforms even if they are building on another chain. For example, despite being built on Polygon, Lens Protocol and its flagship social app Lenster uses Arweave for data storage.

Active projects: Permafacts, Metaweave, decent.land, Mirror, Lens

- Low fees for data storage that is efficient for storing content.
- Permanent storage of content/interactions creating censorship resistance and a better experience.
- The community of the chain is not as large as EVM-compatible chains

# Near

NEAR’s blockchain can be used to run smart contracts, but it also has compatibility with the Ethereum Virtual Machine (EVM) to allow Ethereum developers to easily port over applications through the Aurora network. 

![Screen Shot 2023-01-10 at 14.08.16.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-10_at_14.08.16.png)

To scale, instead of sharding the main chain into individual blockchains, Near’s NightShade works by sharding individual blocks. Each shard produces its own batch of data, called a “chunk”, which is then organized into a block by a lead validator. Each block contains all the chunk headers, which are metadata that include information about the content of the chunk: the full list of that shards transactions. This approach reduces the space that shards take up in each block. In this way, communication about individual shard transactions is also propagated throughout the entire blockchain. 

This allows the chain to parallelize processing, storage, and network propagation. From a user and developer point of view, NEAR looks and feels like one chain for processing, instead of multiple independent chains like Cosmos or Polkadot. NEAR just recently expanded from one to four shards this past December. This system upgrade required zero network downtime, and no changes were needed from its developers or users. 

NEAR has built the public key as human-readable addresses, similar to what ENS built for Ethereum, but free. This public key doesn’t have to be associated with one master private key, it can be associated with multiple private keys that have varying levels of permission. They can be permissioned to only interact with certain contracts, spend only a certain amount, be used for only a certain period of time, etc. 

source: *[Nightshade Whitepaper](https://near.org/papers/nightshade/)*

Example Social:
Sweatcoin 

![Screen Shot 2023-01-10 at 14.17.40.png](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Screen_Shot_2023-01-10_at_14.17.40.png)

Sweat Economy has registered over 3.5 million active users, and 15 million unique wallets, ranked as the most used application across crypto, ranked as the top finance application in 51 countries, and amassed over 100 million SWEAT staked. It was also the No. 1 Health & Fitness app globally for 2022. 

Source: [Messari State of Near Q3 2022](https://messari.io/report/state-of-near-q3-2022)

Intuition:
- The launch of Sweat Economy was a positive development bringing more users on-chain and lifting community sentiment despite the bear market.
- This proves that NEAR has a great capacity for scaling apps and connecting web2 users with web3. NEAR has raised over $1 billion to accelerate the development of the NEAR protocol ecosystem, however, further development of social apps is yet to be seen.

# Cosmos

Cosmos is an ecosystem of interconnected blockchains that ensure interoperability through their inter-blockchain communication (IBC) protocol. Instead of deploying smart contracts on a general-purpose blockchain, developers can create application-specific blockchains that are designed for their use case and interconnected to the wider cosmos ecosystem.

By designing their own application chain, social apps may implement new solutions that are not possible or simply too costly in other chains. For example, **Bitsong** is combining the functionality of an NFT marketplace and a streaming service to create a unified music experience.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2027.png)

## Desmos

Desmos is an open-source project that is being built on Cosmos that wants to democratize social media and remove the intermediary from the online advertisement market.

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2028.png)

![Untitled](Essential%20Guide%20to%20Decentralized%20Social%20on%20Chains%20%2053a3b5d2d06f43f9a3ea9635b47d0083/Untitled%2029.png)

## Intuition

Even though its application chain approach is suitable for creating social applications, there have been very few projects to actually try and built a social platform on Cosmos.

# Other Chains

While all chains are working towards similar goals of decentralization, scalability, and security, there are a few chains where social app development is not yet significant or is not the primary focus for the ecosystem. Some Ethereum L2s are examples of this, neither Starknet nor zksync host any remarkable attempts at building a decentralized social.

For Mina, the priorities are security through ZK proofs for transaction verification and scalability through a lightweight, fixed-size blockchain of around 11kB. Mina’s zkApps can privately interact with any website and access verified off-chain data for use on-chain, and there is currently work being done to establish a bridge between Mina and Ethereum. The promise of security through a ZK Mina ID and interoperability between on-chain/off-chain data and multichain capabilities makes Mina a promising ecosystem for social app development. However, Mina’s Dapp ecosystem development is premature for now, and there aren’t significant examples yet of what can be built. 

Despite the lack of development of social platforms so far, Tezos has promised to evolve into a chain with lots of social growth. Tezos is unique in its ability to have forkless upgradeability and self-amending functionality which allows a network to continually evolve. Also, native Tezos ID and flexible API indexer tooling through DipDup allow for some degree of data interoperability that would be beneficial for developing social platforms.

The main focus of Avalanche has traditionally been DeFi applications, although it is now transitioning into NFT and GameFi ecosystems. Advancements in elastic subnet development that include subnet asset transfers show promising signs for scalability. At present, Avalanche does not publicly share its development roadmap, so it is yet to be seen if social apps are a part of its long-term strategy.  

On Polkadot, despite having a few social apps in the works, there are currently no social platforms that are live and fully functioning. Considering the scalability and high developer activity of the network, Polkadot might start building the social ecosystem in the near future if it becomes a priority.
