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
<td><strong>Milestone</strong>
</td>
<td><strong>Tasks_______________________________</strong>
</td>
<td><strong>Deliverables & Outcome</strong>
</td>
<td><strong>Funding</strong>
</td>
<td><strong>Effort___</strong>
</td>
</tr>
<tr>
<td>#1
</td>
<td>
- Research, analysis

- Install Lotus (Node+Miner)
- Install Go-Filecon and analyze heartbeats
- Learn the process and details about nodes and consensus is represented
<p></p>
- Define UI requirements

- Information
- Charts
- Nodes and network data
<p>- Design mockups and final UI.
<p>- Endpoints definition
<p>- Architecture & infrastructure definition
<p>- Validation of scope and roadmap definition
<p>- Write backlog tickets

</td>
<td><strong>Deliverables:</strong>

- Document with defined scope
- UI mockups designs 
- Infrastructure design
- API endpoint definitions
- Roadmap document and completed Backlog

<p>
<strong>Outcome:</strong>

Definition of what and how the visual tool accomplishes the objective(s), alongside with a prioritization of them (scope and roadmap). This definition will be made up by the deliverables previously listed, so that the engineering team and stakeholders goals are aligned at the end of the feedback rounds and for the milestones ahead.
   </td>
   <td>35K
   </td>
   <td>3 weeks
   </td>
  </tr>
 <tr>
<td>#2
</td>
<td>
- Organize 2 sprints of 2 weeks
<p>- Frontend

- Setup
- UI layout design
- Dev React components
- Data connection to backend
- Unit tests
- CI

<p>- Backend (if needed)

- Setup
- API endpoints unit tests 
- New endpoints
- Unit Tests
- CI
<p>- Local/Develop and Cloud/Test environments setups
<p>- 2 Demos
<p>- Feedback rework


</td>
<td><strong>Deliverables:</strong>

- Consensus Visualization Tool Dapp
- Dapp based on React+Typescript and interactive visualization libraries (d3.js, Highcharts, Nvd3, rechart, etc) and other libraries 
- Dapp displays new messages, blocks, tipsets, ancestors, forks, miners and related information via live updates
- Additional tools, infrastructure or backend if it's defined
- Tests: Apply units tests, CI and manual QA


<p>
<strong>Outcome:</strong>

Generate a working implementation that meets the objectives previously defined, and that is approved by stakeholders.
   </td>
   <td>35K
   </td>
   <td>3 weeks
   </td>
  </tr>
</table>


### Acceptance Criteria

This proposal accept the acceptance criteria defined [here](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md#acceptance-criteria). Before starting the project we will make a detailed document with the acceptance criteria based on the final defined scope.


### A Similar Tool

Protofire built a network explorer for the [Enigma Protocol](https://enigma.co/) project that shows status and statistical information of the network. The application reads and processes blockchain data and Enigma network and handles events of all Enigma workers (nodes), epochs (rounds), tasks and users' information. 

The plan for the Consensus Visualization Tool resembles the Network Explorer Dapp’s plan, and in this context we have positive experiences. We built a good infrastructure behind the Dapp where we process the Ethereum data through building a [subgraph](https://thegraph.com/), increasing the data access speed to the frontend and creating a backend API (NodeJs) in order to process statistical data and manage complex formulas to handle different events. The complete solution was developed using containers based on docker-compose that allowed easy deploys on cloud services.

Our engineering team was responsible for the complete development process working in the analysis, scope definition and UI/UX design through mockups & prototypes, data schema definitions, flows, roadmap and finally the complete development. We worked focused on keeping a good balance between the UI/UX data and backend process. 

<p></p>
![Home](https://drive.google.com/file/d/1rv8sdAXkwJ5KoBpo2qjiNUw-aOKcxOJy/preview)

<table>
 </td>
   <td>The main page intends to show a quick overview of the network status. All data of the network, progressive chart, Epocs boxes, and tasks are updated in real-time. The user has all the information in a screenshot and one-click access to go in deeper details. \
We have used React, Typescript, web3, material-ui, Apollo, Koajs+hapi, etc.
   </td>
  </tr>
</table>
<p></p>
![Worker](https://raw.githubusercontent.com/cristianmalfesi/chm/master/Enigma%20Network%20Explorer%20-%2008%20Worker%20Single%402x.png?raw=true)

<table>
 </td>
   <td>List pages show complete details of different entities including features like filter, search, sort, etc. Based on the subgraph + backend-API, we have complete access to all data with high speed.
   </td>
  </tr>
</table>
<p></p>
![Task details](https://drive.google.com/file/d/1hQMc5iA9VQavyAbIJ9ZELm8MPPLDiAfx/preview)

<table>
 </td>
   <td>User has the complete entity information of workers (nodes), tasks and users and all is synchronized and has related links to any direction.
   </td>
  </tr>
</table>


## Key Personnel and Roles

Five is the proposed team and roles. Some staff members may take on multiple resource roles. \


<table>
  <tr>
   <td>
    <strong>Resource Title</strong>
   </td>
   <td>
    <strong>Resource</strong>
   </td>
   <td>
    <strong>Resource Description</strong>
   </td>
  </tr>
  <tr>
   <td>
    Product Manager
   </td>
   <td>
    <a href="https://team.altoros.com/cv1b3d1a/CristianMa">Cristian Malfesi</a>
   </td>
   <td>
    Project Managers are responsible for overseeing the design & development teams. 
   </td>
  </tr>
  <tr>
   <td>
    Technical Architect
   </td>
   <td>
    Franco Victorio
   </td>
   <td>
    Technical architects are responsible for providing guidance and oversight on technical requirements for the product.
   </td>
  </tr>
  <tr>
   <td>
    Frontend Engineer
   </td>
   <td>
    Jorge Shirai / \
Fernando Greco
   </td>
   <td>
    FE engineers are responsible for developing the front end services for the product. Experts using React, Javascript, Typescript and related interactive visualization libraries (web3.js, d3.js apollo, web3, koajs, hapi, mongoose and much more) 
   </td>
  </tr>
  <tr>
   <td>
    Backend Engineer
   </td>
   <td>
    Lisandro Corbalán /  Darío Miñones
   </td>
   <td>
    BE engineers are responsible for developing the back end services for the product. Work with these technologies: NodeJs, API, GraphQL, SQL/NonSQL,CI/CD, etc..
   </td>
  </tr>
  <tr>
   <td>
    QA and Reviewer
   </td>
   <td>
    Nicolás Dominguez
   </td>
   <td>
    QA engineers are responsible for ensuring the product is bug-free and meets client requirements.
   </td>
  </tr>
  <tr>
   <td>
    UI Designer
   </td>
   <td>
    Gabriel Rodriguez
   </td>
   <td>
    UI Designers are responsible for the development of a Design System which includes UI and UX.
   </td>
  </tr>
</table>


## Project Management

The Project Manager will be the primary Point of Contact for Filecoin. Work arrangements and communication plans include:

*   100% remote team that works across geographies and timezones.
*   Set up a shared Slack channel to maintain active dialogue with Filecoing team.
*   Set up Slack webhooks from all project management tools for visibility on progress.
*   Weekly updates will be organized and scheduled demos and discussions.
*   We use agile methodologies (Scrum, Kanban) and periodic time reports. Sprints of 2 weeks
*   Organize work and tickets through a Board Administrator




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
