# User flow

## Stages

1. **Operation.** The twin runs with its telemetry. One system fills one screen.
2. **Test.** The learner varies one parameter with one gesture and the twin responds.
3. **Build.** The learner solves a design challenge. Meeting the objective exports the learner's values, with the structure of the DT-HRES-S repository, to a repository of their own.
4. **Request.** A school or a student asks for the physical instrument. Its measurements return as validation data.

The metric of interest is conversion between stages, not views.

## Interface rules

- Vertical 9:16; stages are traversed with horizontal swipes.
- Hierarchy by type weight and size, not by shades of gray.
- One accent color, reserved for the value that changes.
- One panel per stage.
- Results in plain language.
- Every file upload is reversible.

## Composition primitives

Systems are composed on a grid from nine primitives bound to the test parameter: block, tank, gauge, rotor, flow, emitter, disk, line and text. Publishing a system requires a test built from bound primitives, frames or code; a video alone is not enough.

## Challenges

| Type | The learner |
|---|---|
| Parameter tuning | Adjusts values until the objective is met |
| Control-logic ordering | Orders blocks of control logic |
| Sequential calibration | Calibrates in a fixed order of steps |

Each challenge has an evaluation function. An exported solution is checked against the repository tests and the recorded telemetry before it is published with attribution.

## DT-HRES-S pilot

| Stage | Content |
|---|---|
| Operation | Nodes N1 to N8 |
| Test | Irradiance or ambient temperature |
| Build | Panel, turbine and battery sizes above 90 % coverage |
| Request | Instrument delivered unassembled with its repository linked |
