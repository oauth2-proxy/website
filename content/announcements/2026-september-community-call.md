---
title: "September 2026 community call recap"
date: 2026-09-02
summary: "A recap of our first monthly community call, including updates on v8, project priorities, and the slides. Our next call is on October 7th."
---

Thank you to everyone who joined our first monthly community call on September 2. It was great to connect with users and contributors to discuss where OAuth2 Proxy stands today and where it is headed next.

You can view the full [presentation slides on Google Slides](https://docs.google.com/presentation/d/1Scz3xwwZUrjDKon8wL8fL4UagcMlqJl3mLC_j3Lrb-I/edit?usp=sharing).

## Highlights from the call

### Project health and current focus
With limited maintainer time right now, our primary month-to-month focus remains on security updates and bug fixes to keep the project dependable.

### What is planned for v8
We shared progress on the upcoming v8 release:

- Moving structured YAML configuration from alpha toward beta and stable. Around 160 legacy flags have moved to YAML, replacing ambiguous booleans with explicit enum values.
- Introducing structured contextual logging through a logr interface backed by zerolog.

Looking further ahead, we also discussed aligning more strictly with the official OAuth2 and OIDC specifications, separating those flows cleanly, and sharpening the project scope around authentication rather than policy enforcement.

### Where we need help
Keeping OAuth2 Proxy healthy takes a community, and maintainer capacity is currently low. We welcome contributions in several areas:

- **Documentation.** Practical how-to guides, real-world integration guides, and better configuration examples.
- **Issue and PR triage.** Reviewing, reproducing, and categorizing incoming issues and pull requests.
- **End-to-end testing.** Expanding automated test coverage across common identity providers and deployment setups.

If you would like to help out, feel free to reach out on Slack or LinkedIn or join the next call.

## Next community call

Our next community call will take place on **October 7, 2026, from 13:00 to 14:00 UTC**.

- 09:00-10:00 EDT
- 14:00-15:00 BST
- 15:00-16:00 CEST
- 18:30-19:30 IST

[Join the next community call](https://meet.google.com/dqw-zngc-xir) to ask questions, share how you use OAuth2 Proxy, or get involved.

