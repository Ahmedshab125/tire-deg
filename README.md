# tire-deg
F1 Tire Degradation Analysis

Analyzing real Formula 1 telemetry data to model tire degradation across race stints, using the FastF1 Python library.

What this project does

Pulls official F1 timing data for a given race and:

Visualizes lap times across a stint, broken down by tire compound
Calculates tire degradation rate (seconds lost per lap) by fitting a linear trend to each stint
Compares degradation across drivers/compounds to see how tire choice affects pace over a stint
Why

Tire strategy is one of the biggest performance levers in F1 — race engineers build exactly this kind of model to decide when to pit and which compound to run. This project is a first step toward understanding that from a data/engineering angle, motivated by my interest in breaking into motorsport engineering (I'm part of my university's Formula Student Autonomous team).
