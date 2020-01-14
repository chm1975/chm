# RFP: Consensus Visualization Tool

**Name of Project:** `Consensus Visualization Tool`

**Proposal Category:** `app-dev`

**Proposal Type:*** `rfp`

## Summary
This document outlines Protofire’s (a sub-division of [Altoros](https://www.altoros.com/)) proposition on providing a blockchain specialist developer team to build the [Consensus Visualization Tool](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md#rfp-consensus-visualization-tool). We believe that we can build a robust solution and contribute with our experience to the Filecoin network community.

## Who we are

[Protofire](https://protofire.io) is a team of engineers that helps providers of decentralized protocols, infrastructures and developer platforms accelerate growth of their ecosystems. By providing hands-on coding and contributions, Protofire specializes in supercharging developer adoption and network usage. We ship applications, smart contracts, and developer tools (SDKs/APIs/sample apps), as well as assist you in improving performance/cost of oracles.

Having been interested in Filecoin, our team researched the network to get a deeper understanding of the structure, scalability, and security. 

Having experience working with different protocols, networks and as specialists in developing blockchain technologies, we believe that our team qualifies as suitable for delivering the Consensus Visualisation tool.

#Consensus Visualization Tool

## Objetives

The objectives of this proposal is to develop an open-source blockchain consensus visualization tool that demonstrates Filecoin's [Expected Consensus](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md#about-expected-consensus-ec) process. It must show the main chain and also other forks.

## Deliverables

This proposal covers all the deliverables described in the RFP that is available by this [link](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md#deliverables). \
Additional deliverables are:


*   Open source Github repository with public access
*   Hosted application working with Testnet and Mainnet
*   The tutorial with demo usage that will be published in the repo.
*   Blog post that will be published on Protofire medium account and shared through linkedin, twitter and other platforms
*   Updated estimates for milestones 2-4

## Scope of Work
Below you can find the table describing the milestones schedule, tasks and deliverables that are based on the the requirements stated in [RFP](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md).


<table>
<tr>
<td><strong>Milestone</strong>
</td>
<td><strong>Tasks________________________________</strong>
</td>
<td><strong>Deliverables & Outcome</strong>
</td>
<td><strong>Fund</strong>
</td>
<td><strong>Effort_____</strong>
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
<strong>Outcomes:</strong>

Definition of what and how the visual tool accomplishes the objective(s), alongside with a prioritization of them (scope and roadmap). This definition will be made up by the deliverables previously listed, so that the engineering team and stakeholders goals are aligned at the end of the feedback rounds and for the milestones ahead.
   </td>
   <td>30K
   </td>
   <td>3 weeks
   </td>
  </tr>
 <tr>
<td>#2
</td>
<td>
- Organize sprints of 2 weeks each one
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
<p>- Demos per sprint
<p>- Feedback rework

<p>Sprint duration may be adapted according to team size and scope; as well as demos & feedback rework sessions.

</td>
<td><strong>Deliverables:</strong>

- Consensus Visualization Tool Dapp
- Dapp based on React+Typescript and interactive visualization libraries (d3.js, Highcharts, Nvd3, rechart, etc) and other libraries 
- Dapp displays new messages, blocks, tipsets, ancestors, forks, miners and related information via live updates
- Additional tools, infrastructure or backend if it's defined
- Tests: Apply units tests, CI and manual QA


<p>
<strong>Outcomes:</strong>

Generate a working implementation that meets the objectives previously defined, and that is approved by stakeholders.
   </td>
   <td>TBD
   </td>
   <td>4 weeks
   (TBD)
   </td>
  </tr>
  <tr>
<td>#3
</td>
<td>
<p>- Improve documentation and support information (if needed): README, wikis, tutorials, etc.
<p>- Transfer ownership of CI/CD and services that support the architecture to Filecoin (if needed, use free/open source-based service when possible).
<p>- Move codebase/repos to Shipyard and adapt to meet Filecoin standards.
- Work on feedback 



</td>
<td><strong>Deliverables:</strong>

- Changes and improvements from feedback
- Create well-documented, human-readable codebase
- Create blog post and/or tutorial with demo usage


<p>
<strong>Outcomes:</strong>

Wrap up the project's codebase to add it to the Shipyard so it can be further modified or maintained by a Filecoin developer/community. The blogpost or tutorial may improve the understanding of how the project works and represents the consensus process (ideal to aid new people looking for understanding the consensus process) and, maybe, tell something cool about the development experience to improve community engagement.
   </td>
   <td>TBD
   </td>
   <td>2 weeks
   (TBD)
   </td>
  </tr>
  <tr>
<td>#4
</td>
<td>
Maintenance and Upgrades during Testnet and Mainnet

</td>
<td><strong>Deliverables:</strong>

- Feedback: changes and improvements

<p>
<strong>Outcomes:</strong>

Protofire team will support problems and bugs detected during the agreed period.
   </td>
   <td>TBD
   </td>
   <td>2 weeks
   (TBD)
   </td>
  </tr>
  <tr>
<td><strong></strong>
</td>
<td><strong></strong>
</td>
<td><strong>TOTAL</strong>
</td>
<td><strong>TBD</strong>
</td>
<td><strong>11 weeks</strong>
</td>
</tr>
</table>



### Acceptance Criteria

This proposal accept the acceptance criteria defined [here](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-consensus-visualization-tool.md#acceptance-criteria). Between milestones 1 and 2, we will make a detailed document with the acceptance criteria based on the final defined scope.


## Assumptions
- Code hosted into the public Protofire Github repository.
- Long term maintenance should be agreed with Filecoin.
- We assume that API (Lotus) has all necessary endpoints and is well documented so that the visualization tool can consume the corresponding data and transform it into a graphical representation.
- We recommend work with sprint 0 for the milestone 1, to define UI mockups and endpoints.
- The frontend and backend will be hosted by Filecoin.
- The proposed time is based on timeframes suggested by Filecoin in the instructions of this link. We assume that Filecoin understands the risks and could be necessary to rethink the estimates.

### A Similar Tool

Protofire built a network explorer for the [Enigma Protocol](https://enigma.co/) project that shows status and statistical information of the network. The application reads and processes blockchain data and Enigma network and handles events of all Enigma workers (nodes), epochs (rounds), tasks and users' information. 

The plan for the Consensus Visualization Tool resembles the Network Explorer Dapp’s plan, and in this context we have positive experiences. We built a good infrastructure behind the Dapp where we process the Ethereum data through building a [subgraph](https://thegraph.com/), increasing the data access speed to the frontend and creating a backend API (NodeJs) in order to process statistical data and manage complex formulas to handle different events. The complete solution was developed using containers based on docker-compose that allowed easy deploys on cloud services.

Our engineering team was responsible for the complete development process working in the analysis, scope definition and UI/UX design through mockups & prototypes, data schema definitions, flows, roadmap and finally the complete development. We worked focused on keeping a good balance between the UI/UX data and backend process. 

<p></p>

![](images/Enigma%20Network%20Explorer_Home.png)

<table>
 </td>
   <td>The main page intends to show a quick overview of the network status. All data of the network, progressive chart, Epocs boxes, and tasks are updated in real-time. The user has all the information in a screenshot and one-click access to go in deeper details. \
We have used React, Typescript, web3, material-ui, Apollo, Koajs+hapi, etc.
   </td>
  </tr>
</table>
<p></p>

![](images/Enigma%20Network%20Explorer_Task_details.png)

<table>
 </td>
   <td>List pages show complete details of different entities including features like filter, search, sort, etc. Based on the subgraph + backend-API, we have complete access to all data with high speed.
   </td>
  </tr>
</table>
<p></p>

![](images/Enigma%20Network%20Explorer%20-%2008%20Worker%20Single@2x.png)

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


## Grant Payment Terms

This is a proposal for a fixed bid grant. Tezos is requested to pay as follows:

*   50% upon start of the project and 50% upon project completion, with net 14 payment terms.
*   Any changes to the scope of work or overages to the price must be agreed in writing by the parties through a change request.
*   All work is expected to be done remotely, with no travel required.


## Capabilities of our team and related experience

We have extensive experience in developing protocols, tooling, dApps, from PoCs and prototypes to MVPs, etc. To learn more, please visit [our website](https://protofire.io).

Protofire works exclusively with entrepreneurs who are builders of decentralized infrastructure protocols, applications, and ecosystems.

## Our services, customers and works

![About Protofire](http://protofire.io/presentation-customers-works)

