# 📝 CampusThread

## 🌟 Project Overview

**Tagline**
The student internet—powered by Web3.
A global platform for 254 million students to connect, earn, and grow—powered by decentralized identity and token rewards on Polkadot.

**Brief Description**

CampusThread is a Web3-native student community platform for the 254 million+ global students to share updates (like tweeting), ask questions, connect across campuses, and earn through content creation. We’re building the social economy of the student world—powered by the $CAMP token and backed by an AdTech layer that allows advertisers to reach student audiences, while sharing revenue with student creators.

CampusThread empowers students to:

Create and monetize content

Engage with verified student communities

Participate in social challenges, global discussions, and gamified experiences

Tip or be tipped in $CAMP for valuable contributions


H**ow the Project Relates to / Integrates with Polkadot**:
CampusThread leverages Polkadot to:

Decentralized Student Identity (DID) — Using KILT Protocol, we enable privacy-preserving, verified student credentials without storing personal data. This adds trust to content, rewards, and ad targeting.

$CAMP Token on Polkadot — Our utility token is used for:

Creator rewards based on ad revenue and engagement

Fan tipping and unlockable premium content

Voting and community governance (DAO features)

Gamified experiences (e.g., CampusQuest)

Future NFT Use Cases — Students can mint achievement badges, collectibles, or marketplace items on a Polkadot parachain.

Interoperability — We plan to integrate with other Polkadot-based services (e.g., wallets, games, marketplaces), growing the token’s use and value across the broader ecosystem.

**Why We’re Building It:**
We believe students are the most overlooked demographic in Web3. They are social, tech-savvy, and always online—but existing platforms don’t reward them for their influence, time, or creativity.

We're building CampusThread because:

We want to give students ownership over their identity, content, and data.

We want to help students monetize their school life, not just survive it.

We want to create a trusted, verified social layer that brands can advertise on—while redistributing ad revenue to creators.

We believe Web3 can power the next social media revolution, and students are the ones who will lead it.



### 🔍 Project Details

### 🧱 **Technology Stack**
- **Frontend**: Flutter (for mobile/web cross-platform development)
- **Backend**: Firebase + Node.js Cloud Functions (currently powering core logic)
- **Web3 Integration**:  
  - **Polkadot Identity Layer** via **KILT Protocol** (for decentralized student verification)
  - **Smart Contracts** & Tokenization on **Polkadot/Substrate** (for $CAMP utility token logic)
- **Database**: Firestore (NoSQL, real-time database)
- **AdTech Integration**: Custom-built ad server with impression tracking and reward distribution
- **Analytics & Monitoring**: Firebase Analytics, Polkadot on-chain stats for token movement

### 🧩 **Architecture & Core Components**
- **CampusThread App**:  
  - Global student content feed (“tweet-like”)  
  - Verified student profiles (DID-powered)  
  - In-app wallet & tipping system using $CAMP  
  - Creator dashboard (earnings, impressions, tips)
- **Identity Layer**:  
  - DID verification using KILT + Firebase fallback for early users  
  - Backend service to validate issued credentials and manage wallet linkage
- **Token Reward Engine**:  
  - Smart contract (on Polkadot) tracking $CAMP distributions per activity  
  - Reward logic for content impressions, engagement, and referrals
- **AdTech Platform**:  
  - Advertiser onboarding dashboard  
  - Smart contracts for ad purchase, delivery, and automated revenue sharing with student creators

### 🧪 **PoC / MVP**
- MVP live with Firebase backend and Flutter frontend  
- Demo available on request (or we can link a test build)  
- Token distribution logic prototyped with mock data (ready for Substrate integration)  
- Identity verification simulated; KILT integration pending

### 🎨 **UI Mockups (Examples)**  
- Feed UI  
- Wallet & Earnings  
- Ad portal (admin + advertiser views)  
- DID verification flow  
> *(Mockups link or screenshots can be attached if needed)*


### 🔧 **Data Models / API Specs**
- **User**: id, DID, wallet address, school name, isVerified, totalEarned  
- **Post**: id, userId, content, media, timestamp, impressionCount, engagementScore  
- **AdCampaign**: id, advertiserId, budget, targeting, status, impressionsServed  
- **RewardLog**: id, userId, type (tip, ad, referral), amount, timestamp  

APIs are designed in REST (Firebase Cloud Functions) and will include hooks to interact with on-chain smart contracts on Polkadot.


### 🚫 **Out of Scope**
- CampusThread **does not** aim to:
  - Compete with or replace TikTok, Instagram, or mainstream social platforms
  - Provide full financial services (like DeFi lending/borrowing) in the initial phase
  - Verify *non-students* or include anonymous content creators (content quality & trust is key)
  - Store sensitive identity data on-chain—only proofs and hashes will be stored


## 🧩 **Ecosystem Fit**

### 🔗 **Where and how does your project fit into the ecosystem?**
CampusThread introduces **a new social and economic layer to the Polkadot ecosystem**, focused on **global student engagement**. By integrating **decentralized identity (DID)** through KILT Protocol and issuing a utility token ($CAMP) on Polkadot, the platform:
- Showcases **Web3’s ability to verify identity** and distribute rewards transparently at scale.
- Bridges **social networking**, **content monetization**, and **on-chain token economies** in a way that’s currently underrepresented in the Polkadot space.
- Acts as a **launchpad for young Web3 users**, onboarding millions of students into the Polkadot ecosystem.

