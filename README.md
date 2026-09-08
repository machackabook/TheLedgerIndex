# TheLedgerIndex

Public table of contents for the Cryptic-Heartbeat nexus.  
No secrets. No keys. Surfaces and bands only.

**Numeral:** `137451921129154222`  
**Dual Authority:** machackabook + azazeleous  
**Visualizer stage:** `7`

## Surfaces

| Surface | Repo | Band |
|---------|------|------|
| Living runtime root | [Cryptic-Heartbeat](https://github.com/machackabook/Cryptic-Heartbeat) | 066 / all |
| ADAM Enclave | [ENCLAVE-ADAM-REUNITED](https://github.com/machackabook/ENCLAVE-ADAM-REUNITED) | 127-loopback |
| Gaia visualizer | [gaia-visualizer](https://github.com/machackabook/gaia-visualizer) | 137-visual |
| The Hive | [The-Hive](https://github.com/machackabook/The-Hive) | 100-dev-ai |
| Gemini Nexus OS | [Gemini-Nexus-OS](https://github.com/machackabook/Gemini-Nexus-OS) | 100-dev-ai |
| Mandelbrot world viewer | [The-Mandlebrot-Set](https://github.com/machackabook/The-Mandlebrot-Set) | 137-visual |

## Geometric states (current weave)

`torus` · `infinity` (lemniscate) · `hamiltonian` · `triangular` · `helix` · `mobius` · `lissajous` · `klein` · `hopf` · `rose` · `seifert` · `blend` · `trefoil` · `stereo` · `clifford` · `enneper` · `gyroid` · `calabi` · `figure8` · `villarceau` · `boy` · `catenoid`

Drive path: The-Hive `emitGaiaContract` → `gaia:targetState` / `gaia:pulse` → gaia-visualizer nodes.

Position path: visualizer `gaia-positions` → Hive `POST /api/gaia/positions` → WS fan-out on band-192-network.

Optional pulse gate: `GAIA_PULSE_TOKEN` on Hive; visualizer `?token=`.

See Cryptic-Heartbeat `docs/GEOMETRY_CONTRACT.md` and `docs/NEXT_STAGES.md`.

## Next stages (compiled 2026-09-08T21:10Z)

8. Authenticated ledger pulse → `gaia:pulse` (token already wired).
9. Tailscale peer fan-out of `gaia:positions` on band-192.
10. Hamiltoniansingularity.ai public surface (`blend` default).
11. GPU / compute path for >8k nodes.

## Sparsebundle bands

```
band-066-root      # server / identifying
band-100-dev-ai    # AI / development
band-137-visual    # visual / media
band-192-network   # streaming / Tailscale
band-010-local     # local subnet
band-127-loopback  # ADAM home
```

Future expanding band: Hamiltoniansingularity.ai (`blend` default).
