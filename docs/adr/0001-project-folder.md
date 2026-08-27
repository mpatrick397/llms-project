# ADR-001: Location of the project folder on my machine

**Status:** Accepted?
**Date:** 2026-08-27

## Context

Setting up the course location required cloning it to a specific location
on my Windows machine. I needed a place that Git, VS Code, and Claude Code could all point to consistently. I had no existing place for where coding projects live.

## Decision

I clone the repository into Documents\llms-project, keeping it alongside my other personal files rather than in a separate location.

## Alternatives considered

**A dedicated top-level folder. It keeps coding projects visually and physically separate from other personal files. and scales better if I end up with many repositories. I did not choose this because documents is a familiar strategy from my economics classes with R.

**The Desktop.** Faster to find and open, but clutters the desktop and mixes project files with icons/shortcuts. I ruled this out for the same
organizational reasons as above, just more so.

## Consequences

This makes it faster to find the project right now since Documents is a
familiar, easy-to-navigate location. It makes future organization harder if
I take more courses or start more coding projects.

I would revisit this the first time I have two or more unrelated projects for space in Documents.

