---
title: "How Large Stake Accounts Shape the Solana Validator Set"
publishDate: "2023-04-23T16:39:36.050Z"
image: "https://preview.redd.it/e8vdvqx39xg91.png?width=1080&format=png&auto=webp&v=enabled&s=663387087e8e3a074b71e612353e1e0b906a06cd"
author: "Chainflow"
tags: [blockchain]
---

## Intro

Chainflow has supported Solana from the early days. We helped design [Tour De Sol](https://twitter.com/ChainflowPOS/status/1166698951543853057?ref=chainflow.io)—the original testnet program that set the foundation for the healthy ecosystem of validators securing the network today—and have run a [high-performing Solana validator](https://www.validators.app/validators/2mMGsb5uy1Q4Dvezr8HK2E8SJoChcb2X7b61tJPaVHHd?locale=en&%3Bnetwork=mainnet&ref=chainflow.io) ourselves ever since. As a result, we were able to attract about 3 million staked SOL in the months after the launch of mainnet beta.

We've remained an active supporter of the network, leading initiatives like:

- Building [Solana Validator Mission Control](https://chainflow.io/introducing-solana-mission-control/) , an open-source toolkit for independent validator operators
- Launching [Nakaflow.io](https://nakaflow.io/?ref=chainflow.io), an open-source Nakamoto Coefficient aggregator that has been cited in reports by the Solana Foundation and other researchers
- Sponsoring the [Decentralized Infra track](https://twitter.com/ChainflowPOS/status/1621629142226665478?s=20&ref=chainflow.io) at this year's inaugural Sandstorm hackathon
- Co-organizing the network's new [independent validator community calls](https://twitter.com/ChainflowPOS/status/1640715446411497472?ref=chainflow.io)

Over time, however, we've lost about 90% of our staked SOL. The vast majority of this loss happened when a few large stake accounts delegated away from us. While we still have around 2900 delegators, each of whom we feel sincerely grateful for, the impact of the loss of these large stake accounts has been significant.

It's tough to speculate on why owners of these large stake accounts, a/k/a whales, move stake—one assured us that we did nothing wrong to merit their un-delegation, for example—but this experience left us wondering:

> How many other highly-staked validators are similarly dependent on a small number of stake accounts?

> So, we decided to take a closer look. Below, we present our high-level findings, as well as a path to gaining new insight into increasing Solana's Nakamoto Coefficient.

## Heavy Reliance on Heavy Bags

We looked at stake distribution by stake account across the 50 highest staked validators, which together account for roughly 40% of all staked SOL. Our initial research illustrates that many of the 50 highest staked validators also rely heavily on a small number of stake accounts.

### Percentage of Stake Held by Top Two Delegators

First we looked at the percentage of stake held by a validator's top two delegators. Here's what we found:

Some interesting things stand out:

- 7 of the 50 validators (14%) rely on 2 delegators for 99%+ of their stake (not show in graph). Unsurprisingly these are all "anonymous" validators.
- 11 of the 50 validators (22%) rely on 2 delegators for 90%+ of their stake. Unsurprisingly these are all "anonymous" validators.
- 19 of the 50 validators (38%) rely on 2 delegators for 80%+ of their stake. This is a mix of named and "anonymous" validators.
- 26 of the 50 validators (52%) rely on 2 delegators for 50%+ of their stake. This is a mix of named and "anonymous" validators.

### Percentage of Stake Held by Top Five Delegators

Then we expanded the analysis to the top five biggest stake accounts for each validator. Here's what we found:

The trends continue here as well:

- 18 of the 50 validators (36%) rely on 5 delegators for 99%+ of their stake (not shown in graph). Unsurprisingly these are, again, all "anonymous" validators.
- 25 of the 50 validators (50%) rely on 5 delegators for 90%+ of their stake. This is a mix of named and "anonymous" validators.
- 29 of the of the 50 validators (58%) rely on delegators for 80%+ of their stake. This is a mix of named and "anonymous" validators.
- 36 of the 50 validators (72%) rely on 5 delegators for 50%+ of their stake. This is a mix of named and "anonymous" validators.

## Whales Crown Kings

It's pretty clear from this analysis that whales with big bags heavily influence what the validator set looks like. In many ways, these delegators act as the validator king makers.

Though these whales are largely anonymous, to the extent their identities are known, they're likely most-known to the larger validator businesses, staking as a service providers, and other institutional-focused entities that receive their stake. They may or may not be known to the smaller independent validator operators, however.

## The Impact on and Value of Smaller, Independent Validator Operators

This creates a concerning imbalance of power, as smaller, independent validators are likely much more dependent than larger staking companies on whales, yet have less visibility into the whales' intentions.

And for independent validators like Chainflow, losing a few key stake accounts can be the difference between a running sustainable validator and a break-even or even money losing operation.

We feel that a healthy validator set must include smaller, independent operators. It's these operators who often punch above their weight and make outsized contributions relative to their size.

If you agree and want to see them continue to exist within the Solana validator set, it's important to support their work by staking to them.

## Diving Deeper

We'd like to continue diving deeper here. For example, it would be interesting to investigate the relationships among the king-making whales.

Discovering commonalities among operators, particularly among the "anonymous" validators that rely heavily on five or fewer stake accounts, would be interesting as well.

Even more interesting would be understanding the incentives that validators may be offering to their large stake account delegators. From our experience in the space, it's not unheard of for validators, if not even common, for validators to offer special terms to delegators with large stake accounts.

Given how much of a reliance there is on small number of whales, this isn't terribly surprising. (For our part, Chainflow never offers such deals to anyone; we treat all delegators equally, no matter how big or how small their delegation may be.)

We plan to dive deeper into these areas in subsequent posts.

## What about Solana's Nakamoto Coefficent?

Solana's Nakamoto Coefficient is usually near the top among the networks we track at [Nakaflow.io](https://nakaflow.io/?ref=chainflow.io), hovering typically in the 30-32 range. As shown by our friends (and [winners](https://twitter.com/ChainflowPOS/status/1621629142226665478?s=20&ref=chainflow.io) of our Decentralized Infra track at this year's Sandstorm Hackathon) Solana Compass, it seems to have plateaued there for a while now:

Source: [Solana Compass Decentralization Dashboard](https://solanacompass.com/statistics/decentralization?ref=chainflow.io) as of April 16th, 2023. 

It would seem, even from this cursory analysis, that shifting a few stake accounts around could push this number even higher. We plan to run a few scenarios and present them in future posts.

## Conclusion

Our research suggests that a small number of large stake accounts heavily influence Solana's validator set, with a small number of big-ticket delegators accounting for a significant portion of the stake held by some of the largest-staked validators.

This leaves independent validators particularly vulnerable: If a whale decides to move their stake elsewhere,  a smaller validator operator can transition quickly from a sustainable and profitable operation to a money losing and unsustainable one. Given this vulnerability, continued support of these validators is particularly important.

This isn't to say that our findings are entirely grim. Whales may have the power to concentrate their stake with a small set of larger validators, but they also have the power to distribute their stake more equitably across the broader validator set.

A few moves by some of the larger stake account holders could help to increase Solana's Nakamoto Coefficient. We also hope that by bringing awareness to the fragility of the smaller independent validators staying power, delegators will support them with a renewed enthusiasm.

While this analysis answers some initial questions, it raises many others. We look forward to digging deeper and presenting additional findings in future posts.

_P.S - If you'd like to support our work as an independent Solana validator, please consider [delegating to us.](https://chainflow.io/chainflow-staking-systems/#solana)_

_We appreciate all delegations, no matter how small or big. All delegators are created equally in our eyes, and we don't cut backroom deals with larger stakeholders._



