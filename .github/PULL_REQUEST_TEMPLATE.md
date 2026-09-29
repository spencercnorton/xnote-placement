## What changed

## Why

## How it was tested (GNOME Shell and XNote versions, monitors, what you moved and what came back)

## Checklist

- [ ] `node --check` on an `.mjs` copy of `extension.js` and `python3 tests/static-check.py` pass
- [ ] The "until settled, every geometry signal is the compositor's" rule still holds (see README, Timing)
- [ ] No note titles, monitor serials, machine names or personal paths in the diff
- [ ] `CHANGELOG.md` and `metadata.json` `version-name` updated if behaviour changed
