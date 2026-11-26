## Hi, I'm George Drakou

**Senior Platform Engineer. I design and build large real-time systems, end to end.**

From the Linux kernel and the network to the trading engine, the database, the business logic and the screens people use all day. C++ and Go on Linux, with security built in from the first line. 20+ years in software, 10 of them as Head of CRM Systems at a global forex broker. Based in Nicosia, Cyprus, working remotely.

### 👉 [See my portfolio](https://george-cd.github.io)

**Systems I've built**, independently and in my own time (built and tested, now moving to production servers; source code private, developed for commercial use). The first versions of the trading platform, the UI framework, the CRM and the client portal were presented to IronFX; the others followed along the way:

- **Trading platform** · own engine instead of MetaTrader. **Core in C++** (prices, orders, margin, stop-outs, the accounts' money): about 1 µs per price (median, 100,000 accounts) and 325,000 prices a second with every feature on. **Everything around it in Go** (API, sign-in, dealing desk, back office, integrations). Load-tested with 10,000 simulated users on one small machine. Web and mobile apps (iOS & Android), copy trading, PAMM/MAM, prop challenges, liquidity provider connectivity over FIX · C++, Go, JavaScript, React · [showcase](https://george-cd.github.io/go-webtrader-showcase/)
- **AI-native broker CRM, the CRM you build by talking to it** · a manager writes what they want in plain words (a module, an access rule, a report, a compliance check); the AI turns it into a proposal, shows what would change, and nothing is applied until a person approves it. Underneath: leads and clients, KYC, AML per regulator, partner (IB) commissions, wallets, reports, and access control built for real brokers. Mobile app · Go, PostgreSQL
- **White-label client portal** · one portal, many brands, each with its own domain, look, logins and language. Sign-up, KYC, trading accounts, deposits and withdrawals (2FA asked again on every withdrawal), and a partner area with a "Why?" for every commission. Mobile app · Go, PostgreSQL
- **Payment orchestration hub** · routing and fallbacks, reconciliation, fraud checks; new providers as configuration, not code, straight from their official docs, tested against a built-in provider emulator · Go, PostgreSQL
- **Real-time broadcast server** · live data to many thousands of users, bot and account-farm detection, client libraries in C++, Python, Go and JavaScript · C++, Linux
- **Multi-layer security platform** · from the network card to the application: AI-bot and scraper detection, honeypots, fraud signals, its own model per customer, threats mapped to MITRE ATT&CK · C++, Go, Linux kernel
- **UI framework** for all-day web applications · Go, JavaScript · [showcase](https://george-cd.github.io/customframework-showcase/)
- **Pen-test and hardening toolkit** · 180+ attacks and checks run against every system before it goes live: Python engine and checks, low-level attacks in C (fast port scan, connection exhaustion, slow-header, HTTP/2 Rapid Reset), coverage-guided fuzzers in C++ and Go with AddressSanitizer, and a read-only Linux server audit · Python, C, C++, Go

**1,700+ automated tests** across these systems · **200+ payment provider integrations** in my career.

**Open to** senior C++, Go, Linux and platform engineering roles, remote.
📧 drakou.george@gmail.com · [LinkedIn](https://www.linkedin.com/in/george-drakou-982a76421)
