# Gateway hardware status

## Current candidate

The current gateway candidate is the **ELECROW ThinkNode G3**. Physical inspection
identified:

| Item | Public status |
| --- | --- |
| Controller | ESP32-S3 identified on the received device |
| Radio module | ELECROW LR1262 identified on the received device |
| Network role | Placeable LoRa gateway with local-network backhaul |
| Stock recovery | Preservation and restoration exercised during bounded trials |
| Diagnostic firmware | Initial recoverable probes completed |
| Live LoRa operation | Not established |
| Supported Trail gateway firmware | In development |

The device is a candidate under investigation, not an endorsed or
production-ready Trail Server gateway. The enclosure, setup interface, network
options, and selectable regional settings were inspected, but configuration
options alone do not prove radio compatibility or legal operating parameters.

## Acceptance still required

- complete and document the supported hardware binding;
- establish repeatable radio startup;
- demonstrate live receive and transmit behavior with compatible test devices;
- verify restart, reconnect, bounded queue, and recovery behavior on hardware;
- confirm the intended regional radio configuration; and
- complete field and operational testing before any readiness claim.

Private identifiers, board-level recovery instructions, pin mappings, captures,
and detailed diagnostic evidence are intentionally excluded.
