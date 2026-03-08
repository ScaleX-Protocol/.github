# ScaleX

ScaleX is the **Most Capital Efficient and Safe DApp for Agent and Human** — a unified platform where you can trade, lend, and predict while your capital automatically earns yield. Every deposited dollar mints **sxToken** — a yield-bearing token that works across all three products simultaneously. For those who want to automate, ScaleX provides an **Agent** layer that executes strategies on your behalf within rules you define — non-custodial, on-chain, policy-enforced via **Chainlink CRE**, and fully accountable.

---

## Problems with Current Trading Tools

### 1. Missed Entries, Human Limits
- **Sleep is a Liability**: Good setups happen at 3AM. Most traders miss them entirely.
- **Emotion and Fatigue**: Manual trading introduces fear, greed, and exhaustion into every decision.
- **No Trustworthy Automation**: Copy trading copies human flaws. Sniper bots race each other to the bottom. LLM agents act with no guardrails and no accountability.
- **No Agent You Can Actually Trust**: No existing tool gives you an autonomous assistant with a verifiable track record and on-chain identity.

### 2. Capital That Sits Idle
- **Idle Trading Capital**: $100,000 deposited on an order book CEX/DEX earns zero yield when not actively filling.
- **Unproductive Limit Orders**: Billions in liquidity sit in order books waiting for execution, generating zero return.
- **Manual Asset Management**: To earn yield, traders must manually move funds to separate lending accounts, sacrificing trading access.
- **Lost Opportunities**: Your portfolio either trades or earns. It was never designed to do both at once.

### 3. Forced to Choose: Trade or Earn
- **Fragmented Protocols**: One protocol for trading, another for lending, two sets of gas fees, two interfaces, two sets of risk.
- **Zero Borrowing Power on DEXes**: Deposited trading balances have no collateral value on CEX/DEX platforms.
- **Extra Collateral Required**: To access leverage, traders must deposit separately, locking up even more idle capital.
- **No Unified Capital Layer**: There is no single system that lets your portfolio trade, earn, and borrow simultaneously.

### 4. Liquidation with No Defense
- **Forced Market Sells**: Lending protocols liquidate at market price during crashes, devastating slippage with no warning.
- **Helpless Watching**: Users watch collateral get sold at the worst possible prices, unable to intervene.
- **No Strategic Conversion**: Can't pre-position to stable assets before liquidation triggers.
- **ADL and Insurance Funds**: Platforms compensate for bad liquidation design with systems that socialize losses onto other traders.

### 5. No Identity or Accountability for Agents
- **Black-Box Execution**: Existing AI agents have no on-chain history. You can't audit what they did or verify their track record.
- **No Trust Without Keys**: To automate anything, most setups require sharing private keys or full custody.
- **No Reputation System**: There is no way to compare agents, verify their strategy, or hold them accountable.
- **No Monetization Standard**: Agent developers have no standard way to charge for their strategies fairly.

---

## ScaleX Unified Solution

### 1. Your Private Trading Agent
- **Policy-Bound Execution**: The agent acts only within rules you define, max trade size, allowed pairs, time limits, risk thresholds.
- **No Keys Shared**: Delegation without custody. The agent is authorized, not trusted with your keys. Revoke and it stops.
- **24/7 Coverage**: Monitors markets around the clock, places orders at your target prices, never sleeps, never panics.
- **Emotion-Free Strategy**: Pure execution, no fear, no greed, no fatigue. Your strategy runs exactly as designed.

### 2. Capital Efficiency Solution
- **Auto-Yield on Deposits**: All deposited assets automatically earn yield in the lending pool, no manual transfers.
- **Yield on Active Orders**: Your limit orders generate yield while waiting for execution. Capital works even between trades.
- **Single Platform**: No more moving assets between trading and lending accounts.
- **Continuous Returns**: Your entire portfolio works 24/7, whether the agent is trading or waiting for the right entry.

