# Asheville, NC Configuration

Complete Baofeng UV-5R configuration for Asheville, North Carolina and the
Western North Carolina Blue Ridge Mountain region.

## Files

- [config.csv](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/asheville-nc/latest/config.csv)
  — CHIRP-compatible channel list
- [metadata.json](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/asheville-nc/latest/metadata.json)
  — Configuration metadata

## Channel Overview

| Range   | Service Type               | Channels | License              |
| ------- | -------------------------- | -------- | -------------------- |
| 1-9     | Amateur Radio Repeaters    | 9        | Ham License Required |
| 20-23   | Amateur Radio Simplex      | 4        | Ham License Required |
| 30-40   | Fire & EMS Services        | 11       | Listen Only          |
| 41-57   | Law Enforcement & Aviation | 17       | Listen Only          |
| 58-68   | Interoperability           | 11       | Listen Only          |
| 70-73   | Weather Services           | 4        | Listen Only (Skip)   |
| 80-82   | Public Service             | 3        | Listen Only          |
| 90-91   | Personal Radio             | 2        | FRS/GMRS             |
| 100-104 | Legacy Amateur             | 5        | Ham License Required |

---

<!-- dprint-ignore-start -->
!!! warning "Listen Only Configuration" Most frequencies are for monitoring
only. Transmitting on these channels without proper authorization is illegal and
subject to significant penalties. Amateur radio channels require a valid FCC
license to transmit.
<!-- dprint-ignore-end -->

## Key Services

### Emergency Services

- **Asheville Fire Dept** (154.070/130/175) - Tone: 179.9
- **Buncombe County Fire** (453.125/175) - Tone: 203.5
- **Mission Hospital EMS** (453.500) - Tone: 167.9
- **Buncombe County EMS** (453.550/600) - Tone: 162.2
- **Asheville Police** (460.125/175/225) - DCS: 174
- **Buncombe County SO** (453.900/950) - Tone: 192.8

### Federal Land Management

- **Pisgah National Forest**: National Forest Service (170.775, Tone: 156.7), US
  Forest Service Fire (168.625, Tone: 156.7)
- **Blue Ridge Parkway**: National Park Service (168.050, Tone: 167.9)

### State Agencies

- **NC State Highway Patrol** (155.475) - Tone: 156.7
- **NC Wildlife Resources** (155.340) - Tone: 123.0

## Coverage Area

**Primary**: Asheville, Black Mountain, Weaverville

**Extended**: Buncombe County, Pisgah National Forest, Blue Ridge Parkway,
Western North Carolina mountain region

## Download

Configuration files are located in the `Asheville-NC/` directory of the
repository:

```bash
radios/baofeng/uv-5r/regions/us/southeast/asheville-nc/latest/
├── config.csv      # CHIRP-compatible CSV file
└── metadata.json   # Configuration metadata
```

## Mountain Amateur Radio

### High-Altitude Repeaters

**Strategic mountain peak locations for maximum coverage**:

**VHF Repeaters**:

- **W4AMC** (145.190) - Asheville Medical Corps - Tone: 131.8
- **W4SKY** (145.370) - Skyland (Blue Ridge) - Tone: 123.0
- **K4RDU** (146.640) - Blue Ridge Link - Tone: 131.8
- **W4MOX** (146.760) - Mount Mitchell (highest peak) - Tone: 107.2
- **W4BRB** (147.000) - Blue Ridge Parkway - Tone: 94.8
- **NC4AB** (147.360) - Appalachian Backbone - Tone: 167.9

**UHF Repeaters**:

- **K4WNC** (442.125) - Western NC Link - Tone: 123.0
- **W4BRC** (442.800) - Buncombe Radio Club - Tone: 107.2
- **NC4DMR** (444.000) - WNC DMR Network - Tone: 100.0

### Emergency Networks

- **APRS** (144.390) - Automatic Packet Reporting System
- **SKYWARN** (147.045) - Weather spotter network - Tone: 94.8
- **Emergency Simplex** (146.550) - Mountain emergency coordination

## Aviation Services

### Asheville Regional Airport (AVL)

**Complete air traffic control frequencies**:

- **Tower** (121.700) - Airport traffic control
- **Ground** (121.900) - Ground vehicle coordination
- **Approach** (134.050) - Arrival/departure control
- **ATIS** (119.425) - Automated weather/airport info
- **UNICOM** (122.950) - Pilot coordination

### Emergency Aviation

- **Aviation Emergency** (121.500) - International emergency frequency

## Western NC Emergency Coordination

### Regional Fire Services

- **WNC Fire Mutual Aid** (453.300) - Tone: 127.3
- **US Forest Service** (168.625) - Tone: 156.7 (wildfire suppression)

### Regional EMS

- **WNC EMS Coordination** (453.650) - Tone: 136.5
- **Mission Hospital** (453.500) - Regional trauma center

### Emergency Management

- **Buncombe County EM** (155.175) - Tone: 203.5
- **WNC Emergency Management** (155.280) - Tone: 136.5

## Mountain Weather Services

### NOAA Weather Radio

**Critical for mountain weather and flash flood warnings**:

- **162.400** - Primary Asheville weather
- **162.475** - Secondary mountain coverage
- **162.500** - Regional weather broadcasts
- **162.525** - Extended mountain coverage

### Weather Spotting

- **SKYWARN Net** (147.045) - Storm spotter coordination
- Critical for mountain flash flood and severe weather reporting

## Interoperability Systems

### National Interoperability Channels

- **TACALL** (151.145) - Tactical calling frequency
- **VTAC 11/12** (151.1375/154.4525) - VHF tactical channels
- **UTAC 41/42** (453.2125/458.2125) - UHF tactical channels
- **8-Call** (154.755) - Regional interoperability calling
- **8-Tac 91/92** (775.000/800.000) - Regional tactical channels

### Western NC Regional

- **WNC Regional Coord** (453.700) - Multi-county coordination
- **WNC Mutual Aid** (453.750) - Cross-jurisdictional assistance

## Transportation

### Railroad Operations

- **Norfolk Southern** (161.010) - Freight operations through Asheville
- Main line connects Charlotte to Tennessee

<!-- dprint-ignore-start -->
!!! warning
    Radio coverage in mountains is highly dependent on elevation and terrain. Line-of-sight to repeater sites is critical for reliable communications.
<!-- dprint-ignore-end -->

## Download

Configuration files are located in the `Asheville-NC/` directory of the
repository.
