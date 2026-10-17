<!--
  Sagar Tailor · github.com/slazyverse

  Every figure on this page is generated from one set of design tokens by
  tools/build_assets.py; the activity figure is rebuilt every six hours by
  .github/workflows/telemetry.yml. Figures ship as dark and light files,
  chosen per viewer with <picture> and prefers-color-scheme. Link chips carry
  both palettes inside one file instead, because GitHub cannot keep a
  <picture> inside a link — so nothing linked on this page is a <picture>.
-->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/hero/name-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/hero/name-dark.svg" width="100%" alt="Sagar Tailor">
</picture>

**Computer Science & Engineering**<br>
AI&nbsp;/&nbsp;ML &nbsp;·&nbsp; Backend &nbsp;·&nbsp; Systems &nbsp;·&nbsp; Scientific&nbsp;Computing

<br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/hero/headline-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/hero/headline-dark.svg" alt="builds the layer underneath">
</picture>

<a href="https://github.com/slazyverse"><img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/links/github.svg" height="36" alt="GitHub"></a>&nbsp;
<a href="https://sagar-tailor-portfolio.vercel.app/"><img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/links/portfolio.svg" height="36" alt="Portfolio"></a>&nbsp;
<a href="https://www.linkedin.com/in/sagar-tailor-9a7646377/"><img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/links/linkedin.svg" height="36" alt="LinkedIn"></a>

<br>

Software is strata. People touch the surface; almost nobody sees the scheduler, the lock, the migration or the trace beneath it. That lower layer is where I work — and this page descends through it.

</div>

<br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-00-surface-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-00-surface-dark.svg" width="100%" alt="Stratum 00: Surface">
</picture>

### Who I am

I'm a B.Tech Computer Science & Engineering student at Lovely Professional University, building toward backend engineering, systems and applied AI/ML.

I'm drawn to the part of software that has to be *right* rather than merely visible: shared state under contention, a pipeline fed by unreliable sources, a service that should refuse a dangerous configuration instead of trusting that nobody will ask for one. I like taking an idea through data, experiment, implementation and validation — and then writing down why it works, next to the code that makes it work.

Everything below links to a repository, a file or a pull request. If a claim can't be pointed at, it isn't here.

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/signal-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/signal-dark.svg" width="100%" alt="">
</picture>

### What I work on

<table>
<tr>
<td width="50%" valign="top">

**Systems & concurrency**<br>
Shared state under contention, safety checks, cycle detection, and live state pushed over WebSockets.<br>
<sub>→ <a href="https://github.com/slazyverse/deadlockd">deadlockd</a></sub>

</td>
<td width="50%" valign="top">

**Backend & data platforms**<br>
Async APIs, migrations, structured logging, scheduled collection, containerised environments.<br>
<sub>→ <a href="https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-">AKASH</a> · <a href="https://github.com/Rexy-5097/apix">APIx</a></sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Scientific computing**<br>
Satellite, atmospheric and instrument data, and pipelines that fail closed when the data breaks their assumptions.<br>
<sub>→ <a href="https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-">AKASH</a> · <a href="https://github.com/Rexy-5097/AdityaNet/pull/23">AdityaNet</a></sub>

</td>
<td width="50%" valign="top">

**Applied AI / ML**<br>
Where I'm heading next: from the platform around models to the models themselves — features, evaluation, error analysis.<br>
<sub>→ <a href="#current-direction">current direction</a></sub>

</td>
</tr>
</table>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-01-interface-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-01-interface-dark.svg" width="100%" alt="Stratum 01: Interface">
</picture>

### Toolkit

Split the way my portfolio splits it: what has shipped in a public repository, and what I use but haven't shipped yet.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/toolkit/icons-light.svg">
    <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/toolkit/icons-dark.svg" height="40" alt="Go, Python, TypeScript, FastAPI, PostgreSQL, Docker, GitHub Actions, Next.js, React, Three.js, Tailwind CSS, Linux">
  </picture>
</p>

