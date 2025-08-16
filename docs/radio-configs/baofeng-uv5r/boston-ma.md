# Boston, MA Configuration

Complete 50-channel Baofeng UV-5R configuration for Boston, Massachusetts and
the Metro Boston Homeland Security Region (MBHSR).

## Files

- [config.csv](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/northeast/boston-ma/latest/config.csv)
  — CHIRP-compatible channel list
- [config.img](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/northeast/boston-ma/latest/config.img)
  — Radio memory image
- [metadata.json](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/northeast/boston-ma/latest/metadata.json)
  — Configuration metadata

## Channel Overview

| Range | Service Type       | Channels | License              |
| ----- | ------------------ | -------- | -------------------- |
| 1-9   | Amateur Radio      | 9        | Ham License Required |
| 11-17 | Fire Services      | 7        | Listen Only          |
| 21-24 | EMS Services       | 4        | Listen Only          |
| 31-47 | Police & Emergency | 17       | Listen Only          |
| 51-54 | Weather Services   | 4        | Listen Only (Skip)   |
| 61-73 | MBHSR Interop      | 13       | Listen Only          |
| 81-83 | Additional MBHSR   | 3        | Listen Only          |
| 91-92 | Personal Radio     | 2        | FRS/GMRS             |

---

<!-- dprint-ignore-start -->
!!! warning
    Most frequencies are for monitoring only. Transmitting on these channels without proper authorization is illegal and subject to significant penalties. Amateur radio channels require a valid FCC license to transmit.
<!-- dprint-ignore-end -->

## Key Services

### Emergency Services

- **Boston Fire Department** – Dispatch and tactical channels
- **Boston EMS** – Emergency medical dispatch and operations
- **BAPERN** – Boston Area Police Emergency Radio Network
- **MBTA Police** – Transit authority police and operations

### Interoperability

- **UCALL** (453.2125) – MBHSR primary calling channel
- **UTAC 1-3** – Unified tactical channels
- **Metro Fire** – Regional fire coordination
- **MBHSR Coordination** – Regional incident management

### Amateur Radio

- **W1BOS** (145.23) – Boston repeater
- **W1KBN** (145.31) – Northeastern University repeater
- **DMR** (449.175) – Digital mode repeater
- **Simplex** – 2M and 440 calling frequencies

## Coverage Area

**Primary**: Boston, Cambridge, Somerville, Brookline

**Extended**: Chelsea, Everett, Quincy, Revere, Winthrop

## Download

Configuration files are located in the `Boston-MA/` directory of the repository:

```bash
radios/baofeng/uv-5r/regions/us/northeast/boston-ma/latest/
├── config.csv      # CHIRP-compatible CSV file
├── config.img      # Radio memory image
└── metadata.json   # Configuration metadata
```

!!! warning Emergency service frequencies are **listen only**. Transmission
without authorization is illegal and subject to significant penalties.
