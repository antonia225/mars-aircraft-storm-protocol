# Mars Aircraft Storm Protocol

Design document for an autonomous aircraft operating on Mars, tasked with deciding how to handle a dust storm mid-flight with no real-time communication with Earth.

## Problem

The aircraft is mid-flight when a dust storm is detected approximately 12 minutes ahead. Communication with Earth has a 14-minute round-trip delay, making autonomous decision-making the only viable option. The document defines the protocol the aircraft must follow.

## Contents

- `autonomous_mars_aircraft.pdf` — compiled document
- `autonomous_mars_aircraft.tex` — LaTeX source
- `References.bib` — bibliography

## Structure

The document is divided into two parts:

**Part 1 — Problem Analysis:** Research findings, key questions, assumptions, difficulties, and a detailed account of how the thinking evolved throughout the exploration of the problem.

**Part 2 — Proposed Solution:** Energy architecture, storm boundary detection, decision logic with explicit trigger conditions and thresholds, terrain avoidance strategy, pseudocode, cargo contingency planning, and justification of the approach.
