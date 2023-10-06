---
title: "The Layers of Decentralization: Understanding the Accumulation of Power in the Staking Economy"
publishDate: "2022-03-23T16:39:36.050Z"
image: "https://hbr.org/resources/images/article_assets/2019/08/Sep19_03_1153768857.jpg"
author: "Chainflow"
tags: [blockchain]
---

## Centralization Threatens the Staking Economy

Decentralization takes many forms. This is true in the broader crypto/Web3 world, and especially so in the growing Proof-of-Stake (or, simply, “staking”) economy.

Plenty of people in the staking economy talk the talk of decentralization, but it’s clear, when you look beneath the surface, that far fewer actually walk the walk. Various forces are causing Proof-of-Stake networks to centralize into top heavy oligarchies, but participants don’t seem to notice. Why?

Big-money interests are engaging in a kind of “decentralization theater” in order to deflect attention away from their accumulation of power in the staking economy. Instead of a crypto revolution, we’re staring down centralization by another name.

There’s a disconnect here—one that threatens everything we’re working toward in Web3. In order to address it, and preserve the promise of the staking economy, we need a shared movement to recognize and better understand centralization on Proof-of-Stake networks.

This piece takes a step forward in that movement by defining a simple framework that we can use to identify—and, ultimately, address—the sources of centralization across the staking economy.

## The Layers of Decentralization

Rather than thinking of the different forms of decentralization in the staking economy as separate things, we can understand them as the connected layers of a “decentralization stack.”

Those layers include the following:

- **Infrastructure layer**
- Technical Sub-Layer
- Operator Sub-Layer
- **Capital Layer**
- Owner Sub-Layer
- Consolidation Sub-Layer
- Custodian Sub-Layer

The **Infrastructure Layer** is the foundation of the staking economy; it defines where and how a Proof-of-Stake network runs. On top of the Infrastructure Layer is the **Capital Layer,** which defines the capital required to make the network run.

For a network to be truly decentralized, it must be decentralized at both the Infrastructure Layer and the capital Layer. Infrastructure needs to be diverse enough to provide security and resilience, and Capital must be distributed among enough entities to ensure that a small number of them can’t collude, or be coerced, to censor or otherwise manipulate the network.

We need to understand these layers and the mechanics at work within them in order to identify the threats posed by different centralization vectors. All of these vectors pose risks, but some represent a more urgent threat than others. We’ll see shortly that, while infrastructure represents the foundation of any network, it’s Capital that captures the real power.

## Infrastructure, the Foundation

On a Proof-of-Stake network, a layer of validator infrastructure makes the network run and secures it. That infrastructure layer is complex, and we’ll break it down into the following sub-layers:

- **Infrastructure layer**
- Technical Sub-Layer
- Operator Sub-Layer

The **Technical Sub-Layer** defines the client software, physical servers, data centers, and networks that comprise the chain’s validator infrastructure. The **Operator Sub-Layer** defines who operates the validators themselves.

(For simplicity’s sake, let’s assume that the same entity runs collectively the servers, data centers, and networks. In this way, the Technical Sub-Layer can be used as a proxy for cloud service providers, such as AWS and GCP. In reality, this can also be broken down further, but that’s beyond the scope of this piece.)

The centralization vectors across these sub-layers may not be readily apparent—but, to see them, just follow the money.

The Technical Sub-Layer generates revenue by providing server, data center, and network services to validator operators. As a result, it’s not uncommon for any one provider of such services to sell these services to many different customers from the Operator Sub-Layer.

You can see where this is going: the same server (in the case of virtualization) and/or data center may house multiple validator operators; and many operators may ride the same network connections, both from the data center to the network backbone and within the network backbone itself. In this way, heavy infrastructure deployments on market-leading cloud providers are a major vector for Infrastructure Sub-Layer centralization.

