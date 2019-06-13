# Bounties

1. Bounties provide a mechanism for funding tasks. 
1. Tasks are tracked as [Lexinomicon issues](https://github.com/cryptotechguru/Lexinomicon/issues).
1. The bounty MUST get its own page which includes:
* name (Bounty-#) where # is the issue #
* associated issue link
* lead [Director](../../Roles/Director)
* lead [Executive](../../Roles/Executive)
* assigned [Treasurer](../../Roles/Treasurer)
* associated project link
* requirements
* estimate
* funding deadline
* bounty address 
* deliverables

## Process

The players involved SHOULD marshal the bounty through the following standard stages in the [Bounties project](TBD):

### Triage

1. The bounty's wiki page and corresponding issue are created and cross-linked.
1. Requirements (acceptance criteria) are managed by the Director.
1. An estimate (from the table below) is provided by the Executive.
1. The Director and Executive negotiate requirements and estimates until they come to a common understanding.
1. When ready the Director moves the issue to `Proposed` and hands off (assigns the issue) to the Treasurer.

### Proposed

1. The Treasurer reviews the bounty's market value against comparable work in other markets. If out of line the Treasurer SHOULD send the issue back to `Triage`.
1. The Treasurer creates a crowdfund page on the pay server and publishes the corresponding link on the wiki page.
1. The Treasurer notifies subscribers that the bounty is open for funding.
1. The Treasurer monitors the funding and periodically notifies subscribers of progress.
1. If the bounty funding reaches 100% the Treasurer moves the issue to `In Progress` and hands off to the Executive.
1. If the deadline is reached before the bounty is funded the Treasurer is responsible for sending refunds to participants, updating the wiki page and closing the issue.

### In Progress

1. The Executive is responsible for delivering on the requirements.
1. The Executive should periodically update the issue with progress reports.
1. After the bounty is funded the requirements and/or estimate MAY only be updated if both the Director and Executive approve the changes.
1. When ready the Executive updates the Deliverables section of the wiki page, moves the issue to `In Review`, and hands off to the Director.

### In Review

1. The Director is responsible for testing deliverables against requirements.
1. The Director opens separate issues for any deltas found, moves the bounty issue back to `In Progress` and hands off to the Executive.
1. If the requirements are all satisfied the Director moves the issue to `Complete` and hands off to the Executive and Treasurer.

### Complete

1. The Executive creates a payment request in the pay server and sends a link directly to the Treasurer.
1. The Treasurer verifies the request and sends the payment to the Executive.
1. When the payment is received the Executive closes the issue.

## Estimates

1. The Treasurer is responsible for periodically adjusting bounty sizing estimate table.
1. The Director and Executive can request an update to the estimate table at any time.

| size | time (hours, P50/P90) | bounty (BTC) | 
| ---- | ----- | ----- |
| S    |  5/10 | 0.125 |
| M    | 10/20 | 0.250 |
| L    | 20/40 | 0.500 |
| XL   | 40/80 | 1.000 | 
