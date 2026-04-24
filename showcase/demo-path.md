# Demo Path

## Demo strategy: real-run first, scripted fallback

This project should be demonstrated through a real AI interaction whenever possible.

A purely scripted demo can look too polished and may fail to show the actual challenge this project is trying to solve: turning general-purpose AI tools into a more stable learning workflow.

However, because the system currently runs on general AI tools rather than a dedicated backend, the demo should also keep a documented fallback path. This makes the demo honest without pretending that the current system is already a finished application.

## Recommended real demo path

### Step 1 — Load the runtime entry documents

The evaluator or presenter opens a new AI conversation and loads the prepared runtime documents.

The goal is not to show every internal rule. The goal is to show that the AI can enter a controlled learning workflow after receiving the system documents.

### Step 2 — Start from onboarding

The user provides basic learning information, such as:

- native language;
- target language;
- current level;
- learning goal;
- preferred explanation language;
- available time for one session;
- preferred content type.

### Step 3 — Confirm a minimal learning plan

The system should produce a limited plan instead of an endless open-ended conversation.

The plan should include:

- what the user will practice;
- how the session is bounded;
- what counts as completion;
- what record or summary will be produced.

### Step 4 — Run one short learning session

The demo should run only one compact session.

A good demo session may include:

1. a short learning material;
2. one or two comprehension questions;
3. user response;
4. correction and explanation;
5. a brief session summary.

### Step 5 — Show continuity boundary

At the end of the session, the system should not pretend to remember future progress automatically.

Instead, it should produce a small continuation anchor or summary that can be saved and reused later.

This is important because the project does not assume a persistent backend.

## What the demo should prove

The demo should prove that the system can:

- start from structured onboarding;
- avoid immediately becoming a generic chatbot;
- keep one session bounded;
- produce useful feedback;
- generate a continuation anchor;
- expose limitations honestly.

## What the demo should not claim

The demo should not claim that the current system already has:

- a full backend;
- automatic cross-platform memory;
- real-time user monitoring;
- guaranteed stability across all AI models;
- fully validated learning outcomes.

## Fallback path

If the real demo fails because the AI model ignores part of the runtime documents, the presenter should use the failure as evidence for the core design problem:

> General-purpose AI tools need structured runtime constraints to behave consistently as learning systems.

The fallback should show a saved successful run or a shortened transcript, but it should be clearly labeled as a recorded example rather than a live result.

## Suggested demo evaluation questions

Reviewers can use these questions:

1. Did the system behave more like a learning workflow than a generic chatbot?
2. Did it keep the session bounded?
3. Did it avoid making unsupported continuity claims?
4. Did it produce feedback that a learner could act on?
5. Did the project explain its current limitations clearly?
