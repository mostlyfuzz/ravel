# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Ravel is a tabletop RPG ("A Game of Threads") by Mostly Fuzz Studio. The repository currently contains the v1 design document (`README.md`) and no source code, build tooling, or tests.

## Design Document Key Concepts

Ravel's core mechanic is the **Honor → Dice → Pull** economy:
- **Honor** established fiction (relationships, drives, prior events) to earn dice
- **Pull threads** by spending dice to discover new fiction
- Three outcomes: **Clarity** (fiction expands), **Cold** (absence is real), **Breaks** (something gets worse)
- The GM plays by the same economy as players — no planted mysteries, shared authorship
- No combat subsystem — fights are scenes resolved through the same thread-pulling engine
- Campaign persistence through threads (short/mid/long timescales)
- Character development is emergent and constrained by established fiction, not XP tracks

## Repository State

This is a greenfield project. When code is added, update this file with build commands, architecture, and development workflow.
