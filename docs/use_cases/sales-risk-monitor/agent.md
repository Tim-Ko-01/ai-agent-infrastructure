# Sales Risk Monitor Agent

## Agent Role

The Sales Risk Monitor Agent continuously analyzes the sales pipeline and detects deals that are at risk of failing.

The agent evaluates signals from CRM data, sales activities, and communication patterns to identify potential problems early and notify responsible sales managers.

---

## Inputs

The agent uses the following input data sources:

* CRM pipeline data
* Deal stage and deal progression history
* Meeting notes and summaries
* Email sentiment and communication signals
* Sales activity history (calls, meetings, follow-ups)

---

## Risk Signals

The agent evaluates a set of signals that indicate potential deal risk.

Typical risk indicators include:

* Missing or decreasing customer engagement
* Deals stagnating in the same stage for extended periods
* Negative sentiment detected in meeting notes or emails
* Delayed or missing follow-up actions
* Lack of recent sales activities

---

## Agent Reasoning

The agent analyzes the collected signals and evaluates deal health using a combination of:

* predefined scoring rules
* LLM-based reasoning
* pattern detection across deal activity

Each deal receives a risk evaluation based on these signals.

---

## Output

For each analyzed deal, the agent produces:

**Risk Score**

A numerical score between **0–100** indicating the probability that a deal may fail.

**Risk Explanation**

A human-readable explanation of the identified risk signals.

**Recommended Action**

Suggested actions for the sales team, for example:

* Schedule executive alignment call
* Request technical validation from the customer
* Increase engagement with key stakeholders
* Escalate the deal to the sales manager