---

### 🎯 **Who is your target audience?**
- **Primary Users**: 254 million+ university students globally—especially those in emerging markets with limited earning opportunities or online visibility.
- **Secondary Users**: Advertisers, brands, and recruiters interested in targeting the Gen Z student demographic with measurable ad ROI.
- **Web3 Audience**: Builders, DAOs, and DeFi protocols looking to tap into a verified student base for partnerships, growth, or community engagement.

### 💡 **What need(s) does your project meet?**
1. **Verified Identity in Web3**: Students often lack a verifiable, privacy-preserving identity layer. CampusThread uses Polkadot’s KILT Protocol to enable student-only communities and rewards.
2. **Content Monetization for Students**: Students create viral, valuable content daily but rarely monetize it. $CAMP rewards them for impressions, engagement, and tipping.
3. **AdTech Transparency**: Traditional student platforms hoard ad revenue. Our system shares it transparently using smart contracts and on-chain tracking.
4. **Global Connection**: Many students are isolated by geography or lack access to global education communities. CampusThread breaks this barrier.
5. **Token Utility & Economic Literacy**: Students learn how crypto works through daily use of $CAMP—earning, tipping, unlocking perks, and participating in DAO-like activities.


### 🧪 **Are there any similar projects in the Polkadot ecosystem?**
Not currently. While some Polkadot projects explore:
- **Gaming (Moonbeam, Astar)**
- **DeFi (Acala, HydraDX)**
- **DID (KILT)**

…no existing platform combines:
- A **global social network** tailored for students
- A **verified identity system**
- An **AdTech revenue-sharing model**
- And a **utility token economy** for student creators


### ❓ **Why might such a project not exist yet?**
- **Focus on infrastructure over user-facing apps**: Polkadot has prioritized infrastructure (parachains, bridges, DeFi) over social/Web3-native communities.
- **Lack of specialized focus**: Building for students requires understanding education, identity, monetization, and content—all at once.
- **Token mechanics for social engagement** are still evolving, and CampusThread is leveraging best practices learned from past experiments like $STEPN or $AUDIO but adapted for students.


## 👥 Team

- **Team Name:** Name of your team. If you apply as a legal entity, please use its name.
- **Contact Name:** Full name of the contact person in your team
- **Contact Email:** Contact email
- **Website:** Your website, GitHub org, blog, or similar

### Team members

Please list the legal name of all grant beneficiaries. Solo developers (1-person teams) are eligible for funding.

#### LinkedIn Profiles (if available)

- https://www.linkedin.com/{person_1}
- https://www.linkedin.com/{person_2}

### Team Code Repos

- https://github.com/{your_organisation}/{project_1}
- https://github.com/{your_organisation}/{project_2}

Please also provide the GitHub accounts of all team members:

- https://github.com/{team_member_1}
- https://github.com/{team_member_2}

### Team's experience

Please describe the team's relevant experience, including any previous blockchain projects or contributions to the ecosystem.

## 📊 Development Status

If you've already started implementing your project, please provide a link and a description of the code. Otherwise, please provide some documentation on the research and other work you have conducted before applying.

## 📅 Development Roadmap

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, please describe *the functionality we should expect in as much detail as possible*, plus how we can verify and test that functionality.

**Important notes:**
- Each milestone is capped at **$5,000 USD**
- Milestones must be delivered within **3 months** of approval
- The maximum grant amount is **$10,000 USD** per application (up to **$15,000 USD** per project in exceptional cases)
- You will only receive payment after successful milestone delivery

### Overview

- **Estimated Duration:** Duration of the whole project (maximum 3 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project
- **Total Costs:** Requested amount in USD for the whole project (maximum $10,000 USD)

> Note that deliverables 0a to 0d are mandatory. Please adapt their specification to your project.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can... |
| 0c. | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Article | We will publish an **article** that explains what was done/achieved as part of the grant. |
| 1. | Feature X | We will create a feature that will... (Please describe in detail) |
| 2. | Feature Y | The Y feature will... (Please describe in detail) |
| 3. | Feature Z | The Z feature will... (Please describe in detail) |

### 💰 Budget Breakdown

Please provide a breakdown of your budget by milestone:

| Milestone | Deliverables | Cost (USD) | Estimated Completion |
| --- | --- | --- | --- |
| 1 | Features X, Y | $5,000 | 1.5 months |
| 2 | Feature Z | $5,000 | 1.5 months |
| **Total** | | **$10,000** | **3 months** |

## 🔮 Future Plans

Please include:

- How you intend to continue development after the Fast-Grant
- Any plans for seeking additional funding (other grants, VC funding, etc.)
- Your vision for the project's growth and impact in the Polkadot ecosystem

## ℹ️ Additional Information

Here you can add any additional information that you think is relevant to this application, such as:

- Work you have already done
- If there are any other teams who have already contributed to the project
- Other funding you may have applied for

Remember that the Fast-Grants Programme is designed as a first step for promising projects. We're looking for projects that can continue to grow beyond this initial funding.