The Operator Sub-Layer, on the other hand, generates revenue by providing staking services to capital owners (whom we’ll get to in the next section). These operators may work on behalf of their own capital, and they may also sell staking services to third-party capital owners. Operators in the latter case are commonly referred to as “staking-as-a-service” (StAAS) providers.

These mechanics are rarely clear to the average user. Block explorers—the window through which most participants view a network’s validator set—typically display only the capital owner behind a validator. In some instances they don’t even do that, displaying only a crypto address as the validator identifier.

This lack of insight masks the centralization that happens at both the Technical and Operator Sub-Layers. (This makes it all the more refreshing to see a project like [validators.app,](https://www.validators.app/) an example of the Solana network community increasing Infrastructure Layer transparency.)

A StAAS company’s typical customer is a large, and usually institutional, capital owner. In pursuing these customers, StAAS businesses operate according to the typical high-growth, VC-funded playbook: they raise large rounds of funding at huge valuations—some achieving the dubious “unicorn” status of being valued at greater than $1 billion—and chase growth to both justify and raise their valuations even higher.

To fuel this growth, StAAS companies must capture as much market share as possible, by selling staking services to as many capital owners as possible. These growth motives lead to further centralization.

In a perfectly decentralized Infrastructure Layer, stake would be equally distributed across providers at both the Technical and Operator Sub-Layers. In practice, however, the mechanics above cause stake to centralize among a very small number of very large infrastructure providers and validator operators.

Troubling as it may be, centralization in the Infrastructure Layer is often overlooked because most staking network analyses focus on the Capital Layer. But, as we’ll see in the next section, we must indeed be concerned about the centralization of capital.

## King Capital

Like the Infrastructure Layer of the staking economy, the Capital Layer is complex. In this framework, we’ll break it down into three sub-layers:

- **Capital Layer**
- Owner Sub-Layer
- Consolidation Sub-Layer
- Custodian Sub-Layer

The **Owner Sub-Layer** defines the individual to whom capital, in the form of network tokens, ultimately belongs. The **Consolidation Sub-Layer** defines the groups—like institutions, funds, and exchanges—that control and consolidate capital from different capital Owners. The **Custodian Sub-Layer** defines the third parties that hold capital on behalf of many different Owners and Consolidators.

Owners, Consolidators, and Custodians deploy capital, in the form of stake, to validator infrastructure to run and secure Proof-of-Stake networks. How, exactly, does that work?

Validators need to hold a minimum amount of staked capital to operate in the network’s mainnet set of active validators (sometimes referred to in shorthand as “the active set”). Thus, it’s the combination of capital and infrastructure that makes a Proof-of-Stake network run.

In this way, capital is intrinsically linked to power: more capital equates to more power, and vice versa. There is a direct correlation between the amount of capital a network participant holds, and the power they have to censor the network, stop it, and vote to influence its future direction.

Put simply: capital is king, whether we like it or not. Without decentralizing capital, true decentralization can’t exist.

As in the legacy economy, capital in the staking economy begets further capital. Validators on a Proof-of-Stake network earn returns, in the form of more capital, as a reward for securing the network. That return is proportional to the amount of capital that’s already staked to the validator. As such, capital compounds early and fast. So too does the power of the capital holder. Many justify this using the [“skin in the game”](https://chainflow.io/the-skin-in-the-game-staking-paradox/) argument, while brushing off the [“rich get richer”](https://chainflow.io/rich-getting-richer-in-proof-of-stake-chains/) problem.

In a perfectly decentralized Capital Layer, capital would be spread evenly across a wide range of individual capital Owners. These individual capital Owners would then stake their capital evenly to a spread of validator operators. This even distribution would create an equitable balance of power across the network infrastructure and within its governance process.

In practice, however, capital is increasingly accumulated by Consolidators, like institutions, and held by Custodians, like centralized exchanges. This causes large amounts of capital to centralize at each of the capital layer’s three sub-layers.

This further compounds centralization on the Infrastructure Layer since Consolidators and Custodians often deploy their capital to one of a few large infrastructure providers and/or operators. In some instances, an institution (owner), an exchange (consolidator), and a custodian may even be operated collectively by the same entity.

It’s worth noting that the capital which gets deployed onto Proof-of-Stake networks is often accumulated within the legacy economy before being deployed to staking networks. This creates a bridge of privilege into the Web3 world that only those with accumulated privilege can afford to cross.

These mechanics enable Consolidators and Custodians—especially institutions, funds, and exchanges—to accumulate considerable, and often outsized, control of the networks on which they hold large stakes. Their deployment to a small number of infrastructure providers and validator operators further increases infrastructure centralization, causing the networks, and ultimately the staking economy, to become more fragile.

## Seeing the Truth behind Decentralization Theater

We’ve seen that centralization can occur at different points throughout both the Infrastructure and Capital Layers. But, where do we find the biggest threats to the staking economy?

Without capital, nothing else matters. Without capital, validators have nothing to do and a network simply won’t run. This means that points of capital accumulation and consolidation within the Capital Layer are ultimately the most powerful and dangerous vectors for centralization.

Not far behind, however, are third-party centralized infrastructure providers, like large StAAS companies. They actively work to accumulate as much capital as possible on their infrastructure, and this behavior causes them to operate as a primary centralizing force within the networks they operate on.

This is compounded by the fact that they’re pursuing the high-tech, VC-funded, Silicon Valley business models that require unlimited growth to justify huge fund-raising rounds. The business plans these providers follow are orthogonal to the true values of decentralization.

When asked (albeit rarely) about whether they’re centralization vectors, these large, third-party infrastructure providers often fall back to “decentralization theater”—the art of supporting decentralization while actually causing centralization.

A common example is that companies will claim to “decentralize themselves” by not running all of their systems on, say, AWS. From a technical perspective, that’s helpful if true. But, like much of decentralization theater, the reality may differ from the message. Exchanges, for instance, run almost 33% of Eth2 validators today, and deploy sometimes thousands of validators using a single Eth2 client implementation.

Regardless, these explanations don’t address—at all—the fact that capital still accumulates with these large, centralized companies. And remember, it’s the capital accumulation that really matters. Because capital holds the power, the efforts these large StAAS providers make to attract as much capital as possible more than cancel out any benefit we might feel from their efforts to decentralize their infrastructure.

Consider a common argument among larger operators: that they can’t control how much stake they attract. While this may be true technically, there are many steps they can take socially—like actively discouraging new stake while redirecting it to smaller operators.

Some StAAS providers claim to make staking more accessible. In reality, the prices these providers charge make staking more accessible only to the large capital holders who can afford it—rather than the individual token holders who can truly help to decentralize staking networks.

In the end, all of these arguments are smokescreens; they’re intended to deflect from the centralizing influence these providers have on the staking economy, and protect the business models that require them to operate this way. This type of behavior is decentralization theater in its truest sense: decentralization is reduced to nothing more than a platitude.

It’s only with a nuanced understanding of the layers of decentralization that we can work together to counter these centralizing forces. If we don’t, the staking economy will be no different from the legacy economy and the power structure it enables—controlled by a small number of wealthy stakeholders with an outsized influence.

In fact, due to the rapidly compounding economics of staking networks, the staking economy could end up being controlled by an even smaller number of even wealthier stakeholders. And if that’s all the results from the Web3 movement, then what’s the point of this crypto revolution anyway?

_Special thanks to Mario Laul [(@mlphresearch)](https://twitter.com/mlphresearch) for feedback throughout the development of this piece, and to Lucas Griffin [(@GriffinLucas)](https://twitter.com/GriffinLucas) for editing._

_For more resources and discussions around the forces shaping Web3 and the staking economy, follow Chainflow on Twitter [(@ChainflowPOS)](https://twitter.com/chainflowpos) or join us on Telegram [(t.me/chainflowpos).](https://t.me/chainflowpos)_
