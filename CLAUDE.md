# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Legends in the Mist is a repository for tools and resources related to running games in Legends in the Mist (a tabletop RPG system).

Read `Legend In The Mist - Core Book  v1.01.pdf` to understand the core systems for the game.

This is NOT code, but we want to work on it in a systematic, iterative way.

## Change Management

When updating documents:
- Prefer clarity over elegance
- Keep language direct and concrete
- Assume source control. Do not include in-document descriptions of changes from prior versions. The document should always reflect current thinking, no matter what was in there before.
- Always push each commit as you make it.
- When you commit, commit everything. If it isn't in .gitignore, then it goes into the commit, even if you didn't think that you were working on that.

## Working Style

- When you have a proposal, make it and check it in.
- Work iteratively with the user, using a commit for each interaction.
- When you want feedback, make a proposal, commit it, then ask the user to review. If he makes changes and forgets to commit them, commit them before doing anything else.
- When your work naturally breaks into separate steps, do each one as a separate commit. This happens if you have tasks, if you do the same thing many times, or if you first do one thing to every instance, then do another.
