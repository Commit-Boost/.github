# Commit-Boost

**THE CODE IN THIS REPOSITORY IS CURRENTLY NOT AUDITED OR READY FOR PRODUCTION**

## What Is Commit-Boost:

Due to the risks developing for Ethereum, core development, and its validators set, a group of teams / individuals are working on developing a public good called Commit-Boost. Commit-Boost is an open-source public good that is fully compatible with MEV-Boost, but acts as a light-weight validator platform to safely make commitments. Specifically, Commit-Boost is a new Ethereum validator sidecar focused on standardizing the last mile of communication between validators and third-party protocols. It's being developed in Rust from scratch, and has been designed with safety and modularity at its core, with the goal of not limiting the market downstream including stakeholders, flows, proposer commitments, enforcement mechanisms, etc.

## Why Build Commit-Boost: 

- Proposer commitments have been an important part of Ethereum’s history. Today, we already see the power of commitments where over 90% of validators give up their autonomy and make a wholesale commitment that outsources block building to a sophisticated actor called a block builder 
- However, most are starting to agree on a common denominator: in the future, beacon proposers will face a broader set of options of what they may “commit" to–be it inclusions lists or preconfs or other types of commitments such as long-dated blockspace futures–compared to just an external or local payload they see today
- A recent post from Barnabe captures this well; during block construction, the validator “…creates the specs, or the template, by which the resulting block must be created, and the builders engaged by the proposer are tasked with delivering the block according to its specifications”
While this all seems great, the challenge is that many teams building commitments are creating new sidecars driving fragmentation and risks for Ethereum
- For Ethereum, there are going to be significant challenges and increased risks during upgrades if there are a handful of sidecars that validators are running 
- For validators, these risks potentially take us to a world where proposers will need to make decisions on which teams to “bet on” and which sidecars they will need to run to participate in what those teams are offering
- For homestakers, this is difficult and they likely will be unable to participate in more than one of these commitments
- For sophisticated actors, this increases the attack vector and operational complexity as more and more sidecars are required to be run
- Another side effect of this is validators are somewhat locked into using a specific sidecar due to limited operational capacity and the switching costs of running a different sidecar (i.e., vendor lock-in). The higher the switching costs, the more embedded network effects could become if these sidecars only support certain downstream actors / proposer commitment protocols 
- This also could create a dynamic where core out-of-protocol infrastructure supporting Ethereum which should be a public good, starts being used for monetization, distribution, or other purposes
- Due to these dynamics, various teams and individuals across the community are driving the development and testing of open-source / public good software called Commit-Boost. This effort includes researchers, validators, builders, relays, client teams, consulting firms, protocols building commitments, L2s, restaking platforms, and countless others across the community

## Core Principles:

-	North Star: Would Vitalik run this and can we use this to improve decentralization
-	Mission: Not-for-profit, community driven, and an open-source, public good 
-	Product: Validator platform for proposers to safely make commitments
-	Neutrality: Proposer commitment agnostic, preconf agnostic, restaking agnostic, relay agnostic, transaction flow agnostic 
-	Unified: Validators run one core side car to opt into many different commitments 
-	Safety: Community reviews / audits, modularized, increased transparency–the focus is to reduce risk / overhead for the proposer to manage commitments

## How to Contribute:

-	Submit PRs or reach out to us on [Twitter]( https://x.com/Commit_Boost)

## Resources:

- EILI5, read more [here](https://twisty-wednesday-4be.notion.site/Commit-Boost-Reducing-Risks-and-Returning-Autonomy-Over-the-Block-Back-to-Ethereum-s-Validators-0f309f76058e447388381c60550ce67b)
- Orginally proposed on ETH Research, read more [here](https://ethresear.ch/t/based-proposer-commitments-ethereum-s-marketplace-for-proposer-commitments/19517)
- Second post on ETH Research, read more [here](https://ethresear.ch/t/commit-boost-proposer-platform-to-safely-make-commitments/20107)
- First presentation to the community can be found [here](https://www.youtube.com/watch?v=jrm4ZUoj9xY&list=PLJqWcTqh_zKHDFarAcF29QfdMlUpReZrR&index=11)
- Second presentation at zuBerlin can be found [here](https://streameth.org/zuberlin/watch?session=66681afef9b8e98b1ec95fdd)
- zuBerlin Devnet notion can be found [here](https://twisty-wednesday-4be.notion.site/ZuBerlin-Preconfs-Devnet-b693047f41e7407cadac0170a6711dea)
- Mev-Boost Community call [here](https://www.youtube.com/watch?v=UgoFjNkkTac)
- ETH.CC Sequencing day, found [here](https://www.youtube.com/watch?v=HYA0F5xkvr8)
- Expansion Podcast, found [here](https://www.youtube.com/watch?v=rAFFdqEAdj4)
- Infinite Jungle Podcast, found [here](https://www.youtube.com/watch?v=aJlNXc7LSh4)
- Commit-Boost [ChatGPT](https://x.com/Commit_Boost/status/1824521241748967471) created by [RayLin](https://x.com/RayLin0803)
- ETH Staker Community [call](https://www.youtube.com/live/Po66JAzZBqo?t=286s)


