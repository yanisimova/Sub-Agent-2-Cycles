# Innovation and Disruption Agent
Assignment 3 — Yulia Anisimova, Emerging Technologies Section 103.

Version 0.3. Start with records/agent_record.md and records/test_record.md. Cases and final responses are in their named folders. Records also preserves prompt packets, validation results and earlier weak outputs.

From the scaffold directory, run:
```
python tools/check_frozen_core.py
python tools/build_prompt.py --agent agents/innovation_disruption --case agents/innovation_disruption/cases/primary.json
python tools/validate_response.py agents/innovation_disruption/responses/primary_response.json
```
Repeat with contrast_1, contrast_2 and ambiguous. ChatGPT is the reasoning runtime; no API key is needed. Model outputs and scenario assumptions are not independent evidence of commercial outcomes.
