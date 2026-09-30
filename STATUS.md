# Current status

**Checkpoint: September 29, 2026**

Trail Server remains an optional project under development. Host checks establish
bounded behavior; deployment, field and production acceptance remain separate.

| Area | Evidence so far | Still required |
| --- | --- | --- |
| Administration | Named accounts, roles and managed group/device records passed isolated database and interface checks. | Supported deployment and client acceptance. |
| Record lifecycle | Explicit deletion, bounded audit retention and export passed host checks. | Operational storage, access and recovery acceptance. |
| Offline maps | Bounded map-package delivery and a local browser viewer passed host checks. | Trusted client access, deployment and operational recovery. |
| Server and gateway integration | Authenticated sessions, bounded queues, restart and failure paths passed production-code host tests. | Approved protected storage and configuration, physical network and radio validation. |
| Gateway target | Network composition builds for the development target; earlier bounded hardware diagnostics remain limited to their tested components. | Complete hardware binding, interoperability and endurance. |
| Backup and upgrades | Disposable recovery preserved records, stable IDs, schema and permissions. Failed upgrades rolled back; successful upgrades preserved data. | Backup policy, protected-state recovery and supported Linux operational tests. |

Gateway features remain disabled without approved protected storage and
configuration. No supported production release, field readiness, guaranteed
delivery or safety assurance is claimed. Server loss must not disable the
base OpenTrail field path.
