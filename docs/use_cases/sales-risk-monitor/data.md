# Sales Risk Monitor Agent – Data Sources

## Overview

The Sales Risk Monitor Agent analyzes multiple data sources from the sales environment to detect signals indicating potential deal risk.

These data sources are primarily retrieved from the CRM system and related sales activity platforms.

---

## CRM Pipeline Data

The primary data source is the CRM sales pipeline.

Relevant fields include:

* deal ID
* deal stage
* deal value
* expected close date
* deal owner
* deal progression history

This data is used to evaluate deal progress and identify stagnating deals.

---

## Sales Activity Data

Sales activities provide insight into engagement with the customer.

Examples include:

* meetings
* calls
* follow-up tasks
* logged customer interactions

Low or missing activity can indicate reduced deal momentum.

---

## Meeting Notes

Meeting summaries and notes provide qualitative insight into customer interactions.

Signals extracted may include:

* customer concerns
* unresolved objections
* negative sentiment
* uncertainty about budget or timeline

---

## Email Communication Signals

Email interactions between sales teams and customers can indicate deal health.

Signals include:

* response frequency
* communication gaps
* sentiment analysis of messages

---

## Derived Signals

The agent also derives additional indicators from the available data.

Examples:

* time spent in current deal stage
* time since last customer interaction
* engagement trend over time

These derived signals help estimate the probability of deal failure.
