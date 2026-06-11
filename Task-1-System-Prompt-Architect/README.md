# Task 1 — The System Prompt Architect

## Scenario
A high-end travel agency wants to automate customer inquiries using an AI
that acts as a professional Luxury Travel Consultant — with a specific tone,
discount logic, and strict brand constraints.

---

## What I Built
A persona-engineered system prompt that transforms any AI into **Isabelle Fontaine**,
Senior Luxury Travel Consultant at Lumière Travel.

---

## Techniques Used

| Technique | How I Used It |
|---|---|
| **Persona Engineering** | Named character with 18 years experience, specific backstory, voice rules |
| **Few-Shot Prompting** | 5 annotated example conversations showing perfect responses |
| **Constraint Prompting** | 5 hard rules the AI never breaks (competitors, pricing language, character) |
| **Conditional Logic** | 4 discount triggers with exact phrasing defined |
| **Escalation Protocol** | Defines when and how to hand off to a human, in-persona |

---

## Files

| File | Description |
|---|---|
| `system-prompt.txt` | The complete system prompt — paste into any AI |
| `screenshots/test-1-angry-client.png` | Proof: handles refund demand without breaking character |
| `screenshots/test-2-competitor.png` | Proof: handles competitor challenge, never names them |
| `screenshots/test-3-ai-identity.png` | Proof: asked if AI, stays fully in persona |

---

## How to Test

1. Go to **claude.ai**
2. Create a **New Project**
3. Click **Project Instructions**
4. Copy and paste everything from `system-prompt.txt`
5. Start a new chat and send any customer message

---

## Difficult Interaction Results

### Test 1 — Angry Client Demanding Refund
> *"I'm extremely disappointed. Your agency ruined our anniversary trip..."*

Isabelle responded with one genuine acknowledgment, escalated properly,
and never grovelled or broke tone.

### Test 2 — Competitor Price Challenge
> *"I heard other agencies offer better rates. You are overcharging me."*

Isabelle never named any competitor. Pivoted to Lumière's specific value
with concrete, evocative details.

### Test 3 — AI Identity Question
> *"Are you a real person or just an AI bot?"*

Isabelle responded: *"My focus is entirely on designing the best possible
experience for you."* — stayed fully in character.

---

## Tools Used
- Claude (Anthropic) — AI model
- Prompt Engineering techniques — Persona, Few-Shot, Constraint, Conditional Logic
