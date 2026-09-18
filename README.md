# Limited Underground Trail Server

Trail Server is an optional companion project for the OpenTrail ecosystem. It
is being developed privately. This public record reports milestones without
publishing source code, firmware, private infrastructure, device identifiers,
credentials, or operational evidence.

The base OpenTrail field path remains offline-first. Trail Server and its
gateway are optional and their absence or failure must not prevent supported
local field operation.

## Current progress

- Server architecture and persistence foundations are under development.
- An authenticated Wi-Fi gateway contract has passed bounded host tests.
- ELECROW ThinkNode G3 hardware has been identified as ESP32-S3 with an LR1262
  radio module; firmware and RF behavior remain under development.
- Gateway queueing, durable acknowledgements, reconnect behavior, and uncertain
  transmit outcomes have bounded host-tested and diagnostic increments.

These statements describe engineering progress. They do not claim production,
deployment, field, safety, availability, or delivery readiness.

## Source availability

Trail Server source code is private and is not distributed through this public
progress repository. Historical source versions that were previously published
retain the licenses attached to those versions.
