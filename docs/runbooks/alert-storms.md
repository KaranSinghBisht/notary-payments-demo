# Runbook: alert storms

When a burst of alerts is caused by a metrics or label change, consolidate the noise into the existing OPS tracking issue for alert noise and add the evidence (the change that caused it, the alert count, the time window). Do not create a new tracking issue if one exists.

A real incident that fires inside a noise burst stays open and separately tracked. Never suppress it, close it, or merge it into the noise issue.

Do not change monitoring code or label configuration as part of alert triage; that is a follow-up for the owning team.
