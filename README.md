# mateo

> flow state ./

i build at the collision of ai agents and onchain rails: memory layers for llms, intent driven defi, and micropayment apps. the stack is typescript and python, with ai assisted programming in the mix. a lot of these started as hackathon builds and ended up deployed. chains i've shipped on: sui, walrus, x layer, stellar, somnia, tempo, creditcoin, nimiq and bittensor.

this repo is the index. every repo on my github is here: links and explanations for the public ones, notes for the private ones while they're in the works, and anything marked **live ↗** is a deployed build that actually responds.

**18 built** · **2 forks** · **1 private, in the works** · *you are here: [mateo](https://github.com/mateojkk/mateo)*

---

## 🧠 ai agents & memory

agents are only as useful as what they remember, so this is the part of the stack i keep rebuilding: persistence, recall, discovery and verification.

- **[nue-memory](https://github.com/mateojkk/nue-memory)** · TypeScript · [live ↗](https://nue-memory.vercel.app)
  memory layer for ai agents, built with [@nextmathlabs](https://github.com/nextmathlabs). it lets agents persist, recall and adapt across sessions instead of starting from zero each time.

- **[kumo](https://github.com/mateojkk/kumo)** · TypeScript
  a portable memory and discovery layer for the OKX ai agent marketplace.

- **[kuro](https://github.com/mateojkk/kuro)** · TypeScript
  a trustless, deterministic meta-agent for autonomous code verification and swarm orchestration inside the OKX ecosystem.

- **[asknimi](https://github.com/mateojkk/AskNimi)** · TypeScript · [live ↗](https://ask-nimi-chi.vercel.app)
  pocket ai inside nimiq pay. no signup, the wallet is your account, every answer is metered at a fraction of a cent, and top ups are feeless NIM micro-payments. built for the nimiq mini apps competition, cycle II.

## ⚡ agentic defi & markets

defi where the agent does the clicking: routing, risk and execution handled for you.

- **[shiro](https://github.com/mateojkk/Shiro)** · TypeScript
  intent driven defi agent on x layer. plain english turns into sub-second groq reasoning, OKX dex routing and atomic non-custodial execution. built for the x layer build x hackathon.

- **[nour-markets](https://github.com/mateojkk/NOUR-MARKETS)** · TypeScript · [live ↗](https://trynour.xyz)
  prediction market exchange on somnia, powered by dreamdex event contracts. rolling 5m and 15m binary crypto windows (will ETH close UP?) with sub-second settlement and passwordless login. built for the somnia × dreamdex hackathon.

- **[credence](https://github.com/mateojkk/credence)** · TypeScript · [live ↗](https://credence-orcin.vercel.app)
  cross-chain verifiable credit protocol on creditcoin. cryptographically provable repayment history and an ai risk sentinel make undercollateralized lending possible, no more 100%+ overcollateralization. submission for BUIDL CTC 2026 fall.

- **[speedy](https://github.com/mateojkk/speedy)** · Python
  polymarket scanner for the crypto markets actually worth trading. a python bot hits the gamma api every 15 seconds and scores each market on liquidity, volume and spread, while a live dashboard surfaces the btc and eth ones with real liquidity. politics and sports are hardcoded out.

- **[limi](https://github.com/mateojkk/LIMI)**
  real-time new market announcement bot for [limitless.exchange](https://limitless.exchange).

## 📦 onchain apps

everyday apps where the memory, the money or the proof lives onchain.

- **[kibo](https://github.com/mateojkk/Kibo)** · TypeScript
  conversational p2p payments on sui. zkLogin for passwordless non-custodial wallets, a shielded pool for private transfers, gasless sponsored transactions and spend limits. one monorepo: vite front end, fastapi backend, sui move contracts.

- **[bun](https://github.com/mateojkk/Bun)** · TypeScript
  usage-based subscription payment rail on stellar soroban. think stripe checkout for metered billing: the customer authorizes a capped spend, the provider reports usage through an api, and bun handles escrow, crediting, settlement and refunds.

- **[rune](https://github.com/mateojkk/Rune)** · TypeScript
  decentralized form builder for walrus sessions, live on sui mainnet. submitters get a pure web2 experience with no wallet and no popups, while every form and submission lives as an immutable json blob on walrus, with backend enforced admin access control and multi workspace.

- **[people-book](https://github.com/mateojkk/People-Book)** · TypeScript
  a private assistant that remembers everyone in your life, you included, and comes to you instead of waiting to be asked. it never states anything it cannot prove, your memory is owned onchain and revocable in one transaction. built for walrus sessions 8 and verified on mainnet.

- **[vela](https://github.com/mateojkk/Vela)** · TypeScript
  ai football companion for the 2026 world cup. it watches every match, tracks your predictions and keeps every take in fully onchain memory, so its personality evolves around you and roasts the bad picks. built for walrus session 4.

- **[claymore](https://github.com/mateojkk/claymore)** · TypeScript
  onchain nft gallery. the deployment is retired, so clone the repo and run npm install && npm run dev to try it yourself.

- **[tensor-scan](https://github.com/mateojkk/tensor-scan)** · TypeScript
  transaction viewer for bittensor with search, stats and csv export.

- **[trainyard-ai](https://github.com/mateojkk/Trainyard-AI)** · JavaScript · Python
  decentralized marketplace for licensed ai training datasets on sui and walrus. sellers encrypt in the browser with AES-256-GCM so trainyard never touches the raw file, buyers pay in USDC on sui, and the decryption key only releases after the payment is verified. built for the tatum × build on sui with walrus hackathon.

## 🎨 design & sites

- **[portfolio](https://github.com/mateojkk/portfolio)** · [live ↗](https://portfolio-mateodotdevs-projects.vercel.app)
  the previous portfolio site. this repo ([mateo](https://github.com/mateojkk/mateo)) is its successor.

## 🔒 in the works (private)

- **[prjrr](https://github.com/mateojkk/Re)** · TypeScript · [live ↗](https://www.prjrr.com)
  talent network where profiles are indexed from key works, long posts on x and public github repos, with skills matched from the text of those works instead of typed in by hand. x oauth with pkce, no wallet and no signature anywhere. next.js, live today, private repo.

## 🌀 forks & collabs

- **[strk20-hackathon](https://github.com/mateojkk/strk20-hackathon)**
  snapshot of the starknet privacy sprint: apply by pull request to build a privacy app on starknet mainnet.

- **[flowstation](https://github.com/mateojkk/flowstation)**
  fork of [Dev-simeon-tech/FlowStation](https://github.com/Dev-simeon-tech/FlowStation).

---

18 repos written from scratch, 6 live, many hackathon deadlines met. what i remember, ships.
