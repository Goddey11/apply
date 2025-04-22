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


## 👥 Team members

- **Team Name:** Ojewoye wale Goddey
- **Contact Name:** Ojewoye wale Goddey
- **Contact Email:** ojewoyegoddey.ogd@gmail.com
- **Website:** Your website, GitHub org, blog, or similar


#### LinkedIn Profiles (if available)
https://www.linkedin.com/in/wale-goddey-857249167/


### Team Code Repos

- https://github.com/{your_organisation}/{project_1}
- https://github.com/{your_organisation}/{project_2}

Please also provide the GitHub accounts of all team members:

- https://github.com/Goddey11


## 👥 **Team's Experience**

The **CampusThread** team consists of passionate builders with experience across Web2 and Web3 product development, mobile applications, and smart contract integration. Highlights include:

- **Lead Developer & Founder**: 5+ years in full-stack development, mobile-first platforms, and Firebase backend infrastructure. Recently built a crypto trading bot (“Bridge Capital”) with historical performance testing and exchange integration (Bybit API, Python/Node.js, Cloud Functions).
- **Web3 Integration**: Experience working with smart contracts, ERC-20 token creation, and token reward mechanics. Actively researching Polkadot's identity layer (KILT) and Substrate-based token issuance.
- **Community & AdTech Background**: Experience creating student-facing platforms and influencer growth tools (TikTok-based growth app), giving insight into content monetization and viral growth strategies.
- **Design/UX**: Prior design and UX research experience on social platforms, including layout mockups and responsive UI for cross-platform deployment.

While this is our **first Polkadot-native project**, our team is excited to transition from centralized systems to Web3-native experiences, leveraging Polkadot’s identity, scalability, and multichain architecture.


## 📊 **Development Status**

The project is in the early stage of development, with the following components already underway:

### ✅ **Completed**
- MVP mobile app mockups (built using Flutter & Firebase backend)
- Firebase-hosted real-time database schema for posts, user profiles, likes, and ad modules
- Community engagement module for student-generated content (Q&A, hashtags, local campus feeds)
- Initial documentation and architecture for $CAMP utility token and monetization system

