# 💎 Tokenomics (Beta Version 2.10)

Below is an overview of RSK’s evolving tokenomics. Please note that these details are subject to change as development progresses.

Ongoing discussions among the development team may refine specific roles, distributions, and payment models.

## **Revised Token Distribution (Preliminary Estimates)**

<table><thead><tr><th width="296">Category</th><th>Tokens</th><th>Percentage</th></tr></thead><tbody><tr><td>Total Supply</td><td>250,000,000</td><td>100%</td></tr><tr><td>Game</td><td>38,000,000</td><td>15.2%</td></tr><tr><td>LP Raydium (projection)</td><td>25,000,000</td><td>10.0%</td></tr><tr><td>LP Jupiter (projection)</td><td>25,000,000</td><td>10.0%</td></tr><tr><td>LP Crypto.com (projection)</td><td>25,000,000</td><td>10.0%</td></tr><tr><td>Farm Rewards (projection)</td><td>20,000,000</td><td>8.0%</td></tr><tr><td>Smart Contract (projection)</td><td>20,000,000</td><td>8.0%</td></tr><tr><td>Smart Contract NFT (projection)</td><td>10,000,000</td><td>4.0%</td></tr><tr><td>Burn (projection)</td><td>10,000,000</td><td>4.0%</td></tr><tr><td>Future Projects (projection)</td><td>51,575,000</td><td>20.63%</td></tr><tr><td>Airdrop (projection)</td><td>5,000,000</td><td>2.0%</td></tr></tbody></table>

### Graphical view

{% embed url="https://datawrapper.dwcdn.net/Hhf3Y/2/" %}

## **Contract Information / Technical Information**

* **Contract Address:** `Ckz7u6p9L5DD1Qf162ChMoCNfJKphEBnMYdc8jmxxWG5`
* **Explorer Link:** [View on Solscan.io](https://solscan.io/token/Ckz7u6p9L5DD1Qf162ChMoCNfJKphEBnMYdc8jmxxWG5)

**Current Supply:** 249,995,838 RSK\
**Creator’s Current Holdings:**  164,849,109.41 RSK

Raydium LP Token: [Ht7AZjYq87HRFTZhNpdC8ypqNFbujWpMK9n6477UU7pa](https://solscan.io/token/Ht7AZjYq87HRFTZhNpdC8ypqNFbujWpMK9n6477UU7pa)

## **Game Integration**

We are passionate about developing a game that integrates RSK, but we can’t handle all coding and development tasks alone. We’re currently evaluating potential third-party developers for skill, capacity, and reliability. While external teams may handle core development, our role will be to review the process at key milestones, ensuring the end product meets quality standards and community expectations.

To facilitate in-game transactions, we’ve allocated 38,000,000 RSK (about 15% of the total supply) to a dedicated game wallet. The breakdown is as follows:

* **Game Allocation Address:** `J1aPr6bn9PSJsRjnSniwrn8Cyub8gVGNZaUjGsYdS7Gt` (38,000,000 RSK allocated)\
  &#xNAN;_&#x4E;ote:_ The underlying wallet is `HK5792kDm56BUE2u5p8FM3JBwFzmfRJmbRt385xMSbNf`

Over time, additional tokens from the authority wallet may be transferred here, potentially bringing this address’s holdings to around 35%-40% of the total supply. _Currently, this makes it the second-largest holder after the creator’s wallet (remember LP Token Burn program)_.&#x20;

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**However, as the project progresses — through the establishment of new liquidity pools (DEX at first) and other distribution activities as  smart contracts — the creator’s wallet is intended to approach near-zero holdings, eventually retaining only a few thousand RSK.** This gradual transition reflects our commitment to a more balanced and community-driven token distribution.
{% endhint %}



## NFT & SmartContract



RosikoCoin leverages **NFTs integrated with smart contracts** to automate token distributions and offer exclusive benefits to developers, supporters, and fans of the project. Here's an overview of the planned collections (see [Roadmap](../roadmap/roadmap-beta-version-2.10.md)):

### 🛠️ **DEVS Collection** :man\_technologist::woman\_technologist:

Exclusive NFTs privately assigned to core developers.

* Each NFT will be linked to a smart contract that enables RSK payments.
* Payments may be delivered monthly or annually to the wallet holding the NFT.
* These NFTs will be manually distributed as a form of ongoing compensation and recognition for development contributions.
* All transactions will be publicly documented to ensure full transparency.

### :star: **Supporters’ Collection**

NFTs available for public purchase, enabling periodic RSK airdrops.

* Holders will receive **monthly RSK airdrops** directly to the wallet associated with the NFT.
* These NFTs will be available on **RSKSEA** (our upcoming NFT marketplace) or on other compatible platforms.
* **Ownership is transferable**: if an NFT is sold, the new owner inherits the right to future airdrops.
* We may also link **in-game perks** to these NFTs as the RosikoCoin gaming ecosystem evolves.

_Please note that we plan a separate NFT collection on SolSea to help fund the project, but it won’t be part of the airdrop system described above._\


### :sunflower: **Fans’ Edition**

A larger, widely accessible collection for community engagement.

* Features a **high number of identical NFTs**, available to mint or purchase until supply runs out.
* Rewards will be **smaller compared to the Supporters’ Collection**, but may include:\
  — **Micro RSK airdrops** (under evaluation)\
  — **In-game benefits** (e.g. special items, early access)
* We're still debating the most effective reward model (token-based, utility-based, or hybrid).
* The goal is to keep it **accessible to everyone**, while still offering meaningful incentives for project supporters.

## BURN

Discussion about implementing token burn strategies is ongoing within the dev team. We will provide more information once decisions are finalized.

### LP Burn (Liquidity Pool Token Burn)

#### **Definition:**

An **LP Burn** refers to the intentional and permanent destruction of a portion of Liquidity Provider (LP) tokens by sending them to an **irrecoverable wallet address** (commonly called a “dead address”). This action effectively locks the corresponding share of liquidity **forever** in the pool, making it **impossible to withdraw** by anyone — including the project team or liquidity providers.

#### **Use in the RSK Project:**

When liquidity is added to a trading pair such as **RSK/USDC**, the provider receives LP tokens representing their share of the pool. Burning these tokens means **voluntarily giving up any right to withdraw that portion of the funds**.\
In RosikoCoin’s case, the team has opted to conduct LP Burns to **demonstrate a strong commitment to long-term liquidity and market stability**, signaling to users that the project has **no intention of pulling liquidity**. This enhances **trust and credibility**.

#### **Why it matters:**

* 🔒 **Permanently locks a portion of liquidity in the pool**
* 💎 **Signals transparency and trustworthiness**
* ❌ **Ensures the team can’t withdraw the burned liquidity**
* 📊 **Supports a more stable and sustainable market**

#### **Considerations:**

While LP Burns are appreciated by the community as a transparency measure, they must be executed thoughtfully, as they **permanently reduce the team’s flexibility** in managing the liquidity. When **publicly announced and backed by verifiable transactions**, LP Burns become a **powerful symbol of commitment** and decentralization — especially in early-stage or community-driven projects.
