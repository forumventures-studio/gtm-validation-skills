---
name: icp-scoring
description: Scores a list of contacts from 1 to 10 against the user's Ideal Customer Profile, so they know who to reach out to first. Use when the user pastes a list of contacts (text or CSV) and asks to score, rank, prioritize, or qualify them, or says "score these against my ICP."
---

# ICP Scoring

Score every contact from 1 to 10 against the user's ICP, then rank them so the best fits come first.

## Before you start

Read these files from the project:
- **ICP.md**: who the user is targeting, the buying committee, and disqualifiers
- **Buying Signals.md**: top signals, weak signals, and fake signals

If either file is missing, tell the user and ask them to paste it in. Don't guess the ICP.

## Input

A list of contacts, pasted as text or CSV. Use whatever fields are present, such as name, title, company, company size, industry, tools, LinkedIn URL, email, and any notes or recent activity.

## Scoring rubric

| Criteria | Points |
| --- | --- |
| Owns the pain: their role is the champion or decision maker in ICP.md | 0 to 3 |
| Company size fits ICP.md | 0 to 2 |
| A buying signal from Buying Signals.md is present: 2 for a top signal, 1 for a weak signal, 0 for none or a fake signal | 0 to 2 |
| Tech stack fits ICP.md | 0 to 2 |
| Reachable: has a LinkedIn profile or email | 0 to 1 |

Score a contact 0 overall if they match a disqualifier in ICP.md, and say which one.

If a field is missing, score that criterion 0 and note it in the reason. Don't assume.

## Output

A table ranked from highest score to lowest:

| Rank | Name | Company | Score | Reason |
| --- | --- | --- | --- | --- |

Keep each reason to one line, naming what drove the score, like "Head of RevOps, 120 people, just migrated CRMs."

After the table, add one line: how many contacts scored 8 or higher. Those are the ones to reach out to first.

## Rules

- Never invent details about a contact.
- Flag anything you're unsure about, so the user can check it.
- No em dashes.

---

Part of the From Idea to Signal kit by Forum Ventures Studio. Get the full setup guide, the session recording, and the slides: https://gtmsystem.forumvc.com/resources/from-idea-to-signal?utm_source=github&utm_medium=referral&utm_campaign=gtm-kit