### 3. Integrated Trading, Betting and Earning
- **Unified Liquidity Pool**: One pool that powers trading, betting,  lending, and borrowing, no fragmentation.
- **Full Portfolio Borrowing Power**: Your trading balances serve as collateral for leverage, no extra deposits required.
- **Auto-Borrow for Orders**: The agent places orders without you needing to hold the underlying asset.
- **Smart Auto-Repay**: Loans repaid automatically when market conditions are favorable, minimizing borrowing costs.

### 4. On-Chain Identity and Accountability
- **ERC-8004 Agent Identity**: Every agent has a verifiable NFT identity with `agentId`, `agentWallet`, `agentURI`, `active` flag, and traceable on-chain reputation.
- **Reputation Registry**: Every trade, every action, recorded on-chain. Full track record before you authorize anything.
- **Chainlink CRE Policy Enforcement**: Real-time metric computation — volume, PnL, drawdown, trading hours — validated against your policy before every single execution. The chain enforces your rules, not a promise.
- **X402 Subscription Gate**: The agent is only activated after you pay. No payment, no execution. You control access.
- **x402 Monetization**: Agents monetize their strategies per trade, per session, or by subscription, no upfront lock-in.

---

## Key Features

### Agent Features
- **Policy-Gated Execution** - Agent can only act within the rules you set. Fully non-custodial.
- **ERC-8004 On-Chain Identity** - Verifiable NFT identity for every agent: `agentId`, `agentWallet`, `agentURI`, `active` flag, and on-chain reputation traceable per action.
- **Chainlink CRE Enforcement** - Every trade passes through the Policy Engine, which calls Chainlink CRE in real time to verify volume limits, max trades per day, PnL, trading hours, and drawdown against the user's policy before any execution.
- **X402 Subscription Gate** - No payment, no execution. Agents are activated only after the user pays a subscription fee via X402.
- **Reputation Registry** - On-chain track record for every agent action, queryable before trust is granted.
- **Multi-Action Execution** - Single agent call handles orders, borrow, repay, and yield, all within one policy context.

### Trading Features
- **Yield-Bearing CLOB Trading** - Every open order earns yield via sxToken while waiting in the book.
- **Open Market Creation** - Anyone can create a new trading pair.
- **Fair and Transparent Pricing** - Oracle-fed TWAP prices for collateral and settlement.
- **High-Frequency Trading Ready** - Red-Black Tree order book with O(log n) price operations and minimal delay.
- **No LPs Needed** - Orders are matched peer-to-peer; no LP dependency or impermanent loss.

### Yield and Lending Features
- **sxToken on Every Deposit** - Every deposit automatically mints sxToken — yield-bearing, redeemable 1:1, and usable across all three products.
- **Auto-Supply to Lending** - Lending Manager auto-supplies the underlying token whenever a user deposits, generating passive yield that flows back to sxToken holders.
- **Unified Liquidity Pool** - Single pool powering trading, lending, and predictions.
- **Dynamic Interest Rates** - Market-driven rates based on real supply and demand.
- **Auto-Repay Integration** - The agent repays loans at optimal prices using limit orders, not market rates.

### Price Predictions Features
- **Stake sxToken on Market Direction** - Stake UP or DOWN on any market using sxToken, without giving up yield.
- **Yield While Staked** - sxToken continues accruing yield throughout the duration of any active prediction stake.
- **TWAP Settlement** - Oracle TWAP prices determine settlement, ensuring manipulation-resistant outcomes.
- **One Capital, Three Products** - The same sxToken balance is usable across Lending, Orderbook, and Price Predictions simultaneously.

### Revolutionary Features

#### Agent Flywheel
- **Yield Attracts Deposits**: Traders bring capital drawn by continuous yield generation
- **Low Utilization Attracts Borrowers**: Cheap borrowing rates pull in leveraged traders
- **Borrowing Raises Utilization**: Borrow activity activates higher interest accrual
- **Interest Pays Lenders**: Borrower interest flows back to lenders as yield
- **Repay/Reborrow Deepens Liquidity**: Continuous cycling adds dynamic depth to the order book

