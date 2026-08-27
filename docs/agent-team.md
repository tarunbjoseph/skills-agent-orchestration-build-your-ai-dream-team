# Project Pulse Agent Team

For Project Pulse, the Orchestrator coordinates work across the Planner, Designer, and Coder.

## Team summary

- **Orchestrator** — model: **Opus 4.7**; responsibility: break down the request, delegate work, and sequence delivery; definition: `.github/agents/orchestrator.agent.md`
- **Planner** — model: **Gemini 3.1 Pro**; responsibility: produce implementation phases, dependencies, and validation checkpoints; definition: `.github/agents/planner.agent.md`
- **Designer** — model: **GPT-5.5**; responsibility: shape the dashboard structure, UX flow, and visual direction; definition: `.github/agents/designer.agent.md`
- **Coder** — model: **GPT-5.5**; responsibility: implement the planned files and apply the approved design decisions; definition: `.github/agents/coder.agent.md`

## How the team works together

1. The Orchestrator gathers the Project Pulse goal and constraints.
2. The Planner proposes phases and dependencies before coding starts.
3. The Designer provides interface and usability guidance for each phase.
4. The Coder implements the files in execution order and incorporates design guidance.
5. The Orchestrator verifies that outputs align with the plan and validation criteria.