| Layer | Shipped in a public repository |
|:--|:--|
| **Languages** | Go · Python · TypeScript<br><sub>deadlockd · AKASH · portfolio</sub> |
| **Backend & systems** | FastAPI · Go + gorilla/websocket · Pydantic v2 · structlog<br><sub>AKASH · deadlockd</sub> |
| **Data** | PostgreSQL + PostGIS · async SQLAlchemy 2.0 · Alembic · SQLite<br><sub>AKASH · APIx</sub> |
| **Scientific data** | FITS instrument products · pandas · Plotly · Folium<br><sub>AdityaNet · AKASH</sub> |
| **Interface** | Next.js · React · Three.js / React Three Fiber · Tailwind · Streamlit<br><sub>portfolio · deadlockd · AKASH</sub> |
| **Delivery** | Docker Compose · GitHub Actions · Vercel · pytest · go test · Vitest · Playwright<br><sub>all of the above</sub> |
| *Working knowledge* | *Java · C · C++ · scikit-learn · NumPy · Redis*<br><sub>coursework and study — not yet shipped</sub> |

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-02-engine-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-02-engine-dark.svg" width="100%" alt="Stratum 02: Engine">
</picture>

### Selected work

Three repositories I own. Each figure animates something the code actually does.

<br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/projects/deadlockd-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/projects/deadlockd-dark.svg" width="100%" alt="deadlockd replaying its CIRCULAR_WAIT scenario: three processes and three resources close a cycle, the engine detects it, terminates P0, and the state becomes safe">
</picture>

#### [deadlockd](https://github.com/slazyverse/deadlockd)

*A deadlock simulator and concurrency visualiser.* &nbsp;<sub>Go · Next.js · TypeScript · WebSockets · Docker · MIT — sole author</sub>

A Go engine runs every simulated process as its own goroutine, competing for shared resources. Each request is applied tentatively, checked with the Banker's algorithm, and committed or rolled back; when a circular wait closes, the engine finds the cycle and recovers by terminating a victim. A Next.js client renders the resource-allocation graph live over a WebSocket bridge.

