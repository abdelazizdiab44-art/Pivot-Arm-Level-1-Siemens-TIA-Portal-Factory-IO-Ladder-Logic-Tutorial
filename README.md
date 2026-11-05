
**Address and tag map:** add the real Factory I/O tags and TIA Portal PLC addresses here once verified. No I/O addresses are inferred in this README.

## Industrial relevance

- **Material handling:** divert or position objects between stations.
- **Assembly cells:** move a fixture or tool into a working position.
- **Packaging lines:** guide or transfer products through a process step.
- **Machine tending:** coordinate a pivoting mechanism with sensors and other equipment.

These are examples of where similar mechanisms may be used; they do not imply that this tutorial implements each application.

## Repository contents

| Path | Purpose |
|---|---|
| `Pivot Arm/` | Supporting project materials (inspect folder contents for details) |
| `Pivot Arm.factoryio` | Factory I/O scene/project file |
| `README.md` | Project guide and documentation |

## Getting started

1. Open `Pivot Arm.factoryio` in Factory I/O and inspect the scene and its configured I/O driver.
2. Open the corresponding Siemens TIA Portal project from `Pivot Arm/`, if included.
3. Confirm that PLC tags and Factory I/O signals use matching addresses.
4. Run the simulation and observe input, logic, and output behavior.

> TIA Portal project availability and exact run steps depend on the files included in `Pivot Arm/`.

## Learning outcomes

- Read a simulated automation scene as a set of devices and signals.
- Trace input-to-logic-to-output behavior in a PLC program.
- Relate ladder logic to motion in a virtual industrial cell.
- Organize and document an I/O map and basic sequence.

## Project profile

**Domain:** Industrial automation · **Controller environment:** Siemens TIA Portal · **Simulation:** Factory I/O · **Level:** 1

---

<sub>Professional profile palette: charcoal, muted teal, and warm coral.</sub>
