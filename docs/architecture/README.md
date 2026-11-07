# System architecture

The [main README](../../README.md#system-overview) contains the initial conceptual diagram. Keep editable diagram sources here as interfaces are agreed.

For each interface, document producers/consumers, units and coordinate frames, command/feedback schema, update rate, ordering, timeout handling, command authority, and version compatibility. Resolve communication-loss and gripping requirements before defining motion behaviour.

The summary proposes Wi-Fi and considers UDP for glove communication. Transport, topology, and safety semantics remain unverified proposals, not implemented interfaces.
