# Benchmark definition

This is an independent drift stress test using a public QED-C Observable Estimation /
HamLib problem. It is **not** an official QED-C benchmark result, a Metriq accepted
benchmark, or evidence of a physical QPU run.

The fixed case is four-qubit TFIM energy estimation with five Trotter steps and seven
Pauli terms. Four readout conditions were evaluated: control, gradual drift, step
drift, and periodic drift. Each method was scored after its output was fixed.
The published score is relative error against exact truth, in percent.

RAW used target measurements only. Mitiq REM and Kenji each used the same total
shot budget including reference or calibration measurements. Their measurement
inputs and the proprietary Kenji implementation are not distributed publicly.
See RESOURCE_SUMMARY.json for aggregate shot accounting. No variability,
confidence interval, or generalization claim is inferred from four fixed conditions.
