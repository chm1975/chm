# RFP: Consensus Visualization Tool

**Name of Project:** `Consensus Visualization Tool`

**Proposal Category:** `app-dev`

**Proposer:**  @eshon

## Project Description

Develop an open-source blockchain consensus visualization tool that demonstrates Filecoin's Expected Consensus process. It must show the main chain and also other forks.
Expected Consensus based on Storage Power Mining is a very exciting consensus algorithm in Filecoin. Educate those new to Filecoin on how it works. Observe when bad forks happen and probe when and why they may be occurring.

## Deliverables
We agree to work under the scope of work detailed in the deliverable rules shared on this link.
Other deliverables points are:
- Open source Github repository with public access
- Hosted application working with Testnet and Mainnet
- The tutorial will be published in the repo.
- Create a blog post and publish it on medium and share through linkedin, twitter and other social nets

## Assumptions
- Code hosted into the public Protofire Github repository.
- Long term maintenance should be agreed with Filecoin.
- We assume that API (Lotus) has all necessary endpoints and is well documented so that the visualization tool can consume the corresponding data and transform it into a graphical representation.
- We recommend work with sprint 0 for the milestone 1, to define UI mockups and endpoints.
- The frontend and backend will be hosted by Filecoin.

#### Related Tools

- A great example of an interactive tool that shows what is happening on the Ethereum chain is [https//ethviewer.live](http://ethviewer.live/).
- A cool live blockchain sonification and visualization tool from Aleth.io can be seen at [https://audiokitpro.com/the-sound-of-blockchain](https://audiokitpro.com/the-sound-of-blockchain/).
- There are also explorers that show information about uncles and chain reorgs such as [https://etherscan.io/blocks_forked](https://etherscan.io/blocks_forked).

> (If you have other ideas for visualizations or tools that you think would be helpful for observing Filecoin consensus let us know!)

## Deliverables

An open-sourced, dual-licensed (under MIT and APACHE2) implementation that:

- provides an interactive visualization of Filecoin consensus viewable in web browsers
- or alternatively, a proposal to extend and enhance the existing explorer at [http://user.kittyhawk.wtf:8000](http://user.kittyhawk.wtf:8000/) ([Github repo](https://github.com/filecoin-project/filecoin-explorer))
- displays new messages, blocks, tipsets, ancestors, forks, miners and related information via live updates
- visualizes what is happening as messages are pooled into blocks forming Tipsets that extend Parent and GrandParent Tipsets as consensus is formed or forks occur
- shows when natural and bad forks occur (e.g. >51% malicous attack)
- provides explainers for what is happening and a glossary of terms


And also:

- has a well-documented, human-readable codebase
- works with a Filecoin node API (lotus* and/or go-filecoin, local or remote) and database or cache if needed to perform the intended workflow (* starting with the lotus API is recommended)
- has tutorials with demo usage
- can be in any mainstream language with a preference for ones that ensure easy long-term maintenance
- is well-tested and usable by a large audience during Testnet and Mainnet

> NOTE: Node API improvements are likely between now, Testnet and Mainnet. We will work with node implementers to document relevant API calls and provide coordinated opportunities for questions and feedback and recommend starting with the lotus API.

## Recommended Team

- A small team with strong design and front-end web development skills (please show evidence of this in your proposal)
- Familiarity with interactive visualization libraries (such as d3.js or others)
- Familiarity with using node APIs and a solid understanding of blockchain concepts

## Milestones & Funding

| Milestone No. | Milestone Description | Funding | Estimated Timeframe |
| --- | --- | --- | --- |
| 1 | Finalize scope, a list of node API endpoints to be used, UI mockups + feedback rounds with the Filecoin DevGrants team, architectural design | TBD | 2-3 weeks |
| 2 | Implementation interoperable with a Filecoin node and User tested | TBD | 4 weeks |
| 3 | All project deliverables are completed and added to the [Filecoin Shipyard](https://github.com/filecoin-shipyard) (website, documentation, codebase) | TBD | 2 weeks |
| 4 | Maintenance and Upgrades during Testnet and Mainnet | TBD | 2 weeks |

If a milestone is not satisfactorily met, we may not continue to fund your team for this project.

## Acceptance Criteria

**Acceptance criteria for Finalize scope, a list of node API endpoints to be used, UI mockups/prototype + feedback rounds with the DevGrants team, architectural design:**
- This milestone's deliverables must represent the final design of the service and its intended interoperability with a Filecoin node API and functionality.
- The design should address the core goals proposed in the description of this brief, with a focus on educating users about how consensus is forming in the Filecoin network.
- The design team should engage in feedback rounds with the DevGrants team on mockups and user flows.
- If additional tools or infrastructure would be helpful for production deployment that is clearly scoped.

**Acceptance criteria for Implementation interoperable with a Filecoin node and User tested:**
- The service must enable the functionality specified in Milestone 1 in at least one mainstream language.
- A functioning demo of the service to be presented and testable by the PL team.
- Additional feedback rounds with the DevGrants team as implementation progresses.
- The tool is tested with various stakeholders and potential users for comprehensibility, utility and engagement.

**Acceptance criteria for All project deliverables:**
- All of the criteria above have been met.
- A developer on our team can use and test the functionality of this service themselves without needing to talk to anyone.

**Acceptance criteria for Maintenance and Upgrades during Testnet:**
- The application must be usable on the Filecoin Network during Testnet and Mainnet.

If a milestone is not satisfactorily met, we may not continue to fund your team for this project.

## Resources

#### Filecoin Network Stats and Explorers

lotus Devnet
- Grafana Network Dashboard: https://lotus-metrics.kittyhawk.wtf

go-filecoin User Devnet
- NetworkStats: https://stats.kittyhawk.wtf
- Dashboard: http://user.kittyhawk.wtf:8010/
- Explorer: http://user.kittyhawk.wtf:8000/

> NOTE: A DevGrant RFP for a comprehensive Filecoin Block Explorer with full search has been awarded to a team in wave 1. In contrast, this RFP is specifically about exploring ways to explain and visualize Expected Consensus in Filecoin.

#### Additional References

In addition to those listed in the [Related Tools](#Related-Tools) section above:

- https://www.blockchain.com/btc/tree/114688199
- https://dailyblockchain.github.io/
- https://reports.aleth.io/
- https://bitnodes.earn.com/nodes/network-map/

----
**Questions about this RFP?**

Contact @eshon or ask in the [Filecoin DevGrants forum](https://discuss.filecoin.io/c/devgrants).
