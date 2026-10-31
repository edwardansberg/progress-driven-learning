# Original attempt EX-ROOM-T1

Data classification: Synthetic/example data; the response and conditions below are invented solely to show record mechanics.
Unit: [EX-ROOM-01](README.md)
Illustrative date: 2026-01-14
Mode: Guided practice
Activity state: Completed simulated attempt
Assessment: [Separate AI feedback](feedback-01.md)

## Task

A synthetic office wants room reservations. “Stop overlapping bookings, but a meeting can start exactly when another ends.” Write acceptance checks and identify any rule that still needs a decision. Assume all times use the same timezone.

## Agreed conditions

Criteria: Identify the interval boundary; give observable overlap and non-overlap cases; avoid claiming unsupported concurrency behavior; explain unresolved assumptions.
Permitted resources: Task text, own notes and requested agent hints.
Actual help: One agent hint before the final response: “Consider the case where an existing end time equals the new start time.”
Condition basis: In this fictional scenario, the agent saw the task, hint and supplied response in chat. Any absence of other help would be learner-reported; outside assistance cannot be verified. This is assisted practice.

## Original learner response — synthetic, preserved

> For a confirmed booking from 10:00 to 11:00, a request from 10:30 to 11:30 is rejected with a conflict message. A request from 11:00 to 12:00 is accepted. I used the hint to check the shared boundary. I have not specified what happens when two people submit at the same time. I need to ask what confirmed means.

## Limitations and follow-up

No live booking system was tested; these are proposed checks. No independent performance or workplace outcome is established.
Correction / learner revision: None recorded.
Next action: [Suggested practice](feedback-01.md#next-practice); no live next action or review entry.
