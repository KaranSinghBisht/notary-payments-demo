# Reliability policy CRP-6

A test may be placed under a bounded 24-hour quarantine when the same integration test fails during shared sandbox setup in at least three unrelated changes. Record the quarantine on the tracking issue with the test name, failure count, failure phase, and duration, and mirror it in the engineering tracker.

Product-assertion failures are never quarantined; they indicate a real regression and stay active.

Quarantine is a tracking decision. Do not disable workflows, modify test code, rerun every failed job, or merge anything as part of applying it.
