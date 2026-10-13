# Partho Baruah

Trade Support Engineer | Trading Systems Architecture, Risk Automation, TradeOps & Algorithmic Trading

Portfolio & Live Telemetry: https://sigmaquant.space  
LinkedIn: https://linkedin.com/in/parthobaruah  
Email: partho550@gmail.com  
Location: Ahmedabad / Delhi, India  

---

## Executive Summary

Quantitative trading infrastructure and trade operations specialist with over 4 years of production experience supporting and engineering algorithmic execution stacks, real-time risk engines (RMS), and market data telemetry for the National Stock Exchange (NSE).

Specialized in asynchronous Python (AsyncIO), low-latency feed handling, in-memory state caching (Redis), distributed system lifecycle supervision, and automated pre-trade risk containment across equity and index derivatives.

---

## Featured Infrastructure

### [SigmaQuant Platform](https://github.com/parthobaruah/sigmaquant-platform)
Distributed quantitative execution and derivatives risk platform architected for high-throughput NSE equities and index derivatives.

* High-Throughput Quote Multiplexing: Asynchronous batch-polling architecture processing 50-token chunks every 3 seconds across 210 NSE F&O equities with zero tick dropout.
* Contract Master Resolution Engine: Dynamic resolution across 38,000+ daily instruments, mapping ATM/ITM/OTM strikes, lot sizes, and expiries in real time.
* Pre-Trade Risk Management (RMS): Portfolio Greek telemetry (Delta, Gamma, Vega), margin headroom utilization, and automated desk boundary containment.
* Deterministic Process Orchestration: Dependency-ordered process lifecycle orchestration across multi-host trading stacks:
  Market Data (TBT) -> Risk Management (RMS) -> Trade Server (TS) -> Pricing Engine (Pricer) -> Strategy Daemons
* Telemetry Interfaces: Dedicated operator terminals covering multi-timeframe bot execution fleets, market structure zone mappers (CVD, Volume Profile POC), and cash market momentum desks.

---

## Technical Core & Stack

* Trading & Execution: Algorithmic Order Routing, Pre-Trade Risk Checks (RMS), Greek Hedging Limits, Token Multiplexing, Exchange Feed Ingestion.
* Languages & Runtime: Python 3.10+ (AsyncIO, Multiprocessing, Concurrency), Shell Scripting (Bash), SQL.
* Messaging & State: Redis (Key-Value, Pub/Sub, In-Memory State Caching), PostgreSQL, SQLite.
* Networking & Web Protocols: WebSockets, Daphne (ASGI), Django, REST APIs.
* Systems & Infrastructure: Linux (Ubuntu/Debian, Systemd, Kernel Tuning), Docker Containerization, AWS EC2.
* Monitoring & Reliability: Nagios, Incident Triage, Runbook Automation, Slack Webhook Alerting, Post-Mortem Analysis.
* Market Telemetry: National Stock Exchange (NSE F&O / Equities).

---

## Professional Trajectory

* APT Research (2021 – Present)  
  Trade Support Engineer | Quantitative Infrastructure & Operations  
  Responsible for multi-host trading stack availability, market open/close checklists, real-time desk Greek/margin monitoring, and automated incident resolution across high-frequency derivative strategies.

* B. M. S. College of Engineering (2018)  
  Bachelor of Engineering (B.E.), Mechanical Engineering

---

## Repository Portfolio

* [sigmaquant-platform](https://github.com/parthobaruah/sigmaquant-platform): Core architectural reference, telemetry dashboards, and market data infrastructure for NSE derivatives execution.
