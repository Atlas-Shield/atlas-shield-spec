# policies/
Example policy packs (no proprietary heuristics).

## Structure
- `basic/` — minimal guard policies
- `agent-tools/` — safer tool/OS action constraints
- `exfiltration/` — data leakage checks

Each pack SHOULD include:
- `policy.yaml` (schema TBD)
- `README.md` with scope, assumptions, and limitations
- `examples/` with minimal inputs

License: Apache-2.0 unless stated otherwise.
