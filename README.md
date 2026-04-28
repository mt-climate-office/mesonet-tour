# Montana Mesonet — Data Flow Tour

A Prezi-style HTML presentation walking through the Montana Mesonet data pipeline, from field sensors to public API and downstream products.

## Presenting

Serve locally (required for iframe previews to load):

```bash
python3 -m http.server 8888
# then open http://localhost:8888
```

## Controls

- `→` / `Space` — next stop
- `←` — previous stop
- `1`–`7` — jump to stop
- `f` — fullscreen

## Stops

1. **Overview** — full canvas, 215 active stations
2. **AgriMet** — METER sensors, ZL6 logger, Zentra Cloud telemetry
3. **HydroMet** — discrete sensors, CR1000X, bespoke CRBasic programs
4. **The Y-split** — two ingestion stacks converging
5. **Cyberinfrastructure** — AirTable, PostgreSQL, QA/QC, production repos
6. **Products** — Public API v2, Dashboard, Photo Explorer, Drought tools
7. **Closing** — network scale and growth
