---
title: "Initial Findings from Our Open-Source Wallet and Onboarding Research"
excerpt: "Chainflow has supported Solana since the earliest testnets. In addition to running our high-performance validator, we've led a number of efforts over the years to help make Solana more secure, accessible, and decentralized."
publishDate: "2023-03-16T16:39:36.050Z"
image: "https://images.unsplash.com/photo-1669060475309-33f02dc5404a?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1032&q=80"
author: "Chainflow"
tags: [blockchain]
---

## Intro

Chainflow has supported Solana since the earliest testnets. In addition to running our high-performance validator, we've led a number of efforts over the years to help make Solana more secure, accessible, and decentralized.

To highlight a handful, we've:

- Helped design [the original Tour De Sol,](https://twitter.com/ChainflowPOS/status/1166698951543853057) an incentivized testnet program which helped build the foundation for the healthy ecosystem of validators securing the network today.
- Supported independent validator operators with resources like [Solana Validator Mission Control.](https://chainflow.io/introducing-solana-mission-control/)
- Explored decentralization on the network with tools like [Nakaflow,](https://nakaflow.io/) our cross-chain Nakamoto Coefficient tracker.
- Sponsored the [Decentralized Infra track](https://twitter.com/ChainflowPOS/status/1621629142226665478?s=20) at this year's inaugural Sandstorm hackathon to support innovation in the network's infrastructure.
- Co-organized the [validator community postmortem](https://twitter.com/ChainflowPOS/status/1632733337826521098?s=20) following last month's upgrade issue.

Now, we'd like to share an update from one of our current ongoing efforts: an initiative to support Solana's next generation by leading research into open-source wallets and onboarding experiences.

## Background

In early 2022, we approached the Solana Foundation to explore how we could help to improve support for open-source hardware wallets on Solana. While these discussions started with a specific focus on hardware, they led to a broader question: How could we ensure that the Solana community has access to an ecosystem of feature-rich, user-friendly, rock-solid, and open-source wallets? The Solana Foundation provided us with a grant to lead a formal research project to investigate further.

In the spirit of open-source—and with the hope that the teams bringing new participants to Solana, and crypto more broadly, can make use of our work—we're excited to share our initial findings from the project.

## Research Focus

The focus of this research is to better understand the common features in crypto onboarding experiences, and deliver insights for opportunities for the Solana ecosystem to become a leader in those features’ accessibility, effectiveness, and embrace of open-source principles.

## Project Design

We’re taking an iterative approach to this research, starting first with a wide focus on onboarding experiences and core tooling, such as wallets and exchanges); conducting exploratory research; and using our findings to progressively narrow our focus and conclusions with each phase of the project.

This update synthesizes the results of "Phase 1," our initial body of work.

## Phase 1 Interests

In this first phase of our research, we pursued two primary interests:

1. Understanding the “lay of the land” in the Solana wallet ecosystem
2. Learning more about users’ firsthand onboarding experiences when interacting with crypto / blockchain technology

In doing so, we explored a range of wallet and participant types. Wallets included closed- and open-source products, and interview participants varied from crypto skeptics with no direct involvement in blockchains to crypto-curious individuals who eventually ended up working in the space.

## Phase 1 Exercises

To begin this research, we conducted two exploratory exercises:

1. **Wallet Ecosystem Scan:** A comparative review of crypto wallets—including popular Solana wallets like Phantom and Solflare—with a focus on the “new user” flow. 2.** Onboarding Interviews:** A series of interviews with individuals of different backgrounds, with a focus on these users’ experiences of “being onboarded” into crypto.

We were looking to better understand users’ motivations and psychology when engaging with crypto, and the experiences they had when coming into the space. For those who chose not to onboard, we wanted to explore the barriers to entry they experienced, and to better understand what conditions needed to be true for them to possibly re-engage with crypto.

We honed in on various emotional responses, as well as reasonings on why certain subjects performed the actions that they did to better understand their motivations.

## Major Insights

Our initial research produced two major insights:

1. **Technical and user-experience hurdles make it difficult for individuals to onboard to crypto.**

While the selection and setup of a wallet serves as the standard feature in the general crypto onboarding process, the “new user” experience across leading wallets is inconsistent and often calls for a depth of understanding that a new user is unlikely to possess. In response, individuals must turn to trusted sources or available media for assistance, both in mastering crypto’s tools and forming their understanding of crypto’s use cases.

1. **Common tools, like wallets, have standardized features, such as widgets that visualize crypto’s price relationship to fiat currency, that emphasize the most speculative aspects of crypto.**

Given that a user’s chosen tools represent a kind of de facto “trusted source,” the experience of a new user learning these tools reinforces the notion that crypto has primarily speculative use cases. When “the number goes down,” users are more likely to disengage from crypto.

## Supporting Findings

We formed these Major Insights on the back of nine supporting findings from this phase of our research. These findings reflect three themes:

1. Motivations to Onboard
2. Hurdles of the Onboarding Experience
3. Tensions in the Onboarding Experience

## Motivations to Onboard

**Finding 1: It’s common for new participants to rely on a close personal contact with more crypto experience for onboarding.**

One of the most common themes in these initial interviews is the importance of having an experienced crypto user provide hands-on education, support, and training while a new user is onboarding into the crypto ecosystem. We can consider these helpful, more experienced users as something like “Super Onboarders.”

**Finding 2: Available tooling and onboarding resources emphasize the speculative aspects of crypto, reinforcing the sense of crypto as a money game and tying usage incentives to financial success.**

It’s common for new users to onboard to crypto with a financial motivation in mind. Accordingly, when the speculative nature of tokens is performing well (i.e. “the number goes up”), users report being more engaged; when that speculative nature is performing poorly, users report disengaging. Wallets encourage this behavior by emphasizing the speculative nature of crypto (e.g. displaying asset prices in fiat, prioritizing financial widgets like trend lines) and de-emphasizing its other applications (e.g. NFTS, POAPs, browsing dApps).

## Hurdles of the Onboarding Experience

**Finding 3: Current onboarding experiences leave opportunities for catastrophe that intimidate new users.**

While one of the appeals to new users of exploring crypto is the freedom of self-custody, the lack of any kind of recoverability or general safety creates opportunities for catastrophe (e.g. sending tokens to the wrong address, losing your passphrase) that discourage new users.

**Finding 4: Vocabulary and literacy represent significant hurdles for new users.**

As a cutting-edge technology, crypto is overrun with jargon that confuses new users. Without user-friendly glossaries developed for the specific context of a given protocol, wallet, etc., new users are forced to rely on third-party sources of unclear reliability to understand their way around the crypto space.

**Finding 5: Current onboarding experiences provide little in the way of training or sandboxing, leaving users to fend for themselves.**

The typical flows for new users on exchanges and wallets introduce, with little hand holding or context, the full capabilities of crypto. In the absence of low- or no-risk tutorials or sandbox environments where users can comfortably explore feature sets, new users are left to practice using crypto with real-world stakes.

## Tensions in the Onboarding Experience

**Finding 6: Transparency isn’t often top of mind for new users, but trustworthiness is.**

New users, particularly those from non-technical backgrounds, don’t often prioritize features like auditability and open-source when evaluating crypto tools like wallets; rather, they prioritize convenience, stability, and trustworthiness. These features are commonly assessed based upon their proximity to apparently trustworthy sources (e.g. respectable-looking media outlets, close personal contacts) and a critical mass of usage (i.e. “It’s the one most people use”).

**Finding 7: New users seek trustworthy educational resources, but must draw their own conclusions in the absence of comprehensive materials from official sources.**

The glut of scattered crypto content (all of, to a beginner, unclear quality) creates a hurdle for new users to separate signal from noise when seeking trustworthy educational resources. This poses a significant barrier to entry for new users without the help of a “Super Onboarder.” Many users do, however, place an implicit trust in “official” materials from Protocol Foundations and projects.

**Finding 8: There’s a tension between the anti-establishment orientation of crypto, and the need for established and trustworthy resources.**

An observation in conversation with Finding 6 above: while part of the appeal of crypto is its status as a less-regulated frontier in finance and technology, new users still want to be assured that they can trust the tools and resources they use to participate in the space.

**Finding 9: Crypto demands the adoption of new behaviors, which lack well-established norms.**

Crypto introduces a number of unintuitive new concepts (e.g. passphrases, addresses, bridging) that demand the creation of new behaviors (e.g. de-risking the storage of your passphrase); however, typical onboarding experiences leave it up to a new user to parse these behaviors for themselves.

## Initial Recommendation

The Sui ecosystem can create a more sustainable pathway to onboarding and retaining new users by becoming a leader in what we might call “open-source social onboarding”: a standardized, user-centered, and well-socialized onboarding process that includes tooling and educational resources specifically designed to reinforce a relationship with crypto that expands beyond speculation.

## Next Steps

Our findings in Phase 1 point in a compelling direction: crypto calls for a comprehensive, standardized, and well-socialized onboarding experience. We believe that this onboarding experience can reflect a more imaginative and user-centered approach to using blockchains—and that the Solana ecosystem has a unique opportunity to define the key features of that experience.

For our next steps, we're continuing our research, with a focus articulating the opportunity space for the Solana ecosystem to innovate open-source social onboarding.

As part of this next phase of the project, we'll be exploring key areas of the open-source social onboarding opportunity space, including:

- **Onboarding modalities,** such as in-person experiences and digital practice environments.
- **Open source documentation and user experience elements,** such as collaborative, industry-standard user flows and best practices.
- **Personalized New User flows and user experience options**: Such as use case-defined user interface assets.

## Let's Connect

We won't be tackling these next steps alone: We're interested in connecting with the developers, designers, and community managers working to innovate social onboarding for crypto.

Are you working on a wallet, a dApp, or another project that's helping to onboard new users to Solana? We'd love to learn more about your work. Please get in touch at research@chainflow.io.

_This research is made possible in part by a grant from the Solana Foundation. **Want to support our work on Solana? Please consider** [delegating to us.](https://chainflow.io/chainflow-staking-systems/#solana) We sincerely appreciate each delegation, no matter how big or how small._

_Special thanks to **Frank Chen** and **Luke Griffin** for leading this phase of the project, and to **each of our interviewees** for their generous participation._
