# 🌐 MNS - Minima Naming System


[![Minima Compatible](https://img.shields.io/badge/Minima-Compatible-blue)](https://minima.global)
[![Smart Contracts](https://img.shields.io/badge/Smart%20Contracts-MAST-purple)](https://docs.minima.global)
[![License](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
<br>
[![Status: Development](https://img.shields.io/badge/Status-95%25%20Complete-green)]()

## 🌟 Overview

The Minima Naming System (MNS) is a revolutionary decentralized and censorship resistant naming and identity protocol built on the Minima blockchain. 
Powered entirely by **smart contracts** and **edge-first networks**, 
it transcends traditional domain functionality by enabling unique ID identities, profiles, payments, subscriptions, DAOs, services, oracles, and networks IoT and machine to machine interactions - all seamlessly integrated with Minima, Maxima and Omnia layers.

The **MNS**, combined with the **Mega Network** and **Micro Network**, forms the foundational infrastructure to expand the Minima ecosystem toward mass adoption, creating an incredibly powerful and flexible framework for building any system, service, or network imaginable.

- Decentralized registry and resolution (no centralized servers).
- Smart-contract–enforced ownership and actions.
- Mega Network (general purpose) + Micro Network (purpose built) for resilient discovery.
- Configurable economics to fund the ecosystem (up to 50% of revenue goes to growth and incentives).


## 🎯 Key Features

### Core Functionality
- **🆔 Unique Digital Identities** - Human-readable names instead of complex addresses, for users, IoT devices, services and networks
- **💸 Seamless Payments** - Send/receive funds using domain names (including OMNIA payments)
- **👥 Profile Networks** - Out of the box provide a kind of decentralized LinkedIN
- **🌐 Decentralized Service Networks** -  Deploy decentralized services on mobile/server clusters using domain names
- **🔗 Oracle Networks** - Easy-to-build oracle systems with conditional triggers, member identification, voting systems, treasury management
- **🏛️ DAO Governance** - Complete decentralized organization management
- **📧 ChainMail Integration** - Link your domain name with your chanmail email for easy usage
- **🌐 Web Links** - Connect to dApps and websites
- **🔄 BUY** - Acquire unique domain names
- **💰 SELL** - Trade domains in secondary markets
- **🔁 RENEW** - Extend domain ownership
- **➡️ TRANSFER** - Transfer domains to other minima node
- **✏️ MODIFY** - Update domain data and configurations


### Advanced Capabilities
- **🤖 AI & Machine & IoT Networks** - Machine-to-machine communication and payments
- **📦 Supply Chain Tracking** - Peer-to-peer supply chain solutions
- **💬 Decentralized Chat Groups** - Censorship-resistant communication platforms
- **🔄 Automated Services** - Bot networks and automated systems
- **🔶 Decentralized Clusters** - User-run service networks, mobile device participation, reward mechanisms for node operators

## 🏗️ Architecture

### 1. Pools Board Contract
The company/DAO entity, creates, configures and publish all available domain pools with configurable parameters, and also feeds in the initial amount of available domain tokens for all pools:

```KISS MAST contract Capabilities
// Key Features:
- One pool per domain extension (e.g., .minima, .service, .oracle)
- Configurable pricing models and fee distributions
- Flexible conditions and restrictions
- Automated smart contract governance
- No third-party dependencies
```

**Key Benefits:**
- **Fully Autonomous** - Once deployed, runs entirely via smart contracts
- **Flexible Configuration** - Customizable fees, prices, and restrictions
- **Transparent** - All operations visible on-chain
- **Fine Grained constrains** - Company and community driven configuration on pools:
  - Give full control to companies of their own domains names extensions to be  delivered to their employees driven by specific tokens ownership 
  - Launch ear-drops for getting free domains or special discounts on specific pools for communities

### 2. Dynamic MNS Token Contract
Each domain name exists as a unique dynamic smart contract:

```javascript
// Dynamic Address Calculation:
domain_contract_address = hash(domain_name + tokenid + MAST_contract_template)

// KISS MAST Contract Capabilities:
- Domain ownership management
- Data storage and modification
- Profile configuration
- Payment routing configuration
- Service integration points
- Automated updates (e.g., Maxima address synchronization)
```

**Key Benefits:**
- **Censorship Resistant** - Only domain owner can manage their domain
- **Unique Identity** - Each domain has its own smart contract address
- **Extensible** - MAST contracts enable complex functionality

### 3. Management & Distribution DApp
Centralized administration interface for system management:

- **Token Creation & Distribution**
- **Pool Configuration & Deployment**
- **Fee Structure Management**
- **DAO Governance Integration** (future)

### 4. Network Infrastructure

#### Mega Network
- **Purpose**: Multi-purpose network for general queries
- **Nodes**: MMR and ARCHIVE nodes
- **Hosting**: Servers/cloud infrastructure
- **Communication**: Maxima protocol
- **Use Case**: Domain availability checks, general system queries on spent/unspent coins and their data and states which leads to a general purpose network to lookup and discover third parties services and networks.

#### Micro Network
- **Purpose**: Dedicated MNS-specific network, Community-driven infrastructure
- **Nodes**: Mobile MMR nodes
- **Hosting**: User mobile devices
- **Tracking**: MNS tokens exclusively
- **Use Case**: Censorship-resistant domain verification and small services


## 💰 Economic Model

### Revenue Distribution
Up to 50% of every domain purchase is allocated to ecosystem growth and can be different for every pool depending on companies partnerships, commercials and so on, for instance:

```
📊 Revenue Allocation:
├── 20% Mega Network incentives
├── 15% Micro Network incentives
├── 10% Commercial development
└── 5% Community project grants
```

### Domain Pricing
- **Variable Pricing** - Based on name length, popularity, commercials and partnerships
- **Manual/Dynamic Adjustment** - Adapts to MINIMA price fluctuations
- **Renewal Fees** - Sustainable long-term maintenance

## 🔒 Security & Decentralization

### Censorship Resistance
- **Dual Network Architecture** - Mega + Micro networks provide redundancy and censorship resistant
- **Mobile-First Micro Network** - Difficult to target or shutdown
- **Smart Contract Governance** - No central points of control

### Security Features
- **Cryptographic Ownership** - Only private key holders can manage domains
- **Transparent Operations** - All changes recorded on-chain
- **Upgradable Contracts** - MAST-based flexibility without compromising security


## 📈 Project Status

### ✅ Completed
- [x] Proof of Concept (Simple Contracts)
- [x] Proof of Concept (MAST Contracts)
- [x] New Mobile-Responsive Frontend Development
- [x] 95% Core Functionality Implementation

### 🔄 In Progress
- [-] Frontend Migration to MAST POC
- [-] Concurrency Issue Resolution
- [ ] Dynamic Pricing Implementation
- [ ] Price Update Mechanisms

### 📋 Pending
- [ ] Automated Maxima Address Updates
- [ ] Service.js Integration
- [ ] Advanced Oracle Functionality
- [ ] Mobile Network Functionality (Micro network)

[𝕏 Follow us on X](https://twitter.com/MNS_labs)
