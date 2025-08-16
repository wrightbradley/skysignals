# Charlotte, NC Configuration

Complete Baofeng UV-5R configuration for Charlotte, North Carolina and
surrounding Mecklenburg County area.

## Files

- [config.csv](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/charlotte-nc/latest/config.csv)
  — CHIRP-compatible channel list
- [metadata.json](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/charlotte-nc/latest/metadata.json)
  — Configuration metadata

## Channel Overview

| Range   | Service Type            | Channels | License              |
| ------- | ----------------------- | -------- | -------------------- |
| 1-9     | Amateur Radio Repeaters | 9        | Ham License Required |
| 20-23   | Amateur Radio Simplex   | 4        | Ham License Required |
| 30-52   | Emergency Services      | 23       | Listen Only          |
| 53-57   | Aviation                | 5        | Listen Only          |
| 58-68   | Interoperability        | 11       | Listen Only          |
| 70-73   | Weather Services        | 4        | Listen Only (Skip)   |
| 80-82   | Public Service          | 3        | Listen Only          |
| 90-91   | Personal Radio          | 2        | FRS/GMRS             |
| 100-104 | Legacy Amateur          | 5        | Ham License Required |

---

<!-- dprint-ignore-start -->
!!! warning
    Most frequencies are for monitoring only. Transmitting on these channels without proper authorization is illegal and subject to significant penalties. Amateur radio channels require a valid FCC license to transmit.
<!-- dprint-ignore-end -->

## Key Services

### Emergency Services

- **Charlotte Fire Department (CFD)** – Dispatch and tactical channels (30-36)
- **MEDIC** – Emergency medical services dispatch and tactical (37-40)
- **Charlotte-Mecklenburg Police (CMPD)** – Law enforcement channels (41-44)
- **Mecklenburg County Sheriff (MCSO)** – County law enforcement (45-47)
- **CATS** – Charlotte Area Transit System operations (48-49)
- **NC State Highway Patrol** – State law enforcement (50)
- **Emergency Management** – State and county coordination (51-52)

### Amateur Radio

- **W4BFB** – Multiple Charlotte area repeaters
- **W4SCC** – South Charlotte Amateur Radio Club repeater
- **W4QMQ** – Queens City Amateur Radio Club repeater
- **N4VU** – UNC Charlotte repeater
- **K4DZR** – Mecklenburg Amateur Radio Club repeater

### Aviation

- **Charlotte Douglas International Airport** – Complete aviation frequencies:
  - Tower (118.7)
  - Ground (121.9)
  - Approach (119.7)
  - ATIS (127.25)
  - UNICOM (122.95)

### Interoperability

- **TACALL** (151.145) – Tactical calling frequency
- **VTAC 11/12** – VHF tactical channels
- **UTAC 41/42** – UHF tactical channels
- **8-Call/8-Tac** – Regional interoperability system
- **Regional Coordination** – Multi-agency coordination

## Coverage Area

**Primary**: Charlotte, Mecklenburg County

**Extended**: Cabarrus, Gaston, Union, York (SC), Lancaster (SC) counties

## Download

Configuration files are located in the `Charlotte-NC/` directory of the
repository:

```bash
radios/baofeng/uv-5r/regions/us/southeast/charlotte-nc/latest/
├── config.csv      # CHIRP-compatible CSV file
└── metadata.json   # Configuration metadata
```

## Frequency Details

### Fire Services (30-36)

- **154.160** - CFD Dispatch
- **154.250/280/340** - CFD Tactical channels
- **453.550** - CFD Command
- **453.175/458.175** - Mecklenburg County Fire

### EMS Services (37-40)

- **453.825** - MEDIC Dispatch (Tone: 167.9)
- **453.875/925** - MEDIC Tactical 1 & 2
- **458.825** - MEDIC Tactical 3

### Police Services (41-47)

- **460.425/450/475/500** - CMPD channels (DCS: 054)
- **453.750/800** - Mecklenburg SO (Tone: 203.5)
- **458.750** - MCSO Tactical

### Interoperability Channels

- **151.145** - TACALL (Tactical Calling)
- **151.1375** - VTAC 11
- **154.4525** - VTAC 12
- **453.2125** - UTAC 41
- **458.2125** - UTAC 42
- **154.755** - 8-Call
- **775.000/800.000** - 8-Tac 91/92

## Weather Services

NOAA Weather Radio frequencies with skip flags for scanner operation:

- **162.400** - Primary Charlotte weather
- **162.475** - Secondary coverage
- **162.500** - Regional weather
- **162.550** - Extended coverage

<!-- dprint-ignore-start -->
!!! warning
    Emergency service frequencies are **listen only**. Transmission without authorization is illegal and subject to significant penalties.
<!-- dprint-ignore-end -->

## Download

Configuration files are located in the `Charlotte-NC/` directory of the
repository.
