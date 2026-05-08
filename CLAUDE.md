# Claude Code Configuration

## Sub-agent Policy

All sub-agents spawned by Claude Code **must** use the `claude-opus-4-6` model. No other model is permitted for sub-agent tasks.

When using `Task()` or any sub-agent mechanism, always specify `model="claude-opus-4-6"`.
