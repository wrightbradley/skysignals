# Denver, NC Configuration

Complete Baofeng UV-5R configuration for Denver, North Carolina and the greater
Lake Norman area, covering Lincoln, Cabarrus, Iredell, and Gaston counties.

## Files

- [config.csv](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/denver-nc/latest/config.csv)
  — CHIRP-compatible channel list
- [metadata.json](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/denver-nc/latest/metadata.json)
  — Configuration metadata

## Channel Overview

| Range   | Service Type            | Channels | License              |
| ------- | ----------------------- | -------- | -------------------- |
| 1-9     | Amateur Radio Repeaters | 9        | Ham License Required |
| 20-23   | Amateur Radio Simplex   | 4        | Ham License Required |
| 30-40   | Fire & EMS Services     | 11       | Listen Only          |
| 41-57   | Law Enforcement         | 17       | Listen Only          |
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

### Lincoln County

- **Fire Dispatch** (154.280) – Tone: 203.5
- **Fire Tactical** (154.190/220) – Tone: 203.5
- **EMS Services** (453.300/350/400) – Tone: 156.7
- **Sheriff Operations** (453.100/150) – Tone: 100.0
- **Sheriff Tactical** (458.100) – Tone: 100.0
- **Emergency Management** (155.160) – Tone: 203.5

### Cabarrus County

- **Fire Coordination** (460.550) – Tone: 107.2
- **EMS Services** (460.125) – Tone: 167.9
- **Sheriff Operations** (460.450) – Tone: 131.8
- **Emergency Management** (155.250) – Tone: 131.8

### Iredell County

- **Fire/EMS** (453.200) – Tone: 127.3
- **Sheriff Operations** (460.350) – Tone: 146.2
- **Emergency Management** (155.220) – Tone: 146.2
- **Statesville Police** (154.860) – Tone: 146.2

### Gaston County

- **Sheriff Operations** (460.200) – Tone: 141.3
- **Emergency Management** (155.190) – Tone: 141.3

## Coverage Area

**Primary**: Denver, Lincolnton, Cherryville, Concord, Kannapolis, Harrisburg,
Statesville, Mooresville, Gastonia, Belmont

**Extended**: Lincoln, Cabarrus, Iredell, and Gaston counties; Lake Norman area

## Download

Configuration files are located in the `Denver-NC/` directory of the repository:

```bash
radios/baofeng/uv-5r/regions/us/southeast/denver-nc/latest/
├── config.csv      # CHIRP-compatible CSV file
└── metadata.json   # Configuration metadata
```

## Lake Norman Area Municipal Services

### Mooresville

- **Police Operations** (460.075) - Tone: 123.0

### Huntersville

- **Police Operations** (453.775) - Tone: 127.3

### Cornelius

- **Police Operations** (460.025) - Tone: 94.8

### Davidson

- **Police Operations** (453.850) - Tone: 107.2

## Amateur Radio Services

### Regional Repeaters

- **W4CYA** (145.110) - Cabarrus Amateur Radio Club - Tone: 107.2
- **W4OAX** (145.250) - Oak Ridge repeater - Tone: 100.0
- **W4VEC** (145.430) - Volunteer Examiner - Tone: 107.2
- **K4RDU** (146.640) - Research Triangle link - Tone: 131.8
- **W4MON** (146.820) - Monroe repeater - Tone: 123.0
- **K4LKN** (147.105) - Lake Norman ARC - Tone: 94.8

### UHF Repeaters

- **W4SGO** (442.250) - Stanly County - Tone: 107.2
- **W4LKN** (442.775) - Lake Norman UHF - Tone: 123.0
- **NC4EC** (444.075) - Emergency Coordinator - Tone: 131.8

## State Services

### NC State Highway Patrol

- **Frequency**: 155.475 MHz
- **Tone**: 156.7 Hz
- **Coverage**: Statewide law enforcement

### NC Wildlife Resources

- **Frequency**: 155.340 MHz
- **Tone**: 123.0 Hz
- **Coverage**: Conservation enforcement

## Interoperability Systems

### VTAC/UTAC Channels

- **VTAC 11** (151.1375) - VHF tactical
- **VTAC 12** (154.4525) - VHF tactical
- **UTAC 41** (453.2125) - UHF tactical
- **UTAC 42** (458.2125) - UHF tactical

### Regional Coordination

- **TACALL** (151.145) - Tactical calling frequency
- **8-Call** (154.755) - Regional interoperability calling
- **8-Tac 91/92** (775.000/800.000) - Regional tactical
- **Regional Coord** (453.550) - Multi-county coordination
- **Mutual Aid** (453.800) - Cross-jurisdictional assistance

## Aviation Services

### Lake Norman Airpark

- **Frequency**: 122.900 MHz (AM mode)
- **Usage**: Airport operations and traffic

### Emergency Aviation

- **Frequency**: 121.500 MHz (AM mode)
- **Usage**: Aviation emergency communications

## Transportation

### Norfolk Southern Railroad

- **Frequency**: 160.950 MHz
- **Usage**: Railroad operations and dispatch

## Weather Services

NOAA Weather Radio with skip flags for scanner operation:

- **162.475** - Primary Charlotte weather (covers Denver area)
- **162.400** - Secondary weather coverage
- **162.500** - Regional weather broadcasts
- **162.550** - Extended coverage area

<!-- dprint-ignore-start -->
!!! tip
    This configuration is optimized for the Lake Norman area where Denver is located, providing comprehensive multi-county coverage typical of this border region.
<!-- dprint-ignore-end -->

## Download

Configuration files are located in the `Denver-NC/` directory of the repository.
