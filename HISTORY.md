# Project history

This timeline records meaningful Trail Server progress at the level appropriate
for public release. Evidence labels are explained in [Status](STATUS.md).

## September 2026

### September 20 — Gateway cryptographic component hardware pass

The gateway's authenticated-session cryptographic component completed its
bounded hardware checks on the target gateway. The trial also verified return
to the preserved stock application. Credential provisioning, network/API
integration, complete board binding, RF behavior and field operation remain
open.

**Evidence:** hardware-tested component with verified stock restoration; no
network, RF or deployment claim.

### September 18 — Gateway authenticated-session target build

The bounded gateway session behavior advanced from host-only checks to an
ESP32-S3 build of its volatile directional-key and authenticated-frame
boundary. Its deterministic device checks are present in the image but have
not yet been executed on hardware. Wi-Fi/TLS integration, server API wiring,
credential provisioning, board-specific radio bindings and RF evidence remain
open.

**Evidence:** target-built firmware component; no device-runtime or RF claim.

## August 2026

### August 27 — Project foundation

Trail Server was established as an optional companion to the offline-first
OpenTrail field path. The first provisional server architecture was accepted as
a basis for bounded engineering work.

**Evidence:** architecture and project foundation.

### August 28 — Reproducible Linux host baseline

The selected Linux host profile completed initial provisioning and reboot
checks, followed by reproduction on a second clean virtual machine.

**Evidence:** host-tested baseline. Final physical-host and stable-LAN acceptance
remained open.

### August 29 — Local radio boundary and service foundation

A versioned local interface between the server and its dedicated radio process
was exercised in host simulation. An initial web-service health scaffold and a
disabled-by-default radio lifecycle also passed bounded checks.

**Evidence:** host simulation and service-host testing; no physical radio test.

## September 2026

### September 1 — Linux serial-path preflight

The bounded serial transport and pseudo-terminal lifecycle were reproduced on
the selected Linux environment.

**Evidence:** target-host software reproduction; no physical USB or RF test.

### September 7 — Development dashboard

A local development console displayed service-backed health information and a
manual refresh flow.

**Evidence:** rendered development interface; not an operational dashboard.

### September 8 — Persistence foundation

Database-backed persistence, migrations, isolation checks, and separation of
database roles were exercised on the selected host environment.

**Evidence:** host-tested persistence foundation; domain completeness and
production operation remain open.

### September 8 — Authenticated Wi-Fi gateway interface

The planned gateway-to-server interface was exercised for identity and
authentication handling, repeated requests, bounded queues, durable receipt,
reconnection, and degraded outcomes.

**Evidence:** deterministic host tests; no device or RF acceptance.

### September 9 — Operator records and recovery proof

A bounded append-only operator-record slice and an isolated backup/restore flow
were exercised on the selected host.

**Evidence:** host-tested feature and recovery proof; no claim of scheduled,
off-site, or disaster recovery.

### September 10–14 — Local-network administration

Versioned administrator authentication, a corrected browser flow, and a narrowly
restricted second-client local-network path were exercised.

**Evidence:** host-tested and owner-observed client checks. Trusted transport,
individual accounts, recovery, accessibility, and final network persistence
remain open.

### September 16 — ThinkNode G3 characterization

The ELECROW ThinkNode G3 candidate was physically identified with an ESP32-S3
controller and LR1262 radio module. Stock firmware preservation/restoration and
bounded diagnostic firmware checks were completed. The board-independent
gateway lifecycle core also passed bounded host tests.

**Evidence:** physical identification, recoverable diagnostic trials, and host
tests; no operational firmware or RF acceptance.

### September 17 — Radio bring-up investigation

Bounded interface, clock, and startup probes narrowed the radio startup problem
while preserving a recovery path to the stock device state.

**Evidence:** hardware diagnostic investigation; live LoRa receive/transmit was
not established.

### September 18 — Private source and public progress separation

Current implementation authority was established in a private repository, and
this separate progress-only public record was created with fresh history.
Routine dependency and security maintenance was also completed privately.

**Evidence:** repository boundary and maintenance review.

### September 18 — Authenticated gateway session gate

The accepted gateway interface gained a complete bounded wire-frame definition
and a host-tested fixed-buffer firmware session gate. Exact frame bytes are
shared by the server-contract and firmware tests. Invalid
authentication, identity, replay, and canonical-body inputs are rejected before
queue state changes.

**Evidence:** cross-implementation host tests; target cryptography, networking,
device firmware, and RF remain open.
