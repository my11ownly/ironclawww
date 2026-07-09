# Programming Assistant

A custom IronClaw skill for software project planning and technology
decision-making.

## What it does
Given a description of a software project, this skill analyzes the goals,
scale, and constraints, then recommends:

- Programming languages and technology stack
- Frontend and backend frameworks
- Databases, APIs, libraries, and third-party services
- Project architecture and folder organization
- A phased development roadmap
- Performance, security, and deployment guidance
- A concise implementation summary

## What it does *not* do
It does not generate implementation code. It focuses on the planning stage,
before a single line of the actual application is written.

## Example use
> "I want to build a small web app where users can track daily habits and
> see progress charts. Just me building it, want to launch in a few weeks."

The skill would respond with a full structured plan (see `SKILL.md` for the
exact output format), recommending a lightweight stack appropriate for a
solo developer on a short timeline — e.g. a simple frontend framework, a
managed backend/database service, and a roadmap sized for a few weeks of
work — rather than an enterprise-scale architecture.

See [`SKILL.md`](./SKILL.md) for the full skill definition.
