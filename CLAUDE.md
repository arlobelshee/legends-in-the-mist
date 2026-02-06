# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Legends in the Mist is a repository for tools and resources related to running games in Legends in the Mist (a tabletop RPG system).

This is NOT code, but we want to work on it in a systematic, iterative way.

## Understanding the Game System

**Do NOT read the PDF directly** - it is too large (20MB+) for direct reading.

Instead, use these resources in order:

1. **`LITM_Rules_Reference.md`** - Complete rules reference covering:
   - The game loop (Establish → Action → Consequences)
   - Tags (power, weakness, story)
   - Themes and theme development
   - Actions (Simple, Quick, Detailed outcomes)
   - Power calculation and spending
   - Statuses and Limits
   - Consequences and Reactions
   - Might levels
   - Quests (Milestone, Abandon, Improve)
   - Fellowship mechanics
   - Camping and Sojourns

2. **`litm_extracted.txt`** - Full text extraction from the PDF (~24,000 lines). Use this for:
   - Finding specific themebook questions
   - Looking up example tropes and theme kits
   - Searching for exact wording on obscure rules
   - Reading sections not covered in the reference

3. **`character_themes.md`** - Custom adventure-level themes with magic systems

When building new content (themes, NPCs, adventures), start with LITM_Rules_Reference.md to understand the mechanical framework, then consult litm_extracted.txt for specific details or examples.

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
