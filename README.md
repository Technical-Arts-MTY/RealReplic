<h1 align="center">RealReplic</h1>

<p align="center">
A platform where people, from early stages of education to higher education,<br>
can create and watch functional systems, physical, digital, or imaginary,<br>
following a simple engine that everyone can use.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Technical%20Arts-MTY-1f6feb">
<img src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey">
<img src="https://img.shields.io/badge/status-specification-orange">
</p>

## What this repository is

RealReplic is the Observatory: the application through which a learner watches a system run, tests it, builds on it and requests its physical replica. It is an independent project of Technical Arts and is developed separately from the systems it shows.

Its first system is [DT-HRES-S](https://github.com/Technical-Arts-MTY/DT-HRES-S), the digital twin of a hybrid renewable energy system. That repository keeps the twin (simulator, models, AutoCorrector, telemetry, hardware); this one keeps the platform and never duplicates it.

| Repository | Contains |
|---|---|
| `RealReplic` | Platform: user-facing application, composition engine, challenges, export and request flow |
| `DT-HRES-S` | Pilot system shown in the Observatory |

## The four stages

Each system appears in the Observatory as four stages, traversed as chapters.

| Stage | What the learner does | DT-HRES-S pilot |
|---|---|---|
| **Operation** | Watches the twin run with its telemetry | Nodes N1 to N8 of the bench |
| **Test** | Varies one parameter and sees the response | Irradiance or ambient temperature |
| **Build** | Solves a design challenge and exports the solution | Panel, turbine and battery sizes above 90 % coverage of a community |
| **Request** | Asks for the physical instrument | Bench delivered unassembled, studied in stages HRES 1 to HRES 7 |

Measurements from a requested instrument return to its system as validation data.

Details: [`docs/user-flow.md`](docs/user-flow.md).

## Status

Specification stage. The user flow and the interface are defined; no code has been written and no technology has been adopted. Technology choices belong to the development team and are recorded in [`docs/decisions.md`](docs/decisions.md).

Requirements that any choice must meet:

- usable offline; for DT-HRES-S, served from the local network of its control unit
- usable from a phone browser in vertical 9:16 format
- open license, no paid dependencies
- reads each system through that system's own repository, without duplicating it

## Repository layout

```
app/                 application source (empty until development starts)
docs/
  user-flow.md       stages, interface rules, challenges
  decisions.md       technology decisions and their reasons
CONTRIBUTING.md      branches, commits, reviews
```

## Development team

Lead: **Braulio M.** (ITESM)

| Name | Institution | Role | GitHub |
|---|---|---|---|
| Braulio M. | ITESM | Lead | |
| | | | |
| | | | |
| | | | |
| | | | |

Technical Arts: Aaron C. (ITESM)

## License

CC BY-NC-SA 4.0. See [`LICENSE`](LICENSE).
