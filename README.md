# Meridian Collection Custody

This repository publishes the verified close-of-day location register for the Meridian collection.

<!-- CUSTODY-REGISTER:BEGIN -->
## Close-of-day custody register — 9 March 2150
Events: 15 physical | 10 structurally valid | 5 structurally invalid
Replay: 8 accepted | 2 rejected valid
Rejections: 1 source mismatch | 1 broken seal
Locations: 1 gallery | 1 lab | 1 vault A | 1 vault B | 2 quarantine

| Artifact | Title | Final zone | Last accepted event |
| --- | --- | --- | --- |
| AR-02 | Ceremonial Mask | GALLERY | EV-102 |
| AR-01 | Brass Astrolabe | LAB | EV-101 |
| AR-04 | Harbor Tablet | VAULT-A | EV-106 |
| AR-06 | Celestial Globe | VAULT-B | EV-110 |
| AR-03 | Indigo Textile | VAULT-Q | EV-105 |
| AR-05 | Surveyor Compass | VAULT-Q | EV-108 |

### Rejected valid movements
| Event | Artifact | From | To | Seal | Reason |
| --- | --- | --- | --- | --- | --- |
| EV-103 | AR-01 | VAULT-A | GALLERY | INTACT | SOURCE_MISMATCH |
| EV-104 | AR-03 | VAULT-A | VAULT-Q | BROKEN | BROKEN_SEAL |
<!-- CUSTODY-REGISTER:END -->

## Handling policy

Movement evidence is retained verbatim under `evidence/`.