#### Capital Efficiency Revolution
- **Auto-Yield on All Assets**: Every dollar deposited immediately starts earning yield
- **Yield on Active Orders**: Your limit orders generate returns while waiting for execution
- **24/7 Portfolio Performance**: No idle capital, your entire portfolio works around the clock
- **Single-Platform Management**: No more moving assets between trading and lending accounts

#### Risk Management Revolution
- **Strategic Liquidation Protection**: Agent pre-positions orders at liquidation thresholds for zero-slippage exits
- **Real-Time Health Monitoring**: Continuous portfolio health tracking with protective actions
- **Eliminates ADL and Insurance Funds**: Order book liquidation replaces forced market sells entirely
- **Stress-Free Borrowing**: Trade aggressively knowing your positions are actively guarded

#### Trading Efficiency Revolution
- **Auto-Borrow for Limit Orders**: Agent places orders without requiring the underlying asset in advance
- **Smart Auto-Repay**: Automatically repay debt when market conditions are favorable
- **Strategy Without Capital Lock**: Start executing strategy with just collateral
- **Intelligent Debt Management**: Agent optimizes borrow/repay timing to minimize costs

---

## System Architecture

### CRE Integration Flow

![CRE Agent Workflow](images/CRE%20Agent%20Workflow.jpeg)

The agent execution layer enforces user-defined policies through a Chainlink CRE verification step before any trade reaches the Core Protocol:

1. **User Authorization** — User authorizes an AI Agent, sets a trading policy (volume limits, PnL thresholds, drawdown, trading hours), and pays a subscription fee via X402. No payment = no execution.
2. **ERC-8004 Agent Identity** — The AI Agent holds an on-chain NFT identity with `agentId`, `agentWallet` (signs transactions), `agentURI` (strategy and endpoints), `active` status, and a traceable reputation record.
3. **AgentRouter** — Agent calls AgentRouter to execute on behalf of the authorized user.
4. **Policy Engine + Chainlink CRE** — Policy Engine passes the pending order, policy, agent, and user context to Chainlink CRE. CRE computes real-time metrics (daily volume, max trades, PnL, trading hour, drawdown) against the policy. Only on pass does execution proceed.
5. **Core Protocol** — Verified orders execute into the Core Protocol.

### ScaleX Mechanism Flow

![ScaleX Architecture](images/ScaleX%20Architecture.jpeg)

All capital flows through a single entry point into the Balance Manager, where it is unified across three products via sxToken:

1. **Deposit via Router / AgentRouter** — Assets arrive from user (Router) or agent (AgentRouter) into the Balance Manager.
2. **sxToken Minting** — Every deposit mints sxToken: a yield-bearing ERC20 representing ownership of the lent asset and serving as the trading and staking token across all products.
3. **Lending Manager** — Automatically supplies the underlying token on every deposit. Generates passive yield for all sxToken holders. Acts as the yield source for trading and betting activity.
4. **Orderbook** — Users and agents place orders using sxToken. TWAP Oracle provides real-time price feeds.
5. **Price Predictions** — Users stake sxToken on UP/DOWN market outcomes. TWAP Oracle settles positions at expiry. sxToken continues earning yield throughout the stake.
6. **Oracle** — Feeds TWAP prices to Lending Manager (collateral valuation), Orderbook (pricing), and Price Predictions (TWAP settlement).

### Component Overview

