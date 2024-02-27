# TwiTez: Web3 microblogging Smart Service


## Project Overview :page_facing_up:


Empowering Connections on the Decentralised Web: TwiTez, Your Smart Social Network.

### Overview

With the growth of the Democratic deficit, the rise of autocracy and the total disability of the overgrown bureaucracy all over the world, the same trends are evident in the structure of the internet and today's social media platforms.

TwiTez is a social media platform that empowers users with control over their data and interactions. The protocol will be distinguished from other platforms by its foundation of decentralised ownership and data access, and censorship resistance. It will offer a seamless experience for sharing multimedia content, engaging with other users through such interactions as "reactions" and comments, and conducting direct token transfers. 
<br>
<p align="center">
  <img src="https://github.com/twitez/testnet/assets/129535429/d5e3e0eb-8d24-41f8-9b09-d9037ff857dc">
</p> 
<p align="center">
<code>User reactions</code>
<br>
<br>

TwiTez is being developed as a set of Smart Services, providing users the ability to interact with other users through communication, as well as interact with other services in the Tezos ecosystem based on an open API: marketplaces (showcasing, buying, and selling NFTs), DeFi services (buying and exchanging tokens), games (authorisation, messaging), and so on.


### Project Details

The system consists of two parts:

- **The client application (webApp)** provides convenient access to the functionality of the system core for the user.

- **The system core** is a set of smart contracts deployed on the blockchain, which store data and implement rules of user interactions.

The functionality of the system can be divided into three logical user roles:

- Author functionality
- Reader functionality
- System administrator functionality
<br>
<p align="center">
  <img src="https://github.com/twitez/testnet/assets/129535429/c3a9b739-0c3b-4ac6-8392-d8489b1d583a">
</p>
<br> 
<p align="center">
<code>TwiTez: Use Case Diagram</code>
</p>
<br>

The functionality of the author and system administrator will require user authorisation in the system (administrating functionality will be transferred to the DAO-smart service for community governance in the future).

### Structure 

TwiTez is a fully decentralised application based on SmartSOA (smart service-oriented architecture), it's core smart services include:

- **Registration Service** <br>Registers new users and sets up their personalised Smart Services.
- **User Smart Services** <br>Store, manage and enable user data interaction.
- **Message Service** <br>Messaging interactions.

Other Smart Services provide additional functionality. Here are some examples:<br>  
- **Advertising Service** <br>Enables advertisers to create and run campaigns on TwiTez, rewarding users who share their content according to set rules.
- **Donation Service** <br>Allows users to financially support content creators they find interesting directly.
- **NFT Marketplace Service** <br>Facilitates the direct sale of NFTs created by authors on TwiTez.
- **Voting Service** <br>Allows users to participate in voting.
<br>
<p align="center">
  <img src="https://github.com/twitez/testnet/assets/129535429/2a5c8975-6366-4817-a5d0-3d730f564b74">
</p>
<br>
<p align="center">
<code>TwiTez: Component Diagram</code>
</p>
<br>
Interactions example of different components for some business processes can be seen from the Sequence Diagram<br>
<br>

<p align="center">
  <img src="https://github.com/twitez/testnet/assets/129535429/73ad76b5-c5bb-46b3-b49f-0dd8845d2c95">
</p>
<br>
<p align="center">
<code>TwiTez: Sequence Diagram</code>
</p>
<br>


### Technology Stack

- Michelson
- SmartPy
- IPFS
- HTML / CSS / JS / Frameworks for the frontend


### Ecosystem Fit

Decentralised social networks are essential for resisting censorship, especially in regions where internet freedom is threatened. The rising trend of such censorship is alarming. However, TwiTez aims to bolster the potential of the Tezos ecosystem, enhance user engagement, promote cross-chain interoperability, and uphold privacy and data ownership.<br>

We maintain regular communication with the Tezos community and lead the developing team regarding adjustments to the technological structure of the protocol.<br>

We have already identified potential collaborators and are eager to begin engaging with them. We're confident that a decentralised future is possible only through the collaboration of decentralised teams and the automation of services. This understanding has driven our commitment to the concept of Smart Services within the Tezos ecosystem, which is well-known for its autonomy, activity, and support for developers.<br>



## Demo: Web UI ##

<br>
<p align="center">
  <img width="640" src="https://github.com/twitez/testnet/assets/129535429/0a918ef0-78b6-410b-a01c-304735fee127">
</p>
<p align="center">
<code>Feed wall view</code>
</p>
<br><br>

<p align="center">
  <img width="640" src="https://github.com/twitez/testnet/assets/129535429/f53aded7-ea48-440f-98a5-7190c9175484">
</p>
<p align="center">
<code>Message page view</code>
</p>
<br><br>

<p align="center">
  <img width="640"  src="https://github.com/twitez/testnet/assets/129535429/00543c0d-96dc-4122-83ca-66c183d6fb03">
</p>

<p align="center">
<code>User edit profile view</code>
</p>
<br><br>

<p align="center">
  <img width="640" src="https://github.com/twitez/testnet/assets/129535429/cb9f2fee-ab64-4b80-a192-4ff4c12586dc">
</p>
<p align="center">
<code>User profile</code>
</p>
<br>

## Team :busts_in_silhouette:

### Team members

