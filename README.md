# Communication Rob

Turn rough thoughts into tactful, natural messages that sound like you, not AI.

`Communication Rob` is a Codex skill for polishing and drafting thoughtful communication in work and relationship-sensitive scenarios. It is designed for moments when wording matters: work chat, manager communication, work email, and networking outreach.

## What It Does

- infers the likely communication scene from your draft or context
- asks for a lightweight numbered scene choice
- generates 2-3 distinct, sendable versions
- keeps tone tactful, natural, and low-pressure
- lets you save good expressions, weak expressions, and your own revised versions back into the skill

## Default Scenes

1. Work chat
2. Manager communication
3. Work email
4. Networking

## Input It Supports

- raw draft text
- rough intent
- screenshots
- prior conversation context
- notes about the recipient, relationship, or goal

## Reference Library

The skill is designed to improve over time through a lightweight reference workflow:

- `examples-good.md` for strong expressions worth reusing
- `examples-bad.md` for weak or AI-sounding expressions to avoid
- `examples-user-edited.md` for user-revised final versions after seeing Communication Rob's outputs

## Repository Layout

```text
.
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    ├── do-and-dont.md
    ├── examples-bad.md
    ├── examples-good.md
    ├── examples-user-edited.md
    ├── modes.md
    └── style-templates.md
```

## Install

Copy this skill folder into your Codex skills directory:

```text
~/.codex/skills/communication-rob
```

Then invoke it explicitly with:

```text
Use $communication-rob to help with this message.
```
