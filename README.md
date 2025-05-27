# Kleidi: An Incentive-Aligned Fraud Prevention Network

**Author:** Elliot Friedman
**Date:** May 27, 2025
**Version:** 1.0

## Abstract

Infrastructure providers across the cryptocurrency ecosystem lack direct economic incentives to prevent fraudulent transactions. This paper proposes Kleidi, a decentralized Fraud Prevention Network for account abstraction wallets. Validators stake collateral, earn rewards for blocking malicious transactions and incur penalties for reporting false positives. This design aligns infrastructure providers' economic incentives with user security outcomes and has the potential to reduce losses from hacks and scams.

## White Paper

**[Download PDF](./Kleidi-Whitepaper.pdf)**

## Overview

Kleidi addresses a fundamental gap in cryptocurrency security: while sophisticated fraud detection capabilities exist offchain, they remain disconnected from onchain transaction execution. Current infrastructure providers (wallets, RPC providers, validators) earn fees regardless of transaction legitimacy, creating weak economic incentives to protect users.

**Key Innovation:** Kleidi creates the first economically viable mechanism for real-time fraud intervention by:
- Incentivizing specialized validators to protect users through economic rewards
- Penalizing false positives through slashing mechanisms  
- Transforming fraud prevention from a costly externality to a core economic component of transaction processing

## Key Features

- **Economic Incentive Alignment** - Validators earn rewards for successfully blocking fraud
- **Account Abstraction Integration** - Leverages programmable wallets for seamless integration
- **Real-time Protection** - Pre-transaction review and blocking capabilities
- **Decentralized Governance** - Dispute resolution through bonded review councils
- **Opt-in Security** - Users choose to route transactions through fraud prevention screening

## Paper Structure

1. **Introduction** - The incentive gap in crypto vs traditional finance
2. **Problem Definition** - Current infrastructure provider incentives 
3. **Solution Architecture** - Kleidi's fraud prevention network
4. **Economic Mechanisms** - Incentive structure, slashing, and reputation systems
5. **Technical Implementation** - Transaction flows and security considerations
6. **Prior Art Analysis** - Comparison with existing solutions
7. **Conclusion** - Bridging offchain intelligence with onchain execution

---

*This paper represents ongoing research into cryptocurrency security mechanisms and economic incentive alignment.*