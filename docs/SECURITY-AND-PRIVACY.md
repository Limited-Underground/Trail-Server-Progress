# Security and privacy principles

Trail Server is being designed for local, owner-controlled operation. The
current implementation remains private while the project develops.

Publicly stated principles are:

- optional server services must not weaken the independent OpenTrail field path;
- server and gateway interfaces must be versioned, authenticated, and limited to
  their stated purpose;
- durable receipt is acknowledged only after durable server storage;
- repeated requests and uncertain network or radio outcomes must be handled
  explicitly;
- retention, deletion, and operator consent must be defined for accepted data
  flows;
- credentials, private addresses, device identifiers, and raw private payloads
  must not appear in public project records; and
- production security, availability, recovery, and delivery claims require
  evidence beyond development-host tests.

## Repository boundary

This public repository is a deliberately sanitized progress record. It does not
contain the current source, firmware, tests, deployment material, detailed
contracts, internal evidence, credentials, or private infrastructure data.

Historical source versions that were previously released remain governed by the
licenses distributed with those versions. Their publication does not make later
private work public.
