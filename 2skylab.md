# Mintbase Grant Proposal

- **Project Name:** 2SkyLab's NFT utility tools app
- **Team Name:** 2SkyLab
- **Payment Address:** 2skylabfund.near
- **[Level](../README.md#level_slider-levels):** 2

## Project Overview :page_facing_up:

### Overview

- 2SkyLab brings together innovative technology with creative works, delivering products and experiences which are not only sensual, but also functional
- This particular project focuses on developing NFT utility tools which can be used by other Mintbase stores as an effort to answer one simple question - "Why would someone own an NFT as opposed to right click saving it's content?"
- Our project aims to build on top of the existing store functions, creating more functions in the form of tools, these tools will be available to be applied to specified mints on mintbase stores by using a browser extension app, in support of our business model, the standalone app will be available to holders of a specific NFT (Key) minted on our 2skylab mintbase store.
- We are currently at a pivotal point in evolution of the digital environment, such times don't come accross all too often, the last significant era was the dot com boom. Today we are presented with the opportunity to shape this environment in the way that we believe would help bring the tech to the masses, it is at a very young stage and we acknowledge the hurdles that need to be overcome in order to make this happen. Our team is well prepared and has the necessary mindset/ experience to innovate this space in the right direction, we are determined to take on this challange and put in the needed effort to actualize NFTs with utility.

### Project Details

- Brief overview of the means we will undertake to carry out 1. Mintbase intergration 2. Auto royalty tool 3. Fixed rate NFT tool -
  
1. Mintbase Integration 
Connect the mintbase sdk as well as other necessary JavaScript libraries.
The final result will be a progressive user interface to include the NEAR wallet login feature so users can authenticate for purchases.
All currently available resources under mintbase.js and mintbase UI will be integrated to our own domain, the only difference will be the BG image of the integrated mintbase pages, we will adapt our existing domain's bg image (renaissance painting with a zoom as you scroll fx). 

2. Royalties 
This tool will be built into a single react application with 2/3 pages. Also a multi-file smart contract to handle preminting and reissuing of NFT royalties to the first buyer of specified NFTs. 

3. Fixed rate NFT
For this scenario we would build an oracle contract to manage the prices. To maintain fixed-rate we would employ the use of an automated market maker which will run on the blockchain and update NFT rates, depicting the price in NEAR. 

The above plans are designed to be utilized by NFT minters on Mintbase.io rather than buyers, they do however encompass benefits to NFT buyers and also serve as an incentive to onboard more businesses to the Mintbase ecosystem.

UX/ UI draft wireframe - https://www.figma.com/file/1o363gp50m7fzKTzafWK6g/Untitled?node-id=0%3A1

### Ecosystem Fit

- We position ourselves as an organization focusing on 2 areas, 1 being NFT utility tool developers, and 2 being a fine arts curators. Our 2nd focal point is generally used to demonstrate our works in the 1st focal point.
- Fellow mintbase stores, established businesses in Hong Kong seeking to adapt web3 technology, art collectors, individuals with no knowledge in the web3 space.
- NFT utility developement. This is a crucial point in demonstrating to people and businesses, how NFT technology can be used in ways to benefit b2b and b2c business models. The current state of NFT has people believing in nothing more than speculative investments, we want to change that to demonstrate that NFTs are actually tools that can be fit to various economic environments.
- Various projects are releasing phygital NFTs, various projects are developing tools to enhance the mintbase store experience, however I haven't found any projects that are focusing specifically on developing NFT utility tools and showcasing their use through their phygital/ digital NFTs, whilst implementing the mintbase js/ ui to their own domains.
  - Our project is different because the main goal of our NFT utility tools are directed not only to other Mintbase stores but also to the general public and established (traditional) businesses as a way to showcase the ways in which we can begin using NFT technology in traditional business practices, by doing so we are not only bringing value to the Mintbase ecosystem but are in line with NEAR protocol's aim for mass adoption.

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

- Konstantin Pozdnyaev: Has the neccessary expertise in the design, arts curation, project management and general operations. Previously incorporated, scaled and sold a company by the name GreenWork. Is a founder of a music label named Beatsolow and is working for a HK based startup developing fintech for high profile investors. 
- Vlada Davidovic: Has the expertise in fine arts, spanning sectors of wine, jewellery and fashion. Holding the position of Asia Developement Manager at a fashion brand Campo Marzio.
- Yukie Chan: Has the expertise in social media management. Previously worked as secretary for HKFBS (Hong Kong Federation of Business Students).
- Lois Lai: Public relations, partnerships and marketing manager. Is a co founder of a membership club Club Lux, director at a high end magazine Jetsetter and the founder of The Rose Rituals.
- Didia Dev: Full stack developer, worked for projects as pythonswap, cartoon cat frens, ever cash and more.

### Team Code Repos

- https://t.me/Didiadevportfolio/<Didia Dev>

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/konstantinpozdnyaev/<Konstantin Pozdnyaev>
- https://www.linkedin.com/in/vlada-davidovic-47917045/<Vlada Davidovic>
- https://www.linkedin.com/in/yukie-chan-0803571b6/<Yukie Chan>
- https://www.linkedin.com/in/lois-lai-06ab73211/<Lois Lai>                                                          
                                                          

## Development Status :open_book:

Project has not commenced developement at this stage. I've been in touch with regards to the tool developement ideas with Mintbase representatives and our first step would be intergrating our mintbase store to our website 2skylab.com. Upon the intergration we will begin developing the tools, for the ask of this grant we are seeking to develop 2 tools which can be used on other mintbase stores through a browser extenstion app. We will have a standalone with a ready UX/UI of these 2 tools, this would be available to holders of specific NFTs sold on our store, otherwise the code is open source and could be implemented by other projects on their own terms. This standalone app will become a work in progress, with time and progress including more of our utility tools we will have developed.
  

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 4 months
- **Full-Time Equivalent (FTE):** 4
- **Total Costs:** 40,000
- **Notes:** The milestones in relation to developement of app encomopass 24,000 USD, remainder 16,000 encompasses paying 4 months of FT positions for
1. Social media management/ influencers, 2. Project management/ laison 3. other necessary operations to engage users with our app.

### Milestone 1 - Mintbase Integration

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 3500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | We will document the steps taken to intergrate our mintbase store to our website and our Github page, Describing steps taken to establish connection with the NEAR blockchain to allow wallet logins as well as the implementation of customized UI |
| 0c. | Article | We will publish the proceess of intergration in simplified terms (geared for our audience) in our news section on 2skylab.com website |
| 1. | Mintbase module: Intergration of Mintbase app to our website | We will allow users to connect their NEAR wallet to the intergrated mintbase store on our website, this intergration pertains only to the existing 2skylab store, our website will not host the greater landsscape of the Mintbase website as for example, the marketplace/ ability to view other stores. The intergrated mintbase store will generally follow a similar UI and UX existing in the original mintbase store (Both back and frontend), with a few iterations of graphics to match the layout of our website, frontend functionality will remain the same as currently is on original Mintbase store, on the backend we will have added functionality of our tools to our store that are described in the milestones below.) |  



