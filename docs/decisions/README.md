# Design decisions

Use `ADR-001-short-title.md`, incrementing the number for each record. Copy the [template](template.md), link sources and the review issue, and preserve accepted history by superseding records rather than rewriting their rationale.

No technical decision has been accepted here yet. Verify these candidates against source documents before recording an accepted decision:

| Area | Approach reported by the planning summary | Status |
| --- | --- | --- |
| Operator backend | Go | Proposed; source verification pending |
| Operator frontend | htmx and Go Templates | Proposed; source verification pending |
| Communication | Wi-Fi, with UDP proposed for the glove | Proposed; interface review pending |
| Glove microcontroller | ESP32-S3 considered | Candidate; selection pending |
| Motion sensing | Three IMUs on body segments | Proposed; source verification pending |
| Finger sensing | Tendon-driven potentiometers | Proposed; source verification pending |
| Operator interface | Web dashboard with video, status, and controls | Proposed; scope verification pending |

Start with the budget and safety questions in the [requirements register](../requirements.md). A decision explains a choice; it does not replace measurable requirements or test evidence.