The ScaleX ecosystem consists of ten integrated components:
- **Balance Manager**: Receives deposits, mints sxToken 1:1, routes capital across all three products
- **sxToken**: Yield-bearing ERC20; ownership of lent asset, trading collateral, and staking token — all in one
- **Lending Manager**: Auto-supplies underlying token on deposit; passive yield source for sxToken holders
- **Order Book**: High-performance CLOB with Red-Black Tree for O(log n) price operations; sxToken-native trading
- **Price Predictions**: UP/DOWN staking markets settled by TWAP Oracle; sxToken earns yield while staked
- **Oracle**: Multi-timeframe TWAP oracle for collateral pricing, order pricing, and prediction settlement
- **AgentRouter**: Routes agent execution requests through Policy Engine; enforces authorization
- **Policy Engine**: Validates each order against user policy via Chainlink CRE before execution
- **Chainlink CRE**: Real-time computation of agent metrics (volume, PnL, drawdown, trading hours) against policy
- **ERC-8004**: On-chain identity NFT standard for agents — verifiable, reputation-tracked, cross-protocol
- **X402**: Subscription payment gate — agent execution is only unlocked after the user pays

---

## Repository Structure

### Agent Infrastructure
- **[scalex-agent](https://github.com/ScaleX-Protocol/scalex-agent)** - Agent execution and identity layer
  - ERC-8004 identity registry and NFT minting
  - AgentRouter for policy-gated order execution
  - ReputationRegistry for on-chain track records
  - x402 pay-per-use integration

### Core Protocol
- **[clob-dex](https://github.com/ScaleX-Protocol/clob-dex)** - Smart contracts for the Yield-Bearing CLOB DEX
  - Red-Black Tree order book with integrated lending awareness
  - Unified liquidity management and synthetic token system
  - Auto-borrow / auto-repay functionality

### Frontend Applications
- **[scalex-frontend](https://github.com/ScaleX-Protocol/scalex-frontend)** - Web trading interface
  - Agent authorization and policy management dashboard
  - Real-time order book visualization
  - Portfolio, yield, and reputation analytics
  - Privy integration for email and social login

### Development Tools
- **[scalex-sdk](https://github.com/ScaleX-Protocol/scalex-sdk)** - TypeScript/JavaScript SDK
  - Type-safe interfaces for all protocol and agent functions
  - Agent integration and policy utilities
  - Trading, lending, and identity helpers
- **[cli](https://github.com/ScaleX-Protocol/cli)** - Command-line interface for ScaleX
  - Developer tooling for interacting with the protocol
  - Agent management and deployment utilities
  - Local development and testing commands

### Chainlink CRE
- **[cre](https://github.com/ScaleX-Protocol/cre)** - Chainlink CRE integration layer
  - Real-time policy metric computation (volume, PnL, drawdown, trading hours)
  - On-chain enforcement logic for agent execution validation
  - CRE workflow definitions and policy rule configurations

### Infrastructure
- **[scalex-indexer](https://github.com/ScaleX-Protocol/scalex-indexer)** - Ponder-based data indexing
  - Real-time order book and lending data
  - Agent activity and reputation history
  - GraphQL API

### Documentation
- **[scalex-docs](https://github.com/ScaleX-Protocol/scalex-docs)** - Technical documentation
  - Protocol and agent architecture
  - ERC-8004 and x402 integration guides
  - API references and deployment instructions

---

## Quick Start

### For Developers

1. **Clone the core protocol:**
   ```bash
   git clone https://github.com/ScaleX-Protocol/clob-dex.git
   cd clob-dex
   ```

2. **Install dependencies:**
   ```bash
   forge install
   npm install
   ```

3. **Run local deployment:**
   ```bash
   make deploy network=local
   ```

4. **Start developing:**
   ```bash
   # Run tests
   make test

   # Compile contracts
   make compile
   ```

### For Users

1. **Visit the app:** [app.scalex.io](https://app.scalex.io)
2. **Sign in** with email, social account, or wallet (via Privy)
3. **Deposit collateral** - automatically starts earning yield
4. **Authorize an agent** - set your policy and let it trade for you 24/7

---

## How It Works

### Agent Flow
1. **Agent Registration** — Agent mints an ERC-8004 NFT identity and registers on-chain with a strategy URI and metadata.
2. **User Authorization + X402** — User calls `AgentRouter.authorize()`, sets a policy (max trade size, allowed pairs, time limits, PnL threshold, drawdown), and pays the subscription fee via X402. No payment, no execution.
3. **Execution via AgentRouter** — Agent calls `AgentRouter.execute*()` on the user's behalf.
4. **Chainlink CRE Validation** — Policy Engine submits the pending order, policy, agent, and user data to Chainlink CRE. CRE computes real-time metrics against the policy. Pass = execute. Fail = reject.
5. **Core Protocol Execution** — Verified order is routed to Balance Manager → Orderbook / Lending / Price Predictions.
6. **Reputation Building** — Every trade, every borrow, every repay is recorded on-chain. Auditable before authorization.
7. **Yield Running Throughout** — All capital in the Balance Manager earns yield via Lending Manager while not actively staked or in a trade.

### ScaleX Mechanism: One Deposit, Three Products
1. **Deposit** — Assets flow in via Router (user) or AgentRouter (agent) to Balance Manager.
2. **sxToken Minted** — Every deposit instantly mints sxToken at 1:1. Yield starts accruing.
3. **Lending Manager** — Auto-supplies underlying token, generating passive yield that continuously flows back to sxToken holders.
4. **Orderbook** — Place orders using sxToken. Oracle provides live TWAP pricing.
5. **Price Predictions** — Stake sxToken UP or DOWN. TWAP Oracle settles at expiry. Yield still runs while staked.
6. **Withdraw** — Redeem sxToken for underlying asset plus accrued yield at any time.

---

## Life-Changing Innovations

### Never Miss an Entry Again
- **24/7 Execution**: The agent monitors and trades around the clock, including 3AM
- **No Emotion**: No fear, no greed, no hesitation, pure strategy execution every time
- **Verifiable Trust**: On-chain reputation and identity mean you know exactly what you're authorizing
- **Your Rules**: Policy-bound execution, the agent only does what you allow, and stops when you say

### End Capital Waste Forever
- **Never Idle Capital**: Every dollar deposited earns yield immediately
- **Yield While Trading**: Your limit orders make money even while waiting for execution
- **No Manual Transfers**: Single platform for all your capital needs
- **Maximum Efficiency**: 100% of your portfolio works 24/7

### Never Fear Liquidation Again
- **Strategic Protection**: Agent pre-positions orders at liquidation thresholds for zero-slippage exits
- **Stress-Free Trading**: Trade aggressively while the agent guards your downside automatically
- **No ADL, No Insurance Fund**: Order book liquidation eliminates forced market sells entirely
- **Proactive Defense**: Agent acts before you even realize the risk

### Never Trust a Black Box Again
- **Full Track Record**: Every agent action recorded on-chain and queryable before you authorize
- **No Key Sharing**: Delegation without custody, revoke at any time
- **Standard Identity**: ERC-8004 gives every agent verifiable, cross-protocol identity
- **Fair Monetization**: x402 pay-per-use means you only pay when the agent performs

---

## Roadmap

### Q1 2026 - Testnet
- Testnet launch
- Community launch
- Mini app testing
- Agent integration
- CRE Integration for policy

### Q2 2026 - Mainnet Beta
- Mainnet Beta
- Security audit
- Deposit via QRIS and popular channels in Indonesia

### Q3 2026 - Mainnet Launch
- Mainnet launch
- Seed liquidity
- Crosschain integrations
- RWA integration

### Q4 2026 - Scale
- Mobile app launch
- Trading pairs expansion

---

## Security

- **Audited Smart Contracts** - Comprehensive security audits by leading firms
- **Policy-Gated Agents** - No agent can exceed the limits the user defines
- **No Key Sharing** - Agents operate via authorization, never custody
- **Bug Bounty Program** - Ongoing security testing and vulnerability rewards
- **Multi-sig Governance** - Secure protocol upgrades and parameter changes

---

## Community

- **Discord** - Join our community for discussions and support
- **Twitter** - Follow us for updates and announcements
- **Telegram** - Real-time community chat and support

---

## License

ScaleX is open-source under the MIT License. See individual repositories for specific licensing information.
