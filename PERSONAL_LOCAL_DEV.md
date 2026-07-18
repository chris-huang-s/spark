# Personal local Spark notes

Personal setup notes for this fork. Not upstream documentation.

## Goals

- Keep a reproducible local Spark play environment
- Capture defaults I actually use for learning and small experiments
- Avoid re-discovering launch flags every session

## Local launch preferences

- Prefer a single-machine local master for day-to-day exploration
- Start with conservative driver memory and increase only when jobs spill
- Keep example jobs small enough to finish in a few minutes

## Session checklist

1. Confirm Java / Scala toolchain versions match what this checkout expects
2. Build or use an already-built distribution for local mode
3. Run one tiny example job end-to-end before changing core code
4. Capture failing command lines here when something breaks

## Notes to extend

- Common failure modes I hit locally
- Useful example jobs for regression smoke checks
- Commands worth aliasing in my shell
