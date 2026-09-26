# Public review and audit boundary

The public package provides four rounded accuracy comparisons, total shot counts,
aggregate processing information, software identity commitments, original
measurement-bundle commitments, truth commitments, and method-output commitments.

The measurement sequences, exact acquisition times, per-shot order, seeds, detailed
reference roles, drift plan, source-bundle adapter, and estimator input contract are
withheld. Exact results remain subject to controlled independent verification.

A SHA-256 commitment permits comparison against the retained original artifact if
an authorized reviewer is given that artifact. A hash alone cannot reconstruct
the measurements, reproduce Kenji's proprietary output, or independently establish
the reported scores. Public replay of these exact measurements is therefore unavailable.

The scoring truth was kept separate from the estimator input and computed after
method outputs were fixed, according to the original run record. This is a
provenance claim, not a third-party validation certificate.

An earlier public starter set included more detailed measurement material.
This summary replaces it as the public review version. Replacement of the
repository's visible history cannot revoke third-party copies or previously
known object links.
