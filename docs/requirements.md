# Requirements tracking

This register starts empty because the original reports are unavailable for this setup. The planning summary supplies context, not an approved requirements baseline.

For each source-verified requirement, add a stable ID, exact measurable criterion, document section/version, owner, status, and verification evidence. Use `Proposed`, `Confirmed`, `Implemented`, and `Verified` to distinguish agreement from implementation and proof.

| ID | Measurable requirement | Source / section / version | Owner | Status | Verification method / evidence |
| --- | --- | --- | --- | --- | --- |
| — | No source-verified requirements entered yet | — | — | — | — |

## Questions to verify with the team

These discrepancies are reported in the supplied summary. Check the original documents before creating binding requirements or changing submitted reports.

| Question | Reported context | Resolution needed |
| --- | --- | --- |
| Budget baseline | Proposal reportedly gives a $500 maximum and a $500–$700 estimate | Confirm currency, approved cap, contingency, and scope; update the BOM baseline |
| Finger feedback scope | Glove scope reportedly describes five fingers while architecture lists two feedback servos for thumb and index finger | Distinguish sensing from force feedback; agree supported digits and acceptance criteria |
| Communication-loss behaviour | Proposal reportedly mentions a safe position after 500 ms without commands and retaining an object for five minutes | Define timeout detection, safe motion versus stopping, grip retention, power-loss handling, recovery, and a controlled test procedure |

Track resolutions in issues, record accepted [decisions](decisions/README.md), and link confirmed sources here. Do not implement a speculative motion or gripping policy from this summary.
