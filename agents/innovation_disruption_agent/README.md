# Assignment 3 working copy

This repository was extracted directly from the frozen Brightspace ZIP. `main` preserves the starting scaffold; `assignment-3` contains the specialist. Only this specialist folder is edited after import. No API key is required.

## Next steps
1. Fill primary.json with your technology, application, organization, and evidence.
2. Use the same technology in contrast_1.json and contrast_2.json with different applications or organizations. Include an ambiguous or insufficient-evidence case.
3. Run `python3 tools/build_prompt.py --agent agents/innovation_disruption_agent --case agents/innovation_disruption_agent/cases/primary.json` from the repository root. Repeat for contrasts.
4. Paste each packet into ChatGPT and save JSON-only responses under this agent's responses folder. Preserve prompt copies in this agent's records folder if needed; root work files are ignored by the supplied scaffold.
5. Run `python3 tools/validate_response.py agents/innovation_disruption_agent/responses/primary_response.json` and `python3 tools/check_frozen_core.py`.
6. Record actual analytical results, diagnose a weakness, preserve the original instructions/responses, revise, rerun identical cases, and commit the tested candidate. Do not label setup smoke checks as completed assignment tests.

See records/test_plan.md and records/agent_record.md. Case files remain the supplied placeholders pending project context.
