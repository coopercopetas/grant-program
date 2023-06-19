# VeChain General Grant Application Template

## Project Overview 

- Project: Thisismagma
- Team Name: MAGMA SAS
- Payment Address: USDT (ERC 20) payment address. 


### Overview

Please provide the following:

- Magma is an intuitive platform designed to bring agility to the real estate industry. The Magme platform enables real estate stakeholders to create a unique digital asset of a building from a digital twin, which includes all the technical and contractual documentation of the building's objects and elements. This digital asset is called the Digital Twin Token (DTT®).

- We chose VeChain for the Digital Twin Token as this blockchain is based on the Proof of Authority consensus and so requires significantly low gas fees. Vechain's global plans to establish itself as the leader in sustainable and environmentally responsible blockchain solutions joins our approach on building a breakthrough platform for real estate which faces significant ESG challenges. Moreover our CTO jurgen Schouppe has extensive experience on the Vechain blockchain.

- To sum up :

    * Early investors and supporters of Vechain
    * Low Gas fee
    * Fee Delegation technology
    * Faster transaction confirmation times
 
- We will use MPP, ATP and also use the connex compatabible wallet from safehaven Comet to interact with the chain.

    * VIP180-181, ERC 1155, ERC 721
    * Comet
    * Connex
    * MPP
    * ATP

### Project Details

- Mockups/designs of any UI 

* 1
![P1. 1](https://github.com/thisismagma/media/blob/main/1.jpg)
* 3
![P2. 2](https://github.com/thisismagma/media/blob/main/2.jpg)
* 3
![P3. 3](https://github.com/thisismagma/media/blob/main/3.jpg)
* 4
![P4. 4](https://github.com/thisismagma/media/blob/main/4.jpg)


- API specifications of the core functionality

https://api-preprod.mymagma.com/api/#/default/HealthCheckController_getHealthCheck

* URL : Magma API
* Github : https://github.com/thisismagma/magma-api

user

GET /user
GET /user/searchByEmail
POST /user/permissions/default
POST /user/permissions
GET /user/stakeholders
POST /user/wallet
GET /user/types
POST /user/nda
POST /user/payment
building
GET /building
POST /building
DELETE /building
GET /building/types
POST /building/stakeholder
DELETE /building/stakeholder
POST /building/fields
GET /building/media/{fileUrl}
POST /building/media
DELETE /building/media
GET /building/media/activity
POST /building/media/activity
POST /building/payment


- An overview of the technology stack to be used

#### Technology stack
Front End:
- NextJS (React + Styled Components)

Back End:
- NestJS (NodeJS)
- we don't share publicy our infrastructure specs, upon requesrt we are happy to share this with the grant commitee privately


- PoC/MVP or other relevant prior work or research on the topic

https://app-preprod.mymagma.com 


### Ecosystem Fit
Other blockchain based real estate projects are globally focused on the sector's liquidity and fractional ownership issues.

Very few projects are really concerned about the environmental impact of the industry and its need of transparency and agility.
 
Magma is revolutionary in the sense that our platform creates an NFT of a building (and child NFT’s of all its components), not only to facilitate ownership, but also to keep an immutable and transparent record of the building's activity.

All the building's elements, objects and documents will be uploaded on Magma and their history will be recorded thanks to blockchain technology.

In addition, we created the Magma Index which evaluate the level of digitization of the building thanks to the data uploaded, but also to measure its environmental performance.
## Team 

### Team members

Matthieu Merchadou - CEO
Cooper Copetas - CIO
Jurgen Schouppe - CTO
Jonathan Wahnich - General Manager
Emre Palandöken - Product Owner 
Andy Demeulemeester - Senior Developer
Yoan Gross - Designer
Hrish Lotlikar - Advisor
Emmanuel François - Advisor
Anthony Carta - Advisor
Michael Benhamou - Advisory board

### Team Website

-  https://thisismagma.com

### Team's experience

Please describe the team's relevant experience. If the project involves development work, then we'd appreciated it if you can single out a few interesting codes commits made by team members on their past projects. 

### Team Code Repos

- https://github.com/thisismagma/magma-ui
- https://github.com/thisismagma/magma-api
- https://github.com/thisismagma/magma-token


### Team LinkedIn Profiles

Matthieu Merchadou - https://www.linkedin.com/mwlite/in/matthieu-merchadou-melki-18b50429
Jurgen Schouppe - https://www.linkedin.com/mwlite/in/jurgen-schouppe-084368119
Jonathan Wahnich - https://fr.linkedin.com/in/jonathan-wahnich-430bb515
Emre Palandöken - https://www.linkedin.com/mwlite/in/emre-palandoken
Andy Demeulemeester - https://www.linkedin.com/mwlite/in/andydemeulemeester
Yoan Gross - https://www.linkedin.com/mwlite/in/yoan-gross-038146153
Hrish Lotlikar - https://www.linkedin.com/in/hrishlotlikar
Emmanuel François - https://www.linkedin.com/mwlite/in/emmanuel-francois-63795232
Anthony Carta - https://www.linkedin.com/mwlite/in/anthony-carta-bim-manager
Michael Benhamou - https://www.linkedin.com/mwlite/in/michael-benhamou-510165

 

## Development Roadmap 

This section should break out the development roadmap into a number of milestones. Since the milestones will appear in the grant contract, it helps to describe the functionality we should expect, plus how we can check that such functionality exists in the product. Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered as expected.

Below we provide an <b>example roadmap</b>. For each milestone:

- Please indicate the milestone duration, workload in terms of full-time equivalent (FTE) and cost. 
- Please be sure to include a specification of the software. The level of details must be high enough so that we are able to verify that the software meets the specification.
- Please note that we require documentation (e.g. tutorials, API specifications, architecture details) in each milestone. This ensures that the code can be widely used by the community.
- Please provide a test suite, comprising unit and integration tests, along with a guide on how to run these.
- Please commit to providing dockerfiles for the delivery of your project.


### Example Roadmap for a dApp Application

#### Overview

|  | Milestone 1 | Milestone 2 | Total |
| - | - |- | - |
| Estimated Duration | 30 d | 30 d | 60 d |
| Full-time equivalent (FTE) | 2 | 1 | 3 |
| Cost (up to $ 30,000) | $ 5,000 | $ 10,000 | $ 15,000|

#### Milestone 1 — Smart Contract & Backend

| Number | Deliverable | Specification |
|-|-|-|
| 0a.| License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that can interact with the deployed smart contracts and backend service. |
| 0c. | Testing Guide | The code will have proper unit-test coverage (e.g. 90%) to ensure functionality and robustness. In the guide, we will describe how to run these tests |
| 1 | Smart Contracts | We will develop smart contracts that will...  (Please list the functionality that will be coded for the contracts) |
| 2 | Backend | "We will create a backend service that will... (Please list the functionality that will be coded for the backend)" |

#### Milestone 2  —  Frontend

...

#### Community engagement

As part of the Program, we require that you produce and publish at least one article/tutorial (e.g., on Medium). It should explain your work done as part of the grant.




## Future Plans

Magma aims to become a fully decentralized web3 platform.

We intend to become a decentralized autonomous organization, owned and governed by its stakeholders: real estate professionals.

Magma's future development plans, rewards and governance would be handled by the platform stakeholders.

 
## Additional Information 

Any additional information that you think is relevant to this application that hasn't already been included.

Possible additional information to include:
- What work has been done so far? 
V1.0 is in auditing phase
- Are there any teams who have already contributed (financially) to the project?
No
- Have you applied for other grants so far?
No