- Core Team:
    - **German Korjagin**
    - **Sergei Pangin**


### Contact

- **Contact Name:** German Korjagin
- **Contact Email:**  g.ko@deus4.com


### Team's experience

- **German Korjagin** <br>15 years of experience in data science, analytics, software and business development. Expertise in cyber security, digital payments and analytics. Proficient knowledge of blockchains and DAGs.<br>

- **Sergei Pangin** <br>Skilled and qualified software developer with 20+ years of experience and the practice of software design, project management and team leading,  proficient in financial services development, with in-depth knowledge of Ethereum, IOTA, and Tezos platforms.


### Team Code Repos

- https://github.com/opdev3<br>
- https://github.com/opdev7<br>
- https://github.com/vendev1<br>
- https://github.com/HelixNetwork/pendulum<br>

### Team LinkedIn Profiles

- https://ee.linkedin.com/in/german-korjagin-833ab8236

## Development Roadmap :nut_and_bolt:

The team plans to release the system sequentially in two versions:<br>

- **Beta Release:** Live on the TestNet ([link](https://twitez.github.io/testnet/)). Includes implementation of the main functionality of the system for readers, authors, and system administrators, which will allow functionality testing for each user role and obtaining initial feedback from test users.<br>

- **Release Version:** This release will include enhanced functionality from the beta release, with additional features for all user roles. Administrator functionality will be limited in terms of access to user data for the reader and author roles. Full documentation will be provided also.<br>


### Existing Functionality

**Basic**

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | License |  MIT  |
| 1. | User registration and user profile | The ability to create and customise a user profile, which is one of the core features of the present and future product roadmap. <br> - Smart Contract. Development of User profile structure, implementation of API for registration and profile management as Registration and User components features. <br> - Web App. Implementation of UI together with the corresponding client-side logic for user registration and user profile editing. |
| 2. | Posting functionality | This functionality allows users to write and publish posts. <br> - Smart Contract. Development of the message structure and implementation of API to store messages as the Messages component. <br> - Web App. Implementation of UI and the corresponding client-side logic for creating messages. |
| 3. | Interactive posting interactions | Functionaltity for interactions with posts, such as *comments*, *reposts* and *reactions*. <br> - Smart Contract. *Comment* and *repost* features will be added to the Message component. API for the *reactions*-feature will be implemented as a Reactions component. <br> - Web App. Implementation of UI and the corresponding client-side logic for user interaction with posts. |
| 4. | System users interaction | Basic functionality for direct interactions between users, such as *search* and *follow*. <br> - Smart Contract. Development of the user-following structure and implementation of API for the *follow*-feature as *Following* components. <br> - Web App. Implementation of the corresponding client-side logic to provide the *follow*-feature, an indexer API for the *search*-feature will be used to get user data. |

**Advanced**

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 5. | Multimedia posting | Support for images and YouTube videos. <br> - Smart Contract. Message structure update for the advanced message data support. <br> - Web App. Implementation of the corresponding client-side logic and UI for adding images and videos to user messages. |
| 6. | Interactive posting interactions II | Adding the message to *favourites*. <br> - Smart Contract. Development of the *favourite* structure, and implementation of API to collect posts. <br> - Web App. Implementation of UI and the corresponding client-side logic for adding messages to users' *favourites* as well as a list of *favourite* messages. |
| 7. | Direct token transfer | The functionality which allows users to transfer tokens to other users without leaving the service, as well as to send and receive donations in these tokens. <br> - Web App. Implementation of the corresponding client-side logic and the UI for token transfers. |
| 8. | User statistics (in development) | Number of posts, replies, reactions etc. <br> - Smart Contract. Adds stats fields to structures and implements the corresponding functionality. <br> - Web App. Display authors and message stats for users. |
| 9. | Functionality for the administrator (in development) | Interface for users authorised as system administrators. Functionality is designed to ensure optimal system operation and provide convenience for other user roles in the system: reader and author. <br> - Smart Contract. Implementation of some admin features in the contract configuration parameters (e.g. username and message length, maximum number of followers, etc.) that will make TwiTez optimal and user-friendly. |


## Future Plans

**1. Registration Smart Service (working title - AccounTez)** <br>
- DNS user names mapping and comparison to their corresponding addresses for personal Smart Services.
- NFT/SBT user account-profile functionality development;
- Plug-and-play system development for the purpose of integrating different services within the Tezos ecosystem;
- Separating the functionality into a standalone service (working title - “AccounTez");
- Creation of API tools for third-party developers to interact with the service;
- Audit of the service;
- Opensource’ing it all.

**2. New TwiTez structure** <br>
- TwiTez rollup;
- Personal service-contract: 
  - Implementing a separate user-specific smart contract to enable decentralised data processing and ownership. Users will have control over their data and can assign roles to others, customising their service according to their needs.
  - This will enhance security and facilitate future feature development.
- NFT-posting (possibility to mint NFT-post (text, images, etc.)) directly from the user's personal service contract.

**3. New functionality and Integrations** <br>
- New structure will allow development and launch of API for interacting with other blockchain services;
- Extended functionality for token transfers;
- Integration of an already existing service in the Tezos ecosystem for voting;
- Advertising Smart Service development for the direct interaction between creators and advertisers;
- User interface web updates.