### Milestone 2 - Auto royalties tool launched on our website's integrated Mintbase app

- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 5000 USD
  

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | Documentation will be available on Github, we will create a Github account for 2SkyLab, there you will find all relevant documentations of the tools we are going to develop |
| 0c. | Testing Guide | Core functions will be covered by unit tests to ensure functionality and robustness. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish the developement in simple terms on our website's news section, the technical documentation of the core functions will be available on our github page.)
| 1. | Mintbase module: X | We will create a Mintbase / NEAR module that will pre-mint and reissue NFTs on assignment of a specific royalty once a NFT transfer function is triggered by buyer. This will be built into a single react application with 2/3 pages. Also a multi-file smart contract to handle preminting and reissuing of NFT royalties. As this function only concerns backend operations, it will only be designed to work with our intergrated mintbase store at first, upon reaching Milestone 4, this tool will be integrated into a standalone app including the tool from the following Milestone 3 |  


### Milestone 3 - Fixed rate NFT tool launched on our website's integrated Mintbase app


- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 5000 USD  
  
| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | Documentation will be available on Github, we will create a Github account for 2SkyLab, there you will find all relevant documentations of the tools we are going to develop |
| 0c. | Testing Guide | Core functions will be covered by unit tests to ensure functionality and robustness. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish the developement in simple terms on our website's news section, the technical documentation of the core functions will be available on our github page.)
| 1. | Mintbase module: X | We will create a Mintbase / NEAR module that will entail an oracle contract to manage prices. To maintain fixed-rate we would employ the use of an automated market maker which will run on the blockchain and update selected NFT rates. The final result should be an open source contract set that can be tailored and redeployed to suit the program in question. |


