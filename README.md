# Kushagra Tandon

I build AI agents, then I try to break them. Usually I win.

CS grad out of Arizona State. I work on the unglamorous half of AI: not the demo that wows people, but the system that proves the demo wasn't lying. Agents, evals, safety, and a few quant models for when I miss the finance world.

[LinkedIn](https://www.linkedin.com/in/k-tandon/) · [Portfolio](https://kushagratandon.netlify.app/) · [Email](mailto:kushagratandon1207@gmail.com)

---

## Projects

**[Redline — LLM Safety Evaluation Platform](https://github.com/kush0o7/Redline-Agent-Safety-Eval)**
I got tired of agents that look fine until they aren't. So I built the thing that hunts for the "aren't." Runs agents through adversarial scenarios, grades where they break, flags regressions before they ship. Proposer → Critic → Revision pipeline, prompt-injection checks, async evals with full traces.
*Python · FastAPI · PostgreSQL · Redis · Docker*

**[Constitutional Safety Agent](https://github.com/kush0o7/Constitutional-Safety-Agent)**
Give a model rules it can't talk its way out of. Pre/post-generation gating with a model-independent rule engine that holds up when someone tries to jailbreak it.
*Python · FastAPI · React · scikit-learn · Docker*

**[VoiceAI Medical](https://github.com/kush0o7/VoiceAI-medical)**
A voice and chat agent that books patient appointments and checks every action against the backend before it commits, because "mostly right" isn't good enough in healthcare. Deployed end to end on AWS.
*Node.js · TypeScript · React · Vapi.ai · Redis · AWS*

**[DE/LU Power Price Forecasting](https://github.com/kush0o7/Case_study_Energy)**
Predicting European electricity prices without pretending the future is certain. Quantile forecasting with LightGBM, 60% lower error than baseline.
*Python · LightGBM · Pandas*

**[QuantAI](https://github.com/kush0o7/QuantAI)**
Multi-tenant backend that reads intent from messy signals and catches drift early using embeddings. Tenant-scoped APIs over pgvector.
*FastAPI · PostgreSQL · pgvector · Docker*

**[WorldweLivein](https://github.com/kush0o7/WorldweLivein)**
A macro scenario engine that runs thousands of possible futures instead of guessing one. Monte Carlo over geopolitical and economic data from FRED and GDELT.
*React · TypeScript · Python*

**[EPL Betting Model](https://bettingisntgood.streamlit.app)**
A calibrated match predictor that's honest about its own uncertainty. XGBoost, ROC-AUC 0.79 on 570 games it had never seen.
*Python · XGBoost · Streamlit*

**[Momentum Strategy Lab](https://github.com/kush0o7/Momentum_Following_Strategy)**
Systematic trading with walk-forward validation, ATR stops, and no curve-fitting fairy tales. Backtested across stocks, ETFs, and crypto.
*Python · Backtrader · yfinance*

---

## Stack

**Languages:** Python · TypeScript · Java · C++ · SQL
**AI/LLM:** adversarial evaluation · red-teaming · safety gating · prompt-injection mitigation · Anthropic SDK · pgvector
**Backend:** FastAPI · PostgreSQL · Redis · Docker · REST · AWS
**Frontend:** React · TypeScript
**ML:** LightGBM · XGBoost · scikit-learn

---

## Experience

**Software Engineer (Contract)** · Wefunder (YC) — *2026*
Shipped a Slack integration on a live fintech codebase with at-least-once delivery, so a worker crash couldn't quietly lose someone's investment message. Found a bug by hand that 711 automated tests missed.

**Teleoperation Associate** · Objectways Technologies — *2026*
Collected and cleaned robot demonstration data for ML training pipelines.

**Research Aide** · ASU School of Earth & Space Exploration — *2023–2025*
Built data pipelines and virtual field modules for the NSF-funded WORM Portal.

---

*Open to roles in AI safety, LLM evaluation, ML engineering, full-stack, and quant systems. I ship fast and I test like I don't trust myself.*

