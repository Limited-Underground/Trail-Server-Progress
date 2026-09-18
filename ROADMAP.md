# Public roadmap

The roadmap is ordered by technical dependency, not by a promised release date.
It describes capability goals without exposing private implementation plans.

## Foundations completed in bounded form

- optional server architecture and project boundaries;
- reproducible Linux development-host baseline;
- service health and development-console foundation;
- database persistence, role separation, and isolated recovery proof;
- versioned local-radio interface in host simulation;
- authenticated Wi-Fi gateway behavior in deterministic host tests; and
- initial ThinkNode G3 identification and recoverable diagnostic trials.

## Work in progress

- repeatable local-network addressing, reboot behavior, and independent-client
  acceptance;
- administrator transport security, account lifecycle, recovery, and
  accessibility;
- remaining domain records and queues;
- server-side authenticated gateway ingestion and credential lifecycle;
- supported ThinkNode G3 firmware binding;
- live LoRa receive, transmit, restart, and recovery evidence; and
- operational backup and recovery procedures beyond the bounded proof.

## Planned after the foundations

- map and live-data experiences backed by accepted server records;
- bounded large-file delivery over local network services;
- broader multi-client and long-running reliability exercises;
- deployment, monitoring, upgrade, and recovery operations; and
- field trials followed by a separately reviewed readiness decision.

Plans may change as hardware and field evidence develops. Completed host tests do
not automatically advance a capability to hardware, field, deployment, or
production acceptance.
