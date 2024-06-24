# Commit-Boost

**THE CODE IN THIS REPOSITORY IS CURRENTLY NOT AUDITED OR READY FOR PRODUCTION**

## What Is Commit-Boost:

Commit-Boost is an open-source public good that acts as a validator platform to enable safe commitments. Specifically, Commit-Boost is a new Ethereum validator sidecar focused on standardizing the last mile of communication between validators and third parties. It has been designed with modularity at its core, with the goal of supporting a broad range of different use cases and protocols. We plan to develop and then sustain this software to limit fragmentation, reduce complexity for core devs, and decrease risks for proposers making commitments–but, still allow for open innovation / not limiting designs developed by proposer commitment protocols

More details on the design can be found in this [presentation](https://docs.google.com/presentation/d/1T06pPKcKkU-EdfYkAtXUYQxjfHXkkFBIVRDyWyiEFVs/edit#slide=id.g2731bc99d1b_0_74), however the high-level schematic is below. We will also be publishing / presenting more detailed specs shortly. 

![Commit-Boost](https://github.com/Commit-Boost/.github/assets/150300937/1f4d32b1-718f-40b8-bff1-99ffd1b34812)

## Why Build Commit-Boost: 

On the surface all the efforts around proposer commitments are a massive unlock for Ethereum, however, most are starting to agree on a common denominator: in the future, beacon proposers will be face a broader set of options of what they may “commit" to–be it ILs or preconfs or other types of commitments–compared to just an external or local payload they see today. Due to this we see a few risks developing that Commit-Boost is trying to mitigate:
-	Fragmentation: Multiple software and standards develop and compromise the security integrity of the entire Ethereum network
-	Development Complexity: Exponentially inflate the burden on core developers tasked with executing / testing major network upgrades
-	Transparency: Limited Transparency around bugs and taking quick actions may be challenging

Commit-Boost is an effort design to help mitigate some of these risks. 


## Core Principles:

-	North Star: Would Vitalik run this and can we use this to improve decentralization
-	Mission: Not-for-profit, community driven, and an open-source, public good 
-	Product: Validator platform for proposers to safely make commitments
-	Neutrality: Proposer commitment agnostic, preconf agnostic, restaking agnostic, relay agnostic, transaction flow agnostic 
-	Unified: Validators run one core side car to opt into many different commitments 
-	Safety: Community reviews / audits, modularized, increased transparency–the focus is to reduce risk / overhead for the proposer to manage commitments


## How to Contribute:

-	We are just getting started, but there already are many ways to contribute. Please reach out to us on [Twitter]( https://x.com/Commit_Boost)

## Resources (this will be continuously updated):

- Orginally proposed on ETH Research, read more [here](https://ethresear.ch/t/based-proposer-commitments-ethereum-s-marketplace-for-proposer-commitments/19517)
- First presentation to the community can be found [here](https://www.youtube.com/watch?v=jrm4ZUoj9xY&list=PLJqWcTqh_zKHDFarAcF29QfdMlUpReZrR&index=11)
- Second presentation at zuBerlin can be found [here](https://streameth.org/zuberlin/watch?session=66681afef9b8e98b1ec95fdd)
- zuBerlin Devnet notion can be found [here](https://twisty-wednesday-4be.notion.site/ZuBerlin-Preconfs-Devnet-b693047f41e7407cadac0170a6711dea)

## Governance Roadmap (to be updated):

## Contributions (to be updated):

## Grants (to be updated):

