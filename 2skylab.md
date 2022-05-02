# Mintbase Grant Proposal

- **Project Name:** 2SkyLab's NFT utility tools app
- **Team Name:** 2SkyLab
- **Payment Address:** 2skylabfund.near
- **[Level](../README.md#level_slider-levels):** 2

## Project Overview :page_facing_up:

### Overview

- 2SkyLab brings together innovative technology with creative works, delivering products and experiences which are not only sensual, but also functional
- This particular project focuses on developing NFT utility tools which can be used by other Mintbase stores as an effort to answer one simple question - "Why would someone own an NFT as opposed to right clikc saving it's content?"
- Our project aims to build on top of the existing store functions, creating more functions in the form of tools, designed to evolve the concept of NFT utility
- We are currently at a pivotal point in evolution of the digital environment, such times don't come accross all too often, the last significant era was the dot com boom. Today we are presented with the opportunity to shape this environment in the way that we believe would help bring the tech to the masses, it is at a very young stage and we acknowledge the hurdles that need to be overcome in order to make this happen. Our team is well prepared and has the necessary mindset to innovate this space in the right direction, hence we are more than happy ot take on this opportunity and put in the needed effort.

### Project Details

- Brief overview of the means we will undertake to carry out 1. Mintbase intergration 2. Auto royalty tool 3. Fixed rate NFT tool -
  
1. Mintbase Integration 
Connect the mintbase sdk as well as other necessary JavaScript libraries.
The final result will be a progressive user interface to include the NEAR wallet login feature so users can authenticate for purchases.

2. Royalties 
This tool can be built into a single react application with 2/3 pages. Also a multi-file smart contract to handle preminting and reissuing of NFT royalties. This application can be designed to run as a standalone app for adoption on other stores.

3. Fixed rate NFT
For this scenario we would build an oracle contract to manage the prices. Also to maintain fixed-rate we would employ the use of an automated market maker which will run on the blockchain and update your rates. If this needs to be adopted for another program the functions of the contract set would be added to the program in question. The final result should be an open source contract set that can be tailored and redeployed to suit the program in question.

- Mockups/designs of any UI components
- Data models / API specifications of the core functionality
- An overview of the technology stack to be used
- Documentation of core components, protocols, architecture, etc. to be deployed
- PoC/MVP or other relevant prior work or research on the topic
- What your project is _not_ or will _not_ provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious

### Ecosystem Fit

- We position ourselves as an organization focusing on 2 areas, 1 being NFT utility tool developers, and 2 being a fine arts curators. Our 2nd focal point is generally used to demonstrate our works in the 1st focal point.
- Fellow mintbase stores, established businesses in Hong Kong seeking to adapt web3 technology, art collectors, individuals with no knowledge in the web3 space.
- NFT utility developement. This is a crucial point in demonstrating to people and businesses, how NFT technology can be used in ways to benefit b2b and b2c business models. The current state of NFT has people believing in nothing more than speculative investments, we want to change that to demonstrate that NFTs are actually tools that can be fit to various economic environments.
- Various projects are releasing phygital NFTs, various projects are developing tools to enhance the mintbase store experience, however I haven't found any projects that are focusing specifically on developing NFT utility tools and showcasing their use through their phygital/ digital NFTs.
  - Our project is different because the main goal of our NFT utility tools are directed not only to other Mintbase stores but also to the general public as a way to showcase the ways in which we can begin using NFT technology in traditional business practices.

## Team :busts_in_silhouette:

### Team members

- Konstantin Pozdnyaev and Vlada Davidovic
- Yukie Chan, Lois Lai, Didia Dev

### Contact

- **Contact Name:** Konstantin Pozdnyaev
- **Contact Email:** VK@2skylab.com
- **Website:** https://www.2skylab.com/

### Legal Structure

- **Registered Address:** NA
- **Registered Legal Entity:** NA

### Team's experience

- Konstantin Pozdnyaev: Has the neccessary expertise in the design, arts curation, project management and general operations. Previously incorporated, scaled and sold a company by the name GreenWork. Is a founder of a music label named Beatsolow. 
- Vlada Davidovic: Has the expertise in fine arts, including areas of wine, jewellery and fashion. Holding the position of Asia Developement Manager at a fashion brand Campo Marzio.
- Yukie Chan: Has the expertise in social media management. Previously worked as secretary for HKFBS (Hong Kong Federation of Business Students).
- Lois Lai: Public relations, partnerships and marketing manager. If a co founder of a membership club Club Lux, director at a hhigh end magazine Jetsetter and the founder of The Rose Rituals.
- Didia Dev: Full stack developer, worked for projects as pythonswap, cartoon cat frens, ever cash and more.

### Team Code Repos

- https://github.com/<your_organisation>
- https://github.com/<your_organisation>/<project_1>
- https://github.com/<your_organisation>/<project_2>

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://t.me/Didiadevportfolio/<Didia Dev>

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/konstantinpozdnyaev/<Konstantin Pozdnyaev>
- https://www.linkedin.com/in/vlada-davidovic-47917045/<Vlada Davidovic>
- https://www.linkedin.com/in/yukie-chan-0803571b6/<Yukie Chan>
- https://www.linkedin.com/in/lois-lai-06ab73211/<Lois Lai>                                                          
                                                          

## Development Status :open_book:

Project has not commenced developement at this stage. I've been in touch with regards to the tool developement ideas with Mintbase representatives and our first step would be intergrating our mintbase store to our website 2skylab.com. Upon the intergration we will begin developing the tools, for the ask of this grant we are seeking to develop 2 tools which can be used on other mintbase stores. We will have a standalone with a ready UX/UI of these 2 tools, this would be available to holders of specific NFTs sold on our store, otherwise the code is open source and could be implemented by other projects on their own terms. This standalone app will become a work in progress, with time and progress including more of our utility tools we will have developed.
  

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Mintbase. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested _per milestone_.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 - Mintbase Intergration

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 3000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Mintbase nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Mintbase module: X | We will create a Mintbase / NEAR module that will... (Please list the functionality that will be implemented for the first milestone) |  
| 2. | Mintbase module: Y | We will create a Mintbase / NEAR module that will... |  
| 3. | Mintbase module: Z | We will create a Mintbase / NEAR module that will... |  
| 4. | NEAR chain integration | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  


### Milestone 2 - Auto royalties tool launched on our website's intergrated Mintbase app

- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 5000 USD
  

### Milestone 3 - Fixed rate NFT tool launched on our website's intergrated Mintbase app


- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 5000 USD  


### Milestone 4 - Tools put together into a standalone app, establish connection between specific NFTs and the UI ready app to allow useage on other stores


- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 7000 USD    


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.
