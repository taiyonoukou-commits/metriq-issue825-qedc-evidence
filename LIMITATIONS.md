# Limitations

- The comparison is a single four-qubit problem under four fixed simulated
  readout conditions, with one reported result per method and condition.
- These results do not measure variance across independent repeats.
- The study is independent: QED-C has not certified it and Metriq has not
  accepted the proposed benchmark or its execution boundary.
- No physical QPU executed these four public comparison conditions.
- RAW uses fewer shots than the mitigated methods, so the reported
  processing times are not an equal-budget speed ranking.
- The external Kenji implementation and original measurements are
  unavailable in this public package; exact public replay is unavailable.
- Mitiq REM used externally derived reference or calibration data; its
  software version was 1.1.0.
