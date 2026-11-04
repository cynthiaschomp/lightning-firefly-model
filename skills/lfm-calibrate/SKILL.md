---
name: lfm-calibrate
license: Apache-2.0
description: >-
  Initializes or recalibrates the Lightning Firefly Model (LFM) for the user's
  business and synchronizes it with the Rainbow Butterfly Model (RBM_PROFILE.md
  & RBM_LEDGER.md). Creates or updates LFM_PROFILE.md (brand offers, price
  floors, buyer ICPs, Lightning Rainmaker voice, Firefly Closer posture, and
  calendar capacity tiers) and LFM_PIPELINE.md (hot leads, active hook voltage
  campaigns, and buyer objection radar). Run this first after installing LFM,
  and run it again anytime offers shift or conversion feels off.
---

# LFM Calibrate: Rainmaker & Closer Setup & Recalibration Engine

## Overview

`lfm-calibrate` tunes **Lightning** (The Rainmaker) and **Firefly** (The Velvet-Rope Closer) to the founder's actual offer ecosystem, verified price floors, buyer psychology, conversion channels, and real-time calendar capacity—while linking directly to `RBM_PROFILE.md` and `RBM_LEDGER.md` when the **Rainbow Butterfly Model (`rbm`)** is installed.

It supports two modes automatically:
1. **Initial Calibration (First Run)**: When `LFM_PROFILE.md` or `LFM_PIPELINE.md` do not yet exist in the workspace.
2. **Recalibration Mode ("Conversions Feel Off")**: When `LFM_PROFILE.md` already exists, or when the user says *"recalibrate LFM"*, *"hooks feel off"*, *"leads are stalling in the DMs"*, or *"our offer changed"*.

---

## Step 1: Detect Calibration & RBM State

Check the current workspace root for `LFM_PROFILE.md`, `LFM_PIPELINE.md`, `RBM_PROFILE.md`, and `RBM_LEDGER.md`.
* **If `RBM_PROFILE.md` exists**: Automatically inherit the verified founder name, core brands/umbrellas, floor prices, and North Stars so the user never has to repeat themselves.
* **If `LFM_PROFILE.md` does not exist**: Announce **Initial Calibration Mode** and proceed to Step 2A.
* **If `LFM_PROFILE.md` exists**: Read both `LFM_PROFILE.md` and `LFM_PIPELINE.md`, announce **Recalibration Mode**, and proceed to Step 2B.

---

## Step 2A: Initial Calibration Interview

Gather or confirm the 5 core conversion dimensions from the user (pre-populating anything already verified in `RBM_PROFILE.md` or workspace docs):

1. **Approved Offers & Verified Floor Prices**:
   * Which brands/offers are active and approved to sell right now, and what is the minimum floor price for each? *(Never guess financial figures; use `--` if unconfigured.)*
2. **Target Buyer ICP & Bleeding-Neck Pain**:
   * Who is the exact decision-maker we want **Lightning** to stop in the feed, and what expensive problem are they actively bleeding money or time on today?
   * Who is our **Anti-Audience** (freebie-seekers or bad-fit prospects we deliberately filter out)?
3. **⚡ Lightning Rainmaker Tuning**:
   * Which Rainmaker Voice fits best?
     * `Forensic Executive Operator` (Leads with live technical receipts, teardowns, and hard architecture truth)
     * `Contrarian Systems Architect` (Exposes why industry-standard agency playbooks fail and shows the structural replacement)
     * `Category-King Builder` (Demonstrates proprietary products and cross-brand benchmarks in action)
4. **✨ Firefly Closer Tuning**:
   * Which Closer Posture fits best?
     * `Velvet-Rope Selective` (Zero chasing; offers at most 2 scarce calendar windows or 1-click portal checkout)
     * `Diagnostic Executive Closer` (Leads with 1 sharp diagnostic question in the DMs before offering a call or portal link)
     * `Async Portal-First Closer` (Routes prospects directly to a time-gated deliverable report with 1-click approval/checkout)
   * How should **Firefly** adapt to your calendar capacity (`PEAK_4`, `LIGHT_1`, `BLACKOUT_0` recovery days)?
5. **Initial Pipeline & Active Campaigns**:
   * What are the top 1–2 active campaigns/keywords or warm threads we should track in `LFM_PIPELINE.md` today?

---

## Step 2B: Recalibration Mode ("When Hooks or Closes Feel Off")

When the user triggers recalibration, read `LFM_PROFILE.md`, `LFM_PIPELINE.md`, and `RBM_LEDGER.md` and diagnose which of the 4 conversion drift patterns is occurring:

1. **A. Scroller-Trap Drift (High Views / Zero Buyers)**: Lightning hooks are too broad; tighten Bolt #2 (`Buyer vs. Scroller Filter`) and Bolt #4 (`Forensic Receipt Proof`).
2. **B. DM Mid-Thread Drop-Off**: Prospects trigger the keyword on Turn 1 but ghost on Turn 2; simplify Firefly's Turn 1 diagnostic question so it takes `< 5 seconds` to reply.
3. **C. Price / Scope Hesitation at Checkout**: Prospects hesitate at the proposal or checkout step; strengthen Firefly's pre-handled ROI anchor and risk-reversal receipt, and feed the objection back to **Rainbow (`rbm-rainbow`)**.
4. **D. Calendar Burnout Drift**: Too many live calls are being offered on low-energy days; tighten Firefly's `LIGHT_1` / `BLACKOUT_0` pivot to async `/portal/` closes.

---

## Step 3: Write `LFM_PROFILE.md` and `LFM_PIPELINE.md`

Using `resources/templates/LFM_PROFILE.template.md` and `resources/templates/LFM_PIPELINE.template.md`, write or update:
* `./LFM_PROFILE.md`
* `./LFM_PIPELINE.md`

Confirm calibration is complete and share clickable links to both files.
