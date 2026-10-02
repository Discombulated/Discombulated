# Vineet Nandwana

I build and investigate AI-assisted software with a focus on evaluation, failure
modes, provenance and engineering tradeoffs.

## Current project: HorizonSeed

[HorizonSeed](https://github.com/Discombulated/HorizonSeed) is an experimental
Python/Streamlit policy-text analysis system combining LLM discovery with
deterministic numeric, relation, evidence and signal gates.

My work centers on problem formulation, architecture, evaluation design,
experimental protocol, adjudication, debugging priorities, validation and
iteration, with extensive coding-agent assistance.

The engineering work includes typed numeric-role handling, class-specific signal
evidence contracts, candidate tracing, isolated benchmark state, subprocess
deadline control and evidence-oriented evaluation.

The first independently adjudicated raw-document evaluation completed 3/3 scored
cases with **0 TP, 6 FN and 4 FP**. Four demonstrated false-positive construction
paths were subsequently reproduced and repaired offline while nearby valid
fixtures survived. Later private implementation work localized candidates for
all six misses that survived offline pipeline tests with stubbed model responses;
live recall improvement remains unverified. These later repairs are not yet in
the published source derivative.

R2 was attempted, but all 26 API calls failed with HTTP 403 and no usable model
responses; its raw score is not semantically evaluable. Subsequent private
runtime-validity checks fail closed before scoring. After two assertion-only
wording corrections, the private deterministic suite passed all 401 tests without
changing production thresholds. A replacement-key synthetic preflight then
returned usable HTTP 200 responses from both unchanged configured models; no
fresh live evaluation followed. The earlier V4.2.1 result was claim-pair replay,
not real-document recall.

I am interested in Applied AI / LLM systems work where reliability, evaluation
and inspectable failure analysis matter more than demo polish.

HorizonSeed is public for technical review and is not production-ready. The
project and this profile were developed with extensive AI assistance; I do not
claim manual authorship of every line.
