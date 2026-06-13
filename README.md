# ShelfShock — Retail Disruption Cascade Agent

> Trace how one retail disruption ripples across suppliers, stores, promotions, and shoppers — and get the optimal fix, grounded in a Fabric IQ business ontology.

## The problem
A single SKU recall sets off a hidden chain reaction across a retail network. No one sees the full blast radius until stores stock out and promotions break.

## What ShelfShock does
Given a disruption event, the agent performs multi-step reasoning over a retail ontology to:
1. Identify the affected SKU and every store stocking it
2. Find active promotions/bundles that depend on it
3. Map the customer segments impacted
4. Quantify the revenue at risk
5. Recommend the optimal intervention, with a cited rationale

## Microsoft IQ integration
Fabric IQ supplies the business ontology and knowledge graph. Every factual claim cites a specific graph node — no ungrounded answers.

## Tech
Microsoft Foundry (agent) · Fabric IQ (ontology/graph) · GitHub Copilot (development) · graph-visualization front end.

## Status
Hackathon MVP. See `docs/architecture.md` for the diagram. Future work: live Fabric workspace connection, real POS/inventory feeds.
