# Vineet Nandwana

I build and investigate AI-assisted software, with a focus on making evaluation,
failure modes and engineering tradeoffs visible.

## Current project: HorizonSeed

HorizonSeed is an experimental Python/Streamlit policy-text analysis system
combining LLM discovery with deterministic numeric, relation and evidence gates.
My work centers on problem formulation, architecture, evaluation design,
adjudication and iterative debugging, with extensive coding-agent assistance.

The engineering work includes typed numeric-role handling, terminal signal
evidence checks, candidate tracing, isolated benchmark state and deadline control.
I treat regression coverage and semantic accuracy as different kinds of evidence.

The independently adjudicated raw-document R1 evaluation completed 3/3 cases
but produced 0 true positives, 6 false negatives and 4 false positives; precision,
recall and F1 were all 0.0. Four demonstrated false-positive construction paths
were subsequently repaired offline, with nearby valid fixtures surviving.
The six false negatives remain unrecovered, and no R2 or live rerun has occurred.
The earlier V4.2.1 result was claim-pair replay, not real-document recall.

I am interested in building systems whose limitations can be inspected, not just
systems with an impressive demo. This profile and the project documentation were
prepared with AI assistance.

Project source is currently undergoing publication review; no public release or
production-readiness claim is made here.
