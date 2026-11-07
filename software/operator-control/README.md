# Operator control software

Entry point for the operator dashboard and service. The planning summary proposes Go, htmx, and Go Templates; confirm these choices against the design document before establishing a module or dependencies.

Suggested Go layout: cmd/ for executable entry points, internal/ for private application packages, and web/ for templates and static assets. Add setup, build, run, configuration, and test instructions with the first implementation.
