# Mechanical Engineering Project Template

A reusable starting point for projects in the Mechanical Engineering Department. Use this repository as a template to organize a project's mechanical design, electronics, software, machine skills, simulation, documentation, experiments, and publications.

## Getting started

1. Select **Use this template** on GitHub to create a repository for your project.
2. Rename the project in this README and update the project summary, team, and objectives.
3. Review the folder READMEs and replace the examples with project-specific information.
4. Create GitHub Issues for tasks and record important design decisions and test results.
5. Check the license placeholder and select appropriate terms before sharing or reusing project work.

## Project overview

- Project name: ***Pick-and-Place Mechanism***
- Team: ***Cheese Stick***  (1 member)
- Status: ***Planning***
- Member: *Kawin Lorchokwattana  6730021021*
- Last updated: *19-10-2026*
- Problem/Purpose:  
>  In a factory, products on the production line need to be transported between conveyor belts or working stations. This mechanism will facilitate such cumbersome processes by the aid of machine and robotics instead of relying solely on manpower. It picks, lifts, places, and releases an object from one position to another which are at most 180 degrees apart, typically on the same elevation. The rotary motion of a uniform electric motor is converted to the oscillatory motion of the vacuum end-effector attached to the linkage. This can be achieved by implementating three types of linkages: a crank-rocker four-bar linkage, a six-bar linkage, and a parallel motion linkage.

## Repository structure

| Path | Purpose |
|---|---|
| `hardware/mechanical/` | CAD models, drawings, and fabrication files |
| `hardware/electronics/` | Schematics, PCB files, and wiring diagrams |
| `hardware/bom.csv` | Bill of materials with quantities, units, and sourcing details |
| `software/firmware/` | Microcontroller code and board setup |
| `software/application/` | PC or Raspberry Pi application code |
| `machine-skills/` | Machine commands, procedures, and skill instructions |
| `simulation/` | Models, scripts, assumptions, and simulation results |
| `docs/` | Assembly, setup, operation, and maintenance instructions |
| `media/` | Images, GIFs, and links to demonstration videos |
| `experiments/` | Procedures, raw data, and results |
| `publications/` | Project-related journal and conference papers |

## Collaboration and file practices

Use descriptive filenames and commit messages. Record units, revisions, software versions, and assumptions. Keep editable source files where practical. Avoid committing credentials, private data, temporary files, or duplicate exports. Consider Git LFS for large CAD, simulation, and video files.

## Safety and validation

Document hazards, safeguards, and operating limits before testing hardware. Validate important calculations and simulation results against measurements where practical.
