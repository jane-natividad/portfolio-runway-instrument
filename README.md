# Portfolio Runway Instrument

An interactive portfolio and runway dashboard prototype for early-stage R&D organizations — one view of every program, gate, CRO, and budget against the runway, with scenario simulation built in.

**[Live demo](https://portfolio-runway-instrument.vercel.app)** — works immediately, no API key or setup required.

## Who it's for

Founders, R&D leads, and program/portfolio leads at early-stage biotech or life-sciences organizations who need a single, always-current view of where every program stands against cash runway and gate criteria — without waiting for someone to assemble a slide deck.

## Why it matters

Early-stage R&D organizations run multiple competing programs against a fixed runway, but the data needed to answer "what happens if we lose X" or "what's the fastest way to extend runway" is usually scattered across spreadsheets, CRO contracts, and someone's memory. This prototype explores what a single instrument for that decision-making could look like — scenario-tested, not just status-reported.

## What it does

- Visualizes a master plan (Gantt-style) of every program against a funded/tight/unfunded runway line
- Runs pre-built scenarios (CRO delays, program stops, parallelization trade-offs) and shows the resulting impact on runway and candidate selection live
- Surfaces a CRO network view and a resource gap (demand vs. capacity) view
- Generates a board-ready summary: headline, decision, risk, and ask

## Product decisions that mattered more than the model

1. **Scenario simulation, not just static reporting** — the value is in showing what changes under pressure, not just current state
2. **One red line (runway) as the organizing principle** — every other view ties back to the same constraint
3. **Board view as a first-class output** — the tool is built to produce the artifact a leadership conversation actually needs, not just a dashboard to explore

## Built with

- HTML, CSS, JavaScript (single-file prototype)

## Status

This is a prototype built to explore a problem space, using illustrative/placeholder data — not a finished product and not tied to any specific organization's real programs. Built by [Jane Natividad](https://github.com/jane-natividad) — see more at [jane-natividad.github.io](https://jane-natividad.github.io).
