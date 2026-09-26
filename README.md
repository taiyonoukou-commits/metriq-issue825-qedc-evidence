# QED-C-derived observable-estimation comparison for Metriq Issue #825

Status: **independent public review material; not an official QED-C or Metriq benchmark result**.

This R2 public summary supersedes the earlier starter review set. It retains the four
reported comparison outcomes and cryptographic commitments. The shot-level measurements,
detailed acquisition protocol, conversion adapter, and replay code are withheld from this
public repository. See [review boundary](REVIEW_BOUNDARY.md) for what the hashes can prove.

| Condition | RAW error | Mitiq REM error | Kenji error |
| --- | ---: | ---: | ---: |
| CONTROL_NONE | 0.279948% | 0.234375% | 0.279948% |
| GRADUAL_MEDIUM | 5.914714% | 0.406901% | 0.335950% |
| STEP_MEDIUM | 4.707031% | 0.065104% | 0.104195% |
| PERIODIC_MEDIUM | 13.601888% | 0.776367% | 0.448924% |

Errors are relative to exact truth; values are rounded to six decimal places. The underlying
four results have not been rerun or changed. Kenji is an external estimator with a fixed
implementation commitment; its proprietary source is not published.

RAW used 28,672 target shots per condition. Mitiq REM and Kenji each used 143,360
total shots per condition, including 114,688 reference or calibration shots.
The methods therefore have different native shot budgets. The four Kenji processing
times have median approximately **0.53 s**, with maximum reported RAM approximately
**70 MB**. These numbers describe local processing, not QPU runtime.

- [Benchmark definition](BENCHMARK_DEFINITION.md)
- [Results and precision](RESULTS.json)
- [Resource accounting](RESOURCE_SUMMARY.json)
- [Input, output, and implementation commitments](COMMITMENTS.json)
- [Review boundary](REVIEW_BOUNDARY.md)
- [Limitations](LIMITATIONS.md)
- [File manifest](STARTER_SET_MANIFEST.json)

Discussion: https://github.com/unitaryfoundation/metriq-gym/issues/825
