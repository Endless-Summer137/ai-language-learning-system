# Live Demo Script — ChatGPT

## Demo position

This demo uses ChatGPT as the live runtime environment.

The goal is not to prove that the project is already a finished app. The goal is to show that a structured runtime package can guide a general-purpose AI model into a bounded language-learning workflow.

## Why ChatGPT?

ChatGPT is selected for the first live demo because it usually has stronger instruction-following, longer-context handling, and more stable English output than many lightweight or free general-purpose models.

This does not mean the system is permanently tied to ChatGPT. The long-term goal is to make the runtime package robust enough to be tested across multiple AI tools.

## Presenter opening

Suggested opening:

> This project is not a normal language-learning app yet. It is a structured AI workflow harness. In this demo, I will load the runtime documents into ChatGPT and show whether a general AI tool can be guided into a bounded learning session instead of becoming a loose translation chatbot.

## Demo setup

Use a fresh ChatGPT conversation.

Recommended conditions:

- Use one clean conversation only for the demo.
- Do not mix development discussion with the demo.
- Use a short learning goal.
- Keep the first run within one compact session.
- Prefer English interface output if presenting to a mixed or international audience.

## Live demo flow

### Step 1 — Load runtime entry

Presenter action:

- Paste or upload the prepared runtime entry documents.
- Ask ChatGPT to initialize the system according to the runtime entry.

Expected result:

- ChatGPT should acknowledge the learning system boundary.
- It should start onboarding rather than freely explaining the whole internal system.

### Step 2 — Provide learner profile

Use a compact test profile, for example:

```text
Native language: Chinese
Target language: English
Current level: intermediate
Goal: understand short cultural or technology-related English articles more naturally
Preferred explanation language: English with occasional Chinese support
Session length: 15 minutes
Preferred content type: short article + comprehension practice
```

Expected result:

- ChatGPT should produce a minimal plan or session setup.
- It should not create an endless curriculum.

### Step 3 — Confirm the plan

Presenter says:

```text
I accept this minimal plan. Please start the first session.
```

Expected result:

- ChatGPT starts one bounded learning session.
- It should present a short learning material and a small number of tasks.

### Step 4 — Answer as the learner

Use a deliberately imperfect answer so the correction function can be shown.

Expected result:

- ChatGPT gives correction.
- The explanation should be useful but not too long.
- It should remain inside the current session.

### Step 5 — End the session and generate anchor

Presenter says:

```text
Please end this session and generate a continuation anchor I can save for later.
```

Expected result:

- ChatGPT gives a short session summary.
- It should generate a continuation anchor.
- It should not claim automatic long-term memory.

## What to say if the demo works

Suggested explanation:

> The key result is not that ChatGPT can answer language questions. The key result is that the runtime documents can constrain a general AI tool into a bounded learning workflow: onboarding, plan confirmation, task execution, feedback, and continuation anchoring.

## What to say if the demo partially fails

Suggested explanation:

> This partial failure is also useful. It shows why the project exists: general AI tools are powerful, but without runtime constraints they easily become unstable, over-helpful, or unclear about progress boundaries. The project is currently focused on making those boundaries more reliable.

## Failure handling table

| Problem | Presenter response |
|---|---|
| ChatGPT explains too much internal system content | Say that the runtime entry needs stronger user-facing masking. |
| ChatGPT creates an endless plan | Point out that plan boundedness is a known design focus. |
| ChatGPT forgets to create a continuation anchor | Ask for the anchor explicitly and mark it as a runtime gap. |
| ChatGPT mixes languages too much | Explain that language-routing rules are still being refined. |
| ChatGPT behaves like a generic tutor | Show how the system still needs stronger session-state enforcement. |

## Demo success criteria

A successful demo should show:

- a clear onboarding start;
- a bounded session;
- task-based learning rather than pure translation;
- correction or feedback;
- a saved continuation anchor;
- honest limitation handling.

## Important boundary

This demo should not overclaim.

Do not say:

- the system has a finished backend;
- progress is automatically remembered across all conversations;
- the learning effect has already been scientifically validated;
- every AI model can run the system equally well.

Say instead:

- the current version is a structured runtime harness;
- the system is being validated through controlled live runs;
- the next step is to improve runtime stability and reduce user setup friction.
