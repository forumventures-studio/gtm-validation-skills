---
name: prospect-list-builder
description: Turns the user's Ideal Customer Profile into a prospecting plan with exact job titles to search, company filters, where to find these people, and a ready-to-fill CSV. Use when the user asks to build a prospect list, find leads, plan who to target, or says "build my prospect list plan from my ICP."
---

# Prospect List Builder

Turn the user's ICP into a plan they can search with today.

## Before you start

Read these files from the project:
- **ICP.md**: the target companies, the buying committee, and disqualifiers
- **Buying Signals.md**: the changes that make a company likely to buy right now

If ICP.md is missing, tell the user to build it first. A list without an ICP is just random contacts.

## Output

### 1. Job titles to search
List the exact titles for each role in the buying committee: champion, decision maker, power user, and gatekeeper. Include common variations, like "Head of RevOps," "Revenue Operations Manager," and "Director of Sales Operations."

### 2. Company filters
Company size, industry, geography, and tech stack, ready to enter into LinkedIn Sales Navigator, Apollo, or a similar tool. Include the disqualifiers to exclude.

### 3. Signals to search for
Turn Buying Signals.md into specific searches, like "companies hiring a scheduler," "a new VP of Operations in the last 90 days," or "posts about migrating off spreadsheets."

### 4. Where to find these people and their signals
The specific channels and communities where this buyer spends time, like LinkedIn, Slack and Discord groups, subreddits, events, and warm intro paths. For each signal in Buying Signals.md, name where to spot it, like job boards, news, funding databases, or review sites.

### 5. A ready-to-fill CSV header

```
Name,Title,Company,Size,LinkedIn,Email,Signal,ICP Score,Reason,Angle,Connection Msg,Follow up 1,Follow up 2,Status
```

Start with 10 to 25 people, not 1,000. Small lists teach you faster.

## When tools are connected

If Apollo or Databar is connected, pull and verify the list automatically instead of leaving it for the user to fill by hand. Test on 10 rows first, then check them with the user before pulling more.

## Rules

- Never invent contacts, emails, or company details.
- No em dashes.

---

Part of the From Idea to Signal kit by Forum Ventures Studio. Get the full setup guide, the session recording, and the slides: https://gtmsystem.forumvc.com/resources/from-idea-to-signal?utm_source=github&utm_medium=referral&utm_campaign=gtm-kit
