# monoprop-electronics

**Avionics hardware** for the Monoprop UAV / lander: PCB schematics, board
layouts, gerbers, and datasheets.

> **Provenance:** Split out of the monolithic
> [`GTPL-Testing/MonopropUAV`](https://github.com/GTPL-Testing/MonopropUAV)
> repository during the July 2026 reorganization. Full commit history for these
> files is preserved. See the [GTPL-test root README](../README.md) for the
> complete old→new mapping.

## Contents

| Path | What it is |
|------|------------|
| `Electronics/6-axisIMU/` | 6-axis IMU board |
| `Electronics/ESP32/` | ESP32-based avionics board |
| `Electronics/finalSchematic/`, `Electronics/fullSchem/` | Full-system schematics |
| `Electronics/GSE_SignalConditioningBoard/` | Ground-support-equipment signal conditioning board |
| `Electronics/TICC1101/` | CC1101 radio transceiver board |
| `Electronics/VCSEL/` | VCSEL sensor board |
| `Electronics/Jetec JPT 131/` | Component / vendor reference |

## Related repos

- [`monoprop-firmware`](../monoprop-firmware) — firmware that runs on these boards
- [`monoprop-flight-software`](../monoprop-flight-software) — real-time integrated control loop
