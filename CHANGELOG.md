# Changelog

## v0.1.0

Initial release of EXCO — Autonomous Engineering Intelligence Platform:

- **Voice Overview & Live Voice Chat**:
  - 0–100 Voice Overview benchmark table in **Settings → Voice** ranking connected API voices (ElevenLabs, Gemini Native, OpenAI, Custom) ahead of generic Edge Neural fallback.
  - Interactive **Turbo / Standard / Deep Thought** workflow mode picker on Live Voice Chat startup, with same-model cross-key failover and session-locked voice consistency.
  - Play / Stop preview toggles on all voice cards and distinct Edge Neural fallback voices.
- **Model Overview & Same-Model Failover**:
  - Unified 0–100 model benchmarking across Turbo, Standard, and Deep Thought workflow modes with automatic cross-key failover for the same model before moving to the next-best model.
- **Workspace Organizer & Multi-Select**:
  - Automatic clean workspace folder organization (`config/`, `docs/`, `data/`, `assets/`), Recycle Bin deletion, and multi-select checkboxes with bulk delete in the Sidebar.
- **Process & Reliability**:
  - Bounded `spawn` output capture eliminating `stderr maxBuffer length exceeded` errors during workspace commands.