### 🔗 **Links**
- [GitHub Repository (Private)](https://github.com) *(Access can be granted upon request)*  
- [UI Mockup Sample (Figma)](https://figma.com) *(Link available for reviewers)*  
- [Litepaper (Draft)](https://notion.so/campusthread-litepaper) *(Describes tokenomics and roadmap)*


## 📅 **Development Roadmap**

Below is a detailed roadmap broken into **two milestones** (as required by the Fast-Grant structure), with verifiable deliverables for each.


### 🚩 **Milestone 1: Decentralized Identity Integration & MVP Platform (3 months)**  
**Grant Requested**: $5,000

**Deliverables:**
- ✅ DID integration using **KILT Protocol** to create verifiable, privacy-preserving student identities.
- ✅ School email/domain verification + frontend DID display on profile.
- ✅ Firebase-to-KILT sync for verified accounts (linking Web2 to Web3).
- ✅ Launch MVP of CampusThread mobile app (Flutter):  
  - Student sign-up, post/tweet, follow, and local feed  
  - Firebase backend for storing content  
  - Admin dashboard for content moderation

**How we’ll verify it:**
- Public testnet account creation using KILT  
- Linkable DID display in the app  
- GitHub repo + testflight/Android APK of MVP  
- Demo video walkthrough

---

### 🚩 **Milestone 2: $CAMP Token Deployment & Ad Monetization (3 months)**  
**Grant Requested**: $5,000

**Deliverables:**
- Deploy $CAMP token on **Polkadot parachain** (via Moonbeam or similar chain)
- Smart contract logic for token distribution:
  - Based on impressions, verified posts, and engagement
  - Tipping system integrated in frontend
- AdTech module MVP:
  - Admin ad submission panel (basic targeting)
  - Ad-to-content mapping logic
- Creator earnings dashboard (tokens earned per post)

**How we’ll verify it:**
- Token smart contract published (with address on Polkadot parachain)  
- Live demo of tipping & ad earning  
- GitHub code for distribution logic  
- Screenshots + demo of earnings dashboard

Great — based on the Polkadot grant guidelines, here’s how we can structure your **milestone and budget plan** to maximize your chances of approval (within the $10,000 USD limit):

---

## 🧱 Milestone Plan & Budget Breakdown

### 🔹 Overview
- **Estimated Duration**: 3 months  
- **Full-Time Equivalent (FTE)**: 2  
- **Total Cost**: $10,000 USD  
- **License**: MIT License

---

### ✅ Milestone 1 – DID Integration & Creator Rewards Module (1.5 months) – $5,000

| Deliverable | Specification |
|------------|----------------|
| **0a. License** | MIT License |
| **0b. Documentation** | Provide inline code documentation + a user-friendly guide explaining DID onboarding and reward logic |
| **0c. Testing and Guide** | Unit tests for DID verification flow and creator reward calculation. Testing guide included. |
| **0d. Article** | Publish a blog post explaining how CampusThread leverages KILT Protocol for student identity and rewards creators with $CAMP |
| **1. DID Integration with KILT Protocol** | Build a module to let users verify student status using KILT. Integrate into onboarding flow. Store proof hash (not sensitive info) on chain/off-chain securely. |
| **2. Creator Rewards Engine** | Implement logic to track engagement (likes, shares, comments) and distribute $CAMP based on post performance. |

---

### ✅ Milestone 2 – Tipping System, Token Faucet, and AdTech Revenue Pool (1.5 months) – $5,000

| Deliverable | Specification |
|------------|----------------|
| **0a. License** | MIT License |
| **0b. Documentation** | Inline code comments and a simple tutorial on tipping, ad revenue, and faucet system |
| **0c. Testing and Guide** | Unit tests for tipping transactions, faucet claim logic, and ad revenue pool distribution. Detailed test instructions. |
| **0d. Article** | Publish article on CampusThread’s Web3 monetization—how students earn from engagement, fans, and ads |
| **3. Tipping with $CAMP Token** | Build a tipping module for in-app and external use (e.g. TikTok creators). User can tip in $CAMP via wallet or app. |
| **4. Faucet System** | Implement faucet for new users to earn a small $CAMP reward after identity verification to encourage onboarding. |
| **5. Ad Revenue Distribution Pool** | Set up logic to distribute ad revenue ($CAMP) to verified creators whose posts hosted ads. Include admin dashboard (basic) to view impressions and payouts. |

---

## 💰 Summary Table

| Milestone | Deliverables                        | Cost (USD) | Estimated Completion |
|----------|--------------------------------------|------------|-----------------------|
| 1        | DID Integration, Rewards Module      | $5,000     | 1.5 months            |
| 2        | Tipping, Faucet, Ad Revenue Pool     | $5,000     | 1.5 months            |
| **Total** |                                      | **$10,000** | **3 months**          |


Here’s a polished draft of the final sections to complete your Fast-Grant application:

---

## 🔮 Future Plans

Following the Fast-Grant, our focus will be on **scaling CampusThread from a functional MVP to a thriving ecosystem** of students, brands, and Web3 contributors.

### 🔧 Post-Grant Development Plans
- **Decentralized Storage Migration**: Transition from Firebase to IPFS/Filecoin or Crust Network for privacy-preserving post and profile storage.
- **In-app DAO Governance**: Enable token holders to vote on feature proposals and university onboarding.
- **Cross-Chain Compatibility**: Explore integrations with Polkadot parachains like Astar or Moonbeam for smart contract expansions.
- **Mobile Wallet Integration**: Build a lightweight wallet directly into the app to simplify $CAMP onboarding and transactions.
- **Campus Ambassador Program**: Recruit student leaders globally to onboard their peers and create local communities.

### 💰 Additional Funding Plans
We plan to raise additional capital through:
- **VC Pre-Seed / Seed Round**: Following this grant, we will raise capital from blockchain-native funds focused on social, gaming, and Gen-Z adoption.
- **Other Grant Programs**: Apply to:
  - Moonbeam Grants (for mobile DApp development)
  - KILT Builders Program (for deeper DID integrations)
  - Web3 Foundation Open Grants (for DAO tooling)
- **Community Crowdsale (planned Q4 2025)**: Offer $CAMP tokens to early users and contributors.

### 🌍 Vision for Growth in the Polkadot Ecosystem
CampusThread aims to become the **default Polkadot-native social identity and monetization layer for students** worldwide. Our goal is to:
- Bring millions of Gen-Z users into Polkadot through a real-world use case
- Promote **decentralized identity as a norm** for student verification and academic credentials
- Showcase a new **AdTech model** where creators share in the upside transparently

---

## ℹ️ Additional Information

### ✅ Work Completed So Far
- Flutter frontend for MVP (completed and tested)
- Firebase-based backend for user auth, feeds, and profile management
- Tokenomics, distribution plan, and DID architecture (via KILT) designed
- Ongoing user testing with student creators in Nigeria, India, and the Philippines

### 🤝 Collaborators
- **In-house team**: 4 members (PM, Flutter dev, Firebase engineer, tokenomics lead)
- **KILT Protocol**: Consultation on DID modules
- **Moonbeam Ecosystem**: Exploring Substrate-based deployment

### 💵 Other Funding Applied
- None yet granted. This Fast-Grant will be our first official funding to date.
