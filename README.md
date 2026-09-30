# Limited Underground Trail Server

Trail Server is an optional companion project for the OpenTrail ecosystem. It
is being developed privately. This public record reports milestones without
publishing source code, firmware, private infrastructure, device identifiers,
credentials, or operational evidence.

The base OpenTrail field path remains offline-first. Trail Server and its
gateway are optional and their absence or failure must not prevent supported
local field operation.

## Current progress

- Named administration, managed group/device records and bounded retention,
  export and deletion have passed isolated database and interface checks.
- Offline map-package delivery and a local browser viewer have passed host
  checks. Deployment, trusted client access and operational recovery remain open.
- Authenticated gateway sessions, bounded queues and interruption recovery have
  passed production-code host tests. The gateway network composition also builds
  for its development target; this is not physical network or radio acceptance.
- Disposable database backup/restore checks preserve records, schema and
  permissions, and a backup cleanup failure path has been corrected and tested.
  Backup policy and operational recovery acceptance are still pending.

The gateway features remain disabled until approved protected storage and
configuration are available. Target network behavior, radio interoperability,
endurance and deployment require separate validation. No supported production
release, guaranteed delivery, safety or field-readiness claim is made.

## Source availability

Trail Server source code is private and is not distributed through this public
progress repository. Historical source versions that were previously published
retain the licenses attached to those versions.
