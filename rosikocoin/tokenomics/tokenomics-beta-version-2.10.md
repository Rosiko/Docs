---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

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

Raydium LP Token: [7uxDGXhMYyG3CW3jK1vRtzZtsf6ToQUtWKGAxEKA4HxA](https://solscan.io/account/7uxDGXhMYyG3CW3jK1vRtzZtsf6ToQUtWKGAxEKA4HxA)

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

Our [roadmap ](../roadmap/)includes leveraging NFTs to automate certain aspects of token distribution and rewards. While we’re currently self-financing and still in development, here’s what we’re planning:

1. **DEVS Collection** :man\_technologist::woman\_technologist::\
   A limited collection (estimated 10-20 NFTs) will be privately gifted to our developers. Each NFT and its transaction will be documented for complete transparency. \
   Holding these NFTs represents a form of ongoing “payment” or reward for the developers who helped turn our ideas into code.\

2.  **Supporters’ Collection** :medal::\
    Another collection will be listed on our NFT marketplace. Purchasing these NFTs grants the owner the right to receive RSK airdrops—potentially on a monthly schedule and possibly lasting up to 10 years (details under discussion). \
    If an NFT changes hands, the new owner inherits the right to future airdrops. \
    We may also provide in-game benefits linked to these NFTs as our gaming ecosystem develops.\


    _Please note that we plan a separate NFT collection on SolSea to help fund the project, but it won’t be part of the airdrop system described above._\

3. **Fans’ Edition** :angel::\
   We’re considering a larger “drop edition” with a high number of identical NFTs, each tied to a third smart contract. We’re currently debating whether the reward should be periodic RSK airdrops (smaller than those from the supporters’ collection) or in-game benefits related to the upcoming game. \
   This edition will be widely available so anyone can mint an NFT with associated perks until the supply is exhausted.

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
