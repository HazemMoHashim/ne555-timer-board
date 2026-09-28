# NE555 Timer Board

555-timer board (NE555P) designed in Altium Designer. Small demo/timing
circuit with schematic, PCB layout, and fabrication outputs.

> **Naming note:** the original working folder was called
> `Simple_LDO_Converter` — a leftover typo. The circuit is a **555 timer**,
> not an LDO, so the repo is named accordingly. The folder on disk keeps its
> old name; only the repo reflects the real circuit.

## Contents

| File | Description |
|---|---|
| `NE555_Timer_Board.PrjPcb` | Altium project (renamed from `Simple_LDO_Converter.PrjPcb` — same typo as the folder) |
| `Schematic.SchDoc` | Schematic (555 timer circuit) |
| `PCB.PcbDoc` | PCB layout |
| `Gerbers.Cam` | CAM / Gerber job |

## Design status

- DRC: 13 rules checked, **0 violations** (last full check, Aug 2026)

## Toolchain

- Altium Designer X2 (24.x)
- BOM export: `Report > Bill of Materials`
- Gerbers: regenerate via the `.Cam` job (`Project Outputs*/` is gitignored)

## Notes

- `History/`, `__Previews/`, `Project Logs*/`, `Project Outputs*/` and
  `*.zip` are Altium-generated artefacts and are intentionally **not**
  versioned (see `.gitignore`). Regenerate them locally as needed.

## License

MIT — see [LICENSE](LICENSE).