- **A short critical section.** The safety check copies the allocation matrices under the mutex and releases it before its O(P²·R) search, so the expensive part never blocks other goroutines — [`banker.go#L15-L30`](https://github.com/slazyverse/deadlockd/blob/main/backend/engine/banker.go#L15-L30)
- **No recursion in cycle detection.** An explicit-stack DFS with white/grey/black colouring, which reconstructs the cycle itself from the stack — [`detection.go`](https://github.com/slazyverse/deadlockd/blob/main/backend/engine/detection.go)
- **Tests assert state, not success.** A granted request must move `Available`, `Allocation` and `Need` to exact values; CI runs `go mod verify`, the Go suite and a frontend build on every push — [`scenarios_test.go`](https://github.com/slazyverse/deadlockd/blob/main/backend/engine/scenarios_test.go) · [`ci.yml`](https://github.com/slazyverse/deadlockd/blob/main/.github/workflows/ci.yml)
- **A stress mode.** `NIGHTMARE=1` releases a thundering herd — 50,000 processes against 5,000 resources — and logs heap and GC behaviour as it runs — [`nightmare.go`](https://github.com/slazyverse/deadlockd/blob/main/backend/engine/nightmare.go)

**Repository** [slazyverse/deadlockd ↗︎](https://github.com/slazyverse/deadlockd) &nbsp;·&nbsp; **Architecture** [runtime flow ↗︎](https://github.com/slazyverse/deadlockd/blob/main/docs/diagrams/runtime-flow.md) &nbsp;·&nbsp; **Run it** `docker compose up` starts the Go engine and the Next.js client together.

<br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/projects/akash-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/projects/akash-dark.svg" width="100%" alt="AKASH: a satellite sweeps an illustrative analysis grid, beside the project's four layers — observe and model were built by teammates; serve and see are mine">
</picture>

#### [AKASH](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-)

*A satellite air-quality platform for India.* &nbsp;<sub>Python · FastAPI · PostgreSQL / PostGIS · Streamlit · Docker — team project; the platform layer is mine</sub>

Surface AQI, formaldehyde (HCHO) hotspots and active-fire monitoring over India, estimated from satellite observations — Sentinel-5P TROPOMI, MODIS aerosol optical depth, ERA5 reanalysis — with CPCB and OpenAQ ground stations as reference. It was built against the [ISRO Bharatiya Antariksh Hackathon 2026 problem statement](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/blob/main/data_collection_pipeline/README.md); inside the codebase it is called VAYU-DRISHTI.

**What I built:** the backend foundation, its live-data API layer and the GIS dashboard — the platform the team's science runs on and is read through.

- **Fails at import, not in production.** The settings model refuses `DEBUG=True` alongside `ENVIRONMENT=production`; the misconfiguration raises before the app can accept a request — [`config.py`](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/blob/main/backend/app/core/config.py)
- **One trace ID per request.** Middleware binds a request ID into structlog's context, so every log line carries it and the caller gets it back as `X-Request-ID` — [`main.py`](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/blob/main/backend/app/main.py)
- **One database driver.** Alembic runs migrations through `asyncio` and `create_async_engine`, so asyncpg serves runtime and migrations alike — and every dependency carries a line saying why it is there — [`requirements.txt`](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/blob/main/backend/requirements.txt)
- **A dashboard with honest states.** Streamlit and Folium pages for surface AQI, HCHO hotspots, fire monitoring, forecasts, explainability and reports, each with explicit loading, empty and error states — [`dashboard/`](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/tree/main/dashboard)

**What teammates built:** the data-collection and ML pipeline (Yeshika), and the AQI calculation, Earth Engine ingestion and Random Forest baseline (Soumyadeb). **State:** in progress — a research pipeline and platform, not an operational air-quality service.

<br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/projects/portfolio-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/projects/portfolio-dark.svg" width="100%" alt="The portfolio's descent: four planes — surface, interface, engine, substrate — pass the camera one after another, each showing one step of a real request">
</picture>

#### [Engineering portfolio](https://sagar-tailor-portfolio.vercel.app/)

*The layer underneath.* &nbsp;<sub>Next.js 16 · TypeScript · Three.js / React Three Fiber · Tailwind v4 · Vitest · Playwright — sole author</sub>

A portfolio built as a cross-section rather than a page. A procedural WebGL city is the way in; beneath it the site descends through interface, engine and substrate, following one real deadlockd request from the click down to the four lines of Go that decide whether it is safe.

- **Claims are typed.** A `Claim` cannot be constructed without a `Source` pointing at the file that proves it, so the honesty rule is enforced by the compiler — [`types.ts`](https://github.com/slazyverse/portfolio/blob/main/src/data/types.ts)
- **Evidence is tested.** A CI suite fetches every cited source and fails the build if a link dies or a quoted excerpt drifts from the file it quotes — [`evidence.test.ts`](https://github.com/slazyverse/portfolio/blob/main/tests/evidence.test.ts)
- **Budgets are gates.** Initial JavaScript has a hard 200 KB gzipped ceiling checked in CI; the WebGL layer is split out and loaded only after capability probes — [`check-budget.mjs`](https://github.com/slazyverse/portfolio/blob/main/scripts/check-budget.mjs)
- **Contrast is asserted.** A test parses the design tokens and checks every text–surface pairing against WCAG AA, alongside axe checks in Playwright — [`contrast.test.ts`](https://github.com/slazyverse/portfolio/blob/main/tests/contrast.test.ts)

**Live** [sagar-tailor-portfolio.vercel.app ↗︎](https://sagar-tailor-portfolio.vercel.app/) &nbsp;·&nbsp; **Repository** [slazyverse/portfolio ↗︎](https://github.com/slazyverse/portfolio)

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/orbit-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/orbit-dark.svg" width="100%" alt="">
</picture>

### Collaborative work

Repositories owned by other people, where I built a defined part. Kept separate from my own work on purpose.

<table>
<tr>
<td>

**[APIx](https://github.com/Rexy-5097/apix)** &nbsp;<sub>repository owned by <a href="https://github.com/Rexy-5097">Rexy-5097</a> · collaborative contribution</sub>

A quality-adjusted, high-frequency airfare price index for India, and the auditable infrastructure that produces it — built against MoSPI problem statement 26056.

**My part:** the data acquisition and ingestion layer — collectors, the SQLite observation store, the collection scheduler, execution-boundary and exclusion-replay analysis, and the test suites around them. 16 of the 29 commits on `main`, and 17 merged pull requests.

The project deliberately publishes no index yet: one collection wave on one route cannot carry that claim, and [its README says so](https://github.com/Rexy-5097/apix#readme).

</td>
</tr>
<tr>
<td>

**[AdityaNet](https://github.com/Rexy-5097/AdityaNet)** &nbsp;<sub>repository owned by <a href="https://github.com/Rexy-5097">Rexy-5097</a> · open-source contribution</sub>

A verifiable research platform for the Aditya-L1 SoLEXS and HEL1OS solar X-ray archive.

**My part:** the HEL1OS instrument parsers — light curves, spectra, housekeeping, good-time intervals and photon events, plus orbit identity and version precedence — in [one merged pull request](https://github.com/Rexy-5097/AdityaNet/pull/23). The pull request's archive-wide verification reports 389 of 391 orbits parsing fully clean, up from 134 before it; the other two are known archive defects. Where the real data falsified a rule in the spec, the parser kept enforcing the rule as written and recorded the evidence for the maintainer, rather than quietly weakening it.

</td>
</tr>
</table>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/pulse-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/pulse-dark.svg" width="100%" alt="">
</picture>

### System core

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/system/core-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/system/core-dark.svg" width="100%" alt="A core of four stacked strata with a request descending through it, while a hover vehicle orbits the outside and passes behind the core">
</picture>

The interface moves around the system; the system is the thing underneath. GitHub renders images, not runtimes, so this is only a preview — the interactive version, a WebGL descent through one real request and a Banker's algorithm you step through by scrolling, lives on the [portfolio ↗︎](https://sagar-tailor-portfolio.vercel.app/).

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-03-substrate-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/stratum-03-substrate-dark.svg" width="100%" alt="Stratum 03: Substrate">
</picture>

### How I think

I like problems where the obvious layer is not the interesting one.

> A race condition nobody noticed.<br>
> A dataset that rejects the clean assumption.<br>
> A model that looks correct until you test it.<br>
> An API that works locally and fails under load.<br>
> A system that only becomes elegant once its architecture is understood.

These are the principles I've taken from that kind of problem, each linked to the code where it was practised:

| Principle | Practised in |
|:--|:--|
| **Hold the lock for as short as you can.** Copy the state you need, release, then compute. | deadlockd · [`banker.go`](https://github.com/slazyverse/deadlockd/blob/main/backend/engine/banker.go#L15-L30) |
| **Make the failure impossible, not unlikely.** A dangerous configuration should fail to construct. | AKASH · [`config.py`](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/blob/main/backend/app/core/config.py) |
| **A system you can't observe is one you can't operate.** One trace ID from middleware to query. | AKASH · [`main.py`](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/blob/main/backend/app/main.py) |
| **When the data breaks the spec, record it — don't bend the rule.** | AdityaNet · [PR #23](https://github.com/Rexy-5097/AdityaNet/pull/23) |
| **Don't publish a number the evidence can't carry.** | APIx · [README](https://github.com/Rexy-5097/apix#readme) |
| **A decision that isn't written down didn't happen.** Reasons live beside the code. | AKASH · [`requirements.txt`](https://github.com/slazyverse/AKASH-Atmospheric-Knowledge-AQI-from-Satellite-Harmonics-/blob/main/backend/requirements.txt) |

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/wave-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/wave-dark.svg" width="100%" alt="">
</picture>

### Current direction

Directions I'm actively working in — not credentials.

- **Data structures & algorithms** — [slazyverse/leetcode](https://github.com/slazyverse/leetcode) is set up to record accepted Java solutions automatically, with pattern notes, complexity references and progress statistics generated from the solutions themselves.
- **Backend & real-time systems** — deeper Go concurrency, state synchronisation over WebSockets, and services that are observable by default.
- **Applied AI / ML** — moving from the platform around models to the models themselves: feature pipelines, evaluation, and honest error analysis.
- **Scientific & geospatial data** — satellite and instrument archives, and pipelines that keep their provenance.
- **System design** — the trade-offs behind an architecture, written down before it is built.

<sub>Coursework: Data Structures & Algorithms · Object-Oriented Programming · Programming in Java — iamneo × LPU &nbsp;·&nbsp; [certificates](https://github.com/slazyverse/slazyverse/tree/main/certificates)</sub>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/scan-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/scan-dark.svg" width="100%" alt="">
</picture>

### Activity

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/output/contribution-telemetry-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/output/contribution-telemetry-dark.svg" width="100%" alt="Contribution activity for the last twelve months: a scan line sweeps the contribution calendar and each active day flares as it passes, above a trace of weekly totals">
</picture>

<sub>Rendered every six hours from the public contribution calendar by [a workflow in this repository](https://github.com/slazyverse/slazyverse/blob/main/.github/workflows/telemetry.yml) — no third-party stats service.</sub>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/signal-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/dividers/signal-dark.svg" width="100%" alt="">
</picture>

### Connect

If you're working on systems, data infrastructure or research software — or you've found something wrong in one of my repositories — I'd like to hear about it.

<p align="center">
  <a href="https://sagar-tailor-portfolio.vercel.app/"><b>Portfolio ↗︎</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/sagar-tailor-9a7646377/"><b>LinkedIn ↗︎</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/slazyverse"><b>GitHub ↗︎</b></a>
</p>

<br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/footer/footer-light.svg">
  <img src="https://raw.githubusercontent.com/slazyverse/slazyverse/main/assets/footer/footer-dark.svg" width="100%" alt="Sagar Tailor — builds the layer underneath">
</picture>
