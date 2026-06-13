# shelfshock
ShelfShock — Retail Disruption Cascade Agent

#ShelfShock is a multi-step reasoning agent that predicts the full downstream impact of a retail disruption before it hits the shelf. When a supplier flags a defect or recall on a single SKU, ShelfShock traverses a Fabric IQ business ontology — Supplier → SKU → Store → Promotion → Customer Segment → Revenue — to trace exactly which stores, bundles, and shopper segments are affected and how much revenue is at risk. It then reasons over substitution options and recommends the optimal intervention (recall scope, substitute SKU, customer communication), citing every claim back to a specific node in the knowledge graph so nothing is hallucinated.

Built for the Reasoning Agents track on Microsoft Foundry, grounded by Fabric IQ's ontology and knowledge-graph layer, and developed with GitHub Copilot. Technologies: Microsoft Foundry (agent orchestration), Fabric IQ (semantic ontology + graph reasoning), and a graph-visualization front end.

# ShelfShock — Retail Disruption Cascade Agent

> Trace how one retail disruption ripples across suppliers, stores, promotions, and shoppers — and get the optimal fix, grounded in a Fabric IQ business ontology.

## The problem
A single SKU recall sets off a hidden chain reaction across a retail network. Today, no one sees the full blast radius until stores stock out and promotions break.

## What ShelfShock does
Given a disruption event, the agent performs multi-step reasoning over a retail ontology to:
1. Identify the affected SKU and every store stocking it.
2. Find active promotions/bundles that depend on it.
3. Map the customer segments impacted.
4. Quantify revenue at risk.
5. Recommend the optimal intervention, with a cited rationale.

## Microsoft IQ integration
Fabric IQ supplies the business ontology and knowledge graph. Every factual claim cites a specific graph node — no ungrounded assertions.

## Tech
Microsoft Foundry (agent) · Fabric IQ (ontology/graph) · GitHub Copilot (development) · [front-end TBD]

## Status
Hackathon MVP. See `/docs/architecture.md` for the diagram. Future work: live Fabric workspace connection, real POS/inventory feeds, multi-event simulation.