### Milestone 4 - Tools put together into a standalone app, establish connection between specific NFTs and the UI ready app to allow useage on other stores


- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 7000 USD    

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | Documentation will be available on Github, we will create a Github account for 2SkyLab, there you will find all relevant documentations of the tools we are going to develop |
| 0c. | Testing Guide | Core functions will be covered by unit tests to ensure functionality and robustness. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish the functionality of this module on our githbub account in detailed terms as well as on our website's news section in simplified terms, we will provide documentation describing the proceedure needed to gain access to the standalon app at hand, if other stores want to use the NFT utility tools without our standalone app they may find the opensource code on our Github and implement the utility tools to their own store on their on terms.)
| 1. | Mintbase module: Standalone App with NFT utility tools available to fellow Mintbase stores | We will build on top the mintbase SDK to establish an NFT API that will allow fellow Mintbase stores utilize our tools described in the previous 2 milestones in a ready to use standalone app with our custom UI elements, this standalone app will be available to holders of a designated NFT purchaseable from our Mintbase store, this NFT will serve as API key to gain access to the ready standalone app. |

  
## Future Plans

- Short term, we plan to promote the mintbase marketplace and the utility tools we have developed to attempt to bring in more traffic to the marketplace. We will promote our utility tools to other mintbase stores through our social accounts and personal connections. We plan to host events to showcase our devised NFT utility to the general public, showcasing the benefits of owning our mints (such as auto royalties to first buyer), onboarding new users to NEAR (by helping them set up NEAR wallets) and taking on partenrships with established businesses in Hong Kong, trying to appeal to them by promoting our fixed rate NFT functionality + encouraging them to set up their own Mintbase stores and implement our NFT utility tools as a way to meaningfully engage in the evolution of web3 and blockchain. We are honing in on the 'FOMO', but instead of merely monetizing this aspect, we want to offer a meaningful means for businesses to incorporate NFT and web3 apps to their own business practices, positioning mintbase and our utility tools as the perfect way to jump on board.
- In the long term, we plan to develop more NFT utility tools and add them to the standalone app we are developing (Milestone 4), prior, we will need to undergo the development of the tools described in the milestones above, taking into consideration all the difficulties encountered in the process. This is something new to our team and we are taking on a learning curve, we don't want to over extend our ambitions but are sincerely willing to position ourselves as key players in developement of NFT utility tools pertaining to the Mintbase/ NEAR ecosystem. Upon completion of Milestone 4 we will begin to draw out further NFT utility tools. We hope that down the line we would be able innovate our standalone app with NFT utility tools towards compatibility not only with other stores on mintbase but also other NFT standards and markeplaces, truly living up to the LAB' part of our company name.

## Additional Information :heavy_plus_sign:

- Thus far we have received funding from Mintbase DAO to startup our store, to this date we have released one collection of NFTs, this is a phygital collection featuring works of the infamous rockstar graphic designer Ruby Mazur, we are currently working on releasing the second collection with HK based sketch artist The Ink Trail, furthermore we have artworks ready from a famous HK artist Anna Salenko. We plan to host our second event towards the end of July to showcasse the releases and announce further releases, in this event we want to use some of the profits from ticketing in order to fund NEAR wallets for our attendees. Through our previous release of Ruby Mazur's artwork we have onboarded 2 new users to the NEAR blockchain. We are in the talks with local NFT startups as (Whub) in attempts to devise a collaboration utilizing their Decentraland land. We have also talked with Hang Seng Bank to help them design NFTs, we are currently awaiting their response, ideally we can present the tools we outlined above as an incentive for them to open their own Mintbase store to meaningfully adapt the current web3 trends. We also partnered with a local firm The Rose Rituals on a project called ForkX, which will is a NFT pop up museum in Hong Kong, first event is scheduled for November 2022, details are being worked on as I am writing this grant proposal.

