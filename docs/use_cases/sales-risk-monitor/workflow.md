# Sales Risk Monitor Agent – Workflow

## Overview

The Sales Risk Monitor Agent continuously evaluates the sales pipeline to detect deals that are at risk.

The workflow combines data retrieval, signal analysis, and risk evaluation.

---

## Step 1 – Trigger

The workflow can be triggered in two ways:

* scheduled analysis (e.g., every night)
* event-based triggers when deals are updated in the CRM

---

## Step 2 – Data Retrieval

The agent retrieves relevant deal data from the CRM system.

This includes:

* deal stage
* deal history
* recent sales activities
* meeting notes
* communication signals

---

## Step 3 – Signal Detection

The agent analyzes the retrieved data and identifies potential risk signals.

Examples:

* deal stagnation in a pipeline stage
* declining customer engagement
* negative meeting signals
* missing follow-ups

---

## Step 4 – Risk Evaluation

The agent evaluates all detected signals and calculates a **risk score**.

The score represents the probability that a deal may fail.

The evaluation may combine:

* rule-based scoring
* pattern detection
* LLM-based reasoning

---

## Step 5 – Output Generation

For each evaluated deal, the agent produces:

* risk score
* explanation of detected signals
* recommended actions

---

## Step 6 – Notification

If a deal exceeds a defined risk threshold, the system notifies the responsible sales manager.

Notifications may be delivered via:

* CRM alerts
* email
* internal messaging tools
