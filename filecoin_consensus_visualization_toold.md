# RFP: Consensus Visualization Tool

**Name of Project:** `Consensus Visualization Tool`

**Proposal Category:** `app-dev`

**Proposal Type:*** `rfp`

## Summary
This document outlines Protofire’s (a sub-division of Altoros) proposition on providing a  blockchain specialist developer team to build the Consensus Visualization Tool. We believe that we can build robust solution and contribute with our experience to Filecoin network community.

## Who we are

[Protofire](https://protofire.io) is a team of engineers that helps providers of decentralized protocols, infrastructures and developer platforms to accelerate the growth of their ecosystems. By providing hands-on coding and contributions, Protofire specializes in supercharging developer adoption and network usage. We ship applications, smart contracts, and developer tools (SDKs/APIs/sample apps), as well as assist you in improving performance/cost of oracles.
Having been interested in Filecoin, our team researched and checked the network to learn and understand the structure, scalability, and security. 
Based on our experience working with different protocols, networks and as specialists in developing blockchain technologies, we propose our Protofire’s team to build the required tool.

## Project Description

Develop an open-source blockchain consensus visualization tool that demonstrates Filecoin's [Expected Consensus](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md#about-expected-consensus-ec) process. It must show the main chain and also other forks.
Expected Consensus based on Storage Power Mining is a very exciting consensus algorithm in Filecoin. Educate those new to Filecoin on how it works. Observe when bad forks happen and probe when and why they may be occurring.

## Deliverables
We agree to work under the scope of work detailed in the deliverable rules shared on this [link](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md#deliverables).
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

## Scope of Work
Protofire’s team has the capability and expertise to develop the required tool detailed on the [RFP](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md).
According to the requirements, our team is ready to work on these milestones :

<table>
  <tr>
   <td>Milestone
   </td>
   <td>Tasks
   </td>
   <td>Deliverables
   </td>
   </tr>
  <body>
  <tr>
   <td>#1
 </td>
 <td>- Research, analysis  
    - Install Lotus (Node+Miner)   
    - Install Go-Filecon and analyze heartbeat  
    - Learn the process and details about nodes and consensus is represented  
- Define UI requirements
    - Information
    - Charts
    - Nodes and network data    
- Design mockups and final UI
- Endpoints definition
- Architecture & infrastructure definition
- Validation of scope and roadmap definition
- Write backlog tickets
</td>
   <td>- Document with defined scope
    - UI mockups designs 
    - Infrastructure design
    - API endpoint definitions

-Roadmap document and completed Backlog
   </td>
    </tr>
  <tr>
   <td vertical-align:text-top>#2
   </td>
   <td>- Organize 2 sprints of 2 weeks
- Frontend
        - Setup
        - UI layout design
        - Dev React components
        - Data connection to backend
        - Unit tests
        - CI
- Backend (if needed)
        - Setup
        - API endpoints unit tests 
        - New endpoints
        - Unit Tests
        - CI
- Local/Develop and Cloud/Test environments setups
- 2 Demos
- Feedback rework
Sprint duration may be adapted according to team size and scope; as well as demos & feedback rework sessions.
   </td>
   <td>- Consensus Visualization Tool Dapp
<p>
- Dapp based on React+Typescript and interactive visualization libraries (d3.js, Highcharts, Nvd3, rechart, etc) and other libraries  \
- Dapp displays new messages, blocks, tipsets, ancestors, forks, miners and related information via live updates
<p>
- Additional tools, infrastructure or backend if it's defined
<p>
- Tests: Apply units tests, CI and manual QA
   </td>
   </tr>
  <tr>
   <td>#3
   </td>
   <td>- Improve documentation and support information (if needed): README, wikis, tutorials, etc.
- Transfer ownership of CI/CD and services that support the architecture to Filecoin (if needed, use free/open source-based service when possible).
- Move codebase/repos to Shipyard and adapt to meet Filecoin standards.
   </td>
   <td>- Feedback
- Create well-documented, human-readable codebase
- Create blog post and/or tutorial with demo usage
   </td>
  </tr>
  <tr>
   <td>#4
   </td>
   <td>Maintenance and Upgrades during Testnet and Mainnet
   </td>
   <td>- Feedback
   </td>
     </tr>
  </body>
</table>

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
