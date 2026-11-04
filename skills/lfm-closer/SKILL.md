---
name: lfm-closer
license: Apache-2.0
description: >-
  Calls on Firefly (lfm-firefly), your calibrated Velvet-Rope Closer. Audits and
  scripts multi-turn DM conversations, landing page closes, executive call
  decks, portal deliverables, objection pre-handling, and hot-lead follow-ups
  in LFM_PIPELINE.md.
---

# LFM Closer: Call Firefly (`lfm-firefly`)

## Overview

Use `lfm-closer` whenever you have a warm lead in the DMs, a prospect on deck for a discovery call, a landing page or `/portal/` deliverable that needs to convert, or an open pipeline in `LFM_PIPELINE.md` that needs closing.

## Workflow

1. Read `LFM_PROFILE.md` and `LFM_PIPELINE.md` (plus `RBM_PROFILE.md` and `RBM_LEDGER.md` if present).
2. Check the founder's active **Calendar Capacity Tier** (`PEAK_4`, `LIGHT_1`, or `BLACKOUT_0`) and verified offer floor price.
3. Invoke `lfm-firefly` (or follow `agents/firefly_closer.md`) to:
   * Pre-handle the top 3 buyer objections (*Price/ROI, Trust/Proof, Effort/Timing*).
   * Draft the exact concise, high-status Turn 1 / Turn 2 / Turn 3 DM reply or closing block.
   * Lock in the **Single Pulse CTA** (either 2 scarce calendar slots or 1-click portal checkout).
4. Update `LFM_PIPELINE.md` (and alert **Butterfly** in `RBM_LEDGER.md` if hot leads require immediate follow-up today).
