# Current status

**Checkpoint:** September 18, 2026

Trail Server is an active engineering project. Several foundations have passed
bounded host checks, and the first gateway hardware has entered diagnostic
bring-up. The system has not reached deployment or field acceptance.

## Evidence labels

| Label | Meaning |
| --- | --- |
| Planned | Direction is recorded, but implementation evidence is not accepted. |
| Host-tested | Behavior was exercised in software on a development or target host. |
| Hardware diagnostic | A physical device was inspected or used for a bounded engineering probe. |
| Field-tested | Behavior was exercised in its intended field setting. |
| Production-ready | Deployment, operations, recovery, and supported behavior are accepted together. |

## Capability snapshot

| Area | Current level | Public status |
| --- | --- | --- |
| System architecture | Host-tested foundations | Optional server boundaries and core host profile are established. |
| Linux host setup | Host-tested | Clean-host reproduction passed; final physical-host and network acceptance remain open. |
| Service foundation | Host-tested | Health and development-console paths exist in bounded form. |
| Persistence | Host-tested | Database, migrations, role separation, and a bounded recovery proof exist. |
| Local administration | Host-tested | Authentication and narrow local-client access were exercised; security and usability work remains. |
| Local server radio | Host simulation | The versioned process boundary was tested without physical RF acceptance. |
| Wi-Fi gateway interface | Host-tested | Authentication, queues, durable receipt, reconnect, and uncertain outcomes were exercised in software. |
| ThinkNode G3 gateway | Hardware diagnostic | Hardware was identified and diagnostic firmware probes were recoverable. Live RF is not established. |
| Large-file delivery | Planned | File transfer is intended to use local network services rather than LoRa. |
| Field deployment | Planned | No field or production acceptance has been claimed. |

## Current engineering focus

- complete the supported ThinkNode G3 hardware binding and live RF evidence;
- connect the authenticated gateway interface to the server service;
- finish repeatable local-network startup and independent-client acceptance;
- strengthen local administration security, recovery, and accessibility;
- extend persistence, backup, and recovery beyond the bounded foundation; and
- keep all optional services independent from OpenTrail's offline field path.

## Claims deliberately not made

Trail Server is not described here as deployed, production-ready, field-tested,
safety-certified, highly available, or capable of guaranteed message delivery.
Gateway radio emission would not by itself prove end-device delivery.
