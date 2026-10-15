# Plan.md — Risk, Architecture & Budget (Build 2)

**Due:** Monday, Nov 16, 2026 at 12:00 PM (Noon)  
**Builder:** [Your Name]

---

## 1. What is the riskiest part?
*What is the single most likely reason this product fails to work for a real user (e.g., model hallucination on messy PDFs, latency, auth, bad data, third-party API limits)? How does your smallest live version test that risk first?*

- **#1 Technical / Product Risk:** 
- **How Build 2 tests it right now:** 

## 2. The Smallest Working Version (Architecture)
*Keep it small enough to explain every file without the agent's help.*

- **Stack (Frontend / Backend / DB):** 
- **Where it is hosted:** 
- **Live URL (Build 2):** 
- **Models used (via OpenRouter or provider):** 

## 3. Time & Money Budget
*Estimate what it will cost to build and what it costs each time a user runs a job.*

| Item | Estimate | Notes |
| :--- | :--- | :--- |
| **Build budget (coding agent / OpenRouter)** | `$` | |
| **Unit cost per user action (inference/API)** | `$ / run` | |
| **Hosting cost (monthly)** | `$ / mo` | |
| **Your engineering time budget** | `hrs/wk` | |

## 4. Security & Recovery Checklist
- [ ] `.env` and API keys are excluded via `.gitignore`
- [ ] API keys have spending limits set on OpenRouter
- [ ] Least-privilege permissions on any external data/APIs
- [ ] Clear rollback path if a bad deploy breaks production
